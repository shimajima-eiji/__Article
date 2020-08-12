[公開先](https://qiita.com/nomurasan/items/f157a03e83761b0920ec)

[本家](https://takaya1992.hatenablog.jp/entry/2017/04/06/022344)の更新が2018年で止まっていたので、最新版に対応しつつGASでも作ってみる。

# GASでスクレイピングするなら「Cheeriosgs」が便利！最低賃金APIを作ってみる

いつもどおり、ソースは[Github](https://github.com/shimajima-eiji/Hosting/blob/GAS-minimum_wage/set.gs#L3-L74)。

<details><summary>ソースコード</summary><div>
```
  /**
   * ユーザー定義
   */
  const years = [
    {
      name: "令和",
      start: 2019,
    },
  ];

  /**
   * データクレンジング
   */    
  function replaces ( str )
  {
    return getDate( str ).trim()
      .replace( / /g, "" )
      .replace( /　/g, "" )
      .replace( /\)/g, "" )
      .replace( /\(/g, "" )
      .replace( /[０-９]/g, function ( word )
      {
        return String.fromCharCode( word.charCodeAt( 0 ) - 0xFEE0 )
      } );
  }
  function getDate ( str )
  {
    // 日付でなければやらない
    if ( str.indexOf( "年" ) == -1 ) return str;

    // 年号を西暦に直す。
    var ad = -1;  // 元年分を減らしておくため-1
    years.forEach( function ( year )
    {
      if ( str.indexOf( year.name ) > -1 )
      {
        ad += year.start;
        str = str.replace( year.name, "" );
      }
    } );

    // 元年は1年
    str = str.replace( "元", 1 )

    // 西暦を算出して-でつなげる
    var split = str.split( "年" );  // 2桁以上の検出に対応
    return ( Number( split[ 0 ] ) + ad )
      + "-"
      + split[ 1 ].replace( "月", "-" ).replace( "日", "" );
  }

  /**
   * メイン
   */
  const URL = PropertiesService.getScriptProperties().getProperties().url;
  const content = UrlFetchApp.fetch( URL ).getContentText();
  const $ = Cheerio.load( content );

  var result = [];
  var pointer = -1;
  const EXCLUDE_COLUMN = 3; // 最初の行だけおかしなものがあるので除外
  const COLUMNS = 4;
  $( "td" ).each( function ( i, td )
  {
    if ( i < EXCLUDE_COLUMN ) return;
    if ( i % COLUMNS == EXCLUDE_COLUMN )
    {
      result.push( [] );
      pointer++;
    }
    result[ pointer ].push( replaces( $( td ).text() ) );
  } );
```
</div></details>

スクレイピングでつらいのは、スクレイピングの処理ではなく、取得したデータのクレンジング。
具体的には、

- 必要な部分の括り出し
- 不正な値やデータを取り除く、置き換える

これを如何に頑張らないかが重要だと考える。
pythonだととりあえずpandas辺りに入れてしまえ！となるがJavascriptにそこまで求めるのは酷だろうか。

## Cheeriogs
[公式](https://github.com/tani/cheeriogs)

使い方はCheerioと同じなのでJQueryでスクレイピングをしている人にとっては馴染みやすい。

## 当初案
[Github(History)](https://github.com/shimajima-eiji/Hosting/commit/334503222be20d519d5cc5d9fbf88e163c732da9#diff-210a8378ce33326115f9b72aea5adcb2R3-R96)。

<details><summary>ソースコード</summary><div>
```
  /**
   * ユーザー定義
   */
  var yearsname2ad = {
    "元年": 2019,
  };
  const PROPERTIES = PropertiesService.getScriptProperties().getProperties();

  /**
   * システムロジック
   */

  function __scraping ()
  {
    var html = UrlFetchApp.fetch( PROPERTIES.url ).getContentText( 'UTF-8' ).replace( /\r?\n/g, "" ).replace( /[０-９]/g, function ( word )
    {
      return String.fromCharCode( word.charCodeAt( 0 ) - 0xFEE0 )
    } );
    var start = "<tbody>";
    var end = "</tbody>";
    return __cut( html, start, end );
  }

  var __match = {
    tr: /\<tr \w(.*?)\<\/tr\>/g,
    td: /\<td \w(.*?)\<\/td\>/g,
    year: /[\d元](.*)年/g,
    month: /年\d(.*)月/g,
    day: /月\d(.*)日/g,
    run: function ( str, pattern ) { return str.match( __match[ pattern ] ) },
  }
  function __cut ( str, sep )
  {
    return str.substring( str.indexOf( sep ) + sep.length, str.length );
  }
  function __rsubstring ( str, sep )
  {
    return str.substring( 0, str.indexOf( sep ) );
  }

  function __getYMD ( str, pattern )
  {
    var tmp = __match.run( str, pattern )[ 0 ]

    switch ( pattern )
    {
      case "year":
        tmp = yearsname2ad[ tmp ];
        break;

      case "month":
      case "day":
        tmp = tmp.substring( 1, tmp.length - 1 );
        if ( tmp.length == 1 ) tmp = "0" + tmp;
        break;
    }
    return tmp;
  }
  function __getDate ( str )
  {
    var year = __getYMD( str, "year" );
    var month = __getYMD( str, "month" );
    var day = __getYMD( str, "day" );
    return year + "-" + month + "-" + day;
  }

  /**
   * メイン
   */

  var table = __scraping()
  //  var table = test()

  /**
   * データクレンジング
   */
  var tr_items = __match.run( table, "tr" );
  var td_items = tr_items.map( function ( tr )
  {
    var tds = __match.run( tr, "td" );
    return tds.map( function ( td )
    {
      var clean_td = __rsubstring( __cut( td, ">" ), "<" )
        .trim()
        .replace( / /g, "" )
        .replace( /　/g, "" )
        .replace( /\(/g, "" )
        .replace( /\)/g, "" )
        ;
      if ( clean_td.indexOf( "年" ) > -1 ) clean_td = __getDate( clean_td );
      return clean_td;
    } );
  } );
  td_items.shift();
```
</div></details>

このように、うまいパターンマッチングを考えるしか方法が思いつかなかった。

なお、`getDate`関連と`str.replace`をリファクタリングしているので、そこは目を瞑ってほしい。

# 動くもの
[Web版](https://shimajima-eiji.github.io/Hosting/man-month/)

![簡易人月シミュレーター.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/122800/89d1c099-d5ec-ae0a-e02b-b90f7cb319a4.png)

Chrome拡張機能にも対応している。

# 手引
[最低賃金APIを使って簡易人月計算機をChrome拡張機能で作ってみた](https://note.com/nomuragoro/n/nf11cbbaf8f96)

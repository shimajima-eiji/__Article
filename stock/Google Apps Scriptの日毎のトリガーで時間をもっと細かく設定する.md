[元記事](https://qiita.com/sumi-engraphia/items/465dd027e17f44da4d6a)

```
// その日の17時59分にトリガーを設定
function setTrigger() {
  var triggerDay = new Date();
  triggerDay.setHours(17);
  triggerDay.setMinutes(59);
  ScriptApp.newTrigger("main").timeBased().at(triggerDay).create();
}

// その日のトリガーを削除する関数(消さないと残る)
function deleteTrigger() {
  var triggers = ScriptApp.getProjectTriggers();
  for(var i=0; i < triggers.length; i++) {
    if (triggers[i].getHandlerFunction() == "main") {
      ScriptApp.deleteTrigger(triggers[i]);
    }
  }
}
```

[公開先](https://qiita.com/nomurasan/items/a85555f4c6964c69cb9c)

# chocolateyとは？

chocolateyがどういうものかは[他の方の記事](https://qiita.com/kangetsu121/items/b6352b547cd32e71bc65)を参照していただいた方がいいです。
雑に言うと、

* windowsでもchocoでyumやらaptっぽいコマンドの振る舞いをさせて
* 作った環境を他のwindows端末にも持っていける

ものです。
これで、新しい端末を使うたびにいちいちダウンロードサイトまで行ってほげほげする必要がなくなります。

# chocolateyで入れられるもの 【2019/08/16時点】
どれができて、どれがだめなん？って情報は重要ですよね。

``` cmd
choco list (なんとか)
```

で、それっぽいものは引けるんですが、何となく眺めたくなったので。
「これも入れられるんだ！」っていう気付きにどうぞ。
（探しやすいようにasciiコード順にソートしています）

``` cmd.bat(for Administrator)
@choco list
010editor 8.0.1 [Approved] - Possibly broken
010editor.install 8.0.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
010editor.portable 8.0.0.20170515 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
0ad 0.0.23.1 [Approved] Downloads cached for licensed users
0install 2.16.7 [Approved]
0install.install 2.15.1 [Approved]
0install.portable 2.15.1 [Approved]
1c-barcode-printing 8.0.14.2 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
1c-barcode-scanner 8.0.8.4 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
1c-its 8.3 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
1clipboard 0.1.8 [Approved] Downloads cached for licensed users
1password 7.3.705 [Approved]
1password4 4.6.2.626 [Approved] Downloads cached for licensed users
2gis 3.16.3.0 [Approved]
360ts 10.6.0.1179 [Approved] Downloads cached for licensed users
360tse 8.8.0.1114 [Approved] Downloads cached for licensed users
3cx 15.5 [Approved] Downloads cached for licensed users
3dduke-shareware 1.3.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
3dmark 2.6.6238 [Approved] Downloads cached for licensed users
3proxy 0.8.13 [Approved] Downloads cached for licensed users
3rvx 2.9.2.10 [Approved] Downloads cached for licensed users
4k-stogram 2.2.2 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
4k-video-downloader 4.8.2 [Approved] Downloads cached for licensed users
4k-youtube-to-mp3 3.7.1 [Approved] Downloads cached for licensed users
4t-tray-minimizer 6.07 [Approved] Downloads cached for licensed users
7-taskbar-tweaker 5.7 [Approved] Downloads cached for licensed users
7KAA 2.14.15 [Approved] Downloads cached for licensed users
7zip 19.0 [Approved]
7zip.commandline 16.02.0.20170209 [Approved]
7zip.install 19.0 [Approved]
7zip.portable 19.0 [Approved]
8gadgetpack 28.0 [Approved] Downloads cached for licensed users
8x8virtualoffice 6.2.4.4 [Approved]
9kw-client 1.2.1 [Approved] Downloads cached for licensed users
a0toolkit 1.4.0 [Approved]
aacgain 1.9.0.2 [Approved] - Possibly broken
aaclr 1.0.2 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
abastart 3.3.0 [Approved] Downloads cached for licensed users
ABC-Update 2.2.1 [Approved] Downloads cached for licensed users
absolute-uninstaller 5.3.1.26 [Approved] Downloads cached for licensed users
acardaoutboundagent 7.4.0.2988 [Approved]
acardaoutboundsolo 7.4.0.2988 [Approved]
acc5client 5.10.24.2 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
acc6client 6.14.6.30 [Approved] - Possibly broken
Accents 1.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
access-data-registry-viewer 1.8.0.5 [Approved] Downloads cached for licensed users
access-to-mysql 5.2.0.252 [Approved]
access2016runtime 4288.1001.1 [Approved] Downloads cached for licensed users
accesschk 6.12 [Approved] Downloads cached for licensed users
accessdirector 2.5 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
accessenum 1.32 [Approved] Downloads cached for licensed users
accesspv 1.12 [Approved] Downloads cached for licensed users
acddokannet 1.7.3 [Approved] Downloads cached for licensed users
ace 1.3 [Approved]
acestream 3.1.32 [Approved] Downloads cached for licensed users
ack 2.22 [Approved]
acm 1.00 [Approved] Downloads cached for licensed users
acme-sh 2.8.2 [Approved] Downloads cached for licensed users
acmesharp-posh-all 0.8.1.0 [Approved] - Possibly broken
acr 2.7 [Approved] Downloads cached for licensed users
acronis-vdi 1.1.2141.20190805 [Approved] Downloads cached for licensed users
acrylic-dns-proxy 0.9.35 [Approved] Downloads cached for licensed users
acs-engine 0.26.3 [Approved] Downloads cached for licensed users
actiona 3.9.4 [Approved]
actiona.install 3.9.4.20190322 [Approved]
actiona.portable 3.9.4.20190322 [Approved]
Actionaz 3.9.4 [Approved]
activator 1.2.12 [Approved]
active-directory-photos 1.3.2.0 [Approved] Downloads cached for licensed users
activeexit 17.3.0 [Approved] Downloads cached for licensed users
ActiveMQ 5.15.6.20180913 [Approved] Downloads cached for licensed users
ActivePerl 5.24.3.2404 [Approved] Downloads cached for licensed users
ActivePerl-EqEmu-x86 5.16.3.1605
activepresenter 7.5.8 [Approved]
ActiveTcl 8.6.4.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
activitywatch 0.7.1 [Approved] Downloads cached for licensed users
ActySystemStyleRule 1.0.0
acunetix-free 1.0.0.20180331 [Approved] Downloads cached for licensed users
ad-acl-scanner 5.6.3 [Approved] Downloads cached for licensed users
ad-awarefreeantivirus 11.12.945.9202 [Approved] Downloads cached for licensed users
ad-photo-edit-free 2.6.1.20161008 [Approved] Downloads cached for licensed users
ad-tidy-free 2.1.7.0 [Approved] Downloads cached for licensed users
adafruit-pi-finder 3.0.0 [Approved] Downloads cached for licensed users
adb 29.0.1 [Approved] Downloads cached for licensed users
adblockplus-firefox 2.7.1 [Approved]
adblockpluschrome 1.12.4 [Approved]
adblockplusfirefox 0.0.0.2 [Approved]
adblockplusie 1.4 [Approved] Downloads cached for licensed users
adblockplusopera 1.13.3 [Approved]
addnewfile 3.5.135 [Approved]
addo 0.9.0 [Approved] Downloads cached for licensed users
address-tagging-exchange 1.0.1 [Approved] Downloads cached for licensed users
addtoany-chrome 3.0.4 [Approved]
adexplorer 1.44 [Approved] Downloads cached for licensed users
AdFender 1.83 [Approved] - Possibly broken
adguard-chrome 3.0.13 [Approved]
adiirc 3.3 [Approved] Downloads cached for licensed users
adinsight 1.20 [Approved] Downloads cached for licensed users
admincenter 1.1.1902.25004 [Approved]
admobilize-malos-vision 1.6.5 [Approved] Downloads cached for licensed users
admobilize-vision-service 1.3.0.0 [Approved] Downloads cached for licensed users
admprovider 2.1.0 [Approved] Downloads cached for licensed users
adobe-creative-cloud 1.0 [Approved] - Possibly broken
AdobeAIR 32.0.0.125 [Approved] Downloads cached for licensed users
adobedigitaleditions 4.5.10.20190316 [Approved] Downloads cached for licensed users
adobereader 2019.012.20036 [Approved]
adobereader-disable-updates-winconfig 0.0.1 [Approved] - Possibly broken
adobereader-update 18.011.20058 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
adobeshockwaveplayer 12.3.4.204 [Approved] Downloads cached for licensed users
adoptopenjdk 12.0.2.10 [Approved] Downloads cached for licensed users
adoptopenjdk11 11.0.4.11 [Approved] Downloads cached for licensed users
adoptopenjdk11jre 11.0.4.11 [Approved] Downloads cached for licensed users
adoptopenjdk8 8.212.2 [Approved] Downloads cached for licensed users
adoptopenjdk8jre 8.212 [Approved] Downloads cached for licensed users
adoptopenjdkjre 12.0.2.10 [Approved] Downloads cached for licensed users
adoptopenjdkopenj9jdk 12.0.1.12 [Approved] Downloads cached for licensed users
adoptopenjdkopenj9jre 12.0.1.12 [Approved] Downloads cached for licensed users
adrestore 1.10 [Approved] Downloads cached for licensed users
advanced-bat-to-exe-converter 4.11 [Approved] Downloads cached for licensed users
advanced-codecs 11.9.0 [Approved]
advanced-file-finder 5.0.0 [Approved] Downloads cached for licensed users
advanced-installer 10.6 [Approved] Downloads cached for licensed users
advanced-ip-scanner 2.5.3850 [Approved] Downloads cached for licensed users
advanced-renamer 3.85 [Approved]
advanced-renamer.install 3.85 [Approved]
advanced-renamer.portable 3.85 [Approved]
advancedrun 1.07 [Approved] Downloads cached for licensed users
advancedsystemtweaker 2.0.0.20141128 [Approved]
advor 0.3.1.2 [Approved] Downloads cached for licensed users
advtor 0.3.1.2 [Approved] Downloads cached for licensed users
adwcleaner 7.4 [Approved] Downloads cached for licensed users
aegisub 3.2.2.20161107 [Approved] Downloads cached for licensed users
aeroadmin.portable 3.0.2037
aerozoom 4.0.0.7 [Approved]
AESCrypt 3.10 [Approved]
Afedteated 12.5.0 [Approved] Downloads cached for licensed users
ag 2.1.0.1 [Approved] Downloads cached for licensed users
agen 0.1 [Approved]
agentransack 8.0.867.0 [Approved] Downloads cached for licensed users
agentsvn 2.56.20.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
ags 3.4.3.1 [Approved] Downloads cached for licensed users
agwchateaux.portable 1.7.8 [Approved] Downloads cached for licensed users
agwmultiactivites.portable 1.2.5 [Approved] Downloads cached for licensed users
ai-web-originalip 1.0.1 [Approved]
aida64-business 6.00.5100 [Approved] Downloads cached for licensed users
aida64-engineer 6.00.5100 [Approved] Downloads cached for licensed users
aida64-extreme 6.00.5100 [Approved] Downloads cached for licensed users
aida64-extreme.portable 6.00.5100 [Approved] Downloads cached for licensed users
aida64-networkaudit 6.00.5100 [Approved] Downloads cached for licensed users
aida64extreme 4.60.3100 - Possibly broken
aimp 4.51.2084 [Approved] Downloads cached for licensed users
airdroid 3.6.5.000 [Approved] Downloads cached for licensed users
airserver 5.5.8 [Approved] Downloads cached for licensed users
airship 2.4.0 [Approved]
airstream-futuropolis-regular-font 1.0 [Approved]
airtame 3.5.1 [Approved]
akelpad 4.9.8 [Approved] Downloads cached for licensed users
akiee 0.0.4 [Approved] Downloads cached for licensed users
aks-engine 0.39.1 [Approved] Downloads cached for licensed users
alacritty 0.3.3 [Approved] Downloads cached for licensed users
alacritty.install 0.3.3 [Approved]
alanstevens.utils 1.17
alanstevens.utils.vm 1.06
alanstevens.vs2012extensions 1.03
alanstevens.vsextensions 1.07
albumstomp 2.14 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
alcohol52-free 2.0.3.9326 [Approved] - Possibly broken
algobox 1.0.2 [Approved]
aliengame 0.2.31 [Approved] Downloads cached for licensed users
all-to-mp3 0.3.3 [Approved] Downloads cached for licensed users
allbrowsers 1.0
alldup 4.4.3 [Approved] Downloads cached for licensed users
allow-block-remove-firewall 1.0.0 [Approved] Downloads cached for licensed users
allpairs 1.2.1.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
allway-sync 18.4.8 [Approved]
allwemo 6.75 [Approved]
alt-tab-terminator 3.9 [Approved] Downloads cached for licensed users
altap-salamander 3.0.8 [Approved] Downloads cached for licensed users
altcopy 1.0.7 [Approved] Downloads cached for licensed users
altdrag 1.1.0.20170610 [Approved] Downloads cached for licensed users
alternatestreamview 1.56 [Approved] Downloads cached for licensed users
altools 1.0 [Approved] Downloads cached for licensed users
altstreamdump 1.05 [Approved] Downloads cached for licensed users
Amaya 11.4.4
amazingmarvin 1.41.2.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
amazon-assistant-chrome 10.1610.8.1201 [Approved]
amazon-music 5.3.3.1671 [Approved] Downloads cached for licensed users
amazon-music-chrome 1.4 [Approved]
amazon-photos 5.8.3.230 [Approved] Downloads cached for licensed users
amazon-workspaces 2.5.8 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
amazondrive 5.6.0.102 [Approved] Downloads cached for licensed users
amcacheparser 1.3.0.2 [Approved]
amd-ryzen-chipset 18.50.0422 [Approved]
amidst 4.3 [Approved]
amiduos 2.0.8.8511 [Approved]
Amiri 0.111 [Approved] Downloads cached for licensed users
ammyy-admin 3.9.0.0 [Approved]
ampfontviewer 3.8.6.20160708 [Approved] Downloads cached for licensed users
amsexplorer 4.3.4.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
amt 11.0 [Approved] Downloads cached for licensed users
amule 2.3.1 [Approved]
amule.install 2.3.1 [Approved] Downloads cached for licensed users
amule.portable 2.3.1 [Approved] Downloads cached for licensed users
anaconda2 2019.07 [Approved]
anaconda3 2019.07 [Approved]
android-insomnia-regular-font 1.0 [Approved]
android-ndk 20.0 [Approved]
android-sdk 26.1.1 [Approved] Downloads cached for licensed users
AndroidStudio 3.4.2.0 [Approved]
angband 4.1.0 [Approved] Downloads cached for licensed users
angry-birds-star-wars 0.38.6.0 [Approved] Downloads cached for licensed users
angryip 3.5.5 [Approved] - Possibly broken
AnkhSvn 2.5.12703 [Approved] Downloads cached for licensed users
anki 2.1.13 [Approved] Downloads cached for licensed users
annatar 0.3.3 [Approved]
annie 0.9.4 [Approved] Downloads cached for licensed users
AnonymousPro 2014.12.31 [Approved]
anote 4.2.4 [Approved] Downloads cached for licensed users
ansiblevaultcmd 1.0 [Approved]
ansicon 1.66.0.20150407 [Approved] Downloads cached for licensed users
ansifilter 2.14.1 [Approved]
ant 1.10.5 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
ant-renamer 2.12.0.20170526 [Approved]
antidupl 2.3.9 [Approved] Downloads cached for licensed users
antimicro 2.23 [Approved]
antimicro.install 2.23 [Approved] Downloads cached for licensed users
antimicro.portable 2.23 [Approved] Downloads cached for licensed users
antlr4 4.7.2 [Approved] Downloads cached for licensed users
antlrworks2 2.1.0 [Approved] Downloads cached for licensed users
anvide-seal-folder 5.30 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
any2ico 2.4.0.0 [Approved]
any2ico.portable 2.4.0.0 [Approved] Downloads cached for licensed users
anydesk 5.2.2 [Approved] Downloads cached for licensed users
anydvd 8.3.8.0 [Approved] Downloads cached for licensed users
AnyRail6 6.25.3 [Approved]
anyvideoconverter 6.0.0 [Approved] - Possibly broken
apache-cassandra 3.7 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
apache-fop 2.2 [Approved] Downloads cached for licensed users
apache-httpd 2.4.41 [Approved]
apache-zookeeper 3.4.9 [Approved] Downloads cached for licensed users
ApacheCommonsDaemon 1.0.15
apacheds 2.0.0.19 [Approved] - Possibly broken
apimonitor 2.13.0.20160115 [Approved] Downloads cached for licensed users
apktool 2.3.4 [Approved] Downloads cached for licensed users
apo-ok 1.66 [Approved]
apo-ok.install 1.66 [Approved]
apo-ok.portable 1.66 [Approved]
app-shop 1.0.31 [Approved] Downloads cached for licensed users
appaudioconfig 1.10 [Approved] Downloads cached for licensed users
appcharger 1.0.6 [Approved] Downloads cached for licensed users
appcompat-cacheparser 1.4.0.2 [Approved]
appcrashview 1.31 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
appease.client.powershell 0.0.88 [Approved]
appfabric 1.1 - Possibly broken
appfabric.caching 1.1 [Approved]
appharborcli.install 1.2 [Approved]
appinstallrecorder 1.0.0.20161105 [Approved] Downloads cached for licensed users
appium-desktop 1.12.1 [Approved] Downloads cached for licensed users
Apple_Airport_Utility 5.6.1
applicationcompatibilitytoolkit 5.6 [Approved] Downloads cached for licensed users
appverifier 4.0.665 [Approved] Downloads cached for licensed users
appveyor-evu 1.0.0 [Approved]
appveyor-server 7.0.2353 [Approved]
appvmanage 5.0.1.0 [Approved] Downloads cached for licensed users
appvprovider 0.6.0.4 [Approved] Downloads cached for licensed users
Apricot 7.5.0.0 - Possibly broken
aptana-studio 3.7.2 [Approved] Downloads cached for licensed users
AquaSnap 1.23.8 [Approved] Downloads cached for licensed users
araxismerge 2018.5059 [Approved] Downloads cached for licensed users
arcanist 2017.08 [Approved]
Archi 4.3.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
archive 0.0.7 [Approved]
archiver 3.1.0 [Approved] Downloads cached for licensed users
ardev 0.3.0.0 - Possibly broken
arduino 1.8.9 [Approved]
arduinoide 1.6.1 [Approved]
arduinoidegalileo 1.0.2 - Possibly broken
ArecaBackup 7.5 [Approved] Downloads cached for licensed users
ares 2.4.3 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
argouml 0.34.1 - Possibly broken
argyll 2.0.1 [Approved] Downloads cached for licensed users
aria2 1.34.0.1 [Approved] Downloads cached for licensed users
arkana 0.0.5 [Approved] Downloads cached for licensed users
armagetronad 0.2.8.34 [Approved] Downloads cached for licensed users
ARMClient 1.2.0 [Approved]
armory 0.96 [Approved] Downloads cached for licensed users
armyknife 1.2.0.106 [Approved]
arq 5.16 [Approved] Downloads cached for licensed users
arsclip 5.09 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
Artifactory 6.5.13 [Approved]
artifactory-pro 6.5.13 [Approved] Downloads cached for licensed users
artmoney.install 7.44 [Approved]
artools 0.3.0.0 - Possibly broken
as-ssd 2.0.6821.41776 [Approved] Downloads cached for licensed users
asciidoctorj 2.1.0 [Approved]
asio4all 2.14 [Approved] Downloads cached for licensed users
asmspy 1.3.71 [Approved]
asn1editor 1.3.11.3 [Approved]
asp-net-mvc-boilerplate 6.2.0.28901 [Approved]
aspeed-graphics-driver 1.05 [Approved] Downloads cached for licensed users
aspnetcore-runtimepackagestore 2.2.5 [Approved]
aspnetmvc 3.0.0.2 [Approved]
aspnetmvc.install 3.1.0.20140613 [Approved]
aspnetmvc2 2.0.60926.0 [Approved] Downloads cached for licensed users
aspnetmvc4.install 4.0.20714.0 [Approved]
asrock-3tb-plus-unlocker 1.1.1 [Approved] Downloads cached for licensed users
assaultcube 1.2.0.201 [Approved]
assfiltermod 0.4 [Approved] Downloads cached for licensed users
astah 6.6.4 - Possibly broken
asterie 1.03 [Approved] Downloads cached for licensed users
asteroids 2013.07.29 [Approved]
Astley 3.0
AstroGrep 4.4.7 [Approved] Downloads cached for licensed users
astromenace 1.3.2 [Approved] Downloads cached for licensed users
astyle 3.1 [Approved]
atlassian-plugin-sdk 5.0.13 [Approved] Downloads cached for licensed users
atlassianconnector-for-visualstudio 1.3.12.20150410 [Approved]
atmel-studio 7.0.1931 [Approved]
atnow 1.1 [Approved] Downloads cached for licensed users
atol-dto 10.4.5.0 [Approved] Downloads cached for licensed users
Atom 1.39.1 [Approved] Downloads cached for licensed users
atomicparsley 0.9.6 [Approved]
atraci 0.7.0 [Approved]
attractmode.portable 2.3.0 [Approved] Downloads cached for licensed users
attributechanger 9.10.5 [Approved]
atubecatcher 3.8.9622 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
au 2019.5.22 [Approved]
audacious 3.9 [Approved] Downloads cached for licensed users
audacity 2.3.2 [Approved]
audacity-ffmpeg 2.2.2.20181007 [Approved] Downloads cached for licensed users
audacity-lame 3.100.0.20190331 [Approved]
audio-router 0.10.2 [Approved] Downloads cached for licensed users
AudioConverter 3.1
audioshell 2.3.6 [Approved] Downloads cached for licensed users
audioswitcher 1.8.0.142 [Approved] Downloads cached for licensed users
auditbeat 7.3.0 [Approved] Downloads cached for licensed users
authy-desktop 1.7.0 [Approved] Downloads cached for licensed users
auto-dark-mode 2.3 [Approved]
autobootdisk 5.7 [Approved] Downloads cached for licensed users
autoclicker 3.0 [Approved] Downloads cached for licensed users
autocomplete 1.3 [Approved] Downloads cached for licensed users
autodesk-fusion360 2.0.6231 [Approved]
AutoFixture. AutoMoqPrig 0.0.0 [Approved]
autohotkey 1.1.30.03 [Approved]
autohotkey_l 1.1.14.20140119
autohotkey_l.install 1.1.14.20140119
autohotkey_l.portable 1.1.14.20140119 [Approved]
autohotkey-compiler 1.0
autohotkey.install 1.1.30.03 [Approved]
autohotkey.portable 1.1.30.03 [Approved]
autoit 3.3.14.5 [Approved]
autoit.commandline 3.3.14.2 [Approved] Downloads cached for licensed users
autoit.install 3.3.14.5 [Approved]
autoit.portable 3.3.14.5 [Approved]
autoload 4.1
autologon 3.10 [Approved] Downloads cached for licensed users
automation-spy 1.1.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
automise 5.0.0.1075 [Approved] Downloads cached for licensed users
automiserunner 5.0.0.1075 [Approved] Downloads cached for licensed users
automiseruntime 5.0.0.1075 [Approved] Downloads cached for licensed users
automouseclick 97.2 [Approved] Downloads cached for licensed users
AutoRest 1.0.0 [Approved]
AutoRuns 13.96 [Approved] Downloads cached for licensed users
autover 2.2.1.20160814 [Approved] Downloads cached for licensed users
avast-premier-trial 12.3.2279 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
avast-pro-trial 12.3.2279 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
avastbrowsercleanup 9.0.0.224
avastfreeantivirus 19.7.4674.0 [Approved]
avbin 10.0 [Approved] Downloads cached for licensed users
avd-nativeapp 4.1.19 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
AvgAntivirusBusiness 2013.3349 - Possibly broken
avgantivirusfree 18.1817.103 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
avginternetsecurity 15.0.6125 [Approved] - Possibly broken
avgpctuneup 15.0.1001.105 - Possibly broken
avidemux 2.7.1 [Approved]
avinaptic 2011.12.18 [Approved]
avirafreeantivirus 14.0.6.552 - Possibly broken
aviraiss 14.0.5.450 - Possibly broken
avisynthplus 0.1.0.2772 [Approved] Downloads cached for licensed users
avogadro 1.2.0.20190217 [Approved]
awake 1.4.2.1 [Approved]
awatch 1.05 [Approved] Downloads cached for licensed users
AwesomeAlexDev 1.1.2
awesomebump 5.1 [Approved] Downloads cached for licensed users
awk 4.2.132 [Approved]
aws-iam-authenticator 0.4.0 [Approved] Downloads cached for licensed users
aws-monitor-diskusage 1.2.0 [Approved]
aws-password-extractor 1.1.0 [Approved]
aws-sdk-net 2.0.5.0
aws-vault 4.6.3 [Approved]
awscli 1.16.218 [Approved]
awslambdapscore 1.2.0.0 [Approved]
awssdk-tools 1.0.0
AWSTools. Powershell 1.1.1120.20130916 [Approved]
axcrypt 2.1.1585.0 [Approved]
axel 2.4.1
axhelper 1.12 [Approved] Downloads cached for licensed users
axis2-war 1.6.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
azclient 0.5 [Approved] Downloads cached for licensed users
azcopy 8.1.0 [Approved] Downloads cached for licensed users
azcopy10 10.2.1 [Approved] Downloads cached for licensed users
azpazeta 2.0.75
azshell 0.2.2 [Approved] Downloads cached for licensed users
AzToolkit 1.0.1 [Approved]
azure-cli 2.0.71 [Approved] Downloads cached for licensed users
azure-data-studio 1.9.0 [Approved] Downloads cached for licensed users
azure-data-studio-sql-server-admin-pack 0.0.1 [Approved]
azure-devops-policy-configurator 1.1.0 [Approved]
azure-documentdb-data-migration-tool 1.7 [Approved] Downloads cached for licensed users
azure-documentdb-emulator 1.11.136.2 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
azure-functions-core-tools 2.7.1505 [Approved] Downloads cached for licensed users
azure-information-protection-client 1.48.204.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
azure-information-protection-unified-labeling-client 2.0.779.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
azure-pipelines-agent 2.155.1 [Approved]
AzureBuildSDKvs2012 2.4.0 - Possibly broken
AzureBuildSDKvs2013 2.4.0 - Possibly broken
azuredatafactorytools15 0.9.3527.2 [Approved] Downloads cached for licensed users
AzurePowerShell 6.9.0 [Approved]
azurestorageemulator 4.4.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
AzureStorageExplorer 5.0.0.20180315 [Approved]
babelmap 9.0.0.3 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
babelpad 9.0.0.3 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
babun 1.2.0.20180102 [Approved]
back-to-backspace-chrome 1.3.0 [Approved]
backupper-server 4.6.3 [Approved] - Possibly broken
backupper-standard 4.6.3 [Approved] Downloads cached for licensed users
backupvault 3.2.2018.32 [Approved] Downloads cached for licensed users
bacula 9.4.4 [Approved] Downloads cached for licensed users
badaboom-media-converter 2.0.0.128 [Approved] Downloads cached for licensed users
badger 1.0.0 [Approved]
balabolka 2.15.0.708 [Approved]
balsamiqmockups.install 1.0.8 [Approved] - Possibly broken
balsamiqmockups3 3.4.4 [Approved]
bamboo-tray 1.0.0.41 [Approved]
banana-buchhaltung 9.0.4 [Approved] Downloads cached for licensed users
bandizip 6.24 [Approved] Downloads cached for licensed users
bandlab-assistant 5.0.4 [Approved] Downloads cached for licensed users
barcode-to-pc-server 3.1.1 [Approved] Downloads cached for licensed users
baregrep 3.50.0.20120225 [Approved]
baretail 3.50.0.20120226 [Approved]
barrier 2.3.0 [Approved]
barryschiffer-netscaler-script 2.5 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
basilisk 2019.03.08 [Approved]
basilisk.install 2019.03.08 [Approved] Downloads cached for licensed users
basilisk.portable 2019.03.08 [Approved] Downloads cached for licensed users
Bat 0.11.0 [Approved] Downloads cached for licensed users
batch-docs 5.6.0 [Approved] Downloads cached for licensed users
batch-encoding-converter 5.0.0 [Approved] Downloads cached for licensed users
batch-file-encrypt 5.0.0 [Approved] Downloads cached for licensed users
batch-file-manager 5.0.0 [Approved] Downloads cached for licensed users
batch-file-rename 5.0.0 [Approved] Downloads cached for licensed users
batch-files 5.0.0 [Approved] Downloads cached for licensed users
batch-hex-editor 5.0.0 [Approved] Downloads cached for licensed users
batch-image-converter 5.6.0 [Approved] Downloads cached for licensed users
batch-image-enhancer 5.6.0 [Approved] Downloads cached for licensed users
batch-image-resizer 5.6.0 [Approved] Downloads cached for licensed users
batch-image-splitter 5.6.0 [Approved] Downloads cached for licensed users
batch-image-watermarker 5.6.0 [Approved] Downloads cached for licensed users
batch-install-vsix 1.0.1
batch-photo-face 5.6.0 [Approved] Downloads cached for licensed users
batch-regex 5.0.0 [Approved] Downloads cached for licensed users
batch-text-file-editor 5.0.0 [Approved] Downloads cached for licensed users
batch-word-replace 5.6.0 [Approved] Downloads cached for licensed users
Batik 1.7 - Possibly broken
Batte. LoadOuts. Dev 1.0.5 - Possibly broken
battecode.cmder.dev 1.1.3.1
BatteryBar 3.6.6 [Approved] Downloads cached for licensed users
batteryinfoview 1.23 [Approved] Downloads cached for licensed users
battle.net 0.3
battoexeconverter 3.1.0.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
Batzendev. Tools 3.0.3 [Approved]
bazel 0.28.0 [Approved]
bbwin 0.13.20160427 [Approved] Downloads cached for licensed users
BCC-MSBuildLog 0.1.9 [Approved]
BCC-Submission 0.1.3 [Approved]
bdfilehash 1.1.3 [Approved] - Possibly broken
beacon 1.3.0 [Approved]
beaker 0.8.8 [Approved] Downloads cached for licensed users
becyicongrabber 2.30.0.20161027 [Approved] Downloads cached for licensed users
beebeep 5.6.4 [Approved]
Beersmith 2.2.12.0
belarcadvisor 8.5 [Approved] Downloads cached for licensed users
bellavista 1.1.0.75 [Approved] Downloads cached for licensed users
belvedere 0.7.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
bepo 0.1 [Approved] Downloads cached for licensed users
berrybrew 1.2.3 [Approved] Downloads cached for licensed users
BetterCredentials 2.0.0.1
bettertls-psmodule 0.1.0.0 [Approved]
beyondcompare 4.2.10.23938 [Approved]
beyondcompare-integration 1.0.1 [Approved]
beyondcompare2 2.5.3
bfg-repo-cleaner 1.13.0 [Approved]
bginfo 4.27 [Approved] Downloads cached for licensed users
bgpkiller 0.9.6.0 [Approved] Downloads cached for licensed users
biber.portable 1.9
bibletime 2.11.2 [Approved]
biblioteq 2016.03.03 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
big-stretch-reminder 2.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
bigbyte 1.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
BigGit 1.1.5 [Approved]
bigstash 1.5.1 [Approved] - Possibly broken
biicode 2.8 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
bills-jammin-jukebox 6.1.20161009 [Approved]
bind-toolsonly 9.14.2 [Approved] Downloads cached for licensed users
Bing 5.0
BingBar 7.3.126 - Possibly broken
BingDesktop 1.3.478.0 [Approved] Downloads cached for licensed users
biorhythms-calculator 2.0.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
bioviadraw-ae 2018.0.0.20180925 [Approved] Downloads cached for licensed users
bis-f 6.1.3 [Approved] Downloads cached for licensed users
bistudio 8.3.9 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
bit 0.10.9 [Approved] Downloads cached for licensed users
bitcoin 0.18.0 [Approved]
bitcoin-unlimited 1.0.2.0 [Approved] - Possibly broken
bitcoin-unlimited.install 1.0.2.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
bitcoin-unlimited.portable 1.0.2.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
bitcoin.install 0.18.0 [Approved] Downloads cached for licensed users
bitcoin.portable 0.18.0 [Approved] Downloads cached for licensed users
bitcoinxt 0.11.04 [Approved]
bitcoinxt.install 0.11.04 [Approved] Downloads cached for licensed users
bitcrypt 0.0.3 [Approved] Downloads cached for licensed users
bitdefender-usb-immunizer 2.0.1.901 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
bitdefenderavfree 1.0.21.1099 - Possibly broken
bitdiffer 1.5.0.4 [Approved] Downloads cached for licensed users
bitkinex 3.2.3.20130823 - Possibly broken
bitmessage 0.6.1 [Approved] Downloads cached for licensed users
bitmeteros 0.7.6 [Approved] Downloads cached for licensed users
Bitnami-XAMPP 7.3.4 [Approved] Downloads cached for licensed users
bitrix24 7.0.44.42 [Approved]
bitstreamverafonts 1.10
bitvise-ssh-client 8.34 [Approved] Downloads cached for licensed users
bitvise-ssh-server 8.34 [Approved] Downloads cached for licensed users
bitwarden 1.15.2 [Approved] Downloads cached for licensed users
bitwarden-cli 1.7.4 [Approved]
BiztalkFactoryPowershellProvider 1.3.0.1 - Possibly broken
blackbird 1.0.78 [Approved] Downloads cached for licensed users
blat 3.2.17 [Approved] Downloads cached for licensed users
bleachbit 2.2.0.20190520 [Approved]
bleachbit.install 2.2.0.20190520 [Approved]
bleachbit.portable 1.12 [Approved] Downloads cached for licensed users
blender 2.80 [Approved]
bless 0.6.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
blink 1.4.2 [Approved] - Possibly broken
blinkys-scary-school 2013.07.30 [Approved]
blitz 2010.05.07 [Approved]
blobby2 1.0.3.0 - Possibly broken
blockcheck 0.0.9.6 [Approved] Downloads cached for licensed users
blockjsvbs-winconfig 0.0.1 [Approved]
blocktality 1.0.1 [Approved] Downloads cached for licensed users
blogspot-image-downloader 1.1.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
bluebeamvu 2017.0 [Approved]
bluebrick 1.8.2 [Approved] Downloads cached for licensed users
bluefish 2.2.10 [Approved]
bluegriffon 3.0.1 [Approved]
bluej 4.2.1 [Approved] Downloads cached for licensed users
bluej-bundled 3.1.7 [Approved] Downloads cached for licensed users
BlueJeansApp 2.14.491 [Approved] Downloads cached for licensed users
bluescreenview 1.55 [Approved]
bluescreenview.install 1.55 [Approved] Downloads cached for licensed users
bluescreenview.portable 1.55 [Approved] Downloads cached for licensed users
bluetoothcl 1.07 [Approved] Downloads cached for licensed users
bluetoothlogview 1.12 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
bluetoothview 1.66 [Approved] Downloads cached for licensed users
bluetracker-cli 1.3.2 [Approved]
Blur-IE 5.5.1930 [Approved] Downloads cached for licensed users
bmfont 1.13 [Approved]
boinc 7.14.2 [Approved] Downloads cached for licensed users
bonjour 2.0.2.0 [Approved] Downloads cached for licensed users
book-collector 19.2.3 [Approved] Downloads cached for licensed users
boomeranggmail-chrome 1.2.7 [Approved] - Possibly broken
boost-msvc-12 1.58.0 [Approved] Downloads cached for licensed users
boostnote 0.12.1 [Approved] Downloads cached for licensed users
boot-clj 2.6.2 [Approved]
boot-no-hyperv 0.1.0 [Approved]
boot2docker 1.6.2 [Approved] - Possibly broken
borderlessgaming 9.5.5 [Approved] Downloads cached for licensed users
borgbackup 1.0.11 [Approved] Downloads cached for licensed users
bosh-cli 5.5.1 [Approved] Downloads cached for licensed users
botpress 12.1.0 [Approved]
boutdutunnel.client 1.5.3369.20120226 [Approved]
boutdutunnel.server 1.5.3369.20120225 [Approved]
bower 1.8.8 [Approved]
bowery-agent 3.1.0 - Possibly broken
bowpad 2.4.5 [Approved] Downloads cached for licensed users
box-drive 2.7.242 [Approved] Downloads cached for licensed users
box.default 1.0.0 - Possibly broken
boxcli 2.3.0 [Approved]
boxcryptor 2.35.1033 [Approved] Downloads cached for licensed users
BoxCryptorClassic 1.7.409.20180501 [Approved] Downloads cached for licensed users
boxes.portable 1.3 [Approved]
boxstarter 2.12.0 [Approved]
Boxstarter. Azure 2.12.0 [Approved]
boxstarter.bootstrapper 2.12.0 [Approved]
boxstarter.chocolatey 2.12.0 [Approved]
BoxStarter. Common 2.12.0 [Approved]
Boxstarter. HyperV 2.12.0 [Approved]
Boxstarter. TestRunner 2.12.0 [Approved]
BoxStarter. WinConfig 2.12.0 [Approved]
Boxstarter. WindowsUpdate 1.1.0 [Approved] - Possibly broken
boxsync 4.0.7965.0 [Approved] Downloads cached for licensed users
bping 2.0 [Approved] Downloads cached for licensed users
BR. AdobeReaderFR 11.0.09 - Possibly broken
Brackets 1.14 [Approved]
Brackets. Theseus 0.2.8
brainsimulator 0.6.0 [Approved] Downloads cached for licensed users
brave 0.68.129 [Approved]
brewtarget 2.3.0.20160816 [Approved] Downloads cached for licensed users
brogue 1.7.3 - Possibly broken
browseraddonsview 1.16 [Approved]
browsermanager 1.3.0.3 [Approved]
browsersync 1.2.21 [Approved] Downloads cached for licensed users
browsinghistoryview 2.21 [Approved] Downloads cached for licensed users
brunchtaskrunner 1.0.13 [Approved] Downloads cached for licensed users
brutaldoom 21.0.0 [Approved] Downloads cached for licensed users
brutaldoom-d2reload 1.0.0 [Approved] Downloads cached for licensed users
brutaldoom-dtwid 1.1.1 [Approved] Downloads cached for licensed users
brutaldoom-epic2 1.0.0 [Approved] Downloads cached for licensed users
brutaldoom-goingdown 1.0.0 [Approved] Downloads cached for licensed users
brutaldoom-hellbound 1.0.0 [Approved] Downloads cached for licensed users
brutaldoom-kamasutra 03.09.05 [Approved] Downloads cached for licensed users
brutaldoom-scythe2 2.0.0 [Approved] Downloads cached for licensed users
bsplayer 2.73.1084 [Approved] Downloads cached for licensed users
bst 1.0 [Approved]
bstrings 1.4.1.1 [Approved]
btprox 1.5.0.1 [Approved]
btprox.install 1.5.0.1 [Approved]
btprox.portable 1.5.0.1 [Approved]
btsync 2.3.6.20170529 [Approved]
buck 2019.06.17.01 [Approved]
buckaroo 2.2.0 [Approved] Downloads cached for licensed users
bud 0.5.2 [Approved] Downloads cached for licensed users
buddybackup 2.0.2.400 [Approved] Downloads cached for licensed users
buffalo-nas-navigator 2.99 [Approved] Downloads cached for licensed users
bugShooting 2.12.4.744 [Approved] - Possibly broken
build-them-all 0.0.8 [Approved]
buildkite 2.6.1 [Approved] Downloads cached for licensed users
buildmaster 5.3.6 [Approved] - Possibly broken
buildmaster.agent.iis 5.3.6 [Approved] - Possibly broken
buildmaster.agent.tcp 5.3.6 [Approved] - Possibly broken
bulk-ad-users 1.0.3267.32645 [Approved] Downloads cached for licensed users
bulk-crap-uninstaller 4.14 [Approved]
bulkfilechanger 1.65 [Approved] Downloads cached for licensed users
bulkrenamecommand 1.3.3.20170403 [Approved] Downloads cached for licensed users
bulkrenameutility 3.0.0.1 [Approved]
bulkrenameutility.install 3.1.0.0 [Approved] Downloads cached for licensed users
bulkrenameutility.portable 3.1.0.0 [Approved] Downloads cached for licensed users
bulletspassview 1.32 [Approved]
bulletspassview.install 1.32 [Approved] Downloads cached for licensed users
bulletspassview.portable 1.32 [Approved] Downloads cached for licensed users
bumpy.portable 0.11.0 [Approved]
bundlerminifier 2.9.406 [Approved]
bunnyhop 2010.01.25 [Approved]
bunqdesktop 0.9.8 [Approved] Downloads cached for licensed users
burgertime 2014.11.18 [Approved]
burnawarefree 12.5.1 [Approved]
burnawarepremium 12.5.1 [Approved]
burnawarepro 12.5.1 [Approved]
burneremails-chrome 0.1.7 [Approved] - Possibly broken
burnttoast-psmodule 0.7.0 [Approved]
burp-suite-free-edition 2.1.02 [Approved] Downloads cached for licensed users
busybox 3128.0 [Approved]
buttercup 1.16.2 [Approved] Downloads cached for licensed users
byteball 2.7.2 [Approved] Downloads cached for licensed users
bytecoin 1.1.8 [Approved] Downloads cached for licensed users
bytemark 3.4 [Approved]
bzeditor 1.7.6 - Possibly broken
bzflag 2.4.10 [Approved] Downloads cached for licensed users
bzip2 1.0.5 [Approved]
bzr 2.5.1.2
C99toC89 1.0.102
cabal 2.4.1.0 [Approved] Downloads cached for licensed users
cacher 2.15.2 [Approved] Downloads cached for licensed users
cacheset 1.0 [Approved] Downloads cached for licensed users
CADConverter 3.1
caddy 0.9.5 [Approved]
caesium.install 1.7.0.20190216 [Approved]
caffeine 1.64.0.20190201 [Approved] Downloads cached for licensed users
cake-bakery.portable 0.4.1 [Approved]
cake-bootstrapper 0.1.0 [Approved] Downloads cached for licensed users
cake.portable 0.34.1 [Approved]
cakerecipe-vscode 0.5.0 [Approved]
calcheck 2.2 - Possibly broken
Calculator. Net 1.2.0.42 [Approved] Downloads cached for licensed users
calibre 3.46.0 [Approved]
cameraraw 9.12.1 [Approved] Downloads cached for licensed users
cameyo 3.1.1446 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
CAMLDesigner2013 1.1.0.0
CamlViewer 2.0.0.0
camstudio 2.7.316.20161004 [Approved] Downloads cached for licensed users
camtasia 2019.0.6.500400 [Approved]
camunda-bpm-tomcat 7.7.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
camunda-modeler 1.11.2 [Approved] Downloads cached for licensed users
canopy 1.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
cantata 2.3.2 [Approved]
capnproto 0.7.0 [Approved] Downloads cached for licensed users
captura 8.0.0 [Approved] Downloads cached for licensed users
capture2text 4.6.1 [Approved] Downloads cached for licensed users
captureflux 6.0.5 [Approved] Downloads cached for licensed users
carbon 2.8.1 [Approved]
caret 3.4.6 [Approved] Downloads cached for licensed users
carina 2.1.3 [Approved]
carlwebster-adds-script 1.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
carlwebster-dhcp-script 1.2 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
carlwebster-pvs-script 4.2 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
carlwebster-xa6-script 4.2 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
carlwebster-xa65-script 4.2 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
carlwebster-xd5-script 1.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
carnac 2.3.3 [Approved] Downloads cached for licensed users
carob 1.1 [Approved] Downloads cached for licensed users
carotdav 1.15.5 [Approved]
carotdav.install 1.15.5 [Approved]
carotdav.portable 1.15.5 [Approved]
casperjs 1.0.0
cass 3.0.2 [Approved] - Possibly broken
cassinidev 3.5.1.8 - Possibly broken
cavesofqud 1.0.4646.16699 [Approved] Downloads cached for licensed users
cccp 2015.10.18 [Approved] Downloads cached for licensed users
ccdcmercury 4.1.3 [Approved] Downloads cached for licensed users
ccenhancer 4.5.4.20190517 [Approved]
ccenhancer.install 4.5.4.20190517 [Approved]
ccenhancer.portable 4.5.4.20190515 [Approved]
ccleaner 5.60.7307 [Approved] Downloads cached for licensed users
ccleaner.portable 5.60.0.7307 [Approved] Downloads cached for licensed users
cctray 1.8.5.20150314 [Approved] Downloads cached for licensed users
cdburnerxp 4.5.8.704200 [Approved]
cdex 2.00 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
cdmessenger 3.3 [Approved] Downloads cached for licensed users
cdrtfe 1.5.8 [Approved]
ceed 0.8.0 - Possibly broken
celestia 1.6.1.20150930 [Approved] Downloads cached for licensed users
cemu 1.15.11.200 [Approved] Downloads cached for licensed users
CentBrowser 4.0.9.112 [Approved]
centipede 2011.09.19 [Approved]
cerebro 0.3.2 [Approved] Downloads cached for licensed users
certifytheweb 4.1.6 [Approved] Downloads cached for licensed users
cevio 1.2.4.2 - Possibly broken
Cevo 1.2.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
cfiler 2.49 [Approved] Downloads cached for licensed users
cfr 0.146 [Approved]
cgithubinst 0.1.2
chainlp 0.40.17 - Possibly broken
chainsaw 2.0.0 [Approved] Downloads cached for licensed users
chandler 2.1.0 [Approved]
change-dns-servers 1.0.0 [Approved] Downloads cached for licensed users
change-screen-resolution 1.0.1.0 [Approved]
changelog 0.0.29 [Approved]
ChanSort 2019.08.13 [Approved]
charissil 5.0 [Approved]
Charles 3.12.3 [Approved] Downloads cached for licensed users
charles4 4.2.8.20190512 [Approved] Downloads cached for licensed users
charmtimetracker 1.12.0 [Approved] Downloads cached for licensed users
chaskis 0.10.1 [Approved] Downloads cached for licensed users
chatty 0.9.7 [Approved] Downloads cached for licensed users
cheatengine 6.8.3 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
check_mk_agent 1.2.45.1
check-mk 1.2.4 - Possibly broken
checkerplusforgmail-chrome 19.3.8 [Approved]
checkstyle 6.18 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
checksum 0.2.0 [Approved]
chef_development 1.0.0.4
chef-client 15.1.36 [Approved] Downloads cached for licensed users
chef-workstation 0.5.1 [Approved] Downloads cached for licensed users
chefdk 4.2.0 [Approved] Downloads cached for licensed users
cherrytree 0.38.8 [Approved] Downloads cached for licensed users
chessx 1.5.0 [Approved] Downloads cached for licensed users
chgkey 1.50 - Possibly broken
chicken 4.13.0 [Approved]
chimera 1.13.1 [Approved] Downloads cached for licensed users
chirp 2019.08.12 [Approved]
chirp.install 2019.08.12 [Approved]
chirp.portable 2019.08.12 [Approved]
ChirpyVSI 2.0.0.4 - Possibly broken
choco-chrome-ext 1.0.0.8 [Approved]
choco-cleaner 0.0.5.2 [Approved]
choco-install-packages-from-web-winconfig 0.0.1 [Approved]
choco-nuspec-checker 2019.03.04 [Approved]
choco-optimize-at 0.0.1.1 [Approved]
choco-package-list-backup 2019.07.02 [Approved]
choco-persistent-packages 2018.05.06 [Approved]
choco-protocol-support 0.0.1 [Approved]
choco-shortcuts-winconfig 0.0.2.2 [Approved]
choco-upgrade-all-at 0.0.5 [Approved]
choco-upgrade-all-at-startup 2018.08.23 [Approved]
chocolatey 0.10.15 [Approved]
Chocolatey-AutoUpdater 1.0.1 [Approved] Downloads cached for licensed users
chocolatey-core.extension 1.3.3 [Approved]
chocolatey-fastanswers.extension 0.0.2 [Approved]
chocolatey-font-helpers.extension 0.0.1 [Approved]
chocolatey-fosshub.extension 0.6.1 [Approved]
chocolatey-isomount.extension 1.0.0 [Approved]
chocolatey-misc-helpers.extension 0.0.3.1 [Approved]
chocolatey-preinstaller-checks.extension 0.0.2.1
chocolatey-toast-notifications.extension 0.0.3
chocolatey-toast.extension 1.0.1 [Approved]
chocolatey-uninstall.extension 1.2.0 [Approved]
chocolatey-visualstudio.extension 1.8.1 [Approved]
chocolatey-vscode 0.7.1 [Approved]
chocolatey-vscode.extension 1.0.0 [Approved]
chocolatey-windowsupdate.extension 1.0.4 [Approved]
chocolatey.server 0.2.5 [Approved]
ChocolateyDeploymentUtils 1.0.3 - Possibly broken
ChocolateyExplorer 0.2.2.111 [Approved] - Possibly broken
ChocolateyGUI 0.16.0 [Approved]
ChocolateyPackageUpdater 0.6.13.0 [Approved]
chocolateypowershell 0.0.2.1 [Approved]
chocomaint 1.0.3.6 [Approved] Downloads cached for licensed users
chocomon 1.0.1.1 [Approved] Downloads cached for licensed users
ChocoShortcuts 0.4.1 [Approved]
chrlauncher.portable 2.5.6 [Approved]
chromaprint 1.1 [Approved]
chromas 2.6.6 [Approved]
chrome-remote-desktop-chrome 63.0.3239.17 [Approved]
chrome-remote-desktop-host 76.0.3809.117 [Approved] Downloads cached for licensed users
chromecacheview 1.87 [Approved] Downloads cached for licensed users
chromecookiebackup 1.0.0 [Approved]
chromecookiesview 1.56 [Approved] Downloads cached for licensed users
chromedriver 76.0.3809.680 [Approved] Downloads cached for licensed users
ChromeDriver2 2.25 [Approved] Downloads cached for licensed users
chromehistoryview 1.36 [Approved] Downloads cached for licensed users
chromehue-chrome 1.1.6 [Approved]
chromelpass-chrome 2.8.1 [Approved]
chromepass 1.45 [Approved] - Possibly broken
chrometana-chrome 2.0.1 [Approved]
chromium 75.0.3770.142 [Approved]
chromium-stable 64.0.3282.168 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
chromiumbsu 0.9.16.1 [Approved] Downloads cached for licensed users
chrono-chrome 0.10.0 [Approved]
chucknorris 0.6 [Approved]
chunkfs 0.20.10 [Approved] Downloads cached for licensed users
Chutzpah 4.4.6 [Approved] Downloads cached for licensed users
ci-cd-assets-vscode 0.5.0 [Approved]
cica 5.0.1.20190723 [Approved] Downloads cached for licensed users
cimer 0.6 - Possibly broken
cinebench 20.0 [Approved] Downloads cached for licensed users
cisco-proximity 3.0.3 [Approved] Downloads cached for licensed users
citrix-receiver 4.12 [Approved] Downloads cached for licensed users
citrix-workspace 19.7.0.15 [Approved] Downloads cached for licensed users
citrix-xenserver-sdk 6.2.0 [Approved] - Possibly broken
cksdev11 1.1.0.0 - Possibly broken
cksdevserver 2.4.0.0 - Possibly broken
clamav 0.99.3 [Approved] Downloads cached for licensed users
clamsentinel 1.22 [Approved]
clamwin 0.99.4 [Approved] Downloads cached for licensed users
clash-of-clans 0.38.6.0 [Approved] Downloads cached for licensed users
clash-royale 0.38.6.0 [Approved] Downloads cached for licensed users
classic-shell 4.3.1.20180405 [Approved]
classified-ads 0.13 [Approved] Downloads cached for licensed users
classyshark 8.2 [Approved]
claws-mail 3.17.4 [Approved] Downloads cached for licensed users
clcl.portable 2.0.3 [Approved] Downloads cached for licensed users
cleanafterme 1.37 [Approved] Downloads cached for licensed users
cleanup 4.5.2.20190522 [Approved]
clearcomponentcache 1.1.17 [Approved] Downloads cached for licensed users
clementine 1.3.1.20170212 [Approved]
click-monitor-ddc 7.0 [Approved] Downloads cached for licensed users
click-pcl 2.40.0000 [Approved] Downloads cached for licensed users
clickie 1.2.1.20190201 [Approved] Downloads cached for licensed users
clink 0.4.9 [Approved] Downloads cached for licensed users
clion-ide 2019.2 [Approved] Downloads cached for licensed users
clipboard-help-and-spell 2.45.01 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
clipboardfusion 5.6 [Approved]
clipboardic 1.15 [Approved] Downloads cached for licensed users
clipcache 3.6.3.0 [Approved] Downloads cached for licensed users
clipdiary 5.1 [Approved] Downloads cached for licensed users
clipgrab 3.8.4 [Approved]
clipjump 12.5 [Approved] Downloads cached for licensed users
clipx 1.0.3.8
clisp 2.49
clmp 1.0 [Approved]
CLOC 1.80 [Approved] Downloads cached for licensed users
clockres 2.10 [Approved] Downloads cached for licensed users
clojure 1.6.0 [Approved]
clojure.clr 1.3.0
cloneapp 2.12.462 [Approved]
clonespy 3.42 [Approved] Downloads cached for licensed users
CloseTheDoor 0.2.1.1
CloudBerryDrive. Desktop 1.3.0.23 - Possibly broken
CloudBerryExplorer. AmazonS3 5.9.1.192 [Approved] Downloads cached for licensed users
CloudBerryExplorer. AzureStorage 3.1.0.17 [Approved] Downloads cached for licensed users
CloudBerryExplorer. GoogleStorage 3.5.0.25 [Approved] Downloads cached for licensed users
CloudBerryExplorer. OpenStackStorage 1.7.0.27 [Approved] Downloads cached for licensed users
CloudBerryExplorer. S3 5.0.0.29 [Approved] Downloads cached for licensed users
cloudfoundry-cli 6.46.0 [Approved] Downloads cached for licensed users
cloudoman.snapshottercmd 0.11.20140108.12
cloudstation 4.2.5.4396 [Approved] Downloads cached for licensed users
Clover 3.2.3 [Approved] - Possibly broken
clrprofiler 4.5.0.20180517 [Approved] Downloads cached for licensed users
clumsy 0.2 [Approved]
cmail 0.7.9.1 [Approved]
cmake 3.15.2 [Approved]
cmake.install 3.15.2 [Approved]
cmake.portable 3.15.2 [Approved]
cmaptools 6.03.01.1 [Approved] Downloads cached for licensed users
cmcollctr 1.0.0.12
cmdaliases 1.0.0.1
Cmder 1.3.11 [Approved]
cmder.portable 1.1.4.102 [Approved]
cmdermini 1.3.11 [Approved]
cmdermini.portable 1.1.4.102 [Approved]
cmderplus 1.1.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
cmdhere 0.0.1 [Approved] Downloads cached for licensed users
cmdimg.install 1.0.0 [Approved] Downloads cached for licensed users
cmdow 1.4.8.20180816 [Approved]
cmdutils 1.5 [Approved] Downloads cached for licensed users
cms-magic-series 2.4.4.2056 [Approved]
CMSupportCenter 5.0.7958.20190201 [Approved] Downloads cached for licensed users
Cntlm 0.92.3.2 [Approved] Downloads cached for licensed users
coapp 1.23.521.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
cobian-backup 11.2.0.582001 [Approved]
cockatrice 2016.05.06 [Approved] Downloads cached for licensed users
cocuun 2.8.14 [Approved] Downloads cached for licensed users
code-notes 1.2.1 [Approved] Downloads cached for licensed users
CodeAuditor 14.0.0 - Possibly broken
codeblocks 17.12 [Approved]
codecontracts 1.9.10714.2 [Approved] Downloads cached for licensed users
codecov 1.7.1 [Approved]
codelite 13.0 [Approved]
codemaid 11.0.183 [Approved]
coderush-vs2015 18.2.9 [Approved] Downloads cached for licensed users
codetrack 1.0.3.301 [Approved]
CoffeeScript 1.3.1.01
colemak 1.2 [Approved] Downloads cached for licensed users
CollapseSolution 2.0.0
collectdwin 0.5.19 [Approved] Downloads cached for licensed users
collectw.service 1.0.32.0 [Approved]
color-quantizer 0.7.4.4 [Approved] Downloads cached for licensed users
color-sustainer 1.05 [Approved]
colora 0.2.0 [Approved]
ColorCat.portable 0.0.4 [Approved] Downloads cached for licensed users
colorconsole 2.51 [Approved] - Possibly broken
colorconsole.install 4.03 [Approved] Downloads cached for licensed users
colorconsole.portable 4.03 [Approved] Downloads cached for licensed users
colorcop 5.4.3.20130420 - Possibly broken
ColorDesker 2.2.611.1122 - Possibly broken
colorfultabs-firefox 31.0.8 [Approved] - Possibly broken
colormania 6.3 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
ColorPic 4.1 - Possibly broken
colortool 19.04.29002 [Approved] Downloads cached for licensed users
com0com 3.0.0
combofix 18.8.8.1 [Approved] Downloads cached for licensed users
comfortclipboardpro 9.1.0.20190603 [Approved] Downloads cached for licensed users
comic-collector 19.3.3 [Approved] Downloads cached for licensed users
ComicRack 0.9.178.20161008 [Approved] Downloads cached for licensed users
comicreader-plex 1.3.5 [Approved] Downloads cached for licensed users
commandbox 1.0.0
commandtaskrunner 1.3.46 [Approved]
commandWindowHere 1.0.2 [Approved]
commentremover 1.1.8 [Approved] Downloads cached for licensed users
commit 0.0.6 [Approved]
commitmonitor 1.11.2.1123 [Approved]
commitmonitor.install 1.11.2.1123 [Approved] Downloads cached for licensed users
commitmonitor.portable 1.11.2.1123 [Approved] Downloads cached for licensed users
comodo-cocc 6.17.11191.18031 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
comodo-remote 6.17.11326.18031 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
compact-timer 2.4.0.20130816
compactgui 2.6.2 [Approved]
compareit 4.2.0
compassion 1.19 [Approved]
composer 4.10.0 [Approved]
composercat 0.4.0 [Approved] Downloads cached for licensed users
conadvpass 1.01 [Approved] Downloads cached for licensed users
conan 1.11.1 [Approved] Downloads cached for licensed users
concert.env 1.0.20140417 - Possibly broken
concerteenv 1.2.0 - Possibly broken
concourse 5.4.0 [Approved]
ConEmu 19.7.14.0 [Approved] Downloads cached for licensed users
confide 1.8.0 [Approved] Downloads cached for licensed users
confuser 1.9 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
confuserex 1.0.0 [Approved] Downloads cached for licensed users
connectwise 17.1.1.3 [Approved] Downloads cached for licensed users
connectwise-manage-client 2017.03 [Approved] Downloads cached for licensed users
connexion 2.63 [Approved] Downloads cached for licensed users
console-devel 2.00.148
Console2 2.0.148.20140727 [Approved]
consoleclassix 4.30.0 [Approved] Downloads cached for licensed users
ConsoleZ 1.19.0.19104 [Approved] Downloads cached for licensed users
ConsoleZ. Settings 1.0.0.20141027 [Approved] - Possibly broken
ConsoleZ. WithPin 1.12.0.14282
consul 1.5.2 [Approved]
consul-template 0.14.0 [Approved]
ContentSync 1.4.0 [Approved]
contextconsole 2.1.0.20171024 [Approved]
contig 1.80 [Approved] Downloads cached for licensed users
continuainit 1.2.0 [Approved]
continuum 0.40 - Possibly broken
contract-tools 1.30.2.0 [Approved] Downloads cached for licensed users
convertall 0.6.0 [Approved] Downloads cached for licensed users
coolbeans 2018.12 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
copay 4.6.2 [Approved] Downloads cached for licensed users
copy 1.43.0290 - Possibly broken
copyfilename 2.2.022.20160824 [Approved] Downloads cached for licensed users
copypathmenu 4.0 [Approved] Downloads cached for licensed users
copyq 3.9.0 [Approved]
Coq 8.9.1 [Approved] Downloads cached for licensed users
coreinfo 3.31 [Approved] Downloads cached for licensed users
coretemp 1.14 [Approved] Downloads cached for licensed users
corretto11jdk 11.0.4.11 [Approved]
corretto8jdk 8.222.10.3 [Approved]
corretto8jre 8.222.10.3 [Approved]
correttojdk 11.0.4.11 [Approved]
corsixth 0.63 [Approved]
corsixth.install 0.63 [Approved]
corsixth.portable 0.63 [Approved]
corvusskk 2.7.8 [Approved]
cosmosdbexplorer 0.7.5.0 [Approved] Downloads cached for licensed users
couchbase-server-community 4.5.0 [Approved] Downloads cached for licensed users
couchdb 1.2.0 - Possibly broken
CouchPotato 2012.11.04.1 - Possibly broken
countrytraceroute 1.30 [Approved] Downloads cached for licensed users
CovenantEyes 4.5.3.2302 - Possibly broken
coyim 0.3.11.20190702 [Approved] Downloads cached for licensed users
cp210x-vcp-drivers 6.7.6.2130 [Approved] Downloads cached for licensed users
cp210x-vcp-drivers-win10 10.1.3 [Approved]
cpfixit 5.0.16772.0 [Approved] Downloads cached for licensed users
cpfox 45.1.2 [Approved] Downloads cached for licensed users
cports 2.60 [Approved] Downloads cached for licensed users
cppcheck 1.88 [Approved] Downloads cached for licensed users
cprocess 1.13 [Approved] Downloads cached for licensed users
cpu-z 1.89.0.20190626 [Approved]
cpu-z.install 1.89.0.20190626 [Approved]
cpu-z.portable 1.89.0.20190627 [Approved] Downloads cached for licensed users
crane 0.2.0.15 [Approved]
CrashPlan 4.8.3 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
CrashPlanPRO 4.6.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
crawl 0.22.1 [Approved] Downloads cached for licensed users
crealogix-paymaker-office 5.0.8.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
create-synchronicity 6.0 [Approved]
create-synchronicity.install 6.0 [Approved] Downloads cached for licensed users
create-synchronicity.portable 6.0 [Approved] Downloads cached for licensed users
cronical 1.3 [Approved]
cropper 1.9.4.20141123 [Approved] - Possibly broken
croscorefonts-font 1.31.0 [Approved]
crosextrafonts-caladea-font 2013.02.14 [Approved]
crosextrafonts-carlito-font 2013.09.20 [Approved]
crossftp 1.96.4 [Approved]
crowdinspect 1.5.0 [Approved] Downloads cached for licensed users
crowleer 1.7 [Approved] Downloads cached for licensed users
cruisecontrol.net 1.8.5.0 [Approved] - Possibly broken
cryenginesdk 3.5.8 - Possibly broken
cryptcp 5.0.10804 [Approved] Downloads cached for licensed users
cryptoarm 5.3.0.8941 [Approved] Downloads cached for licensed users
cryptomator 1.4.6 [Approved]
cryptool1 1.4.41 [Approved]
cryptopro-browser-plugin 2.0.13738.0 [Approved]
cryptopro-csp 4.0.9842.0 [Approved] Downloads cached for licensed users
cryptopro-office-signature 2.0.11980 [Approved] Downloads cached for licensed users
cryptopro-pdf 2.0.0811 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
cryptopro-ssf 1.0.10908.0 [Approved] Downloads cached for licensed users
cryptopro-stunnel 3.06.3773.0000 [Approved] Downloads cached for licensed users
cryptsync 1.2.7 [Approved] Downloads cached for licensed users
crystaldiskinfo 8.2.3 [Approved]
crystaldiskinfo.install 8.2.3 [Approved] Downloads cached for licensed users
crystaldiskinfo.portable 8.2.3 [Approved] Downloads cached for licensed users
crystaldiskmark 6.0.2 [Approved] Downloads cached for licensed users
crystalexplorer 17.5 [Approved] Downloads cached for licensed users
crystalreports-for-visualstudio 13.0.25.3158 [Approved] Downloads cached for licensed users
CrystalReports2008Runtime 12.4.1 - Possibly broken
CrystalReports2010Runtime 13.0.18 [Approved] Downloads cached for licensed users
cs-script 3.29.0.0 [Approved]
cs-script.core 1.2.1.0 [Approved] Downloads cached for licensed users
CShell 0.1.2.3 [Approved] Downloads cached for licensed users
cspclean 5.0.16002.0 [Approved] Downloads cached for licensed users
CSVConverter 3.1
csved 2.3.2
csvfileview 2.41 [Approved] Downloads cached for licensed users
ctags 5.8.1
ctie 1.01 [Approved] Downloads cached for licensed users
ctop 0.7.2 [Approved] Downloads cached for licensed users
ctrl2cap 2.00 [Approved] Downloads cached for licensed users
ctt 1.0.1 [Approved] Downloads cached for licensed users
CType 1.00.0004 [Approved]
cubepdf 1.0.0.200 [Approved] Downloads cached for licensed users
cubepdfutility 0.5.3 [Approved] Downloads cached for licensed users
cuda 10.1.243 [Approved]
cue 3.13.94 [Approved] Downloads cached for licensed users
cuemounter 0.5 [Approved] Downloads cached for licensed users
cuemounter.portable 0.5 [Approved] Downloads cached for licensed users
cupboard 0.1.0.20130307
Cura 15.04.6 [Approved]
cura-lulzbot 3.6.18 [Approved] Downloads cached for licensed users
cura-new 4.2.1 [Approved] Downloads cached for licensed users
curl 7.65.3 [Approved]
curse-voice 1.0 [Approved] - Possibly broken
cursor-commander 1.0.0.0 [Approved]
customexplorertoolbar 1.05 [Approved] Downloads cached for licensed users
CutePDF 3.2 [Approved] Downloads cached for licensed users
cvtvt 0.60 [Approved]
cwcli 0.2.0
cyberduck 7.0.2.30998 [Approved] Downloads cached for licensed users
cyberduck.install 6.4.6.27773 [Approved] Downloads cached for licensed users
cyberfox 52.9.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
cyg-get 1.2.1 [Approved]
Cygwin 3.0.7 [Approved]
cyohash 1.0.11.20120929 - Possibly broken
cytoscape 3.7.1 [Approved] Downloads cached for licensed users
d-link-network-assistant 2.0.2.4 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
d2codingfont 1.3.2 [Approved] Downloads cached for licensed users
Dable 1.2.1 [Approved]
DacFx-18 15.0.4316.1 [Approved] Downloads cached for licensed users
dacia-media-nav-toolbox 3.18.5.753187 [Approved] Downloads cached for licensed users
dahua-web-plugin 3.1.0.486876 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
dar 2.6.5 [Approved] Downloads cached for licensed users
DarkOberon 1.0.2 [Approved] Downloads cached for licensed users
DarkRoom 0.8.1
darksoulsmapviewer 0.2.0.20160511 [Approved] Downloads cached for licensed users
darktable 2.6.2 [Approved] Downloads cached for licensed users
dart-sdk 2.4.1 [Approved] Downloads cached for licensed users
dart-sdk-dev 2.0.0.49 [Approved] Downloads cached for licensed users
DartEditor 1.5.8 [Approved]
dartium 1.24.3 [Approved] Downloads cached for licensed users
dashcore 0.12.0.58 [Approved] Downloads cached for licensed users
dashlane 6.1920.0.20431 [Approved]
dashlane-chrome 1.0.0 [Approved]
data-lifeguard-diagnostic 1.36 [Approved] Downloads cached for licensed users
data-lifeguard-diagnostic.portable 1.36 [Approved]
data-saver-chrome 2.0.2 [Approved]
database-searcher 1.04.0 [Approved]
databasemaster 8.3.9 [Approved] Downloads cached for licensed users
databasenet 28.4.7159.3 [Approved] Downloads cached for licensed users
databasenetpro 28.4.7161.4 [Approved] Downloads cached for licensed users
datacleaner 5.1.5 [Approved] Downloads cached for licensed users
datacrow 4.1.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
datagrip 2019.2.1 [Approved] Downloads cached for licensed users
datahealthcheck 1.7.1 [Approved] Downloads cached for licensed users
datamash 1.0.6 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
datapixels 1.1.0 [Approved] Downloads cached for licensed users
dataram-ramdisk 4.4.0.36 [Approved] Downloads cached for licensed users
datastar 1.7.0.14 [Approved] Downloads cached for licensed users
datastax.community 2.1.0 - Possibly broken
datomic-free 0.9.5067 [Approved]
dattodrive 2.3.1.923 [Approved] Downloads cached for licensed users
db-visualizer 10.0.17 [Approved] Downloads cached for licensed users
dbachecks 1.2.12 [Approved]
dbatools 1.0.33 [Approved]
dbeaver 6.1.4 [Approved]
dbeaver-ee 6.1.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
dbforge-mysql-cb-std 8.1.1 [Approved] Downloads cached for licensed users
dbforge-mysql-dc 5.5.20 [Approved] Downloads cached for licensed users
dbforge-mysql-dg 2.2.18 [Approved] Downloads cached for licensed users
dbforge-mysql-doc-std 1.2.20 [Approved] Downloads cached for licensed users
dbforge-mysql-qb 4.4.22 [Approved] Downloads cached for licensed users
dbforge-mysql-sc 4.4.20 [Approved] Downloads cached for licensed users
dbforge-mysql-studio-ent 8.2 [Approved] Downloads cached for licensed users
dbforge-mysql-studio-exp 8.2 [Approved] Downloads cached for licensed users
dbforge-mysql-studio-pro 8.2 [Approved] Downloads cached for licensed users
dbforge-mysql-studio-std 8.2 [Approved] Downloads cached for licensed users
dbforge-ora-cb-pro 4.1.20 [Approved] Downloads cached for licensed users
dbforge-ora-dc-exp 5.0.8 [Approved] Downloads cached for licensed users
dbforge-ora-dc-std 5.1.25 [Approved] Downloads cached for licensed users
dbforge-ora-dg 2.1.29 [Approved] Downloads cached for licensed users
dbforge-ora-doc-std 1.1.24 [Approved] Downloads cached for licensed users
dbforge-ora-sc 4.1.23 [Approved] Downloads cached for licensed users
dbforge-ora-studio-ent 4.1.48 [Approved] Downloads cached for licensed users
dbforge-ora-studio-ent-32 4.1.48 [Approved] Downloads cached for licensed users
dbforge-ora-studio-exp 3.10.12 [Approved] Downloads cached for licensed users
dbforge-ora-studio-exp-32 3.10.12 [Approved] Downloads cached for licensed users
dbforge-ora-studio-pro 3.10.12 [Approved] Downloads cached for licensed users
dbforge-ora-studio-pro-32 3.10.12 [Approved] Downloads cached for licensed users
dbforge-pg-dc 3.1.7.1 [Approved] Downloads cached for licensed users
dbforge-postgre-studio 2.1 [Approved] Downloads cached for licensed users
dbforge-sql 4.0.52 [Approved] - Possibly broken
dbforge-sql-cb-pro 5.5.6 [Approved] Downloads cached for licensed users
dbforge-sql-cb-std 5.5.6 [Approved] Downloads cached for licensed users
dbforge-sql-cmpl-exp 5.7.210 [Approved] Downloads cached for licensed users
dbforge-sql-cmpl-std 5.7.210 [Approved] Downloads cached for licensed users
dbforge-sql-db-pro 5.5.6 [Approved] Downloads cached for licensed users
dbforge-sql-dc-pro 4.3.106 [Approved] Downloads cached for licensed users
dbforge-sql-dc-std 4.3.106 [Approved] Downloads cached for licensed users
dbforge-sql-decrypt 3.1.24 [Approved] Downloads cached for licensed users
dbforge-sql-dg 4.0.92 [Approved] Downloads cached for licensed users
dbforge-sql-doc 1.2.86 [Approved] Downloads cached for licensed users
dbforge-sql-ep 1.3.61 [Approved] Downloads cached for licensed users
dbforge-sql-qb 3.12.56 [Approved] Downloads cached for licensed users
dbforge-sql-sc-pro 4.4.92 [Approved] Downloads cached for licensed users
dbforge-sql-sc-std 4.4.92 [Approved] Downloads cached for licensed users
dbforge-sql-studio-ent 5.5.369 [Approved] Downloads cached for licensed users
dbforge-sql-studio-exp 5.5.369 [Approved] Downloads cached for licensed users
dbforge-sql-studio-pro 5.5.369 [Approved] Downloads cached for licensed users
dbforge-sql-studio-std 5.5.369 [Approved] Downloads cached for licensed users
dbforge-studio-mysql-ru 6.1.166 - Possibly broken
dbForgesqlru 4.0.35 [Approved]
dbforgesqlstudio-ent-trial 5.5.311 [Approved] Downloads cached for licensed users
dbforgesqlstudio-pro-trial 5.5.311 [Approved] Downloads cached for licensed users
dbforgesqlstudio-std-trial 5.5.311 [Approved] Downloads cached for licensed users
dbforgesqlstudioexp 5.5.311.1 [Approved] Downloads cached for licensed users
dbgl 0.90.0 [Approved] Downloads cached for licensed users
dbgview 4.81 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
dbkoda 0.8.0 [Approved] Downloads cached for licensed users
dbmigration 11.1.7156.1 [Approved] Downloads cached for licensed users
dbr 5.2.0 [Approved]
dbsync 0.4.1 [Approved]
dcmtk 3.6.4.20190212 [Approved] Downloads cached for licensed users
dcplusplus.portable 0.867.0020180405 [Approved] Downloads cached for licensed users
dd 0.5 [Approved] - Possibly broken
ddecmd 1.6 [Approved]
ddev 1.10.2 [Approved] Downloads cached for licensed users
dds-thumbnail-viewer 1.0.1.001 [Approved] Downloads cached for licensed users
ddu 18.0.1.6 [Approved]
de4dot 0.0.0.15 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
debugdiagnostic 2.2.0.14 [Approved] Downloads cached for licensed users
DebugView 4.81.0.20160210 [Approved] - Possibly broken
deeparmor 2.0.0 [Approved] Downloads cached for licensed users
deepgit 3.2 [Approved] - Possibly broken
deepview 4.10.0.20161116 [Approved] Downloads cached for licensed users
deezer 4.13.4 [Approved] Downloads cached for licensed users
default.template 1.0.0 [Approved]
DefaultProgramsEditor 2.7.2675.2253
defender-injector 1.1 [Approved] Downloads cached for licensed users
DeflOpt 2.0.7 - Possibly broken
defraggler 2.22.995.20181017 [Approved] Downloads cached for licensed users
deimos-driver 1.0.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
dejavufonts 2.37 [Approved] Downloads cached for licensed users
DeleGate 9.9.7 [Approved]
DeleteFiles 1.14 [Approved] Downloads cached for licensed users
dell-omsa 7.2.0.121620132
dell-platform-tags-utility 4.0.27.0 [Approved] Downloads cached for licensed users
dell-update 3.0.1 [Approved] Downloads cached for licensed users
DellCommandUpdate 2.4.0 [Approved] Downloads cached for licensed users
dellcommandupdate-uwp 3.0.1 [Approved] Downloads cached for licensed users
deluge 1.3.15 [Approved] Downloads cached for licensed users
demo.rest.service 1.0.0.3
demohelper 1.3 [Approved] Downloads cached for licensed users
dep 0.5.0 [Approved] Downloads cached for licensed users
dependency-scanner 0.2.0.1 [Approved]
dependency-server2016 2016.1803 [Approved]
dependency-server2019 2019.0 [Approved]
dependency-windows10 10.1903 [Approved]
dependencywalker 2.2.6000.9 [Approved] Downloads cached for licensed users
depressurizer 0.7.4.2 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
designreview 2017.05.24 [Approved] Downloads cached for licensed users
designsparkpcb 6.1 - Possibly broken
desk-drive 2.1.1 [Approved] Downloads cached for licensed users
deskpins 1.32.1 [Approved] Downloads cached for licensed users
deskspace 1.5.8.13 [Approved] - Possibly broken
desktop-notifications-for-android-chrome 4.5.2 [Approved]
desktop-tech 0.13.0 [Approved] Downloads cached for licensed users
desktopicons-winconfig 0.0.1 [Approved]
desktopok 6.45 [Approved]
Desktops 2.0 [Approved] Downloads cached for licensed users
desura 100.53.20141201 [Approved] - Possibly broken
devaudit 3.0.0.3 [Approved] Downloads cached for licensed users
Devbox-Clink 0.4.2.14045 [Approved] - Possibly broken
Devbox-Common 1.0.2
Devbox-Common.extension 1.0.1
Devbox-ConEmu 0.0.0.20130422 - Possibly broken
Devbox-Git 1.8.1.20130422 - Possibly broken
Devbox-GitFlow 0.0.0
Devbox-GitSettings 1.0.1
Devbox-Nano 2.2.6.20130417
Devbox-Notepad2 4.2.25 - Possibly broken
Devbox-P4Merge 131.61.1503 - Possibly broken
Devbox-RapidEE 0.0.0.20141226 [Approved] - Possibly broken
Devbox-Sed 4.2.1 - Possibly broken
Devbox-UnZip 5.52 - Possibly broken
Devbox-VCRedist2010 10.0.40219.20130422
Devbox-Wget 1.11.4.1 - Possibly broken
devcon.portable 10.0.10586.23 [Approved]
devdocs-app 0.6.9 [Approved] Downloads cached for licensed users
deveimageoptimizerwpf 1.0.121 [Approved]
deviceioview 1.05 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
devmanview 1.56 [Approved] Downloads cached for licensed users
dewey 0.0.16 [Approved]
dex2jar 2.0 [Approved] Downloads cached for licensed users
dexed 0.9.4 [Approved]
dexpot 1.6.13
dfu-util 0.7.1 - Possibly broken
dia 0.97.2.2
Dialang 1.0.0.001 - Possibly broken
dialupass 3.60 [Approved]
die 2.03 [Approved]
diffmerge 4.2.0.20170602 [Approved] Downloads cached for licensed users
diffuse 0.4.8.1 [Approved] - Possibly broken
diffutils 2.8.7 [Approved] Downloads cached for licensed users
digiKam 6.1.0 [Approved] Downloads cached for licensed users
digime 7.1.5 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
digimizer 5.3.5 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
digsby 0.91.30192 [Approved] - Possibly broken
dilay 1.9.0 [Approved]
dink-smallwood 1.4.7 [Approved] Downloads cached for licensed users
directorymonitor 2.13.0.4 [Approved] Downloads cached for licensed users
directoryopus 12.16 [Approved] Downloads cached for licensed users
directx 9.29.1974.20180606 [Approved] Downloads cached for licensed users
dirsyncpro 1.53 [Approved] Downloads cached for licensed users
disable-nvidia-telemetry 1.1.0.20190306 [Approved] Downloads cached for licensed users
disable-nvidia-telemetry.portable 1.1.0 [Approved] Downloads cached for licensed users
disable-smb-v1 1.0.0 [Approved]
disable-windows10-upgrade 1.2.0 [Approved]
disabledefender-winconfig 0.0.1 [Approved]
disableofficemacros-winconfig 0.0.1 [Approved]
disableofficenag-winconfig 0.0.1 [Approved]
disableuac 0.0.3 [Approved]
disablewintracking 3.2.3 [Approved] Downloads cached for licensed users
discord 0.0.305 [Approved]
discord.install 0.0.305 [Approved] Downloads cached for licensed users
discordchatexporter 2.11 [Approved] Downloads cached for licensed users
discoverj 2.5.4 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
disk-wipe 1.7 [Approved] Downloads cached for licensed users
disk2vhd 2.01.0.20160213 [Approved] Downloads cached for licensed users
diskcountersview 1.27 [Approved] Downloads cached for licensed users
diskdefragtouch 8.0.12.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
diskdump 0.1.0 [Approved] Downloads cached for licensed users
diskext 1.20 [Approved] Downloads cached for licensed users
diskmarkstream 1.1.2 [Approved] Downloads cached for licensed users
diskmon 2.01 [Approved] Downloads cached for licensed users
disksmartview 1.21 [Approved] Downloads cached for licensed users
diskspd 2.0.21 [Approved]
diskview 2.40 [Approved] Downloads cached for licensed users
dispcalgui 3.8.5.0 [Approved]
dispcalgui.install 3.8.5.0 [Approved]
dispcalgui.portable 3.8.5.0 [Approved]
displaycal 3.8.5.0 [Approved]
displaycal.portable 3.8.5.0 [Approved]
displayFusion 9.5 [Approved]
displaylink 9.2.0 [Approved] Downloads cached for licensed users
disposablefixer 1.6.0 [Approved]
dissenter-browser 0.66.99 [Approved] Downloads cached for licensed users
ditto 3.22.20.0 [Approved]
ditto.install 3.22.20.0 [Approved]
ditto.portable 3.22.20.0 [Approved]
dive 0.7.2 [Approved] Downloads cached for licensed users
divvy 1.4.4 [Approved] Downloads cached for licensed users
djv 2.0.3 [Approved]
dllexp 1.66 [Approved] Downloads cached for licensed users
dmd 2.087.0 [Approved] Downloads cached for licensed users
dmde 3.4.4.740 [Approved]
dmg2img 1.6.7 [Approved] Downloads cached for licensed users
dngrep 2.9.163.0 [Approved]
dnncmd 3.7.523.0 [Approved]
dns-benchmark 1.3.6668.20190425 [Approved]
dnsagent 1.6.5781.1 [Approved]
dnscontrol 2.9 [Approved]
dnscrypt-proxy 2.0.25 [Approved]
dnsdataview 1.56 [Approved] Downloads cached for licensed users
dnsjumper 2.1 [Approved]
dnspy 6.0.5 [Approved] Downloads cached for licensed users
dnsquerysniffer 1.80 [Approved] Downloads cached for licensed users
docash-vega-driver 3.3.2011.11 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
docash-vega-firmware 29.20171109 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
docbook-bundle 1.0.0 [Approved] Downloads cached for licensed users
DocConverter 3.1
docear.install 1.2 [Approved] Downloads cached for licensed users
docear.portable 1.2 [Approved] Downloads cached for licensed users
docear4word 1.30.00 - Possibly broken
docfetcher 1.1.22 [Approved] Downloads cached for licensed users
docfx 2.44 [Approved] Downloads cached for licensed users
docker 99.0.0 [Approved]
docker-cli 18.09.6 [Approved] Downloads cached for licensed users
docker-compose 1.24.0 [Approved] Downloads cached for licensed users
docker-desktop 2.1.0.1 [Approved] Downloads cached for licensed users
docker-for-windows 99.0.0.0 [Approved]
docker-kitematic 0.17.7 [Approved]
docker-machine 0.16.1 [Approved] Downloads cached for licensed users
docker-machine-sakuracloud 1.4.0.29 [Approved]
docker-machine-vmware 0.1.0 [Approved] Downloads cached for licensed users
docker-machine-vmwareworkstation 1.1.0 [Approved] Downloads cached for licensed users
docker-toolbox 19.03.1 [Approved] Downloads cached for licensed users
docker-watch-forwarder 0.1.0 [Approved]
dogecoin 1.10.0 [Approved]
dogecoin.install 1.10.0 [Approved] Downloads cached for licensed users
dogecoin.portable 1.10.0 [Approved] Downloads cached for licensed users
Dogtail. AzureSDK 11.2.13230.2 - Possibly broken
Dogtail. AzureSDK.2.1. VisualStudio2102 11.2.13230.2 - Possibly broken
Dogtail. DevEnv 11.2.13214.1 - Possibly broken
Dogtail. DotNet3.5SP1 11.2.13230.2
Dogtail. VisualStudio2012Ultimate 11.2.13230.2
Dogtail. VisualStudio2013UltimatePreview 11.2.13230.2 - Possibly broken
Dogtail. VisualStudioToolsforGit 11.2.13230.2 - Possibly broken
Dogtail. VS2012.1 11.2.13230.2
Dogtail. VS2012.2 11.2.13230.2
Dogtail. VS2012.2. CTP 11.2.13054.3 - Possibly broken
Dogtail. VS2012.3 11.2.13230.2
dokan-library 0.6.0.20160211 [Approved]
dokandiscutils 0.1 [Approved] Downloads cached for licensed users
dokany 1.2.2.1001 [Approved]
dokany-redistributable 1.2.0.1020181219 [Approved]
dolphin 5.0 [Approved] Downloads cached for licensed users
domainhostingview 1.82 [Approved] Downloads cached for licensed users
donkeykong 3.0 [Approved]
donkeykongjr 2012.03.20 [Approved]
dontsleep 5.57 [Approved]
dontsleep.install 5.57 [Approved]
dontsleep.portable 5.57 [Approved]
doom-sigil 1.1.0 [Approved] Downloads cached for licensed users
doomseeker 1.2.0 [Approved] Downloads cached for licensed users
dopamine 2.0 [Approved] Downloads cached for licensed users
doPDF 10.2.114 [Approved] Downloads cached for licensed users
dos2unix 7.4.0 [Approved]
dosbox 0.74.0.0 - Possibly broken
dotCover 2019.2 [Approved]
dotcover-cli 2019.1 [Approved] Downloads cached for licensed users
dotlocal 0.1.37 [Approved] Downloads cached for licensed users
dotMemory 2019.2 [Approved]
dotmemory-unit 3.0.20171219.105559 [Approved]
dotmemory-unit.portable 3.0.20171219.105559 [Approved] Downloads cached for licensed users
DotNet-4.6.2 4.6.01586.001 [Approved] - Possibly broken
dotnet-verification-tool 4.6.01528.0 [Approved] Downloads cached for licensed users
dotnet-version 1.1.0 [Approved]
dotnet.script 0.30.0 [Approved]
dotnet1.1 1.1 [Approved] Downloads cached for licensed users
DotNet3.5 3.5.20160716 [Approved]
DotNet4.0 4.0.30319.20141222 [Approved]
DotNet4.5 4.5.20120822 [Approved]
DotNet4.5.1 4.5.1.20140606 [Approved]
DotNet4.5.2 4.5.2.20140902 [Approved]
DotNet4.6 4.6.00081.20150925 [Approved] - Possibly broken
DotNet4.6-TargetPack 4.6.00081.20150925 [Approved] - Possibly broken
DotNet4.6.1 4.6.01055.20170308 [Approved]
DotNet4.6.1-DevPack 4.6.01055.0 [Approved] - Possibly broken
dotnet4.6.2 4.6.01590.20190226 [Approved]
dotnet4.6.2-deu 4.6.1590.20181011 [Approved] Downloads cached for licensed users
dotnet4.7 4.7.2053.20190226 [Approved]
dotnet4.7.1 4.7.2558.20190226 [Approved]
dotnet4.7.2 4.7.2.20180712 [Approved]
dotnet4.7.2-deu 4.7.3062.0 [Approved]
dotnetcore 2.2.6 [Approved]
dotnetcore-runtime 2.2.6 [Approved]
dotnetcore-runtime.install 2.2.6 [Approved]
dotnetcore-runtime.portable 2.2.3 [Approved]
dotnetcore-sdk 2.2.401 [Approved] Downloads cached for licensed users
dotnetcore-windowshosting 2.2.6 [Approved] Downloads cached for licensed users
dotnetcoresdk 1.0.1 [Approved] Downloads cached for licensed users
dotnetdash 1.0.0 [Approved] Downloads cached for licensed users
DotNetDeveloperBundle 2.3.2.2621 [Approved]
dotnetfx 4.7.2.20180712 [Approved]
dotnetinstaller 2.4 [Approved] Downloads cached for licensed users
dotnetresourcesextract 1.01 [Approved] Downloads cached for licensed users
DotNetSdk1.1 1.1.4322 [Approved] Downloads cached for licensed users
dotnetversiondetector 17.1.2 [Approved]
dotPeek 2019.2 [Approved]
dotpeek.portable 10.0.2.1 [Approved] Downloads cached for licensed users
dotTrace 2019.2 [Approved]
dotTrace-memory 4.2 [Approved] - Possibly broken
doublecadxt 5.0.30.2 [Approved] Downloads cached for licensed users
doublecmd 0.9.5 [Approved] Downloads cached for licensed users
doubledriver 4.1 [Approved]
doulossil 5.0 [Approved]
downloadapp 1.7.0.190 - Possibly broken
downtester 1.30 [Approved]
downtester.install 1.30 [Approved] Downloads cached for licensed users
downtester.portable 1.30 [Approved] Downloads cached for licensed users
doxygen.install 1.8.15 [Approved] Downloads cached for licensed users
doxygen.portable 1.8.11 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
draft 0.16.0 [Approved]
draftsight 2019.00 [Approved] Downloads cached for licensed users
DragLock 1.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
dragondisk 1.05 - Possibly broken
drawio 11.1.1 [Approved] Downloads cached for licensed users
drawpile 2.1.11 [Approved] Downloads cached for licensed users
dreampie 1.2.1 [Approved] Downloads cached for licensed users
dripcap 0.6.15.20190312 [Approved]
driveletterview 1.45 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
driver-officegate 1.0.0.0 [Approved] Downloads cached for licensed users
driverbooster 6.6.0.500 [Approved]
driverfusion 7.1 [Approved]
drivergenius 19.0.0.145 [Approved] Downloads cached for licensed users
drivermax 10.19.0.63 [Approved] Downloads cached for licensed users
driverpacksolution 17.2017.2.22 [Approved] Downloads cached for licensed users
driverview 1.47 [Approved] Downloads cached for licensed users
drivesnapshot 1.47.18523 [Approved]
DRKSpider 3.2 [Approved] - Possibly broken
drmemory 2.1.17972 [Approved] Downloads cached for licensed users
drmemory.install 1.11.0.20190311 [Approved]
drmemory.portable 1.11.0.20190311 [Approved]
drobo-dashboard 3.4.2 [Approved]
DroidFonts 4.0.0 [Approved] - Possibly broken
DroidSansMono 2014.12.31 [Approved]
dropbox 79.4.143 [Approved] Downloads cached for licensed users
dropbox-for-gmail-chrome 1.1.6 [Approved]
dropboxifier 0.1.8 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
dropit 8.5.1 [Approved]
dropit.install 8.5.1 [Approved] Downloads cached for licensed users
dropit.portable 8.5.1 [Approved] Downloads cached for licensed users
dropkick 0.4.13.0 [Approved]
dropkick.core 0.4.13.0 [Approved]
drush.commandline 5.1.2
ds4windows 1.7.15 [Approved] Downloads cached for licensed users
DSC. ComputerManagement 1.2 - Possibly broken
DSC. DscResourceDesigner 1.1.1 - Possibly broken
DSC. HyperV 2.1 - Possibly broken
DSC. Networking 2.1.1.1 - Possibly broken
DSC. PowerShellCommunity 1.175.1 - Possibly broken
DSC. PSDesiredStateConfiguration 3.0.2.0 - Possibly broken
DSC. WebAdministration 1.3.2 - Possibly broken
dsinternals-psmodule 3.6 [Approved]
dspeech 1.73 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
dsynchronize 2.44 [Approved]
dtc-msys2 1.4.7 [Approved]
dtksneak 1.0.0.20150826 [Approved] Downloads cached for licensed users
du 1.61 [Approved] Downloads cached for licensed users
dual-monitor-tools 2.7.0.0 [Approved] Downloads cached for licensed users
dualism 1.09 [Approved]
dub 1.11.0 [Approved] Downloads cached for licensed users
duck 6.9.4.30164 [Approved] Downloads cached for licensed users
duckietv 1.1.5 [Approved] Downloads cached for licensed users
dukto 6.0.0.20192215 [Approved]
dumeter 6.40.20141201 [Approved] - Possibly broken
dumo 2.18.0.95 [Approved] Downloads cached for licensed users
dumpedid 1.06 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
dupeguru 4.0.4 [Approved] Downloads cached for licensed users
dupeguru-me 6.8.1 [Approved] Downloads cached for licensed users
dupeguru-pe 2.10.1 [Approved]
dupemerge 1.102 [Approved] Downloads cached for licensed users
duplicatecleaner 4.1.0 [Approved] Downloads cached for licensed users
duplicatefilefinder 8.0.0.2 [Approved] Downloads cached for licensed users
duplicati 2.0.4.6 [Approved] Downloads cached for licensed users
duplicati.portable 2.0.3.3 [Approved] Downloads cached for licensed users
durandal-extensions-vs2013 0.2.1 [Approved]
dvassist 2.0.1.6100 [Approved] Downloads cached for licensed users
dvddecrypter 3.5.4.1 [Approved] Downloads cached for licensed users
dvdflick 1.3.0.7 [Approved] Downloads cached for licensed users
dvdstyler 3.1.0 [Approved] Downloads cached for licensed users
dwarf-fortress 0.44.12 [Approved] Downloads cached for licensed users
dwgtrueview 2019.03.27 [Approved] Downloads cached for licensed users
dws.portable 2.2.2.2 [Approved] Downloads cached for licensed users
dymo-connect 1.1 [Approved] Downloads cached for licensed users
dymo-label 8.7.3 [Approved] Downloads cached for licensed users
dynamorio.drmemory 1.11.17918 [Approved] Downloads cached for licensed users
dynatraceagent 6.5.0.1289 [Approved] Downloads cached for licensed users
dynatraceclient 6.5.0.1289 [Approved] Downloads cached for licensed users
e-Haushaltsbuch 1.9.5 [Approved] Downloads cached for licensed users
eac 1.3.0.20171025 [Approved] Downloads cached for licensed users
eagle 7.6.0 [Approved] Downloads cached for licensed users
eagleget 2.0.5.30 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
ealite 14.1.1429 [Approved] Downloads cached for licensed users
earthview-chrome 2.18.5 [Approved]
Easy7zip 0.1.6 [Approved] Downloads cached for licensed users
easybcd 2.2.0.183 - Possibly broken
easyconnect 1.5.1.0
easycrypt 1.3.0.2 [Approved]
easylogusb 7.6.0 [Approved] Downloads cached for licensed users
easytag 2.4.3 [Approved] Downloads cached for licensed users
easytune6 15.0210.1.2 [Approved] - Possibly broken
eazfuscator.net 3.3 [Approved]
ebay-chrome 4.2.25 [Approved]
ec2clitools 1.7.5.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
echoargs 3.2.0 [Approved]
echotool 1.5.0.20150718 [Approved] Downloads cached for licensed users
eclipse 4.12 [Approved]
eclipse-classic-juno 4.2.2.003 - Possibly broken
eclipse-cpp-oxygen 2019.06 [Approved] Downloads cached for licensed users
eclipse-java-juno 4.2.20121004 - Possibly broken
eclipse-java-kepler 4.3.1
eclipse-java-luna 4.4
eclipse-java-oxygen 2019.06 [Approved] Downloads cached for licensed users
eclipse-javaee-juno 4.2.2 - Possibly broken
eclipse-jee-luna 4.4
eclipse-standard-kepler 4.3.20130917
eclipse-standard-luna 4.4
ecm 1.6.0.20190427 [Approved]
edgedeflector 1.1.3.0 [Approved]
edison 1.5.0.12 [Approved] Downloads cached for licensed users
editor-services-command-suite 0.4.0 [Approved]
editorconfig.core 0.12.1 [Approved]
editorconfig.vs 0.2.6 [Approved] - Possibly broken
editthiscookie-chrome 1.5.0 [Approved]
edrawings-viewer 18.3.0.0035 [Approved]
edrawings-viewer-2018 18.3.0.20190301 [Approved] Downloads cached for licensed users
edrawings-viewer-2019 27.1.0.0092 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
eduactiv8 3.80.411 [Approved]
eduke32 7.6.57 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
efsdump 1.02 [Approved] Downloads cached for licensed users
egnyte-connect 3.4.3.98 [Approved] Downloads cached for licensed users
eid-belgium 4.4.4 [Approved]
eid-belgium-viewer 4.4.12.4000 [Approved]
ekeyfinder 0.1.7 [Approved]
ekiga 4.0.1.01 [Approved]
eksctl 0.3.1 [Approved] Downloads cached for licensed users
elastic 1.5.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
elasticsearch 6.7.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
elasticsearch-service 1.4.1.20160203 [Approved] - Possibly broken
electron 1.8.4 [Approved] Downloads cached for licensed users
electron-cash 4.0.9 [Approved]
electron-cash.install 4.0.9 [Approved] Downloads cached for licensed users
electron-cash.portable 4.0.9 [Approved] Downloads cached for licensed users
electrum 3.1.2 [Approved]
electrum-dash 2.4.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
electrum-ltc 3.3.8.1 [Approved]
electrum-ltc.install 3.3.8.1 [Approved]
electrum-ltc.portable 3.3.8.1 [Approved]
electrum-mona 3.3.4 [Approved]
electrum-mona.install 3.3.4 [Approved] Downloads cached for licensed users
electrum.install 3.3.5 [Approved] Downloads cached for licensed users
electrum.portable 3.3.8 [Approved] Downloads cached for licensed users
elements 1.1.6 [Approved] Downloads cached for licensed users
elevate 1.1
elevate.native 1.3.0.20150904 [Approved] Downloads cached for licensed users
elinks 0.12.3.2
Elixir 1.9.1 [Approved]
elkjop-cloud 3.1.45.377 [Approved] Downloads cached for licensed users
ellp 86.20181230 [Approved]
elm-platform 0.19.0 [Approved] Downloads cached for licensed users
elsterformular 20.4.0 [Approved] Downloads cached for licensed users
em-client 7.2.35595 [Approved] Downloads cached for licensed users
Emacs 26.2.0.20190417 [Approved]
emacs64 25.3.1 [Approved] Downloads cached for licensed users
EmbestIDE 2002.0.0.001 - Possibly broken
EMDB 3.46 [Approved] Downloads cached for licensed users
emeditor 15.0.2 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
emet 5.52 [Approved] Downloads cached for licensed users
empv 1.00 [Approved] Downloads cached for licensed users
emsisoft-anti-malware 11.0.0.5958 [Approved] Downloads cached for licensed users
emsisoft-emergency-kit 2019.6.0.9501 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
emulationstation 2.0.1.01 [Approved]
emulationstation.install 2.0.1.01 [Approved] Downloads cached for licensed users
emulationstation.portable 2.0.1.01 [Approved] Downloads cached for licensed users
emule 0.50.01 [Approved] Downloads cached for licensed users
enableloopbackutility 1.2.0.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
encfs4win 1.10.1 [Approved]
encfsmp 0.11.1 [Approved]
encifer 1.5.1 [Approved] Downloads cached for licensed users
encryption-software 108.30.2019.1 [Approved]
encryptr 1.2.0 [Approved] Downloads cached for licensed users
energia 1.8.7.21 [Approved] Downloads cached for licensed users
enigmavirtualbox 9.20 [Approved] Downloads cached for licensed users
enki 16.4.1.20171105 [Approved]
enpass.install 5.6.9 [Approved] Downloads cached for licensed users
EntityFrameworkPowerTools-VS2013 0.9.0.0 - Possibly broken
envelope-printer 2.0.1 [Approved] Downloads cached for licensed users
EnvyCodeR 2015.01.02 [Approved]
epicgameslauncher 1.1.220.0 [Approved]
epr 2.2.7 [Approved]
EpsDevTools. Web 0.4.1 - Possibly broken
epson-perfection-v33-scanner 3.9.2.2 [Approved] Downloads cached for licensed users
equality 1.33 [Approved]
equalizerapo 1.2 [Approved] Downloads cached for licensed users
equick 1.15 [Approved]
equilibrium 1.58 [Approved]
eraser 6.2.0.2983 [Approved]
ericzimmermantools 2.5.2.2 [Approved]
erlang 22.0 [Approved] Downloads cached for licensed users
Erlang16 16.03.4
erpxe 1.2 [Approved] Downloads cached for licensed users
err 6.0.4011.20150904 [Approved] Downloads cached for licensed users
errorcatcher 1.7.40 [Approved] Downloads cached for licensed users
eSafe 1.3.0 [Approved] Downloads cached for licensed users
esedatabaseview 1.63 [Approved] Downloads cached for licensed users
eset.nod32 1.0.0.0
esgen 0.0.1 [Approved] - Possibly broken
essence 1.07 [Approved]
etcd 3.3.13 [Approved]
etcher 1.5.53 [Approved] Downloads cached for licensed users
EthanBrown. ChromeCanaryDevExtensions 0.0.2
EthanBrown. ChromeDevExtensions 0.0.2
EthanBrown. ConEmuConfig 0.0.5 [Approved] - Possibly broken
EthanBrown. DevTools. Web 0.3.1 - Possibly broken
EthanBrown. GitAliases 0.0.5
EthanBrown. GitConfiguration 0.0.4
EthanBrown. GitExtensionsConfiguration 0.0.1 - Possibly broken
EthanBrown. SublimeText2. EditorPackages 0.2.2 - Possibly broken
EthanBrown. SublimeText2. GitPackages 0.2.2 - Possibly broken
EthanBrown. SublimeText2. UtilPackages 0.2.2 - Possibly broken
EthanBrown. SublimeText2. WebPackages 0.3.0 - Possibly broken
ethminer 0.17.1 [Approved] Downloads cached for licensed users
eventghost 0.4.1.1723 [Approved] Downloads cached for licensed users
eventlogsourcesview 1.00 [Approved] Downloads cached for licensed users
eventstore 3.0.0.3 - Possibly broken
eventstore-oss 5.0.2 [Approved] Downloads cached for licensed users
EventStore-ServiceHost 1.0.0 [Approved]
eveonline 0.0.2 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
evernote 6.20.2.8626 [Approved]
evernote-chrome 6.10.3 [Approved]
evernote2onenote 1.2.2 [Approved] Downloads cached for licensed users
Everything 1.4.1935.20190602 [Approved]
everything.beta 1.3.3.658
everything.beta.install 1.3.3.658
everything.beta.portable 1.3.3.658
everything.portable 1.4.1.932 [Approved] Downloads cached for licensed users
evga-precision-xoc 6.2.7 [Approved] Downloads cached for licensed users
eviacam 2.1.0 [Approved] Downloads cached for licensed users
evimsync 1.0.0.118 [Approved] Downloads cached for licensed users
evince 2.32.0.145001 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
ewseditor 1.20 [Approved] Downloads cached for licensed users
exacqvision 9.0.3.124656 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
Excel. Viewer 12.0.6219.1000 - Possibly broken
ExcelConverter 3.2.2
exceptionless 3.2.2128.2 [Approved]
exceptionless-elasticsearch 2.2.0 [Approved] Downloads cached for licensed users
exchange-edb-viewer 15.9 [Approved] Downloads cached for licensed users
executedprogramslist 1.11 [Approved] Downloads cached for licensed users
Executor 0.99.11.1 - Possibly broken
exeinfo 1.01 [Approved] Downloads cached for licensed users
exercism-io-cli 3.0.12 [Approved] Downloads cached for licensed users
exifdataview 1.06 [Approved] Downloads cached for licensed users
exiftool 11.62 [Approved]
exiftoolgui 5.16 [Approved] Downloads cached for licensed users
exifviewer-chrome 2.4.4 [Approved]
expandrive 7.0.16 [Approved] Downloads cached for licensed users
explorer-expand-to-current-folder 1.0.1 [Approved]
explorer-show-all-folders 1.0.0 [Approved]
explorer-winconfig 0.0.1 [Approved]
Explorerplusplus 1.3.5
explorersuite 0.0.0.2012 [Approved] Downloads cached for licensed users
expressionblend 2.0.20525
ExpressionBlend3 1.0.1340.0 [Approved] - Possibly broken
ExpressionBlend4 2.0.20525 [Approved]
expressionweb 4.0.1460.0 [Approved]
expresso 3.0.4750 [Approved] - Possibly broken
expressvpn 7.1.0.7514 [Approved] Downloads cached for licensed users
expurgate 1.05 [Approved]
ext2explore 2.2.71.20100623 [Approved] Downloads cached for licensed users
ext2fsd 0.69.0.20171118 [Approved]
ext2ifs 1.12 [Approved] Downloads cached for licensed users
extensibilitytools 1.10.182 [Approved] Downloads cached for licensed users
extractnow 4.8.3.0 [Approved] Downloads cached for licensed users
eyeframeconverter 1.8.1 [Approved] - Possibly broken
EyesRelax 0.87.1
f-secureav 2.6.303.0 - Possibly broken
f-secureis 2.6.303.0 - Possibly broken
f.lux 4.104 [Approved]
f.lux.install 4.104 [Approved] Downloads cached for licensed users
f.lux.portable 4.104 [Approved] Downloads cached for licensed users
faas-cli 0.9.0 [Approved]
fab 1.6 [Approved]
factor 0.97 [Approved] Downloads cached for licensed users
fah 7.4.4 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
fake 5.15.4 [Approved]
fakenet 1.04 [Approved] Downloads cached for licensed users
FAQ 2.1.0.1
Far 3.0.5445 [Approved]
Far-2 2.0.1807 - Possibly broken
Far-3 3.0.4700 [Approved]
FastCopy 3.82 [Approved]
fastcopy.install 3.82 [Approved]
fastcopy.portable 3.82 [Approved]
fastglacier 3.4.7 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
fastimageresizer 0.98.20181007 [Approved] Downloads cached for licensed users
fastresolver 1.26 [Approved]
fastresolver.install 1.26 [Approved] Downloads cached for licensed users
fastresolver.portable 1.26 [Approved] Downloads cached for licensed users
favbinedit 1.2.4 [Approved] Downloads cached for licensed users
faviconizer 1.4 [Approved] Downloads cached for licensed users
faview 1.32 [Approved] Downloads cached for licensed users
fbcacheview 1.16 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
fbexport 1.90 [Approved] Downloads cached for licensed users
FBReader 0.12.10.20190728 [Approved]
fbvlc 0.1.5 [Approved] - Possibly broken
fciv 1.0.0.20150904 [Approved] Downloads cached for licensed users
fd 7.3.0 [Approved]
feathercoin 0.8.7.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
feeddemon 4.5.0.20160211 [Approved] Downloads cached for licensed users
feedly-chrome 35.0.20170115 [Approved]
feednotifier 2.6 [Approved]
ffdshow 1.3.4531.20140718
ffdshow-x86_32 1.3.4531.20160211 [Approved]
ffe 1.1 [Approved] Downloads cached for licensed users
ffftp 3.9 [Approved]
ffftp.install 3.9 [Approved] Downloads cached for licensed users
ffftp.portable 3.9 [Approved] Downloads cached for licensed users
ffmpeg 4.2 [Approved]
fiddler 5.0.20192.25091 [Approved]
figlet-go 1.0.0 [Approved] Downloads cached for licensed users
figma 75.0.0 [Approved] Downloads cached for licensed users
file-hash-generator 5.0.0 [Approved] Downloads cached for licensed users
filealyzer 2.0.5.57 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
fileassassin 1.06 [Approved] Downloads cached for licensed users
filebeat 7.3.0 [Approved] Downloads cached for licensed users
filebot 4.8.5 [Approved] Downloads cached for licensed users
filedrop 1.1.5.20171015 [Approved] Downloads cached for licensed users
FileFormatConverters 1.0.1 - Possibly broken
filejuggler 2.0.3 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
filelist 4.1.1 [Approved] Downloads cached for licensed users
filenesting 2.3.47 [Approved] Downloads cached for licensed users
FileOptimizer 13.90.2508 [Approved] Downloads cached for licensed users
fileseek 5.2.1 - Possibly broken
fileshredder 2.5.1 [Approved] Downloads cached for licensed users
filesing.portable 1.0.0 [Approved]
filetool 1.0.0.814 [Approved] Downloads cached for licensed users
filetypeeditor 3.1.4.20170309 [Approved] Downloads cached for licensed users
FileTypesMan 1.85 [Approved] Downloads cached for licensed users
filezilla 3.44.1 [Approved]
filezilla.commandline 3.26.2 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
filezilla.server 0.9.60.2 [Approved]
finalbuilder 8.0.0.2523 [Approved] Downloads cached for licensed users
find-and-run-robot 2.234.01 [Approved]
find-and-run-robot.install 2.234.01 [Approved] Downloads cached for licensed users
find-and-run-robot.portable 2.234.01 [Approved] Downloads cached for licensed users
findaes 1.2 [Approved] Downloads cached for licensed users
findandreplace 2.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
finddupe 1.23.0.20170921 [Approved] Downloads cached for licensed users
findlinks 1.10 [Approved] Downloads cached for licensed users
findthatfont 1.0.0 [Approved] Downloads cached for licensed users
fintender-installer 2.5.48 [Approved] Downloads cached for licensed users
fio 3.13.0.20190308 [Approved]
FiraCode 1.207 [Approved] Downloads cached for licensed users
FiraCode-ttf 1.207 [Approved] Downloads cached for licensed users
firealpaca 2.1.21 [Approved] Downloads cached for licensed users
firebird 3.0.4 [Approved]
firebird-odbc 2.0.5.156 [Approved] Downloads cached for licensed users
Firefox 68.0.2 [Approved]
firefoxdownloadsview 1.40 [Approved] Downloads cached for licensed users
FirefoxESR 60.8.0 [Approved]
fireshot-chrome 0.98.93.2 [Approved]
firessh 0.94.10 [Approved] - Possibly broken
firmwaretablesview 1.01 [Approved] Downloads cached for licensed users
Fitbit. Connect 2.0.0.6512 [Approved] - Possibly broken
Fitbit. Ultra 2.1.0.8 - Possibly broken
fl2k-win 0.1 [Approved] Downloads cached for licensed users
flac 1.3.2 [Approved] Downloads cached for licensed users
flacsquisher 1.3.8 [Approved]
flagfox-firefox 5.1.18 [Approved] - Possibly broken
flare 0.19.20141201 [Approved] - Possibly broken
flashcookiesview 1.15 [Approved] Downloads cached for licensed users
flashdevelop 5.3.3.0 [Approved] Downloads cached for licensed users
flashplayeractivex 32.0.0.238 [Approved]
flashplayerplugin 32.0.0.238 [Approved] Downloads cached for licensed users
flashplayerplugin-disable-updates-winconfig 0.0.1 [Approved]
flashplayerppapi 32.0.0.238 [Approved] Downloads cached for licensed users
flatc 1.10.0 [Approved]
flattenpackages 1.1.14 [Approved] Downloads cached for licensed users
flauinspect 1.2.0 [Approved]
fldigi 4.1.08 [Approved]
fleex 2.3.1
flicflac 1.03.20190425 [Approved]
flightgear 2016.4.1 [Approved]
flink 1.6.3 [Approved] Downloads cached for licensed users
flow 6.0.26 [Approved] Downloads cached for licensed users
flowdock 1.0.5.0 [Approved]
flrig 1.3.47 [Approved]
fluent-terminal 0.5.3.0 [Approved]
FluentAutomation. Repl 0.1.0.3
fluffyapp 3.0.4 [Approved]
flutter 1.2.1 [Approved]
fluxctl 1.13.3 [Approved] Downloads cached for licensed users
fluxfonts 2.0 [Approved]
flyway.commandline 5.2.4 [Approved] Downloads cached for licensed users
flyway.commandline.withjre 5.2.4 [Approved] Downloads cached for licensed users
fmedia 1.10.1 [Approved] Downloads cached for licensed users
foca 3.4.3 [Approved] Downloads cached for licensed users
Focus 0.9 [Approved]
focuswriter 1.5.1
fogg 0.7.0 [Approved] Downloads cached for licensed users
Folder_Size 4.2.0.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
folder-marker 4.2 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
folderchangesview 2.27 [Approved] Downloads cached for licensed users
foldercolorizer 2.3.7 [Approved]
foldermenu3 3.1.2.2
foldersizes 9.0.246 [Approved] Downloads cached for licensed users
foldertimeupdate 1.55 [Approved] Downloads cached for licensed users
foldit 0.0.20160904 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
followmee 1.7.20160815 [Approved] Downloads cached for licensed users
folrep 1.21 [Approved] Downloads cached for licensed users
font-awesome-font 5.1.1.0020180724 [Approved] Downloads cached for licensed users
font.gost2.304-81.install 0.7.6 [Approved]
fontbase 2.8.5 [Approved] Downloads cached for licensed users
fontforge 2016.10.04 [Approved] Downloads cached for licensed users
fonts-ricty-diminished 4.1.1 [Approved] Downloads cached for licensed users
foobar2000 1.4.6 [Approved]
force-cli 0.26.2 [Approved] Downloads cached for licensed users
forceps 1.0.0.1 [Approved]
forge 2.3.0 [Approved]
formatfactory 4.3.0.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
forseti 1.0.0.0
forseti.portable 1.0.0.0
forticlientvpn 6.2.0780 [Approved] Downloads cached for licensed users
fossamail 38.2.0 [Approved] Downloads cached for licensed users
fossil 2.9 [Approved] Downloads cached for licensed users
fox-xca 2.0 [Approved] Downloads cached for licensed users
foxe 2.4.2.2 - Possibly broken
foxe.install 2.4.2.2 - Possibly broken
foxe.portable 2.4.2.2 - Possibly broken
FoxitReader 9.6.0.25144 [Approved] Downloads cached for licensed users
foxtelgo 1.6 [Approved] Downloads cached for licensed users
fragstats 4.2.0.20171213 [Approved]
franz 5.2.0 [Approved] Downloads cached for licensed users
fraps 3.5.99.20150108 [Approved] - Possibly broken
freac 1.0.32 [Approved] Downloads cached for licensed users
freac.portable 1.0.28 [Approved] Downloads cached for licensed users
free-hex-editor-neo 6.31.0.5980 [Approved] Downloads cached for licensed users
free-ost-reader 4.1 [Approved] Downloads cached for licensed users
free-pst-reader 4.1 [Approved] Downloads cached for licensed users
free-virtual-keyboard 4.2 [Approved] Downloads cached for licensed users
freearc 0.666 [Approved] - Possibly broken
freearc.install 0.666 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
freearc.portable 0.666 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
freecad 0.18.16131 [Approved] Downloads cached for licensed users
freeciv 2.6.0 [Approved] Downloads cached for licensed users
freecommander 2009.2.2
freecommander-xe 2016.715 [Approved] - Possibly broken
freecommander-xe.install 2019.790.1 [Approved] Downloads cached for licensed users
freecommander-xe.portable 2016.715 [Approved] Downloads cached for licensed users
freedoom 0.11.3 [Approved] Downloads cached for licensed users
FreeDownloadManager 3.9.5.1533 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
freeencoderpack 2019.04.13 [Approved]
freefilesync 10.2.0.20180914 [Approved] - Possibly broken
freemake-audio-converter 1.1.8.10 [Approved] Downloads cached for licensed users
freemake-video-converter 4.1.9.45 [Approved] Downloads cached for licensed users
freemind 1.0.1 - Possibly broken
freenet 0.7.5.1477 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
FreeOrion 0.4.5 [Approved] Downloads cached for licensed users
freepascal 3.0.4 [Approved] Downloads cached for licensed users
FreePlane 1.7.9 [Approved] Downloads cached for licensed users
freerdp 1.1 [Approved] Downloads cached for licensed users
freesnap 1.5.3 - Possibly broken
freeSSHD 1.3.1 [Approved] Downloads cached for licensed users
freeswitch 1.8.5 [Approved]
freeter 1.2.1 [Approved] Downloads cached for licensed users
freevd 1.1.1.0 [Approved]
freevideoeditor 6.3.6 [Approved]
frhed 1.6.0 [Approved]
frhed.install 1.6.0 [Approved] Downloads cached for licensed users
frhed.portable 1.6.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
friture 0.36 [Approved]
fritzing 0.9.3 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
frogger 2013.08.01 [Approved]
frogsay 3.0.0 [Approved] Downloads cached for licensed users
frost 2011.03.05 [Approved]
frozenbytes.baseline.dev 1.0.2
frozenbytes.baseline.dev.core 1.0.5 - Possibly broken
frozenbytes.baseline.dev.sdks 1.0.5 - Possibly broken
frozenbytes.baseline.dev.tools 1.0.5
frozenbytes.baseline.dev.vs 1.0.5 - Possibly broken
frozenbytes.dev.essentials 1.01 - Possibly broken
frozenbytes.essentials 1.07 - Possibly broken
frozenbytes.extras 1.03
frozenbytes.repos 1.03 - Possibly broken
frozenbytes.vs2012.extensions 1.03 - Possibly broken
fruin. CloudStorage 0.0.1
fs-uae 3.0.0 [Approved] Downloads cached for licensed users
fscapture 9.0 [Approved] Downloads cached for licensed users
fselect 0.6.4 [Approved]
fslogix 2.9.7117.27413 [Approved]
fslogix-java 2.9.7117.27413 [Approved] Downloads cached for licensed users
fslogix-rule-editor 2.9.7117.27413 [Approved] Downloads cached for licensed users
FsResizer.install 3.3 - Possibly broken
FStar 0.9.6.001 [Approved]
fsum 2.52 [Approved] Downloads cached for licensed users
fsumfrontend 1.5.5.1 [Approved] Downloads cached for licensed users
fsviewer 7.3 [Approved] Downloads cached for licensed users
ftdi-drivers 2.12.28 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
ftester 2016.01.14 [Approved] Downloads cached for licensed users
ftpdmin 0.96 [Approved] Downloads cached for licensed users
ftprog 2.6.8
ftpuse 2.0
fudge 1.3.0 [Approved] Downloads cached for licensed users
fuelscm 1.0.0 [Approved] - Possibly broken
fuelscm.portable 1.0.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
furmark 1.20.7.0 [Approved]
fuse-nfs 4.0.0 [Approved] Downloads cached for licensed users
fusion-ldv 3.80 [Approved] - Possibly broken
fusioninventory-agent 2.5.1 [Approved]
fusioninventory-agent.install 2.5.1 [Approved] Downloads cached for licensed users
fusioninventory-agent.portable 2.5.1 [Approved] Downloads cached for licensed users
fusionplusplus 1.1 [Approved]
future-n0t-found-regular-font 1.1 [Approved]
futuremark-systeminfo 5.14.693 [Approved] Downloads cached for licensed users
fv 0.6.3.5830 [Approved] Downloads cached for licensed users
fv.install 0.6.3.5830 [Approved] Downloads cached for licensed users
fwup 1.3.0 [Approved]
fxcop 10.0.30319.20180212 [Approved] Downloads cached for licensed users
fxgqlc 2.6.0 [Approved]
fzf 0.18.0 [Approved]
gae.sdk 1.6.6
gajim 1.1.3 [Approved] Downloads cached for licensed users
galaxian 2010.05.07 [Approved]
Gallio 3.4.14.1 - Possibly broken
GallioBundle 3.4 - Possibly broken
gambit 4.6.6.20121126
game-collector 19.4.1 [Approved] Downloads cached for licensed users
game-key-revealer.portable 1.6.32.20161009 [Approved] Downloads cached for licensed users
gamebooster 5.1.38.0 [Approved]
gamedownloader 4.0.20150329 [Approved]
gamedownloader.install 4.0.20150329 [Approved] Downloads cached for licensed users
gamedownloader.portable 4.0.20150329 [Approved] - Possibly broken
gameplay-time-tracker 3.1.0.0 [Approved] Downloads cached for licensed users
gamesavemanager 3.1.455.20190626 [Approved] Downloads cached for licensed users
gamevox 1.0 [Approved] - Possibly broken
gamingapp 6.2.0.83 [Approved] Downloads cached for licensed users
ganttproject 2.6.5.1638 - Possibly broken
Garam-Editor 1.0.0.4 [Approved]
garmin-basecamp 4.7.0 [Approved] Downloads cached for licensed users
garmin-express 6.16.01 [Approved] Downloads cached for licensed users
gatling 2.2.0 [Approved] Downloads cached for licensed users
gauge 1.0.5 [Approved] Downloads cached for licensed users
gawk 5.0.1 [Approved]
GAX2012 3.0.0.0 - Possibly broken
gb. MongoDB 2.4.7.0
gbm 1.1.9 [Approved]
gbstudio 1.1.0 [Approved]
gbstudio.install 1.1.0 [Approved] Downloads cached for licensed users
gbstudio.portable 1.1.0 [Approved] Downloads cached for licensed users
gcc-arm 4.8.1
gcc-arm-embedded 7.3.1.20180627 [Approved]
gcloudsdk 0.0.0.20190318 [Approved] Downloads cached for licensed users
gcompris 0.91 [Approved]
gcstar 1.6.1 [Approved] - Possibly broken
gdevelop 4.0.94 [Approved] Downloads cached for licensed users
gdiview 1.25 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
gdrive 2.1.0 [Approved]
geany 1.35 [Approved] Downloads cached for licensed users
geany-nogtk 1.27 [Approved] Downloads cached for licensed users
gedit 2.30
GeekUninstaller 1.4.6.140 [Approved] Downloads cached for licensed users
geforce-experience 3.19.0.107 [Approved] Downloads cached for licensed users
geforce-experience-disable-updates-winconfig 0.0.1 [Approved]
geforce-game-ready-driver 431.60 [Approved] Downloads cached for licensed users
geforce-game-ready-driver-win10 378.92 [Approved] - Possibly broken
geforce-game-ready-driver-win7 378.92 [Approved] - Possibly broken
genet 0.5.0 [Approved] Downloads cached for licensed users
genius-chrome 0.1.2 [Approved]
genuinetools 0.0.1 [Approved]
geoda 1.12.1.161 [Approved]
geogebra 5.0.134.0 [Approved]
geogebra-geometry 6.0.546.0 [Approved]
geogebra6 6.0.546.0 [Approved]
geosetter 3.4.16
geosetter.portable 3.4.16
geppetto 4.3.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
gerrit-vet 3.22 [Approved]
get-childitemcolor 2.1.1 [Approved]
getdataback-simple 5.50 [Approved] Downloads cached for licensed users
getdiz 4.91 [Approved]
geteventstore 2.0.1.6 - Possibly broken
getignore 1.0.0.20170723 [Approved] Downloads cached for licensed users
getiplayer 3.21 [Approved] Downloads cached for licensed users
getopt 2.14.1 [Approved] Downloads cached for licensed users
getter1 4.2 - Possibly broken
gevent 1.0.4
gfwlive 3.5.92.0 - Possibly broken
gh-api-cli 4.0.2 [Approved]
ghb0t 0.4.0 [Approved]
ghc 8.6.5 [Approved]
ghidra 9.0.2 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
ghost 0.5.5.1 [Approved] - Possibly broken
ghost-desktop 1.7.0 [Approved] Downloads cached for licensed users
ghostdoc-enterprise 2019.2.19200 [Approved]
ghostdoc-pro 2019.2.19200 [Approved]
Ghostscript 9.27 [Approved]
Ghostscript.app 9.27 [Approved]
ghostwriter 1.5.0 [Approved] Downloads cached for licensed users
gifcam 5.5.0.1 [Approved] Downloads cached for licensed users
gifsicle 1.89 [Approved] Downloads cached for licensed users
gigantticloud 3.2.90.974 [Approved] Downloads cached for licensed users
gimagereader 3.3.1 [Approved] Downloads cached for licensed users
gimp 2.10.12 [Approved] Downloads cached for licensed users
git 2.22.0 [Approved]
git-annex 7.20190627 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
git-cola 3.4 [Approved] Downloads cached for licensed users
Git-Credential-Manager-for-Windows 1.19.0 [Approved] Downloads cached for licensed users
git-credential-winstore 2.0.0.20151206 [Approved]
git-disable-gcm 1.0.0 [Approved]
git-flow-dependencies 0.2 - Possibly broken
git-flow-hooks 1.0.4 [Approved]
git-fork 1.37.2 [Approved] Downloads cached for licensed users
git-helper 1.5 - Possibly broken
git-lfs 2.8.0 [Approved]
git-lfs.install 2.8.0 [Approved]
git-lfx 0.1.0 [Approved]
git-phlow 3.8.20 [Approved]
git-sizer 1.3.0 [Approved]
git-status-cache-posh-client 1.0.0 [Approved] Downloads cached for licensed users
Git-TF 2.0.3.20131219 [Approved]
git.commandline 2.11.0.20170203 [Approved]
git.install 2.22.0 [Approved]
git.portable 2.22.0 [Approved]
gitahead 2.5.9 [Approved]
gitblit 1.6.2 [Approved]
gitbook-editor 7.0.12 [Approved]
GitDepend. Portable 0.5.0 [Approved]
GitDiffMargin 3.10.1.191 [Approved]
GitDiffMargin.vs2012 1.0
GitDiffMargin.vs2013 2.0.0 [Approved]
gitea 1.8.2 [Approved] Downloads cached for licensed users
gitextensions 3.1.1 [Approved]
gitextensions.portable 3.1.1 [Approved]
giteye 1.5.0
gitflow-avh 0.0.0 [Approved]
gitflow-hooks 1.0.1 [Approved]
gitg 3.20.0 [Approved]
gitg.install 3.20.0 [Approved] Downloads cached for licensed users
GitHub 3.2.0.20181119 [Approved]
github-build-from-label 1.1 - Possibly broken
github-desktop 2.1.0 [Approved] Downloads cached for licensed users
github-hovercard-chrome 1.4.4 [Approved]
githubforwindows 2.13.0.2 [Approved]
githublink 2.3.0 [Approved]
githubreleasemanager.portable 0.2.0 [Approved]
githubreleasenotes 1.0.4.0 [Approved]
githubsearch 1.2.2 [Approved] Downloads cached for licensed users
gitkraken 6.0.0 [Approved] Downloads cached for licensed users
gitlab-runner 12.1.0 [Approved]
gitlink 3.0.0 [Approved]
gitpad 1.2 [Approved]
gitreleasemanager.portable 0.8.0 [Approved]
GitReleaseNotes 0.6.1 [Approved]
GitReleaseNotes. Portable 0.7.1 [Approved]
GitSvnExternals 1.1.0.7
gitter 4.1.0 [Approved] Downloads cached for licensed users
gittfs 0.30.0 [Approved] Downloads cached for licensed users
GitVersion 1.0.0.1
GitVersion. Portable 5.0.1 [Approved]
GitVersioner 1.0.1.14 [Approved]
glaryutilities-free 5.80 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
glaryutilities-pro 5.121.0.146 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
Glassfish 3.1.2.004 - Possibly broken
glassfish-javaee 5.0 [Approved] Downloads cached for licensed users
glasswire 2.1.152 [Approved] Downloads cached for licensed users
glfw3 3.0.4.2
glip 19.7.1.0 [Approved] Downloads cached for licensed users
glmixer 1.5.1329 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
global 6.5.6 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
glogg 1.1.4 [Approved] Downloads cached for licensed users
glyphexporter 1.1.25 [Approved] Downloads cached for licensed users
glyphr-studio-desktop 0.5.2 [Approved] Downloads cached for licensed users
GMac. Teamcity 8.1.2 - Possibly broken
gmail-growl 2.4.0 [Approved] - Possibly broken
gmailnotifier 1.2.1 [Approved] Downloads cached for licensed users
gmailnotifier-firefox 0.7.0 [Approved] - Possibly broken
gmer 2.2.19882.20161107 [Approved] Downloads cached for licensed users
gmkvextractgui 2.5.0 [Approved] Downloads cached for licensed users
gms 10.4.4 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
gmvault 1.9.1 [Approved]
gnat-gpl 2019.0 [Approved] Downloads cached for licensed users
gnatsd 1.0.2.20170727 [Approved] Downloads cached for licensed users
gnokii 0.6.31 [Approved] Downloads cached for licensed users
gns3 2.1.21 [Approved]
gnucash 3.6 [Approved]
gnucobol 2.2 [Approved] Downloads cached for licensed users
gnupg-modern 2.2.12 [Approved] Downloads cached for licensed users
gnuplot 5.0.5 [Approved] Downloads cached for licensed users
gnuplot.portable 5.0.1 [Approved] Downloads cached for licensed users
GnuWin 0.6.3.1 - Possibly broken
gnuwin32-coreutils.install 5.3.0 [Approved] Downloads cached for licensed users
gnuwin32-coreutils.portable 5.3.0 [Approved] Downloads cached for licensed users
gnvm 0.2.0 [Approved] Downloads cached for licensed users
go-contact-sync-mod 3.10.52 [Approved]
go-fmt-fail 0.0.5 [Approved]
go-ipfs 0.4.22 [Approved]
go-msi 1.0.2 [Approved]
go-repo-utils 0.0.17 [Approved]
goagent 13.4.1.18342 - Possibly broken
gobby 0.5.0.20170419 [Approved]
gocdagent 19.7.0 [Approved]
gocdserver 19.7.0 [Approved]
GoCiAgent 14.2.0 - Possibly broken
gocontactsyncmod 3.10.14.20180818 [Approved]
godmode 1.0 [Approved]
godot 3.1.1 [Approved]
godot-mono 3.1.1 [Approved]
goggalaxy 1.2.57.74 [Approved]
gogs 0.11.91 [Approved] Downloads cached for licensed users
goland 2019.2 [Approved] Downloads cached for licensed users
golang 1.12.7 [Approved] Downloads cached for licensed users
goldendict 1.0.1 [Approved]
goldendict-en-ru-en.install 1.0.1 [Approved] Downloads cached for licensed users
goldendict.install 1.0.1 [Approved] Downloads cached for licensed users
goldendict.portable 1.0.1 [Approved] Downloads cached for licensed users
golly 3.2 [Approved]
golo 3.2.0 [Approved] Downloads cached for licensed users
gols 1.0.0.2 [Approved] Downloads cached for licensed users
gom-player 2.3.43.5305 [Approved] Downloads cached for licensed users
goodbyedpi 0.1.5 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
goodjobb 0.2 [Approved]
GoodSync 10.10.5.20190815 [Approved]
google-backup-and-sync 3.45.5545.5747 [Approved] Downloads cached for licensed users
google-books-downloader 2.7 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
google-calendar-chrome 2.8 [Approved]
google-cast-chrome 15.1120.0.4 [Approved]
google-chrome-for-enterprise 67.0.3396.87 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
google-chrome-x64 47.0.2526.81 [Approved]
google-dictionary-chrome 4.0.8 [Approved]
google-drive-add-to-explorer 1.0.2 [Approved]
google-drive-file-stream 31.0.13.0 [Approved]
google-hangouts-chat 18.2.252 [Approved] Downloads cached for licensed users
google-hangouts-chrome 2017.110.418.20 [Approved]
google-pinyin 1.0 - Possibly broken
google-play-music-chrome 1.390.0 [Approved]
google-play-music-manager 1.0.457.379602 [Approved]
google-shortcuts-firefox 1.1.7 [Approved] - Possibly broken
google-translate-chrome 2.0.7 [Approved]
google-voice-chrome 2.4.4.20170115 [Approved]
google-web-designer 5.0.4.0226 [Approved] Downloads cached for licensed users
google2srt 0.7.7 [Approved]
google2srt.install 0.7.7 [Approved]
google2srt.portable 0.7.7 [Approved]
GoogleChrome 76.0.3809.100 [Approved] Downloads cached for licensed users
GoogleChrome-AllUsers 26.0.1410.64
googlechrome-authy 2.3.0 [Approved]
googlechrome-github-expandinizr 1.0.0 [Approved]
googlechrome-zenhub 1.0.0 [Approved]
GoogleChrome. Canary 28.0.1461.0 [Approved]
GoogleChrome. Dev 27.0.1453.12 [Approved]
googledrive 2.34.5075.1619 [Approved] Downloads cached for licensed users
googleearth 7.1.8.30360001 [Approved] Downloads cached for licensed users
googleearthpro 7.3.2.5776 [Approved] Downloads cached for licensed users
GoogleJapaneseInput 1.3.24.20141007
GooglePhotos 1.1.0.20150530 [Approved] Downloads cached for licensed users
googler 3.9 [Approved]
gopass 1.8.6 [Approved] Downloads cached for licensed users
goreman 0.0.6.0 [Approved]
GoServer 14.1.0.18882 - Possibly broken
gosuslugi-plugin 3.0.7.0 [Approved] Downloads cached for licensed users
gotomeeting 8.41.0.12127 [Approved] Downloads cached for licensed users
gotowindow 0.7.2 [Approved] Downloads cached for licensed users
gource 0.47 [Approved] Downloads cached for licensed users
govc 0.20.0 [Approved]
Gow 0.8.0
gpac 0.8.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
gperf 3.1 [Approved]
gpg4usb 0.3.3.1
Gpg4win 3.1.10 [Approved]
gpg4win-light 2.3.4.20170919 [Approved]
gpg4win-vanilla 2.3.4.20170919 [Approved]
GPMDP 4.6.1.20190424 [Approved]
gpower 3.1.9.2 [Approved] Downloads cached for licensed users
gps-sdr-sim 1.0 [Approved] Downloads cached for licensed users
gptgen 1.1.20180516 [Approved]
gpu-z 2.24.0 [Approved]
gpxeditor 1.7.12.1731 [Approved] Downloads cached for licensed users
graalvm 19.1.0 [Approved] Downloads cached for licensed users
gradle 5.5.1 [Approved] Downloads cached for licensed users
grafana 6.3.3 [Approved]
Grails 3.3.10 [Approved] Downloads cached for licensed users
gramblr 2.8.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
grammarly 1.5.52 [Approved] Downloads cached for licensed users
grammarly-chrome 14.821.1.1383 [Approved]
gramps 5.0.1 [Approved] Downloads cached for licensed users
granit 1.4.0.0 - Possibly broken
graph 4.4.2.20170413 [Approved] Downloads cached for licensed users
graphicsmagick 1.3.32 [Approved] Downloads cached for licensed users
graphingcalculator 6.0.535.001 [Approved]
graphite-powershell 1.2.2 [Approved]
Graphviz 2.38.0.20190211 [Approved]
graphviz.portable 2.38.20180209 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
GravitDesigner 2019.2.4 [Approved]
gravitdesigner.install 2019.2.4 [Approved] Downloads cached for licensed users
gravitdesigner.portable 2019.2.4 [Approved] Downloads cached for licensed users
grayboxsimulator 1.8.0.2 [Approved] Downloads cached for licensed users
greenshot 1.2.10.6 [Approved] Downloads cached for licensed users
grep 2.1032 [Approved] Downloads cached for licensed users
grepwin 1.9.2 [Approved] Downloads cached for licensed users
greyhound-crm 4.9.19 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
grib-tools 1.14.5.1 [Approved] Downloads cached for licensed users
gridcoinwallet 4.0.1.0 [Approved] Downloads cached for licensed users
gridmove 1.19.62.20180721 [Approved] Downloads cached for licensed users
grisbi 1.2.2 [Approved] Downloads cached for licensed users
Grocery-Checklist-Shell 1.0.0 [Approved]
gron 0.6.0 [Approved]
groovy 2.5.7 [Approved] Downloads cached for licensed users
groupy 1.25 [Approved]
Growl 2.0.9.20130406 [Approved] - Possibly broken
grub2win 1.0.5.8 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
grubinst 1.0.1 [Approved] Downloads cached for licensed users
gruntsnippetpack 1.0.3 [Approved] Downloads cached for licensed users
gsmartcontrol 1.1.3 [Approved] Downloads cached for licensed users
gsubs 1.0.2 [Approved]
gsuite-migration-exchange 5.1.20.0 [Approved] Downloads cached for licensed users
gsuite-migration-outlook 4.0.117.10 [Approved] Downloads cached for licensed users
gsuite-new-tab-chrome 1.5.3 [Approved]
gsuite-sync-outlook 4.1.25.0 [Approved] Downloads cached for licensed users
gsuite-training-chrome 1.8.11 [Approved]
gsutil 3.26
GSView 6.0.0.20150422 [Approved] Downloads cached for licensed users
gsync 3.35.6251.4621 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
gsyncit 3.8.148 [Approved] - Possibly broken
gtk-runtime 2.24.10.20121010 [Approved]
gtksharp 2.12.45 [Approved] Downloads cached for licensed users
gtkwave 3.3.100 [Approved]
gtools 4.2 [Approved]
gtypist 2.9.5 [Approved] Downloads cached for licensed users
guetzli 1.0.1 [Approved]
guidgen-console 2.0.0.6 [Approved]
guitarhub 1.1.15 [Approved] Downloads cached for licensed users
gulp-cli 2.2.0 [Approved]
gulpsnippetpack 1.2.5 [Approved] - Possibly broken
gump 0.1.9 [Approved]
gurtle 0.6.0.236 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
gutenberg 0.4.2 [Approved] Downloads cached for licensed users
Gyazo 3.1.6 [Approved] Downloads cached for licensed users
gzdoom 4.1.3 [Approved] Downloads cached for licensed users
gzip 1.3.12 [Approved]
h-opc-cli 0.9.0 [Approved] Downloads cached for licensed users
h264tscutter 1.1.1.20161125 [Approved]
h2database 1.3.169 - Possibly broken
h2testw 1.4.20180717 [Approved] Downloads cached for licensed users
haali-media-splitter 1.13.138.1401 [Approved] Downloads cached for licensed users
habitat 0.83.0 [Approved] Downloads cached for licensed users
hackfont 3.003 [Approved]
hackfont-windows 1.6.0 [Approved] Downloads cached for licensed users
hadoop 3.2.0 [Approved] Downloads cached for licensed users
hadouken 4.6.0 - Possibly broken
Hain 0.6.6 [Approved] Downloads cached for licensed users
hakchi2.portable 2.31.0.20180803 [Approved]
Halite 0.4.0.4 [Approved] Downloads cached for licensed users
handbrake 1.2.2 [Approved]
handbrake.install 1.2.2 [Approved]
handbrake.portable 1.2.2 [Approved]
Handle 4.22 [Approved] Downloads cached for licensed users
handyimagemapper 2.0.0.0 [Approved]
harddriveindicator 1.3.0.0 [Approved]
hardentools 1.0 [Approved]
hardware-freak 2.0.20161030 [Approved]
hardware-identify 2.5.0 [Approved] Downloads cached for licensed users
hardware-identify.portable 2.5.0 [Approved] Downloads cached for licensed users
Hardwipe 5.1.3 [Approved] Downloads cached for licensed users
haroopad 0.13.1 [Approved] Downloads cached for licensed users
hashcheck 2.4.0.20181230 [Approved]
hashdeep 4.4 [Approved] Downloads cached for licensed users
hasher 1.0 - Possibly broken
hasher-erz 1.9.0.1 [Approved]
hashmyfiles 2.35 [Approved] Downloads cached for licensed users
hashtab 6.0.0.3401 [Approved]
hashtools 4.2 [Approved] Downloads cached for licensed users
haskell-stack 2.1.3.20190715 [Approved] Downloads cached for licensed users
hasklig 1.1 [Approved] Downloads cached for licensed users
havdetectiontool 1.0 [Approved] Downloads cached for licensed users
haxe 3.4.7 [Approved]
hazelcast 3.5 [Approved] Downloads cached for licensed users
hddguardian 0.6.2 [Approved] - Possibly broken
hddguardian.install 0.6.2 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
hddguardian.portable 0.6.2 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
hdgrandslam-plex 1.6.2.20170427 [Approved] Downloads cached for licensed users
hdguard 10.0.0.4 [Approved] Downloads cached for licensed users
hdhomerun-view 2019.06.21 [Approved] Downloads cached for licensed users
hdhomerunviewer-plex 1.0.2 [Approved] Downloads cached for licensed users
hdparm 6.9.2 [Approved] Downloads cached for licensed users
hdsentinel 5.40 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
hdtune 2.55.0.1 [Approved] Downloads cached for licensed users
headset 3.0.2 [Approved] Downloads cached for licensed users
heapmemview 1.05 [Approved] Downloads cached for licensed users
hearthstone-deck-tracker 1.1.6 [Approved] Downloads cached for licensed users
hearthstone-deck-tracker-arena-helper 0.8.0 [Approved] Downloads cached for licensed users
heatseeker 1.6.1 [Approved]
heavyload 3.5.1 [Approved]
heavyload.portable 3.5.1 [Approved]
hedgewars 0.9.25 [Approved]
HeidiSQL 10.2.0.5599 [Approved] Downloads cached for licensed users
heimdall 1.4.0 [Approved]
helix-alm-client 2019.3.0 [Approved] Downloads cached for licensed users
Hercules 3.2.5.20120918
herdprotect 1.0.3.9 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
heroesofnewerth 3.5.8 [Approved] - Possibly broken
heroku-cli 7.27.1.0 [Approved]
heroku-toolbelt 0.1.0.20161107 [Approved]
hex2dec 1.10 [Approved] Downloads cached for licensed users
hexamail-pop3-downloader 5.9.22.002 [Approved] Downloads cached for licensed users
hexchat 2.14.1 [Approved] Downloads cached for licensed users
HexEdit 2.0.6.49 - Possibly broken
Hexter.octopus 1.5.1.1658
Hexter.octopus.tentacle 1.6.3.1724 - Possibly broken
Hexter. Teamcity 7.1.42 - Possibly broken
Hexter.webserver 1.0.1
hfs 2.3.12 [Approved]
hfsexplorer 0.23.1 [Approved] Downloads cached for licensed users
hg 5.0.2 [Approved] Downloads cached for licensed users
hhkbcng 1.0
hidemaru-editor 8.88 [Approved]
higan 1.0.096 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
highlight 3.44 [Approved] Downloads cached for licensed users
HighTailExpress 2.14.1.20121122
hijackthis 2.9.0.1 [Approved] Downloads cached for licensed users
hikvision-sadp 3.0.1.7 [Approved] Downloads cached for licensed users
HipChat 4.30.3.1665 [Approved] Downloads cached for licensed users
hiphop 0.4.6.20150612 [Approved]
hitmanpro 3.8.14.304 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
hmailserver 5.6.7.2383 [Approved] Downloads cached for licensed users
hmne 2.0.3 [Approved] Downloads cached for licensed users
HoboCopy 1.0.0
hollowshunter 0.2.2.5 [Approved] Downloads cached for licensed users
homeassistant 0.93.2 [Approved]
homebank 5.2.7 [Approved] Downloads cached for licensed users
homepages-winconfig 0.0.1 [Approved]
HoneyBee. DevOps. Packaging 1.1.0.3
HoneyBee. DevOps. SelfDeployment 1.0.0.2
honeyview 5.31 [Approved]
honeyview.install 5.31 [Approved]
honeyview.portable 5.31 [Approved]
hostinfo 1.0.1 [Approved] Downloads cached for licensed users
hosts 1.1.0 [Approved]
hosts.editor 1.2.0 [Approved] Downloads cached for licensed users
hostsman 4.7.105.20180405 [Approved]
hot-chocolatey 7.0.1.0 [Approved] Downloads cached for licensed users
hotpotato 6.3.0.5
hotswap 6.1.0.0 - Possibly broken
hourglass.install 1.10 [Approved] Downloads cached for licensed users
housecall.portable 1.62.0.1129 [Approved] Downloads cached for licensed users
houselinc 2.10.25.20161003 [Approved]
hp-bios-cmdlets 1.1.0.101 [Approved] Downloads cached for licensed users
hp-coolsense-technology 2.10.51 [Approved] Downloads cached for licensed users
hp-ilo-cmdlets 1.4.0.1 [Approved] Downloads cached for licensed users
hp-oa-cmdlets 1.1.0.701 [Approved] Downloads cached for licensed users
hp-universal-print-driver-pcl 6.8.0.24296 [Approved] Downloads cached for licensed users
hp-universal-print-driver-ps 6.8.0.24296 [Approved] Downloads cached for licensed users
hpglviewer 5.43.0.20180521 [Approved] Downloads cached for licensed users
hppark 1.8.7 [Approved] Downloads cached for licensed users
hpusbdisk 2.2.3.20150303 [Approved]
hsm-usb-serial-driver 3.5.9 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
hst 0.0.0.1 - Possibly broken
hte 2.1.0 [Approved] Downloads cached for licensed users
html-help-workshop 1.32 [Approved] Downloads cached for licensed users
html-tidy 5.6.0 [Approved]
htmlastext 1.11 [Approved] Downloads cached for licensed users
htmlclip 0.60 [Approved]
HTMLConverter 3.1
htmldocedit 1.02 [Approved] Downloads cached for licensed users
HtmlPackager 0.1.6.5 [Approved] Downloads cached for licensed users
httping 2.5 [Approved] Downloads cached for licensed users
httpmaster-express 4.5.1 [Approved] Downloads cached for licensed users
httpmaster-professional 4.5.1 [Approved] Downloads cached for licensed users
httpnetworksniffer 1.63 [Approved] Downloads cached for licensed users
httpPlatformHandler 1.2 [Approved] Downloads cached for licensed users
HttpRest 3.0
https-everywhere-chrome 2016.12.19 [Approved]
https-everywhere-firefox 5.2.15 [Approved] - Possibly broken
httpsysmanager 1.5 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
httrack 3.49.2 [Approved]
httrack.app 3.49.2 [Approved] Downloads cached for licensed users
httrack.tool 3.49.2 [Approved]
hub 2.12.3 [Approved] Downloads cached for licensed users
hubic 2.1.1.145 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
hugin 2019.0.0.20190512 [Approved]
hugin.install 2019.0.0.20190512 [Approved]
hugin.portable 2015.0.0 [Approved]
hugo 0.57.0 [Approved]
hugo-extended 0.57.0 [Approved]
hulu.desktop 0.9.14.2 - Possibly broken
hunspell.portable 1.7.0 [Approved] Downloads cached for licensed users
hv-ms735-config 1.1.0 [Approved] Downloads cached for licensed users
hwinfo 6.10 [Approved]
hwinfo.install 6.10 [Approved]
hwinfo.portable 6.10 [Approved]
HWiNFO32 4.18.1930.1 [Approved]
hwmonitor 1.39 [Approved] Downloads cached for licensed users
HxD 2.3.0.0 [Approved]
hydrairc 0.3.165.1 - Possibly broken
hydrus-network 363.0 [Approved]
hyper 3.0.2 [Approved]
i2pd 2.27.0 [Approved] Downloads cached for licensed users
iboodhuntchecker-be 2.1.1 [Approved] Downloads cached for licensed users
iboodhuntchecker-nl 2.1.1 [Approved] Downloads cached for licensed users
icap4demo 8.3.11.4444 [Approved] Downloads cached for licensed users
Icaros 3.1.0 [Approved] Downloads cached for licensed users
icc-profile-inspector 2.4 [Approved] Downloads cached for licensed users
icecast 2.4.4 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
icecat 60.8.0 [Approved] Downloads cached for licensed users
icinga2 2.10.5 [Approved] Downloads cached for licensed users
iCloud 7.13.0.14 [Approved]
IcoFx 3.3 [Approved] Downloads cached for licensed users
iconizer 2013.06.25 [Approved] Downloads cached for licensed users
iconsext 1.47.0.20150708 [Approved]
iconsext.install 1.47.0.20150708 [Approved] Downloads cached for licensed users
iconsext.portable 1.47 [Approved] Downloads cached for licensed users
IconsExtract 1.47.0.20150708 [Approved]
icopy 1.6.5 [Approved]
icopy.install 1.6.5 [Approved]
ICSharp 0.1 - Possibly broken
ida-free 7.0.20190406 [Approved] Downloads cached for licensed users
idris 1.1.1 [Approved] Downloads cached for licensed users
ie 9.0 - Possibly broken
ie_box2d_api_sample1 0.1.9
ie10 0.0.3
ie11 0.2 [Approved]
ie9 0.0.6 [Approved] Downloads cached for licensed users
iecacheview 1.58 [Approved] Downloads cached for licensed users
iecompo 1.00 [Approved] Downloads cached for licensed users
iedesignmode 1.00 [Approved] Downloads cached for licensed users
IEDriverServer 2.32.3 - Possibly broken
iehv 1.70 [Approved] Downloads cached for licensed users
iepv 1.35 [Approved] - Possibly broken
iepv.install 1.40 [Approved]
iepv.portable 1.40 [Approved]
ietab-chrome 10.1.11.1 [Approved]
ietab2-firefox 6.2.18.120161009 [Approved] - Possibly broken
ietester 0.5.4.20170203 [Approved] Downloads cached for licensed users
iforgot 0.2.44 [Approved] Downloads cached for licensed users
igdm 2.6.5 [Approved] Downloads cached for licensed users
ignore-file 0.0.3 [Approved]
ignorefiles 1.2.65 [Approved] Downloads cached for licensed users
iguana 6.1.2 [Approved]
iguana.install 6.1.2 [Approved] Downloads cached for licensed users
iguana.portable 6.1.2 [Approved] Downloads cached for licensed users
IHateRegions 1.2.6
iis 2.0.0 [Approved]
iis-application-initialization 1.1 [Approved]
iis-arr 3.0.20180207 [Approved] Downloads cached for licensed users
iis-externalcache 1.1.20151123 [Approved] - Possibly broken
iis-media-services 4.1.20160504 [Approved] - Possibly broken
iis.administration 2.2.0 [Approved] Downloads cached for licensed users
iis75.express 7.5.1
IIS7Manager 7.0.0 [Approved] - Possibly broken
iiscrypto 3.0 [Approved]
iiscrypto-cli 3.0 [Approved]
iisexpress 10.0.0.20181007 [Approved] Downloads cached for licensed users
iisgeolocate 1.4.0.1 [Approved]
iishosts 1.0.1 [Approved] Downloads cached for licensed users
iissecurity-psmodule 1.3.0 [Approved]
ike-scan 1.9 [Approved] Downloads cached for licensed users
ikvm 8.1.5717.20170308 [Approved] Downloads cached for licensed users
ilmerge 2.12.0803 [Approved]
ilspy 4.0.1 [Approved]
ILSpy. GetPrigIndirectionStubSetting. Plugin 0.0.0 [Approved]
image-composite-editor 2.0.3 [Approved] Downloads cached for licensed users
imageanalyzer 1.38.4 [Approved]
imagecacheviewer 1.20 [Approved] Downloads cached for licensed users
ImageConverter 3.3
imageglass 7.0.7.26 [Approved] Downloads cached for licensed users
imagej 1.50 [Approved] Downloads cached for licensed users
imagemagick 7.0.8.56 [Approved]
imagemagick.app 7.0.8.56 [Approved] Downloads cached for licensed users
imagemagick.tool 7.0.8.56 [Approved] Downloads cached for licensed users
ImageManager 7.5.6 [Approved] Downloads cached for licensed users
imageoptimizer 3.5.79 [Approved] Downloads cached for licensed users
imageresizerapp 3.1.1 [Approved] Downloads cached for licensed users
ImageSlicer 3.1 - Possibly broken
imagesprites 1.2.34 [Approved] - Possibly broken
imagine 1.0.9 [Approved] - Possibly broken
imagine.portable 1.0.9 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
imdisk 2.0.10.20181231 [Approved]
ImDisk-Toolkit 19.06.29 [Approved]
imgburn 2.5.8.20170708 [Approved] Downloads cached for licensed users
immunet 6.3.0.10988 [Approved] Downloads cached for licensed users
imprimcheques 6.0.0 [Approved] Downloads cached for licensed users
inbox-chrome 1.0.0.1929 [Approved]
Inconsolata 2014.12.31 [Approved]
indentex 0.5.0 [Approved]
IndentGuides 12.1
indihiang 1.0.0.1 - Possibly broken
infekt 1.0.1 [Approved] Downloads cached for licensed users
infinitex 0.9.16 [Approved]
infinitex.install 0.9.16 [Approved]
infinitex.portable 0.9.16 [Approved]
Influx-Capacitor 1.0.89 [Approved]
influxdb 1.7.7.20190716 [Approved]
influxdb1 1.7.7.20190716 [Approved]
InfraRecorder 0.53.0.1
inireloc 2004.09.16 [Approved] Downloads cached for licensed users
initool 0.9.0 [Approved] Downloads cached for licensed users
injecteddll 1.00 [Approved] Downloads cached for licensed users
InkScape 0.92.4.20190121 [Approved]
inno-download-plugin 1.5.1 [Approved]
inno-script-studio 2.3.0.20190125 [Approved] Downloads cached for licensed users
innoextract 1.6 [Approved] Downloads cached for licensed users
InnoSetup 6.0.2 [Approved]
innounp 0.48 [Approved]
InputDirector 1.4.110 [Approved] Downloads cached for licensed users
insideclipboard 1.15 [Approved] Downloads cached for licensed users
insomnia-rest-api-client 6.6.2 [Approved] Downloads cached for licensed users
inspec 4.7.3 [Approved] Downloads cached for licensed users
inssider 3.1.2.13 [Approved]
inssider-lite 1.11.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
install4j 7.0.4 [Approved]
install4j.install 7.0.11 [Approved] Downloads cached for licensed users
install4j.portable 7.0.11 [Approved] Downloads cached for licensed users
installedcodec 1.30 [Approved] Downloads cached for licensed users
installeddriverslist 1.05 [Approved] Downloads cached for licensed users
installroot 5.0.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
installwindowsimage.powershell 2009.5.11 [Approved]
instantbird 1.5.0.20170718 [Approved] Downloads cached for licensed users
instanteyedropper 1.75 [Approved] - Possibly broken
instanteyedropper.app 1.75 [Approved] - Possibly broken
instanteyedropper.tool 1.75 [Approved] - Possibly broken
instantwordpress 5.3.6 [Approved] Downloads cached for licensed users
InstChoco 2.11 [Approved]
InstEd 1.5.15.27 [Approved] Downloads cached for licensed users
InSync 1.5.5.37367 [Approved] Downloads cached for licensed users
intel-chipset-device-software 10.1.17 [Approved] Downloads cached for licensed users
intel-driver-update-utility 3.1.1.220180112 [Approved] - Possibly broken
intel-dsa 19.7.30.2 [Approved] Downloads cached for licensed users
intel-graphics-driver 25.20.100.6323 [Approved]
intel-ipdt 4.1.3.35 [Approved]
intel-me-drivers 1909.12.0.1236 [Approved] Downloads cached for licensed users
intel-network-drivers-win10 24.1.0.7 [Approved]
intel-processor-identification-utility 6.0.0211 [Approved] Downloads cached for licensed users
intel-proset-drivers 20.100.0 [Approved]
intel-rst-driver 17.2.0.1009 [Approved]
intel-xtu 6.5.1.321 [Approved]
Intel. SSD. Toolbox 3.5.11 [Approved] Downloads cached for licensed users
IntelliJIDEA 2018.1 [Approved]
intellijidea-community 2019.2 [Approved] Downloads cached for licensed users
intellijidea-edu 2019.2 [Approved] Downloads cached for licensed users
intellijidea-ultimate 2019.2 [Approved] Downloads cached for licensed users
intellitype 8.20.469.0 [Approved] Downloads cached for licensed users
intelpowergadget 3.5.0 [Approved]
inter 2.5 [Approved] Downloads cached for licensed users
internet-download-manager 6.33.3 [Approved] Downloads cached for licensed users
interopformsredist 2.0.1 [Approved] Downloads cached for licensed users
invantive-bridge-connectors-power-bi 17.32.33 [Approved] Downloads cached for licensed users
invantive-bridge-developers 17.32.33 [Approved] Downloads cached for licensed users
invantive-bridge-power-bi-users 17.30.0 [Approved] Downloads cached for licensed users
invantive-business-for-outlook 17.32.48 [Approved] Downloads cached for licensed users
invantive-business-for-windows 17.32.52 [Approved] Downloads cached for licensed users
invantive-composition-for-word 17.32.52 [Approved] Downloads cached for licensed users
invantive-control-for-excel 17.32.52 [Approved] Downloads cached for licensed users
invantive-data-hub 17.32.52 [Approved] Downloads cached for licensed users
invantive-dotnet-optimizer 17.8.8 [Approved]
invantive-estate-for-outlook 17.32.51 [Approved] Downloads cached for licensed users
invantive-estate-for-windows 17.32.51 [Approved] Downloads cached for licensed users
invantive-query-tool 17.32.52 [Approved] Downloads cached for licensed users
invantive-studio 17.32.49 [Approved] Downloads cached for licensed users
invoke-build 5.5.2 [Approved]
invokebuild 5.5.2 [Approved]
invokemsbuild 1.5.17 [Approved]
io-ninja 3.11.1 [Approved] Downloads cached for licensed users
io-unlocker 1.1.2.1 [Approved] Downloads cached for licensed users
io.js 3.0.0 [Approved] Downloads cached for licensed users
iobit-malware-fighter 7.1.0.5675 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
iobit-uninstaller 8.6.0.10 [Approved] Downloads cached for licensed users
iometer 1.1.0.20161009 [Approved] Downloads cached for licensed users
ioquake3 1.36 [Approved]
ioquake3-data 1.36 [Approved] Downloads cached for licensed users
ioquake3.install 1.36 [Approved] Downloads cached for licensed users
iperf2 2.0.14.1 [Approved]
iperf3 3.1.3 [Approved] Downloads cached for licensed users
ipevo-presenter 6.8.1.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
ipevo-visualizer 1.5.0.500 [Approved]
ipfilter-updater 2.2.2.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
ipfs 0.4.22 [Approved]
ipfs-desktop 0.8.0 [Approved] Downloads cached for licensed users
ipfs-mount 0.3.3 [Approved]
ipinfooffline 1.50 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
ipmicfg 1.27.1.170901 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
ipnetinfo 1.85 [Approved]
ipnetinfo.install 1.85 [Approved] Downloads cached for licensed users
ipnetinfo.portable 1.85 [Approved] Downloads cached for licensed users
ipscan 2.5.3233 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
ipvanish 3.4.4.420190621 [Approved] Downloads cached for licensed users
ipwhoisflags-chrome 3.42.20170115 [Approved]
ireboot 1.1.1.20141201 [Approved] - Possibly broken
ireport 4.5.1
IrfanView 4.53 [Approved]
irfanview-shellextension 1.06 [Approved]
irfanviewplugins 4.53 [Approved]
iridium-browser 2019.04.73 [Approved] Downloads cached for licensed users
iris 1.1.8 [Approved] Downloads cached for licensed users
ironpython 2.7.9 [Approved]
ironruby 1.1.3 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
IronScheme 0.9.111338 [Approved] - Possibly broken
IrScrutinizer 4.36.0.20190617 [Approved]
ISAPIRewrite 3.1.0068 - Possibly broken
iscommandlineapp 1.0.0 [Approved] - Possibly broken
IsePester 1.0.2 [Approved]
isoplex 1.0.4 [Approved] - Possibly broken
isorecorder 3.0.0 [Approved] Downloads cached for licensed users
isowriter 0.6.1.20180514 [Approved] Downloads cached for licensed users
ispy 6.5.0.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
itag 0.483
italc 3.0.1 [Approved] Downloads cached for licensed users
itch 25.4.0.20190311 [Approved] Downloads cached for licensed users
iTunes 12.9.6.3 [Approved]
itunesfusion 3.3 [Approved] Downloads cached for licensed users
ivideon-client 6.7.1 [Approved] Downloads cached for licensed users
ivideon-server 3.7.0 [Approved] Downloads cached for licensed users
ivy 2.4.0.1 [Approved]
IZArc 4.1.7 - Possibly broken
izpack 5.1.0 [Approved] Downloads cached for licensed users
j-kinopoisk2imdb 1.2 [Approved] Downloads cached for licensed users
jabra-direct 4.0.4380 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
JabRef 4.3.1 [Approved] Downloads cached for licensed users
jack 1.9.11 [Approved] - Possibly broken
jackett 0.11.598 [Approved]
jacksum 1.7.0 [Approved] Downloads cached for licensed users
jacobrutski-vcenter-script 1.3 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
jadx 1.0.0.20190724 [Approved]
jamovi 1.0.5.000 [Approved]
jamovi.install 1.0.5.000 [Approved] Downloads cached for licensed users
jamovi.portable 1.0.5.000 [Approved] Downloads cached for licensed users
jana2006 5.193 [Approved] Downloads cached for licensed users
jasp 0.8.500 [Approved]
java.jdk 7.0.75.20150520 [Approved] - Possibly broken
Java7u13x64 7.13.64
Java7u13x86 7.13
javadecompiler-gui 1.4.0.20180728 [Approved] Downloads cached for licensed users
javaruntime 8.0.191 [Approved] - Possibly broken
javaruntime-platformspecific 7.0.79.20161125 [Approved]
javaruntime-preventasktoolbar 1.2
javaruntime-tiger 7.0.55
javascriptsnippetpack 1.0.3 [Approved] Downloads cached for licensed users
javauninstalltool 1.1.0.0020180704 [Approved] Downloads cached for licensed users
JAWS 15.0.5056 - Possibly broken
JayHankins. ConEmuConfig 0.0.8
jboss-as 7.1.1 [Approved] - Possibly broken
jbs 5.2 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
jcpicker 5.2 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
jdk11 11.0.2 [Approved]
jdk8 8.0.221 [Approved]
jdk8.portable 8.0.202 [Approved] - Possibly broken
jdownloader 2.0 [Approved] Downloads cached for licensed users
jdupes 1.12 [Approved] Downloads cached for licensed users
jEdit 5.5.0 [Approved] Downloads cached for licensed users
jekyll 3.8.5.20190622 [Approved]
jenkins 2.176.2 [Approved] Downloads cached for licensed users
jenkins-x 2.0.581 [Approved]
JenkinsOnDesktop 1.0
jetbrains-rider 2019.2 [Approved] Downloads cached for licensed users
jetbrains-youtrack 2019.2.55688 [Approved] Downloads cached for licensed users
jetbrainstoolbox 1.15.5796 [Approved] Downloads cached for licensed users
jetty 9.4.19.20190610 [Approved] Downloads cached for licensed users
jfrog-cli 1.26.3 [Approved] Downloads cached for licensed users
jhead 3.03 [Approved] Downloads cached for licensed users
jhipster 5.8.2 [Approved]
jing 2.8.13007 [Approved]
JiraCli 1.1.0 [Approved]
jitsi 2.10.5550.20180405 [Approved]
jivkok. AutoHotKey 1.0.0.1 - Possibly broken
jivkok.boxstarter1 1.0.0.4 - Possibly broken
jivkok.dev1 1.1.0.8 - Possibly broken
jivkok. GitConfig 1.0.1.0
jivkok. Shell1 1.0.0.3 - Possibly broken
jivkok. SublimeText3. Packages 1.0.0.12 - Possibly broken
jivkok.tools 1.1.0.7 - Possibly broken
jivkok.vsextensions.2013 1.0.0.7
jivosite 4.0.0.0 [Approved] Downloads cached for licensed users
jlecmd 1.2.0.1 [Approved]
jmeter 5.1 [Approved] Downloads cached for licensed users
jmfb-com-import 0.0.2 [Approved]
jmodelica 2.4 [Approved] Downloads cached for licensed users
jmol 14.29.47 [Approved]
join.me 3.2.1.523301 [Approved] Downloads cached for licensed users
jom 1.1.2 [Approved] Downloads cached for licensed users
joplin 1.0.161 [Approved]
jormungandr 0.3.2 [Approved]
josm 15238.0 [Approved] Downloads cached for licensed users
joytokey 6.2.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
jp 1.1.11 [Approved] Downloads cached for licensed users
jpegtran 9.0.0.20180223 [Approved] Downloads cached for licensed users
jpegview 1.0.37 [Approved] Downloads cached for licensed users
jq 1.5 [Approved] Downloads cached for licensed users
jre8 8.0.221 [Approved] Downloads cached for licensed users
jregexanalyser 1.4.0 [Approved] Downloads cached for licensed users
jrt 8.1.4 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
jruby 9.1.2.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
jsae 1.10 [Approved] Downloads cached for licensed users
jsonedit 0.9.32.0 [Approved] Downloads cached for licensed users
jstock 1.0.7.32 [Approved] Downloads cached for licensed users
jtalert 2.14.2 [Approved] Downloads cached for licensed users
jtdx 18.0.0.133 [Approved]
jtrim 1.53 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
jubler 6.0.2 [Approved]
juffed 0.8.1 [Approved] Downloads cached for licensed users
juju 2.6.6 [Approved]
Julia 1.1.1 [Approved]
Jump-Location 0.6.0.20180509 [Approved]
jumplistexplorer 0.8.0.1 [Approved]
JumplistLauncher 7.21
jumplistsview 1.16 [Approved] Downloads cached for licensed users
jumpshare 2.0.10 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
junction 1.07 [Approved] Downloads cached for licensed users
junction-link-magic 2.0.3.20160815 [Approved] Downloads cached for licensed users
justread-chrome 1.1.12 [Approved] - Possibly broken
jwcad 8.03.1 [Approved] Downloads cached for licensed users
jwtdecode 1.0.1 [Approved]
k-litecodecpackbasic 15.1.2 [Approved]
k-litecodecpackfull 15.1.2 [Approved]
k-litecodecpackmega 15.1.2 [Approved]
k-meleon 75.1 [Approved]
k-meleon.install 75.1 [Approved]
k-meleon.portable 75.1 [Approved]
k6 0.25.1 [Approved]
kadu 2.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
kafka 1.1.0 [Approved] - Possibly broken
kafka-tool 2.0.4 [Approved] Downloads cached for licensed users
kantu-xmodules 2.0.1.9 [Approved] Downloads cached for licensed users
karaf 4.0.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
kareemsultan.desktop 1.8 - Possibly broken
kareemsultan.developer.toolkit 1.7 - Possibly broken
kareemsultan.developer.toolkit.dotnet 1.3 - Possibly broken
karen 3.6.9 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
kate 19.04.2 [Approved]
KatMouse 1.7
kav 15.0.2.361 [Approved] - Possibly broken
kaxaml 1.8 - Possibly broken
KB2454826 1.0.4 [Approved]
KB2519277 1.0.0 [Approved] Downloads cached for licensed users
KB2533552 1.0.4 [Approved]
KB2533623 1.0.4 [Approved]
KB2534366 1.0.4 [Approved]
KB2670838 1.0.20181019 [Approved]
kb2701373-v2-64bit 1.0
KB2842230 1.0.2
KB2882822 1.0.3 [Approved]
KB2919355 1.0.20160915 [Approved]
KB2919442 1.0.20160915 [Approved]
KB2999226 1.0.20181019 [Approved]
KB3033929 1.0.5 [Approved]
KB3035131 1.0.3 [Approved]
KB3118401 1.0.4 [Approved]
KB4019990 1.0.2 [Approved]
kb4480955 1.0 [Approved]
KB976932 1.0.0 [Approved]
kcast 3.2.0.0 [Approved] Downloads cached for licensed users
kcleaner 3.6.3.102 [Approved] Downloads cached for licensed users
kdenlive 19.04.3 [Approved] Downloads cached for licensed users
kdevelop 5.3.2 [Approved]
kdevelop.install 5.3.2 [Approved] Downloads cached for licensed users
kdevelop.portable 5.1.2.20190510 [Approved]
kdiff3 0.9.98 [Approved]
keep-chrome 3.1.16302.1110 [Approved]
keepass 2.42.1 [Approved]
keepass-classic 1.37 [Approved]
keepass-classic-langfiles 1.31 [Approved]
keepass-keeagent 0.8.1.20180426 [Approved]
keepass-keepasshttp 1.8.4.220170629 [Approved]
keepass-kpentrytemplates 1.8.0.20190608 [Approved]
keepass-langfiles 2.41 [Approved]
keepass-plugin-1p2kp 0.2.1 [Approved]
keepass-plugin-autotypecustomfieldpicker 1.0.0.0 [Approved]
keepass-plugin-autotypesplitter 1.2 [Approved]
keepass-plugin-certkeyprovider 1.0.0 [Approved]
keepass-plugin-cw3import 2.10 [Approved]
keepass-plugin-databasebackup 2.0.8.6 [Approved]
keepass-plugin-enhancedentryview 2.1.2 [Approved]
keepass-plugin-favicon 1.9.0 [Approved]
keepass-plugin-fieldsadminconsole 0.2.0 [Approved]
keepass-plugin-gost 2.1 [Approved]
keepass-plugin-ioprotocolext 1.16 [Approved]
keepass-plugin-itanmaster 2.28.0.2 [Approved]
keepass-plugin-keeagent 0.10.1.20180815 [Approved]
keepass-plugin-keeanywhere 1.5.1 [Approved]
keepass-plugin-keeautoexec 2.4 [Approved]
keepass-plugin-keechallenge 1.5.20180413 [Approved]
keepass-plugin-keecloud 1.2.0.3 [Approved]
keepass-plugin-keeotp 1.3.9 [Approved]
keepass-plugin-keepasshttp 1.8.4.2 [Approved] - Possibly broken
keepass-plugin-keepassnatmsg 2.0.6 [Approved]
keepass-plugin-keetheme 0.6 [Approved]
keepass-plugin-kpfloatingpanel 7.0 [Approved] - Possibly broken
keepass-plugin-kpscript 2.42.1 [Approved]
keepass-plugin-mskeyimporter 1.0 [Approved]
keepass-plugin-osk 1.2 [Approved]
keepass-plugin-otpkeyprov 2.6 [Approved]
keepass-plugin-passwordcounter 0.1 [Approved]
keepass-plugin-pickcharsdeferred 1.2 [Approved]
keepass-plugin-qrcodegen 2.0.12 [Approved]
keepass-plugin-qualitycolumn 1.2 [Approved]
keepass-plugin-qualityhighlighter 1.3.0.1 [Approved]
keepass-plugin-quickunlock 1.0 [Approved]
keepass-plugin-rdp 7.0 [Approved]
keepass-plugin-readablepassphrasegen 1.1.2 [Approved]
keepass-plugin-spmimport 1.2 [Approved]
keepass-plugin-trayrecent 0.0.2 [Approved]
keepass-plugin-traytotp 2.0.0.5 [Approved]
keepass-plugin-truecryptmount 2.3 [Approved]
keepass-plugin-twofishcipher 1.3 [Approved]
keepass-plugin-webautotype 6.1.0 [Approved]
keepass-plugin-winhello 2.2 [Approved]
keepass-plugin-winkee 2.39.1 [Approved]
keepass-rpc 1.9.0.20190516 [Approved] Downloads cached for licensed users
keepass-yet-another-favicon-downloader 1.2.1.0 [Approved]
keepass.install 2.42.1 [Approved] Downloads cached for licensed users
keepass.portable 2.42.1 [Approved]
keepassx 2.0.3 [Approved]
keepassx-langfiles 1.28.20141006
keepassxc 2.4.3 [Approved]
keesbaggerman-nutanix-script 1.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
keeweb 1.8.2 [Approved]
kega-fusion 3.64 [Approved] Downloads cached for licensed users
Kekiri. Tools 2.0
kellyelton.devenvironment 1.0.0.11 - Possibly broken
kellyelton.vsextensions 1.0.0.8
ketarin 1.8.10 [Approved]
keybase 4.2.0 [Approved] Downloads cached for licensed users
keyboard-layout-creator 1.4 [Approved] Downloads cached for licensed users
keycastow 2.0.2.4 [Approved]
keyferret 2.6 [Approved]
keyferret.install 2.6 [Approved]
keyferret.portable 2.6 [Approved]
keyfinder 2.0.10.13 [Approved]
keyhac 1.77 [Approved] Downloads cached for licensed users
keypirinha 2.23 [Approved] Downloads cached for licensed users
keypose 1.0.0 [Approved] Downloads cached for licensed users
keystore-explorer.portable 5.4.2 [Approved] Downloads cached for licensed users
Khoa. LoadOuts. Dev 1.0.1
kibana 6.2.4 [Approved]
kicad 5.1.4.10 [Approved] Downloads cached for licensed users
kickassconsole 0.1.9
KickAssVim 7.4.0.00 - Possibly broken
kid3 3.7.1 [Approved]
kiki-re 0.5.6 [Approved] - Possibly broken
Kile 2.9.92 [Approved] Downloads cached for licensed users
kill-frozen-programs 1.0.0 [Approved] Downloads cached for licensed users
killprocess 2.44 [Approved] Downloads cached for licensed users
Kindle 1.25.52064 [Approved] Downloads cached for licensed users
kindlegen 2.9.0.20160512 [Approved] Downloads cached for licensed users
kindlepreviewer 3.30 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
kingsoft-office-free 9.1.0.20140820 - Possibly broken
kingston-ssd-manager 1.1.1.8 [Approved] Downloads cached for licensed users
kino-LeaseProvider-Service 0.0.1.2 [Approved]
kino-rendezvous-service 0.0.1.27 [Approved]
kinovea 0.8.27 [Approved] Downloads cached for licensed users
kis 19.0.0.0 [Approved]
kitty 0.71.0.701 [Approved]
kitty.portable 0.67.0.0 [Approved]
kitware-ninja 1.8.2.8127911 [Approved] Downloads cached for licensed users
kkrieger 2004.04 [Approved] Downloads cached for licensed users
klatexformula 4.0.0 [Approved]
klayout 0.25.9 [Approved] Downloads cached for licensed users
klog 0.9.8 [Approved]
klogg 19.2 [Approved] Downloads cached for licensed users
KMDF 1.11 [Approved]
kmttg 2.4.12 [Approved] Downloads cached for licensed users
kmymoney 4.8.3 [Approved] Downloads cached for licensed users
kmymoney.portable 4.8.2 [Approved] Downloads cached for licensed users
knime 4.0.1 [Approved]
knime-full.install 3.4.2 [Approved] Downloads cached for licensed users
knime.install 4.0.1 [Approved]
knime.portable 4.0.1 [Approved]
kobito 2.0.6 [Approved] Downloads cached for licensed users
kodi 18.3.0.20190629 [Approved] Downloads cached for licensed users
kodos 2.4.9 [Approved] Downloads cached for licensed users
koffee 0.4.2 [Approved]
komodo-edit 11.0.2.18122 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
kontur-addtotrusted 2.0.18.2 [Approved] Downloads cached for licensed users
kontur-addtotrusted.portable 2.0.18.2 [Approved] Downloads cached for licensed users
kontur-certificates 4.7.27.6074 [Approved] Downloads cached for licensed users
kontur-diag 2.14.26.54 [Approved] Downloads cached for licensed users
kontur-plugin 3.10.2 [Approved] Downloads cached for licensed users
konversation 1.0.0 [Approved]
kopano-ads-nightly 1.1.88 [Approved]
kopano-deskapp-nightly 2.4.1 [Approved]
koruri 2014.09.04
kotlinc 1.3.30 [Approved] Downloads cached for licensed users
kpcli 3.2 [Approved] Downloads cached for licensed users
kptransfer 3.0.0 [Approved] Downloads cached for licensed users
krita 4.2.5 [Approved] Downloads cached for licensed users
ksign 2016.07.20.20170105 [Approved] Downloads cached for licensed users
ksonnet 0.13.1 [Approved] Downloads cached for licensed users
ksp-ckan 1.26.4 [Approved]
kss 12.0.1.340 - Possibly broken
kuadro 0.9.5 [Approved] Downloads cached for licensed users
kubectx-ps 0.0.1 [Approved]
kubernetes-cli 1.15.2 [Approved]
kubernetes-helm 2.14.3 [Approved] Downloads cached for licensed users
kubernetes-kompose 1.18.0 [Approved]
kubernetes-node 1.11.3 [Approved] Downloads cached for licensed users
kubeval 0.7.0 [Approved] Downloads cached for licensed users
kustomize 2.0.3 [Approved] Downloads cached for licensed users
kvirc 4.2.0 [Approved] Downloads cached for licensed users
kvrt 2019.06.24.1824 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
kzip 0.0.20070414 - Possibly broken
lame 3.100.20190612 [Approved]
lame-front-end 1.8.1 [Approved] Downloads cached for licensed users
lamexp 4.17 [Approved]
lammercontextmenu 1.0.3.19 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
lan-messenger 1.2.35.2017252017 [Approved] Downloads cached for licensed users
lan-messenger.portable 1.2.37 [Approved] Downloads cached for licensed users
lan-speed-test-lite 1.3.2.20180101 [Approved]
lan-speed-test-registered 3.5.20180101 [Approved]
lan-speed-test.portable 4.4.0 [Approved] Downloads cached for licensed users
lanbench 1.1.0.20180725 [Approved] Downloads cached for licensed users
lanconfig 10.30.48 [Approved] Downloads cached for licensed users
languagetool 4.6 [Approved] Downloads cached for licensed users
lanmessenger 1.2.35 [Approved] Downloads cached for licensed users
lanmonitor 10.30.13 [Approved] Downloads cached for licensed users
lanxchange 1.41 [Approved] Downloads cached for licensed users
laragon 4.0.15 [Approved]
laragon.install 4.0.15 [Approved]
large-text-file-viewer 5.2 [Approved]
lastactivityview 1.32 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
lastfmscrobbler 2.1.36 - Possibly broken
lastools 2019.07.28 [Approved] Downloads cached for licensed users
lastpass 4.31.0 [Approved] Downloads cached for licensed users
lastpass-chrome 4.3.0 [Approved]
lastpass-for-applications 4.31.0 [Approved] Downloads cached for licensed users
latencymon 6.71 [Approved] Downloads cached for licensed users
latexdaemon 0.11.91 [Approved]
latexdraw 3.3.9 [Approved]
latexml 0.8.4 [Approved]
lato 2.0.0.1
launchbox 4.1 [Approved] - Possibly broken
launchy 2.5.0.20140301 [Approved]
launchy-beta 2.6.2.1
launchyqt 3.0.9 [Approved]
lavfilters 0.74.1 [Approved] Downloads cached for licensed users
layer0 0.10.7 [Approved] Downloads cached for licensed users
lazarus 2.0.2 [Approved] Downloads cached for licensed users
lazpaint 6.4.1 [Approved]
lazygit 0.8.1 [Approved] Downloads cached for licensed users
ldapadmin 1.8.3 [Approved] Downloads cached for licensed users
ldapexplorer 1.0.0.0
ldc 1.16.0 [Approved] Downloads cached for licensed users
ldmdump 1.02 [Approved] Downloads cached for licensed users
leagueoflegends 1.0.0.20171207 [Approved] Downloads cached for licensed users
lean 3.4.2 [Approved]
leanify 0.4.2 [Approved] Downloads cached for licensed users
leappadmanager 7.5.0 [Approved] Downloads cached for licensed users
lecmd 1.2.0.1 [Approved]
ledger 3.1.2 [Approved] Downloads cached for licensed users
Leechcraft 0.6.70.2 - Possibly broken
legitest 2018.2.4.504 [Approved]
Lein 2.9.1 [Approved]
lenovo-thinkvantage-system-update 5.07.0084 [Approved] Downloads cached for licensed users
lepton 1.8.0 [Approved] Downloads cached for licensed users
Less 5.51 [Approved]
lessmsi 1.6.91 [Approved]
letsencrypt-win-simple 2.0.9 [Approved] Downloads cached for licensed users
Leveret 1.0.0 [Approved] - Possibly broken
lf 0.12 [Approved]
lftp 4.8.0 [Approved] Downloads cached for licensed users
lgbridge 1.2.54 [Approved] Downloads cached for licensed users
lha 1.14 [Approved]
lhaca 0.76 [Approved] - Possibly broken
lhaplus 1.59.3 - Possibly broken
liberationfonts 2.00.5 [Approved] Downloads cached for licensed users
liberica11jdk 11.0.2 [Approved] Downloads cached for licensed users
libericajdk 12.0.1 [Approved] Downloads cached for licensed users
libjpeg-turbo 1.2.1.201304081 [Approved]
libre-hardware-monitor 1.0.107 [Approved]
librecad 2.1.3 [Approved] Downloads cached for licensed users
libreelec-usb-sd-creator 1.3 [Approved] Downloads cached for licensed users
librefox-firefox 2.1 [Approved]
libreoffice 5.4.4.20180111 [Approved] - Possibly broken
libreoffice-fresh 6.2.5 [Approved] Downloads cached for licensed users
libreoffice-help 5.2.0 [Approved] - Possibly broken
libreoffice-oldstable 5.3.7.20180111 [Approved] - Possibly broken
libreoffice-still 6.0.7 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
libressl 2.5.5 [Approved]
licecap 1.28 [Approved]
liclipse 5.2.2 [Approved] Downloads cached for licensed users
lidarr 0.6.2.883 [Approved]
lifesize-cloud 10.1.223 [Approved] Downloads cached for licensed users
light 34.0 [Approved] - Possibly broken
lightalloy 4.10.2 [Approved]
lightbulb 1.6.4.1 [Approved] Downloads cached for licensed users
lightscreen 2.4.0.20180605 [Approved]
lightshot 5.4.0.36 [Approved] - Possibly broken
lightshot.install 5.5.0.4 [Approved] Downloads cached for licensed users
LightTable 0.8.1 [Approved] Downloads cached for licensed users
lightworks 14.5 [Approved]
lili 2.9.4 [Approved]
lili.install 2.9.4 [Approved] Downloads cached for licensed users
lili.portable 2.9.4 [Approved] Downloads cached for licensed users
lilypond 2.18.2 [Approved]
limechat 2.40 [Approved] Downloads cached for licensed users
limitless 1.08 [Approved]
line 5.17.3.1958 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
Line6Monkey 1.72 [Approved] Downloads cached for licensed users
lingering-object-liquidator 2.0.19 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
linkednotes 2.5.0 [Approved] Downloads cached for licensed users
LinkShellExtension 3.8.7.10 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
linotte 2.07.06 [Approved] Downloads cached for licensed users
LinPhone 4.1.1 [Approved] Downloads cached for licensed users
linqpad 5.36.03 [Approved]
linqpad2 2.45.05
linqpad2.install 2.45.05
linqpad4 4.58.0 [Approved] - Possibly broken
linqpad4. AnyCPU.portable 4.57.02 [Approved] Downloads cached for licensed users
linqpad4.install 4.58.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
linqpad4.portable 4.57.02 [Approved] Downloads cached for licensed users
linqpad5 5.36.03 [Approved]
linqpad5. AnyCPU.install 5.36.03 [Approved] Downloads cached for licensed users
linqpad5. AnyCPU.portable 5.26.01 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
linqpad5.install 5.36.03 [Approved] Downloads cached for licensed users
linqpad5.portable 5.36.03 [Approved] Downloads cached for licensed users
linux-reader 3.4 [Approved] Downloads cached for licensed users
liquibase 3.6.3 [Approved] Downloads cached for licensed users
lissi-csp 2.0.0.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
Listary 5.00.2843 [Approved] Downloads cached for licensed users
listdlls 3.20 [Approved] Downloads cached for licensed users
litecoin 0.15.1 [Approved] Downloads cached for licensed users
liteide 33.2.0 [Approved] Downloads cached for licensed users
litemanager-server 4.8.4886 [Approved] Downloads cached for licensed users
litemanager-viewer 4.8.4886 [Approved] Downloads cached for licensed users
little-fighter-2 2.0 [Approved] Downloads cached for licensed users
little-system-cleaner 0.3 [Approved]
littleregistrycleaner 1.6.0.20141201 [Approved] - Possibly broken
livecode 6.010
livecontactsview 1.26 [Approved] Downloads cached for licensed users
livekd 5.4 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
LiveSplit 1.7.4 [Approved] Downloads cached for licensed users
livestreamer 1.12.2 [Approved] Downloads cached for licensed users
livestreamer-twitch-gui 1.0.0 [Approved]
llftool 4.40.20141201 [Approved]
llvm 8.0.0 [Approved] Downloads cached for licensed users
lmms 1.2.0 [Approved] Downloads cached for licensed users
ln 2.9.1.3 [Approved] Downloads cached for licensed users
loc 1.0.0 [Approved]
LocalAdminWMI 1.0.0.4
locale-emulator 2.4.0.0 [Approved] Downloads cached for licensed users
LocaleGraph 1.2.1 [Approved]
locate32 3.1.11.7100 [Approved] Downloads cached for licensed users
lockhunter 3.2 [Approved] Downloads cached for licensed users
log2console 1.6.0.220190214 [Approved] Downloads cached for licensed users
log4om 1.39.0 [Approved]
log4om.install 1.39.0 [Approved]
log4om.portable 1.39.0 [Approved]
log4view 1.4.4.1461 [Approved]
logdna 1.3.0 [Approved]
logdna-agent 1.6.1 [Approved]
logexpert 1.7.1 [Approved]
logfusion 6.2.1 [Approved] Downloads cached for licensed users
logiccards-chrome 1.0.0.2 [Approved]
loginator 1.5.0 [Approved] Downloads cached for licensed users
loginTimer 108.11.4.7 [Approved]
logisim-evolution 2.15.0 [Approved] Downloads cached for licensed users
logitech-media-server 7.9.1 [Approved] Downloads cached for licensed users
logitech-options 7.14.70 [Approved] Downloads cached for licensed users
logitech-presentation 1.52.24 [Approved] Downloads cached for licensed users
logitech-webcam-software 2.80.853.0 [Approved] Downloads cached for licensed users
logitechgaming 9.02.65 [Approved] Downloads cached for licensed users
logmein-rescue-console-desktop 7.8 [Approved] Downloads cached for licensed users
Logmein. Client 4.1.0.32682
logonsessions 1.40 [Approved] Downloads cached for licensed users
logparser 2.2.0.1 [Approved]
logparser.lizardgui 6.8 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
logparserstudio 2.2
LogRotate 0.0.0.14 [Approved] Downloads cached for licensed users
logstalgia 1.0.7 [Approved] Downloads cached for licensed users
logstash 6.2.4 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
logstash-contrib 1.4.2 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
logstash-forwarder 0.4.0 [Approved] Downloads cached for licensed users
LogStitcher.portable 1.0.0 [Approved] Downloads cached for licensed users
loop-drop 3.0.1 [Approved] Downloads cached for licensed users
loot 0.14.5 [Approved]
lossless-audio-checker 2.0.7 [Approved] Downloads cached for licensed users
lossless-cut 2.3.0 [Approved] Downloads cached for licensed users
love 0.10.2 [Approved] - Possibly broken
love.install 0.10.2 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
love.portable 0.10.2 [Approved] Downloads cached for licensed users
lsasecretsdump 1.21 [Approved]
lsasecretsview 1.21 [Approved] - Possibly broken
Lua 5.1.5.52 [Approved] Downloads cached for licensed users
lua51 5.1.5 [Approved] Downloads cached for licensed users
lua52 5.2.4 [Approved] Downloads cached for licensed users
lua53 5.3.5 [Approved] Downloads cached for licensed users
luabuglight 2.3.20161105 [Approved] Downloads cached for licensed users
luarocks 2.4.4 [Approved] Downloads cached for licensed users
luckybackup 0.4.7.20140107 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
luke.portable 6.0.0 [Approved] Downloads cached for licensed users
luminance 2.6.0 [Approved]
luminance.install 2.6.0 [Approved]
luminance.portable 2.6.0 [Approved]
lunacy 4.0.3.20190701 [Approved] Downloads cached for licensed users
LunaORM 4.0.0.1
lunarlander 2013.08.02 [Approved]
lux 1.0.0 [Approved]
luxcorerender 2.1 [Approved]
luxcorerender-opencl 2.1 [Approved]
luxcorerender-opencl-sdk 2.1 [Approved]
luxcorerender-sdk 2.1 [Approved]
luxriot-client 2.5.4 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
lxc 3.16 [Approved]
lxrunoffline 3.4.0 [Approved]
lyncbasic2013 0.1 [Approved] Downloads cached for licensed users
lyncbasic2013x86 0.1 [Approved] Downloads cached for licensed users
LynxToolkit 2015.1.425 [Approved]
lyricsfinder 1.4.5.20190529 [Approved] Downloads cached for licensed users
lyx 2.3.3.1 [Approved]
lzip 1.19 [Approved]
macaddressview 1.42 [Approved] Downloads cached for licensed users
macaroni 0.3.0.1 [Approved]
macrocreator 5.0.5 [Approved]
macrocreator.install 5.0.5 [Approved] Downloads cached for licensed users
macrocreator.portable 5.0.5 [Approved] Downloads cached for licensed users
mactype 2017.628.0 [Approved] Downloads cached for licensed users
made2010 2016.07.01 [Approved] Downloads cached for licensed users
madvr 0.92.17 [Approved] Downloads cached for licensed users
Mages 1.6.0 [Approved] Downloads cached for licensed users
magicavoxel 0.99.4.20190605 [Approved] Downloads cached for licensed users
magicavoxelviewer 0.41.0.20170719 [Approved] Downloads cached for licensed users
magicsplat-tcl-tk 1.9.1 [Approved]
Mahou 2.9.0.1 [Approved] Downloads cached for licensed users
mailboxlogparser 1.0 - Possibly broken
MailConverter 3.1
mailer 1.6 [Approved] Downloads cached for licensed users
mailnoter 1.0.1 [Approved] Downloads cached for licensed users
mailpv 1.86 [Approved]
mailpv.install 1.86 [Approved]
mailpv.portable 1.86 [Approved]
mailsend 1.18 [Approved] Downloads cached for licensed users
mailspring 1.3.0 [Approved] Downloads cached for licensed users
MailViewer 3.1
mainca 2012.07.20 [Approved] Downloads cached for licensed users
make 4.2.1 [Approved] Downloads cached for licensed users
MakeHuman 1.1.1 [Approved] Downloads cached for licensed users
makemeadmin 2.3 [Approved]
MakeMKV 1.14.4 [Approved]
maltego 4.1.0.10552 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
malwarebytes 3.8.3.296512023 [Approved]
mame 0.206 [Approved] Downloads cached for licensed users
mamp 4.1.0 [Approved] Downloads cached for licensed users
mamp3 3.3.1 [Approved] Downloads cached for licensed users
manaplus 1.8.12.8 [Approved] Downloads cached for licensed users
manictime 4.0.15 [Approved]
manictime.install 4.1.9 [Approved] Downloads cached for licensed users
manictime.portable 4.3.4 [Approved] Downloads cached for licensed users
manifest-tool 0.9.0 [Approved] Downloads cached for licensed users
manuskript 0.9.0 [Approved] Downloads cached for licensed users
marble 2.2.0 [Approved] Downloads cached for licensed users
marcedit 7.1.180 [Approved]
marcs-updater 1.5.3.305 [Approved] Downloads cached for licensed users
mariadb 10.4.6 [Approved]
mariadb.install 10.4.7 [Approved]
mariadb.portable 10.4.7 [Approved]
markdown-edit 1.35 [Approved] Downloads cached for licensed users
Markdown-Generator 1.0.2 [Approved] Downloads cached for licensed users
markdowneditor 1.8.159 [Approved] Downloads cached for licensed users
markdownlint-cli 0.17.0 [Approved]
MarkdownMode 2.4
MarkdownMonster 1.18.10 [Approved] Downloads cached for licensed users
MarkdownMonster. Portable 1.18.5 [Approved]
markdownpad.portable 2.5.0.27920 [Approved] Downloads cached for licensed users
markdownpad2 2.3 - Possibly broken
markdownwin 1.0
marker 0.0.6.0 [Approved]
markpad 1.0.5
marktext 0.15.0 [Approved]
marktext.install 0.15.0 [Approved] Downloads cached for licensed users
marktext.portable 0.15.0 [Approved]
marv 0.2.0.1
masgau 1.0.6 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
massigra 0.45.0.1 [Approved]
master-pdf-editor 5.4.38 [Approved] Downloads cached for licensed users
masterpackager 19.4.1 [Approved] Downloads cached for licensed users
matchmaking-server-picker 4.5 [Approved] Downloads cached for licensed users
Math 1.0
matrikon-explorer 5.0.0.0 [Approved]
matrix-io-malos-vision 1.0.0 [Approved]
mattermost-desktop 4.2.1 [Approved]
maven 3.6.1.20190711 [Approved] Downloads cached for licensed users
maxima 5.43.0 [Approved] Downloads cached for licensed users
maxmind-geoip-dat 1.0.0.121720133 - Possibly broken
maxthon 4.9.4.1000 [Approved] - Possibly broken
maxthon.commandline 5.2.7.5000 [Approved] Downloads cached for licensed users
maxthon.install 4.9.4.1000 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
mbca 2.0.0.1 - Possibly broken
mboxviewer 1.0.3.3 [Approved]
mbruler 5.3.0.20180802 [Approved]
mbsa 2.3.2211 [Approved] Downloads cached for licensed users
mc 4.8.21.209 [Approved] Downloads cached for licensed users
mcollective 2.4.1
mcr-r2014b 8.4.0.20190708 [Approved] Downloads cached for licensed users
mcr-r2015a 8.5.0.20190708 [Approved] Downloads cached for licensed users
mcr-r2015b 9.0 [Approved] Downloads cached for licensed users
mcr-r2016b 9.1 [Approved] Downloads cached for licensed users
mcr-r2019a 9.6.0.1150989 [Approved] Downloads cached for licensed users
md5 2.2 [Approved]
md5deep 0.1 [Approved]
md5sums 1.2 [Approved] Downloads cached for licensed users
mdaemon 17.5.1 [Approved] Downloads cached for licensed users
mdprojecttimer 3.17.1
mdprojecttimer-pro 3.17.1
MDT 6.3.8456.1 [Approved] Downloads cached for licensed users
MeatPlay 0.0.2 - Possibly broken
meazure 2.0.1 [Approved] Downloads cached for licensed users
mediacoder 0.8.32 - Possibly broken
MediaElch 2.6.0 [Approved] Downloads cached for licensed users
mediainfo 19.07 [Approved] Downloads cached for licensed users
mediainfo-cli 19.04 [Approved] Downloads cached for licensed users
mediamonkey 4.1.24 [Approved] Downloads cached for licensed users
mediatab 1.4 [Approved]
MediathekView 13.2.1.20181016 [Approved]
mednafen 1.21.3 [Approved] Downloads cached for licensed users
megasync 3.1.4 [Approved] Downloads cached for licensed users
megatools 1.10.2 [Approved] Downloads cached for licensed users
megui 1.0.2896 [Approved] Downloads cached for licensed users
meinberg-ntp 4.2.8.0 [Approved] Downloads cached for licensed users
meld 3.20.0 [Approved]
mellowplayer 3.5.90 [Approved]
memcached 1.4.4 [Approved] - Possibly broken
MemProfiler 5.6.53 [Approved] Downloads cached for licensed users
memreduct 3.3.5.20190310 [Approved]
mendeley 1.19.5 [Approved] Downloads cached for licensed users
mery 2.4.6.5927 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
MeshLab 2016.12 [Approved]
MesloLG. DZ 1.00 - Possibly broken
messengerreviver 2.2.5.0 - Possibly broken
metafox 1.7.2 [Approved]
metanorma 1.1.8 [Approved]
metapad 3.6 [Approved]
metapad-light 3.6 [Approved]
MetaX 2.69 [Approved] Downloads cached for licensed users
meteor 0.0.2 [Approved] Downloads cached for licensed users
metricbeat 7.3.0 [Approved] Downloads cached for licensed users
metropolislauncher 1.2.0 [Approved]
mfaws 1.0.4 [Approved]
MFCMapi 2019.2.19207.938 [Approved]
mftecmd 0.4.0.1 [Approved]
micro 1.4.1 [Approved] Downloads cached for licensed users
microsip 3.19.17 [Approved] Downloads cached for licensed users
Microsoft-Band-Sync 1.3.20517.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
microsoft-build-tools 15.0.26320.2 [Approved]
microsoft-build-tools-2013 2013.1 [Approved] Downloads cached for licensed users
microsoft-message-analyzer 1.4.1.20161119 [Approved] Downloads cached for licensed users
microsoft-office-deployment 16.0.11901.20022 [Approved]
microsoft-r-open 3.5.2 [Approved] Downloads cached for licensed users
microsoft-teams 1.2.00.19260 [Approved] Downloads cached for licensed users
microsoft-teams.install 1.2.00.19260 [Approved] Downloads cached for licensed users
microsoft-visual-cpp-build-tools 14.0.25420.1 [Approved] Downloads cached for licensed users
microsoft-windows-terminal 0.3.2171.0 [Approved]
microsoftazurestorageexplorer 1.9.0 [Approved] Downloads cached for licensed users
microsoftbandtools 1.0.10 [Approved] Downloads cached for licensed users
microsoftmathematics 4.0.1108.0000 [Approved] Downloads cached for licensed users
MicrosoftSecurityEssentials 4.5.0216.0 [Approved] - Possibly broken
microsoftwebdriver 1.0.0 [Approved]
MicrosoftWSE 3.0 - Possibly broken
midori-browser 0.5.9.20141201 [Approved] - Possibly broken
mightymoose 1.47.0 - Possibly broken
mightytext-chrome 19.6.20170115 [Approved]
miktex 2.9.7152 [Approved]
miktex.install 2.9.7152 [Approved] Downloads cached for licensed users
miktex.portable 2.9.6942 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
mileswilford. DefaultInstall 1.0.0 - Possibly broken
milightcli 1.0 [Approved] - Possibly broken
millipede 2013.11.10 [Approved]
milton 1.6.2 [Approved]
milton.install 1.6.2 [Approved]
milton.portable 1.6.2 [Approved]
mimeview 1.10 [Approved] Downloads cached for licensed users
min.portable 1.10.1 [Approved] Downloads cached for licensed users
minecraft 1.9 [Approved] Downloads cached for licensed users
minermanager 1.0.18 [Approved]
minetest 0.4.10.20141201 [Approved] - Possibly broken
mingw 8.1.0 [Approved] Downloads cached for licensed users
mingw-get 1.0.2 - Possibly broken
mini-squeezebox-control-chrome 1.2.20170115 [Approved]
Miniconda 4.3.21 [Approved] Downloads cached for licensed users
miniconda3 4.6.14 [Approved]
Minikube 1.3.1 [Approved]
minimus-regular-font 1.0 [Approved]
minio-client 2019.08.14 [Approved]
minio-server 2019.08.14 [Approved]
minipacman 2011.01.09 [Approved]
minishift 1.34.1 [Approved]
minisign 0.8.0 [Approved] Downloads cached for licensed users
mipony 2.2.1 [Approved] - Possibly broken
miranda 0.10.70 [Approved] Downloads cached for licensed users
miranda-ng 0.95.9.1 [Approved] - Possibly broken
mirc 7.57 [Approved] Downloads cached for licensed users
mirth 3.2.2.7694 [Approved] - Possibly broken
misslecommand 2011.06.16 [Approved]
mitkerberos 4.1 [Approved] Downloads cached for licensed users
mitmproxy 4.0.4 [Approved] Downloads cached for licensed users
mixxx 2.2.2 [Approved]
mkcert 1.3.0 [Approved]
mkdocs 1.0.4 [Approved]
mkdocs-material 4.4.0 [Approved]
mkey 1.3.5.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
mkvtoolnix 36.0.0 [Approved]
mkvtoolnix.portable 36.0.0 [Approved] Downloads cached for licensed users
mls-software-openssh 8.0.1.2 [Approved] Downloads cached for licensed users
mm-choco.extension 0.0.4.1 [Approved]
mmbot 0.9.8.8 [Approved]
MMDB. WebsiteBeaterUpper 1.0.0.2 - Possibly broken
mnemosyne 2.6 [Approved] Downloads cached for licensed users
mo2 2.2.1 [Approved]
mobalivecd 2.1 - Possibly broken
MobaXTerm 12.1.0 [Approved] Downloads cached for licensed users
mobipocket.reader 6.2 - Possibly broken
mobizen 2.21.1.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
moboplay 3.0.6.355 [Approved]
mockoon 1.4.0 [Approved]
moddb.extension 0.1.0 [Approved]
modernmix 1.15
modsecurity 2.9.1 [Approved] Downloads cached for licensed users
molotov 4.1.0 [Approved] Downloads cached for licensed users
momentum-chrome 0.92.2 [Approved]
monero 0.10.3.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
money-manager-ex 1.3.3.0 [Approved] Downloads cached for licensed users
moneydance 0.0.1880 [Approved] Downloads cached for licensed users
moneyguru 2.10.1 [Approved] Downloads cached for licensed users
mongoclient 1.5.0 [Approved] Downloads cached for licensed users
mongodb 4.0.12 [Approved]
mongodb-3 3.0.2 [Approved] Downloads cached for licensed users
mongodb.core 2.4.9.2014021902
mongodb.core.2.2 2.2.7.2014021906 - Possibly broken
mongodb.core.2.4 2.4.9.2014021905
mongodb.core.2.6 2.6.1.2014061320
mongodb.install 4.0.12 [Approved] Downloads cached for licensed users
mongodb.portable 4.0.12 [Approved]
MongoDBForTango 1.0 - Possibly broken
mongoose.tiny 5.0
MongoVUE 1.6.6
MonitorDetails 1.0.0.4
monitorinfoview 1.21 [Approved] Downloads cached for licensed users
monitorswitcher 0.7.0.0 [Approved] Downloads cached for licensed users
monkeyacademy 2014.05.07 [Approved]
mono 6.0.0.319 [Approved] Downloads cached for licensed users
mono3 3.2.3.20150323 [Approved]
monodevelop 5.10.1.6 [Approved] Downloads cached for licensed users
monogame 3.7.1 [Approved]
Monosnap 4.0.9 [Approved] Downloads cached for licensed users
mooncoin 1.862.1 [Approved] - Possibly broken
moonlight 1.0.0 [Approved]
moonlight-qt 1.1.0 [Approved]
moonlight-qt.install 1.1.0 [Approved]
moonlight-qt.portable 1.1.0 [Approved]
moonlight.install 1.0.0 [Approved]
moonlight.portable 1.0.0 [Approved]
moose.portable 0.77.20161009 [Approved] Downloads cached for licensed users
Moq. Prig 0.0.0 [Approved]
mosh-for-chrome 0.4.5 [Approved]
mossawir-lan-messenger 3.0 [Approved] Downloads cached for licensed users
motorolamobiledrivers 2.0.2.0 [Approved] Downloads cached for licensed users
mountain-duck 3.1.2.14611 [Approved] Downloads cached for licensed users
mouse-jiggler 1.8.27 [Approved] Downloads cached for licensed users
mousecontroller 1.7.1.20141201 [Approved] - Possibly broken
MouseTrap 1.0.1 [Approved]
mousewithoutborders 2.1.8.105 [Approved] Downloads cached for licensed users
movefile 1.20 [Approved] Downloads cached for licensed users
movie-collector 19.3.2 [Approved] Downloads cached for licensed users
MovieConverter 3.1
movieexplorer 0.84.03 [Approved] Downloads cached for licensed users
mozbackup 1.5.1.20141130 [Approved]
MozillaBuild 2.0.0 [Approved] Downloads cached for licensed users
mozillacacheview 1.81 [Approved] Downloads cached for licensed users
mozillahistoryview 1.65 [Approved] Downloads cached for licensed users
mp3directcut 2.25 [Approved]
mp3gain 1.5.2 [Approved]
mp3gain-gui 1.2.5.20190112 [Approved] Downloads cached for licensed users
mp3skyperecorder 4.52 [Approved] Downloads cached for licensed users
mp3tag 2.97 [Approved]
mpack 1.7 [Approved] Downloads cached for licensed users
mpc-be 1.5.3.20190428 [Approved]
mpc-be-nightly 1.5.3.4455 [Approved]
mpc-hc 1.7.13.20180702 [Approved]
mpc-hc-clsid2 1.8.7 [Approved]
mpc-qt 18.08 [Approved]
mpd 0.21.13 [Approved]
mpg123 1.24.0 [Approved] Downloads cached for licensed users
mpress 2.19.0.20160512 [Approved] Downloads cached for licensed users
mpv 2018.10.02 [Approved]
mpv.install 2018.10.02 [Approved]
mpv.portable 2018.10.02 [Approved]
mpw 2.7.10 [Approved]
mpw.portable 2.7.10 [Approved]
mqttfx 1.7.1 [Approved] Downloads cached for licensed users
mrboom 4.7 [Approved] Downloads cached for licensed users
mRemoteNG 1.76.20.24615 [Approved] Downloads cached for licensed users
mro 1.12.20141201 [Approved]
mro-launcher 0.2.1.20141201 [Approved]
mrswatson 0.9.8 [Approved] Downloads cached for licensed users
mrviewer 5.1.8.20190813 [Approved]
ms-reportviewer2015 12.0.2402.15 [Approved] Downloads cached for licensed users
MSAccess2010-redist 1.0
MSAccess2010-redist-x64 1.1 [Approved]
MSAccess2010-redist-x86 1.2 [Approved]
msbuild-sonarqube-runner 4.3.0 [Approved]
msbuild-structured-log-viewer 2.0.61 [Approved]
msbuild.awstasks 1.2
msbuild.communitytasks 1.5.0.235 [Approved] Downloads cached for licensed users
msbuild.extensionpack 4.0.15.0 [Approved] Downloads cached for licensed users
MSBuildDumper 1.0.0 [Approved]
msdeploy 2.10.1
msdeploy3 3.0
MSFilterPack2-redist-x64 1.1 [Approved]
msi.template 1.0.2 [Approved]
msi2xml 2.2.1.957 [Approved]
msiafterburner 4.6.1.20190525 [Approved] Downloads cached for licensed users
msigna 0.10.5 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
msinttypes 0.26 - Possibly broken
msmtp.portable 1.6.1 [Approved]
msoid-cli 7.250 [Approved] Downloads cached for licensed users
msoidcli 2.1 [Approved] Downloads cached for licensed users
msoledbsql 18.1.0.0 [Approved] Downloads cached for licensed users
mspacman 2012.06.20 [Approved]
mspacmannes 2012.07.08 [Approved]
mspass 1.43 [Approved]
mspass.install 1.43 [Approved]
mspass.portable 1.43 [Approved]
mssql2014express-defaultinstance 12.00.2000.2015022400 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
mssqlexpress2014sp1wt 1.1.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
mssqlserver-compact3.5 3.5.5386.2 [Approved]
MsSqlServer2012Express 11.00.3000.20140928 [Approved]
MsSqlServer2012ExpressAdv 11.0.2100.60 - Possibly broken
MsSqlServer2012ExpressWithReporting 11.00.3000.20140928 - Possibly broken
mssqlserver2014-sqlexpradv 12.0.5000.0 [Approved] Downloads cached for licensed users
mssqlserver2014-sqllocaldb 12.0.5000.0 [Approved] Downloads cached for licensed users
MsSqlServer2014Express 12.2.5000.20170905 [Approved]
MsSqlServer2016ExpressAdv 13.0.4001.0 [Approved] - Possibly broken
MsSqlServerManagementStudio2014Express 12.2.5000.20170905 [Approved]
MsSqlServerSchoolSampleDatabase 1.0.5 - Possibly broken
mssyncframework21-corecomponents-x64 2.1.1648.0 [Approved] Downloads cached for licensed users
MSSyncFramework21-sdk-x86 1.1 [Approved]
mstream 4.2.1 [Approved]
mstream.install 4.2.1 [Approved] Downloads cached for licensed users
mstream.portable 4.2.1 [Approved] Downloads cached for licensed users
MSVisualCplusplus2012-redist 1.1
MSVisualCplusplus2013-redist 1.1 [Approved]
msxml4.sp3 4.30.2100 [Approved] Downloads cached for licensed users
MSXML6. SP1 6.10.1129.0 [Approved]
msys2 20180531.0.0 [Approved]
msys2-installer 20161025.0.0 [Approved] Downloads cached for licensed users
msysgit 1.7.10.20120526 [Approved]
mtn 1.1 [Approved] Downloads cached for licensed users
mtputty 1.6.1.176 [Approved] Downloads cached for licensed users
mucommander 0.9.3.3 [Approved] Downloads cached for licensed users
muicacheview 1.01 [Approved] Downloads cached for licensed users
muleesb 3.8.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
mullvad-app 2019.5 [Approved] Downloads cached for licensed users
multiavchd 4.1 - Possibly broken
multibit 0.5.19 [Approved] Downloads cached for licensed users
multibit-hd 0.3.0 [Approved] Downloads cached for licensed users
MultiCommander 9.0.0.2532 [Approved] Downloads cached for licensed users
multihasher 2.8.2 [Approved] Downloads cached for licensed users
MultilingualAppToolkit 4.0.1900 [Approved] Downloads cached for licensed users
multimarkdown 6.4.0 [Approved] Downloads cached for licensed users
multimonitortool 1.95 [Approved] Downloads cached for licensed users
MultiPar 1.3.0.501 [Approved]
multipar.install 1.3.0.501 [Approved] Downloads cached for licensed users
multipar.portable 1.3.0.501 [Approved] Downloads cached for licensed users
multiplicity 1.03 [Approved]
mumble 1.2.19.20180702 [Approved]
munin-node 1.6.1.20130823 - Possibly broken
mupdf 1.14.0.20181105 [Approved] Downloads cached for licensed users
mupen64plus 2.5 [Approved] Downloads cached for licensed users
mupen64plus-qt 1.10 [Approved] Downloads cached for licensed users
musescore 3.2.3 [Approved]
music-collector 19.2.2 [Approved] Downloads cached for licensed users
musicbee 3.3.7115 [Approved] Downloads cached for licensed users
musique 1.5 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
mvc 3.0.2 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
mve 2016.05.17.00 [Approved] Downloads cached for licensed users
mweather 1.73 [Approved] - Possibly broken
mweather.install 1.76 [Approved] Downloads cached for licensed users
mweather.portable 1.76 [Approved] Downloads cached for licensed users
mwrock. DefaultInstall 1.0.0 - Possibly broken
mybrowserpage-chrome 1.0 [Approved]
myeventviewer 2.25 [Approved] Downloads cached for licensed users
myfamilytree 8.9.4.0 [Approved]
myfamilytree-languagepack 8.9.4.0 [Approved]
myharmony 1.0.1 [Approved]
myhomelib 2.2.0.822 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
myhomelib.portable 2.2.0.822 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
myhotkey 4.0.0.20170311 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
mylastsearch 1.65 [Approved] Downloads cached for licensed users
myoddweb.piger 0.9.2.2 [Approved]
myopenlab 3.11.0 [Approved] Downloads cached for licensed users
myphoneexplorer 1.8.12 [Approved] Downloads cached for licensed users
myrica 2.006.20150301.20190415 [Approved] Downloads cached for licensed users
myrulib 0.29.16 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
myrulib-cr 0.29.16 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
mysql 8.0.17 [Approved]
mysql-32bit 5.6.15 - Possibly broken
mysql-cli 8.0.11 [Approved]
mysql-connector 8.0.17 [Approved] Downloads cached for licensed users
mysql-connector-java 8.0.15 [Approved] Downloads cached for licensed users
mysql-odbc 5.3.12 [Approved] Downloads cached for licensed users
MySQL. Installer 5.6.17
mysql.odbc 5.1.13
MySql. Utilities 1.6.5 [Approved] Downloads cached for licensed users
mysql.workbench 8.0.17 [Approved] Downloads cached for licensed users
myuninst 1.77 [Approved] Downloads cached for licensed users
mzcv 1.56 [Approved] Downloads cached for licensed users
Nagstamon 3.2.1 [Approved] - Possibly broken
nagstamon.install 3.2.1 [Approved]
nagstamon.portable 3.2.1 [Approved]
namebench 1.3.1.20160928 [Approved]
namecoin 0.3.80 [Approved] Downloads cached for licensed users
namemytvseries.portable 1.8.4 [Approved] Downloads cached for licensed users
Nancy. Blog 0.1.0.0 - Possibly broken
nano 2.5.3 [Approved] Downloads cached for licensed users
NAnt 0.92.2 [Approved] Downloads cached for licensed users
nantcontrib 0.92.20190211 [Approved] Downloads cached for licensed users
nanum-gothic-coding-font 2.5.1.20180701 [Approved] Downloads cached for licensed users
nanumfont 3.0 - Possibly broken
naps2 6.1.2 [Approved]
naps2.install 6.1.2 [Approved] Downloads cached for licensed users
naps2.portable 5.3.3 [Approved] Downloads cached for licensed users
NArrange 0.2.9
nasm 2.14.02 [Approved] Downloads cached for licensed users
nateon 5.1.5.0 - Possibly broken
Natron 2.3.14.20190807 [Approved]
natron.install 2.3.14.20190807 [Approved] Downloads cached for licensed users
natron.portable 2.3.14.20190807 [Approved]
nats-server 2.0.0.20190610 [Approved] Downloads cached for licensed users
nats-streaming-server 0.15.1.20190610 [Approved] Downloads cached for licensed users
nautilus 1.2.1 [Approved]
nbfc 1.6.3 [Approved] Downloads cached for licensed users
ncftp 3.2.5.20140402 - Possibly broken
ncollector-studio-lite 3.7.0.2917 [Approved]
ncrunch-console 3.30.1 [Approved] Downloads cached for licensed users
ncrunch-gridnodeserver 3.30.1 [Approved] Downloads cached for licensed users
ncrunch-vs2008 3.30.1 [Approved] Downloads cached for licensed users
ncrunch-vs2010 3.30.1 [Approved] Downloads cached for licensed users
ncrunch-vs2012 3.30.1 [Approved] Downloads cached for licensed users
ncrunch-vs2013 3.30.1 [Approved] Downloads cached for licensed users
ncrunch-vs2015 3.30.1 [Approved] Downloads cached for licensed users
ncrunch-vs2017 3.30.1 [Approved] Downloads cached for licensed users
ncrunch-vs2019 3.30.1 [Approved] Downloads cached for licensed users
ncrunch.vs2013 0.0.0.0 [Approved] - Possibly broken
ndm 1.2.0 [Approved] Downloads cached for licensed users
neat 5.7.1.20190403 [Approved] Downloads cached for licensed users
negativescreen 2.6 [Approved]
neko 2.2.0 [Approved]
nem 0.6.91 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
neo4j-community 3.5.1 [Approved]
NeocronCE 2.2.180.16 - Possibly broken
neovim 0.3.8 [Approved]
nero-aac 1.5.4 [Approved] Downloads cached for licensed users
Nestopia 1.40
netbalancer 9.5.2 [Approved] - Possibly broken
NetBeans 8.2.20171030 [Approved]
netbeans-cpp 8.2 [Approved]
netbeans-html5 8.2 [Approved]
netbeans-jee 8.1 [Approved] Downloads cached for licensed users
netbeans-jse 8.2 [Approved]
netbeans-php 8.2 [Approved]
netbeans-web 8.2 [Approved]
netbscanner 1.11 [Approved] Downloads cached for licensed users
netcat 1.12 [Approved]
NetCFPowerToys 3.5.0 - Possibly broken
NETCFSVCUTIL 3.5.0 - Possibly broken
netconnectchoose 1.07 [Approved] Downloads cached for licensed users
netdrive 3.6.571 [Approved] Downloads cached for licensed users
netease-cloudmusic 2.1.0 [Approved]
NetfoxDetective 0.9.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
netfx-4.0.1-devpack 4.0.447.20180614 [Approved] - Possibly broken
netfx-4.0.2-devpack 4.0.506 [Approved]
netfx-4.0.3-devpack 4.0.551.20180614 [Approved] - Possibly broken
netfx-4.5.1-devpack 4.5.50932 [Approved]
netfx-4.5.2-devpack 4.5.5165101.20180721 [Approved] Downloads cached for licensed users
netfx-4.6-devpack 4.6.81 [Approved] - Possibly broken
netfx-4.6.1-devpack 4.6.01055.00 [Approved] - Possibly broken
netfx-4.6.2-devpack 4.6.01590.20170129 [Approved] - Possibly broken
netfx-4.7-devpack 4.7.2053.0 [Approved] Downloads cached for licensed users
netfx-4.7.1-devpack 4.7.2558.20190225 [Approved] Downloads cached for licensed users
netfx-4.7.2-devpack 4.7.2.20190225 [Approved] Downloads cached for licensed users
netfx-pcl-reference-assemblies-4.6 4.6.20150820 [Approved] Downloads cached for licensed users
netfx-repair-tool 4.6.1535.020180101 [Approved] Downloads cached for licensed users
nethack 3.6.2 [Approved] Downloads cached for licensed users
netio-gui 1.0.4 [Approved] Downloads cached for licensed users
NetLogo 6.1.0 [Approved] Downloads cached for licensed users
netmagic 1.0.25 [Approved]
netpass 1.50 [Approved]
netpass.install 1.50 [Approved]
netpass.portable 1.40 [Approved] - Possibly broken
netresview 1.27 [Approved] Downloads cached for licensed users
netrouteview 1.30 [Approved] Downloads cached for licensed users
netscan 6.2.1.20161101 [Approved] - Possibly broken
netscan.install 6.2.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
netscan.portable 6.2.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
netscan32 5.4.9.20160330 [Approved] - Possibly broken
netscan64 5.4.9.20160330 [Approved] - Possibly broken
netsetman 4.7.1 [Approved] Downloads cached for licensed users
netspeakerphone 4.9.1 [Approved] Downloads cached for licensed users
netstat-agent 3.5 [Approved] Downloads cached for licensed users
netstat-agent.portable 3.5 [Approved] Downloads cached for licensed users
netstat-viewer 1.0.20180725 [Approved] Downloads cached for licensed users
netstress 2.0.9686 [Approved] Downloads cached for licensed users
netsurf 3.6 [Approved] Downloads cached for licensed users
nettime 3.14.20161102 [Approved] Downloads cached for licensed users
network-inventory-advisor 5.0.155 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
networkconnectlog 1.11 [Approved] Downloads cached for licensed users
networkinterfacesview 1.15 [Approved] Downloads cached for licensed users
networklatencyview 1.65 [Approved] Downloads cached for licensed users
NETworkManager 1.11.0.0 [Approved]
networkmonitor 3.4.0.20140224
networktrafficview 2.30 [Approved] Downloads cached for licensed users
networkusageview 1.13 [Approved] Downloads cached for licensed users
networx 6.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
neverball 1.6.0 [Approved] Downloads cached for licensed users
newfiletime 3.63 [Approved] Downloads cached for licensed users
NewRelic 3.8.1.0 - Possibly broken
newrelic-dotnet 8.17.438.0 [Approved]
newrelic-infra 1.5.26 [Approved] Downloads cached for licensed users
NewRelic-Server-Agent 3.3.6.0 [Approved] Downloads cached for licensed users
newrelicserver 3.2.6.0
NewRelicWindowsServerAgent 3.2.6.0
news-feed-eradicator-for-facebook-chrome 1.0.6 [Approved] - Possibly broken
newsbin 6.72 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
newt 1.0.0.1 - Possibly broken
nextcloud-client 2.5.3 [Approved] Downloads cached for licensed users
nextiva 22.6.3.64 [Approved] Downloads cached for licensed users
nexus-oss 2.14.14.01 [Approved]
nexus-repository 3.15.2.01 [Approved]
nexus-root-toolkit 2.1.9.20170607 [Approved]
nexusfile 5.3.3.5532 [Approved]
nexusfile.install 5.3.3.5532 [Approved] Downloads cached for licensed users
nexusfile.portable 5.3.3.5532 [Approved] Downloads cached for licensed users
nexusfont 2.6.2 [Approved]
nexusfont.install 2.6.2 [Approved] Downloads cached for licensed users
nexusfont.portable 2.6.2 [Approved] Downloads cached for licensed users
nexusimage 1.1.3.992 [Approved] Downloads cached for licensed users
nfopad 1.74 [Approved] Downloads cached for licensed users
nfopad.portable 1.74 [Approved] Downloads cached for licensed users
nfs-win 1.0.17083 [Approved] Downloads cached for licensed users
nginx 1.17.3 [Approved]
nginx-service 1.16.0 [Approved]
ngrok 2.0 [Approved]
ngrok.portable 2.0.1 [Approved]
ngspice 30.0 [Approved]
niftywindows 0.9.3.1
nightcode 2.6.0 [Approved] Downloads cached for licensed users
Nightingale 1.11.0 - Possibly broken
nim 0.11.2 [Approved] Downloads cached for licensed users
nimbleset 2.0.2.25075 [Approved]
NimbleText 2.9.1.36018 [Approved] Downloads cached for licensed users
ninefs 2010.01.21 [Approved] Downloads cached for licensed users
ninja 1.9.0.20190208 [Approved]
nircmd 2.86 [Approved]
nirext 1.01 [Approved] Downloads cached for licensed users
nirlauncher 1.22.20 [Approved]
nitrate 1.0.26 [Approved]
nitroreader.install 5.5.9.2 [Approved] Downloads cached for licensed users
nitroshare 0.3.4 [Approved] Downloads cached for licensed users
nk2edit 3.35 [Approved] - Possibly broken
nk2edit.install 3.40 [Approved] Downloads cached for licensed users
nk2edit.portable 3.40 [Approved] Downloads cached for licensed users
nledger 0.7 [Approved] Downloads cached for licensed users
nmap 7.80 [Approved]
nmm 070.8 [Approved]
no-cash-psx 2.0 [Approved] Downloads cached for licensed users
no-ip-duc 4.1.1.20170207 [Approved] Downloads cached for licensed users
node-webkit 0.6.2
node-webkit-0.9.2 0.9.2 - Possibly broken
nodejs 12.8.1 [Approved]
nodejs-lts 10.16.2 [Approved]
nodejs.commandline 6.11.0 [Approved]
nodejs.install 12.8.1 [Approved]
nodist 0.9.1 [Approved]
nomachine 6.7.6.700 [Approved]
nomacs 3.12.1 [Approved]
nomacs.portable 3.12.1 [Approved]
nomad 0.9.4 [Approved]
nordvpn 6.23.11 [Approved] Downloads cached for licensed users
norman 0.0.1 [Approved] Downloads cached for licensed users
norton-text-search-resurrection 1.0.0.1 [Approved] Downloads cached for licensed users
noscript 2.9.0.2 [Approved]
notable 1.7.2 [Approved] Downloads cached for licensed users
notcl 1.2.4
notebar 1.0.0 [Approved] - Possibly broken
notepad2 4.2.25.20160422 [Approved] Downloads cached for licensed users
notepad2-mod 4.2.25.99800 [Approved] Downloads cached for licensed users
notepad3 5.19.630.2381 [Approved]
notepad3.install 5.19.630.2381 [Approved]
notepadplusplus 7.7.1 [Approved]
notepadplusplus-npppluginmanager 1.14.2 [Approved]
notepadplusplus.commandline 7.7.1 [Approved]
notepadplusplus.install 7.7.1 [Approved]
Notepadplusplus. Settings 1.0.0.20141029 [Approved] - Possibly broken
notepadreplacer 1.1.6 - Possibly broken
notifier-for-github-chrome 3.0.5 [Approved]
notify-me-ci 1.3.3.13 [Approved] Downloads cached for licensed users
notion 1.0.6 [Approved] Downloads cached for licensed users
Noto 0.20171025 [Approved] Downloads cached for licensed users
now 5.0.1 [Approved] Downloads cached for licensed users
npackd 1.20.5 [Approved]
npackd-cli 1.20.5 [Approved]
npackd-cli.install 1.20.5 [Approved] Downloads cached for licensed users
npackd-cli.portable 1.20.5 [Approved] Downloads cached for licensed users
npackd.install 1.20.5 [Approved] Downloads cached for licensed users
npackd.portable 1.20.5 [Approved] Downloads cached for licensed users
npmtaskrunner 1.1.35 [Approved] Downloads cached for licensed users
npppluginmanager 1.4.12 [Approved]
nQuant 1.0.3 [Approved]
nrfjprog 10.2.1 [Approved] Downloads cached for licensed users
nsbuilder 2018.9.11 [Approved]
nsbuilder.install 2018.9.11 [Approved] Downloads cached for licensed users
nsbuilder.portable 2018.9.11 [Approved] Downloads cached for licensed users
NSClientPlusPlus.x64 0.3.8.1 [Approved]
NSClientPlusPlus.x86 0.3.8.1 [Approved]
nscp 0.5.2.39 [Approved] Downloads cached for licensed users
nservicebus 4.4.2 [Approved]
nsis 3.04 [Approved]
nsis-advancedlogging 3.04.0.20190220 [Approved]
nsis-unicode 2.46.5 [Approved] Downloads cached for licensed users
nsis.install 3.04 [Approved] Downloads cached for licensed users
nsis.portable 3.04 [Approved] Downloads cached for licensed users
nspec4nunit 0.9.66.5 - Possibly broken
nsq 1.1.0 [Approved] Downloads cached for licensed users
NSSM 2.24.101.20180116 [Approved]
nsudo 6.2.1812.31 [Approved]
NSwagStudio 13.0.4 [Approved]
nteract 0.14.5 [Approved] Downloads cached for licensed users
nteract.install 0.1.0.20170315 [Approved] Downloads cached for licensed users
ntfsinfo 1.20 [Approved] Downloads cached for licensed users
ntfslinksview 1.30 [Approved] Downloads cached for licensed users
ntfssecurity-psmodule 4.2.4 [Approved]
ntlite-free 1.8.0.7025 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
NTop. Portable 0.3.3 [Approved]
ntstrace 1.0.1.1 - Possibly broken
ntttcp 5.33 [Approved] Downloads cached for licensed users
nubasic 1.50 [Approved]
nuclear 0.5.1 [Approved]
nuget-credentialprovider-vss 0.37.0 [Approved] Downloads cached for licensed users
NuGet. CommandLine 5.2.0 [Approved]
NuGet. ContextMenu 1.0.0.20141024
NuGet.vs 2.8.60318.667 [Approved]
NugetPackageExplorer 5.2.88 [Approved]
NugetPackageManager 2.8.60318.667 [Approved]
NugetPackageManagerForVisualStudio2013 2.12.0.817 [Approved] Downloads cached for licensed users
nugetupload 1.0.3 [Approved]
numpy 1.17.0 [Approved]
nunit 3.4.0.20180717 [Approved]
nunit-console-runner 3.10.0 [Approved]
nunit-extension-nunit-project-loader 3.6.0 [Approved]
nunit-extension-nunit-v2-driver 3.7.0 [Approved]
nunit-extension-nunit-v2-result-writer 3.6.0 [Approved]
nunit-extension-teamcity-event-listener 1.0.6 [Approved]
nunit-extension-vs-project-loader 3.8.0 [Approved]
nunit-gui 0.6.0 [Approved]
nunit-project-editor 1.0 [Approved]
nunit.install 3.4.0.20180717 [Approved]
nunit.parallel 1.05.0.0 [Approved] - Possibly broken
nunit.portable 3.4.0.20180717 [Approved]
nvda 2019.1.1.20190702 [Approved]
nvidia-display-driver 431.60 [Approved] Downloads cached for licensed users
nvidia-display-driver-disable-updates-winconfig 0.0.1 [Approved]
nvidia-inspector 1.9.7.8 [Approved]
nvidia-profile-inspector 2.1.3.10 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
nvika 1.0.1 [Approved] Downloads cached for licensed users
nvm 1.1.5 [Approved]
nvm.portable 1.1.7 [Approved] Downloads cached for licensed users
nvs 1.5.2 [Approved] Downloads cached for licensed users
nvu 1.0.0.1 - Possibly broken
nxlog 2.10.2150 [Approved]
nxt 1.11.5 [Approved] Downloads cached for licensed users
nyagos 4.4.4.3 [Approved] Downloads cached for licensed users
nyanfi 14.04 [Approved]
nytdl 1.1.25 [Approved] Downloads cached for licensed users
nzbget 20.0 [Approved] Downloads cached for licensed users
nzxt-cam 3.7.8 [Approved] Downloads cached for licensed users
ober 0.5.4 [Approved]
ober.portable 0.5.56 [Approved]
obs 0.659 [Approved] Downloads cached for licensed users
obs-mp 0.14.2.2202107 [Approved]
obs-studio 23.2.1 [Approved]
obs-studio-wiiplayer2-scripts 0.4.6657.3109 [Approved]
obs-studio.install 23.2.1 [Approved]
obs-studio.portable 23.2.1 [Approved]
ocaml 4.00.1.20141015 - Possibly broken
ocaml-ocpwin64 4.00.1.20141010 - Possibly broken
occt 5.3.1.99 [Approved] Downloads cached for licensed users
ocenaudio 3.7.2 [Approved]
ocenaudio.install 3.7.2 [Approved] Downloads cached for licensed users
ocenaudio.portable 3.7.2 [Approved] Downloads cached for licensed users
ocpwin 4.02.1.20160113 [Approved] Downloads cached for licensed users
octant 0.5.1 [Approved] Downloads cached for licensed users
Octave 5.1.0 [Approved]
octave.install 5.1.0 [Approved] Downloads cached for licensed users
octave.portable 5.1.0 [Approved] Downloads cached for licensed users
OctgnDevPackage-Express 1.0.0.2
OctopusDeploy 2019.5.12 [Approved] Downloads cached for licensed users
OctopusDeploy. Tentacle 5.0.2 [Approved] Downloads cached for licensed users
OctopusTools 6.12.0 [Approved]
oda-file-converter 19.12.0.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
odata2poco-commandline 3.1.0 [Approved]
odrive 1.6452 [Approved] Downloads cached for licensed users
OffCAT 2.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
office-online-chrome 1.5.0.20170115 [Approved]
office-to-pdf 1.8 [Approved]
office2013-proofingtools-nl 15.0.4420.1017 [Approved] Downloads cached for licensed users
office365-2016-deployment-tool 16.0.7614.3602 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
Office365Business 11509.33604 [Approved]
Office365HomePremium 2016.20160728 [Approved] Downloads cached for licensed users
Office365ProPlus 2016.20190418 [Approved]
officecustomuieditor 1.1 - Possibly broken
officedevtools 14.0.23930 [Approved] Downloads cached for licensed users
officegate-configuration-tool 1.2.8 [Approved] Downloads cached for licensed users
officeins 1.20 [Approved] Downloads cached for licensed users
OfficeProPlus2013 15.0.4827 [Approved] Downloads cached for licensed users
officeremote 1.1.3.0 [Approved]
officeribboneditor 4.4.2 - Possibly broken
officetabenterprise 9.80 - Possibly broken
officetabfree 9.70.20140510 - Possibly broken
ofview 1.85 [Approved] - Possibly broken
ofview.install 1.86 [Approved] Downloads cached for licensed users
ofview.portable 1.86 [Approved] Downloads cached for licensed users
Okta. Core. Automation 0.2.0.0 [Approved]
okular 19.07.90 [Approved]
oldcalc 1.1.171010 [Approved] Downloads cached for licensed users
olex2 1.2.8.5506 [Approved] Downloads cached for licensed users
ollydbg 1.10 [Approved] Downloads cached for licensed users
omegat 3.1.8 [Approved] - Possibly broken
omnidb-app 2.16.0 [Approved]
omnidb-server 2.16.0 [Approved]
omnifyhotspot 1.1 [Approved]
omnirig 1.19 [Approved] Downloads cached for licensed users
onedrive 17.3.6798.0207 [Approved]
onenote 16.0.11901.20218 [Approved] Downloads cached for licensed users
onenote-taggingkit-addin.install 3.5.6972.33231 [Approved] Downloads cached for licensed users
onescript 1.0.21 [Approved] Downloads cached for licensed users
onescript-cli 1.1.1 [Approved] Downloads cached for licensed users
onetastic 4.2.1 [Approved]
onionshare 2.1 [Approved]
onlyoffice 4.8.0 [Approved] Downloads cached for licensed users
ontopreplica 3.5.1.20170427 [Approved]
op 0.5.5 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
opc-components 106.0.201.2 [Approved]
open-delta 1.02 [Approved] Downloads cached for licensed users
open-dvd-producer 16.11 [Approved]
open-mahjong-java 3.1 [Approved] Downloads cached for licensed users
open-screenshot-chrome 24.0 [Approved]
open-shell 4.4.131 [Approved]
open-stage-control 0.47.3 [Approved]
open-visual-traceroute 1.7.1 [Approved] Downloads cached for licensed users
openal 2.07.0.20170623 [Approved] Downloads cached for licensed users
openalsdk 1.1 [Approved] Downloads cached for licensed users
openaudible 1.5.2 [Approved] Downloads cached for licensed users
openboard 1.5.2 [Approved] Downloads cached for licensed users
openchrom 1.3.0 [Approved] Downloads cached for licensed users
opencl-intel-cpu-runtime 16.1.1 [Approved] Downloads cached for licensed users
opencodecs 0.85.17777 [Approved]
opencommandline 2.1.212 [Approved] Downloads cached for licensed users
openconnect-gui 1.5.3 [Approved] Downloads cached for licensed users
OpenCover 4.7.922 [Approved] Downloads cached for licensed users
opencover.portable 4.7.922 [Approved] Downloads cached for licensed users
opencppcoverage 0.9.7.0 [Approved] Downloads cached for licensed users
OpenCV 4.1.1 [Approved] Downloads cached for licensed users
opendns-updater 2.2.1.20170716 [Approved] Downloads cached for licensed users
openfire 4.4.1 [Approved] Downloads cached for licensed users
openflexure-ev 1.1.0 [Approved] Downloads cached for licensed users
openhab 2.4.0 [Approved]
OpenHardwareMonitor 0.8.0 [Approved] Downloads cached for licensed users
openide 0.9.2
openinsublimetext 1.0.8 [Approved] Downloads cached for licensed users
openinvscode 1.3.19 [Approved] Downloads cached for licensed users
openjdk 12.0.2 [Approved] Downloads cached for licensed users
openjdk.portable 11.0.1 [Approved] Downloads cached for licensed users
openjdk11 11.0.2.01 [Approved] Downloads cached for licensed users
openjdk11redhatbuild 11.0.3 [Approved] Downloads cached for licensed users
openjdk8redhatbuild 8.212.1 [Approved] Downloads cached for licensed users
openldap 2.4.39 - Possibly broken
openlivewriter 0.6.0.0 [Approved]
openlp 2.4.6 [Approved]
openmodelica 1.13.2 [Approved] Downloads cached for licensed users
openmpt 1.28.6.0 [Approved]
openmw 0.45.0 [Approved] Downloads cached for licensed users
openni-x64 2.2.0.33 - Possibly broken
openni-x86 2.2.0.33 - Possibly broken
openocd 0.10.0.20190715 [Approved] Downloads cached for licensed users
OpenOffice 4.1.6 [Approved]
openpht 1.8.0 [Approved] Downloads cached for licensed users
openproj 1.4 [Approved]
openra 2019.03.14 [Approved] Downloads cached for licensed users
openrct2 0.1.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
OpenSans 1.0.0 [Approved]
opensavefilesview 1.15 [Approved] Downloads cached for licensed users
openscad 2019.05 [Approved] Downloads cached for licensed users
OpenShark 1.4
openshift-cli 3.11.0 [Approved]
OpenShot 2.4.4 [Approved] Downloads cached for licensed users
openssh 8.0.0.1 [Approved]
OpenSSL. Light 1.1.1.20181020 [Approved]
opensslkey 1.3.0.20130622 [Approved]
openstego 0.6.1 [Approved]
openstego.install 0.6.1 [Approved] Downloads cached for licensed users
openstego.portable 0.6.1 [Approved] Downloads cached for licensed users
opentoonz 1.1.3 [Approved]
opentrack 2.3.9 [Approved] Downloads cached for licensed users
openttd 1.9.2 [Approved] Downloads cached for licensed users
opentyrian 2.1.0 [Approved] Downloads cached for licensed users
openvpn 2.4.7 [Approved]
openvpn-community 2.3.6 [Approved]
openwithview 1.11 [Approved] Downloads cached for licensed users
openxcom 2019.07.28.0403 [Approved] Downloads cached for licensed users
Opera 62.0.3331.99 [Approved] Downloads cached for licensed users
opera-developer 64.0.3409.0 [Approved]
opera-neon 1.0.2531.0 [Approved] Downloads cached for licensed users
Opera. Next 32.0.1948.19 [Approved]
operacacheview 1.40 [Approved] Downloads cached for licensed users
operapassview 1.10 [Approved]
opos-cco 1.14.001 [Approved] Downloads cached for licensed users
opsview-agent-x32 28.01.15.1600 [Approved] - Possibly broken
opswatsecurityscore 7.0.137.10 [Approved]
OptiPNG 0.7.7 [Approved]
opus-tools 0.1.9 [Approved] Downloads cached for licensed users
oracle-sql-developer 18.4.0 [Approved]
orca 3.1.3790.0000 [Approved] Downloads cached for licensed users
OrchardCms 1.8.1.2 - Possibly broken
orientdb 3.0.22 [Approved]
origin 10.5.44.29072 [Approved]
orion 1.1.3 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
orionsdk 2.5.0.214 [Approved] Downloads cached for licensed users
ortep3 2014.1 [Approved]
orvibos20cli 1.0 [Approved]
orwelldevcpp 5.11 [Approved] Downloads cached for licensed users
oscar-mouse-editor 12.08.17 [Approved] Downloads cached for licensed users
osfmount 3.0.1004 [Approved] Downloads cached for licensed users
osfontpack 1.4.0 [Approved] - Possibly broken
osmc-installer 130.0.0.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
osquery 3.4.0 [Approved]
ossec-agent 2.8 [Approved] - Possibly broken
ossec-client 3.3.0 [Approved] Downloads cached for licensed users
ost2 2.13.0.28 [Approved] Downloads cached for licensed users
ost2pst-wizard 4.2 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
osu 1.0.0.20170521 [Approved] Downloads cached for licensed users
osuhelper 2.0.2 [Approved] Downloads cached for licensed users
otter-browser 1.0.81 [Approved] Downloads cached for licensed users
otterbrowser 0.9.03.20171117 [Approved]
OuiGuiChocolatey 0.3 [Approved]
outlook-photos 2.1.2.0 [Approved] Downloads cached for licensed users
outlookaddressbookview 2.17 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
outlookattachview 3.16 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
Outlookcaldav 3.6.2 [Approved]
outlookconnector 4.5.0 [Approved] Downloads cached for licensed users
OutlookConverter 3.1
outlookstatview 2.17 [Approved] Downloads cached for licensed users
OutlookViewer 3.1
outlyer-agent 1.5.5 [Approved] Downloads cached for licensed users
outwiker 1.8.1 [Approved] Downloads cached for licensed users
OwinHost 3.0.0
owncloud-client 2.5.4.11654 [Approved]
OxygenMono 2014.12.31 [Approved]
ozcode 3.1.0.3913 [Approved] Downloads cached for licensed users
ozcode-vs2017 4.0.0.1229 [Approved]
p4 2019.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
p4d 2018.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
P4Merge 2018.3.1719708 [Approved] Downloads cached for licensed users
p4scc 2012.1 - Possibly broken
p4v 2018.1 [Approved] Downloads cached for licensed users
packageinstaller 2.0.89 [Approved] Downloads cached for licensed users
packageintellisense 1.8.110 [Approved] Downloads cached for licensed users
packer 1.4.2 [Approved]
packer-post-processor-vagrant-vmware-ovf 0.2.1.20150603 [Approved] Downloads cached for licensed users
packer-provisioner-windows-update 0.7.1 [Approved] Downloads cached for licensed users
packer-windows-plugins 1.0.0 [Approved] Downloads cached for licensed users
packetbeat 7.3.0 [Approved] Downloads cached for licensed users
pacman 2013.08.04 [Approved]
pacman-revenge 2017.05.18 [Approved]
padgen 3.1.1.51 [Approved] Downloads cached for licensed users
padmanager 2.0.0.76 [Approved] Downloads cached for licensed users
paint.net 4.2.1 [Approved]
painter 2016.11.29 [Approved]
Paket 5.216.0 [Approved]
Paket. PowerShell 4.8.8 [Approved]
paketinit 1.0 [Approved]
pal 2.7.6.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
palemoon 28.6.1 [Approved] Downloads cached for licensed users
pan 0.140.216 [Approved]
pandabank 3.0.2.0 [Approved]
pandabank.install 3.0.2.0 [Approved] Downloads cached for licensed users
pandabank.portable 3.0.2.0 [Approved]
PandaFreeAntivirus 18.07.04 [Approved]
pandoc 2.7.3 [Approved]
pandoc-crossref 0.3.4.1 [Approved] Downloads cached for licensed users
PangolinQuickshow 2.5.393 - Possibly broken
papercut 5.1.44 [Approved]
papyrus 1.0.2 [Approved] Downloads cached for licensed users
par2cmdline 0.6.13 [Approved] Downloads cached for licensed users
parq 5.1.1.0 [Approved]
Parse. CloudCode 1.0.6.0 - Possibly broken
parsec-cloud 0.12.0 [Approved] - Possibly broken
PartitionMasterFree 13.0.0.20190121 [Approved] Downloads cached for licensed users
partitionwizard 11.5 [Approved] Downloads cached for licensed users
PasS 1.5.2 [Approved] - Possibly broken
pass-winmenu 1.9.1.20190612 [Approved]
pass4win 1.1.7 [Approved] Downloads cached for licensed users
passkey 8.2.7.9 [Approved] Downloads cached for licensed users
passprotect-chrome 0.1.8 [Approved]
password-checkup-chrome 1.10 [Approved]
password-control 2.4.3061.39299 [Approved] Downloads cached for licensed users
password-generator 3.0.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
passwordfox 1.56 [Approved] - Possibly broken
passwordSafe 3.47.2 [Approved]
passwordscan 1.42 [Approved]
passwordscan.install 1.42 [Approved] Downloads cached for licensed users
passwordscan.portable 1.42 [Approved] Downloads cached for licensed users
pasteboard 1.1.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
pasteintofile 1.4.0 [Approved] Downloads cached for licensed users
patch 2.5.9 [Approved] Downloads cached for licensed users
patch-my-pc 4.1.0.3 [Approved] Downloads cached for licensed users
patchcleaner 1.4.2.0 [Approved]
patchwork 3.11.4 [Approved] Downloads cached for licensed users
path-copy-copy 16.0 [Approved]
path-manager 2.3 [Approved] Downloads cached for licensed users
patheditor 1.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
pathlengthchecker 1.2.0 [Approved]
pathmanager 1.1.1 [Approved] Downloads cached for licensed users
pathmanager.portable 1.1.1
pavement 1.0.1 - Possibly broken
pavement.dev 1.0.1 - Possibly broken
pavement.standard 1.0.2
payara 4.1.2.1810 [Approved] Downloads cached for licensed users
pc-decrapifier 3.0.1.20161106 [Approved] Downloads cached for licensed users
pcanypass 1.12 [Approved] Downloads cached for licensed users
pcanyscan 1.0 [Approved] Downloads cached for licensed users
PCDIMMER 5.3.1.4594 [Approved] - Possibly broken
pci-z 2.0 [Approved] Downloads cached for licensed users
pcmark8 2.10.901 [Approved] Downloads cached for licensed users
pcsx2 1.4.0.20160603 [Approved] - Possibly broken
pctransfree 9.10 [Approved] Downloads cached for licensed users
pcwrunas 0.4.0.20161129 [Approved] Downloads cached for licensed users
PdbGit 3.0.38 [Approved]
pdbproject-vs2013 2.1
pdbproject-vs2015 1.0 [Approved]
pdf-ifilter-64 11.0.01.20180614 [Approved] Downloads cached for licensed users
pdf24 8.9.1 [Approved]
pdf2djvu 0.9.13 [Approved]
pdf2json 0.68 [Approved] Downloads cached for licensed users
pdf2svg 0.2.2 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
pdf417 3.2.4 [Approved] Downloads cached for licensed users
PDFCombine 3.1
PDFConverter 3.1
PDFCreator 3.5.1 [Approved]
pdfedit 2014.0526.1531 [Approved]
pdffactorypro-workstation 7.02 [Approved]
pdfill 11.0
pdfsam 4.0.3 [Approved]
pdfsam.install 4.0.3 [Approved]
PDFSplitter 3.1
pdftk 2.02
pdftk-server 2.02 [Approved] Downloads cached for licensed users
pdftkbuilder 3.9.4 [Approved]
PDFXchangeEditor 8.0.331.0 [Approved]
pdfxchangelite 6.0.322.5 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
PDFXChangeViewer 2.5.317.20161116 [Approved]
pdk 1.12.0.0 [Approved] Downloads cached for licensed users
pdq-deploy 13.3.0.0 [Approved] Downloads cached for licensed users
pdq-inventory 15.1.0.0 [Approved] Downloads cached for licensed users
pe-client-tools 19.1.3 [Approved] Downloads cached for licensed users
peach 3.1.53 [Approved] Downloads cached for licensed users
peazip 6.8.1 [Approved]
peazip.install 6.8.1 [Approved]
peazip.portable 6.0.3 [Approved] Downloads cached for licensed users
pebear 0.3.9.5 [Approved] Downloads cached for licensed users
pecmd 1.2.0.3 [Approved]
peco 0.5.3 [Approved] Downloads cached for licensed users
pedeps 0.1.6 [Approved] Downloads cached for licensed users
peerblock 1.2.0.693 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
peerunity 0.1.1 [Approved]
peerunity.install 0.1.1 [Approved] Downloads cached for licensed users
peerunity.portable 0.1.1 [Approved] Downloads cached for licensed users
pelles-c 8.00.0.0 [Approved] Downloads cached for licensed users
pelles-c-sdk 8.00.0.0 [Approved] Downloads cached for licensed users
Pencil 3.0.4 [Approved] Downloads cached for licensed users
pendmoves 1.2 [Approved] Downloads cached for licensed users
peonefs 1.0.3938.18045 [Approved] Downloads cached for licensed users
perfect-privacy 1.10.29 [Approved] Downloads cached for licensed users
perfmonitor2 2.0.4.1 [Approved] Downloads cached for licensed users
performance-monitor 4.1.3.20170523 [Approved] Downloads cached for licensed users
performancetest 9.0.1031 [Approved] Downloads cached for licensed users
perfview 2.0.45 [Approved] Downloads cached for licensed users
PerfWatsonMonitor 11.0.51209.0
permain 0.7 [Approved] Downloads cached for licensed users
permissionsreporter 2.9.228.0 [Approved] Downloads cached for licensed users
persepolis 3.1.0 [Approved]
PersonalBackup 6.0.0700 [Approved] Downloads cached for licensed users
pesieve 0.2.1 [Approved] Downloads cached for licensed users
pester 4.8.1 [Approved]
PeStudio 4.5 [Approved] - Possibly broken
petabridge-cmd 0.6.3 [Approved]
pgadmin3 1.22.2.20170504 [Approved]
pgadmin4 4.11 [Approved] Downloads cached for licensed users
pgcli 3.3.6.20180604 [Approved] Downloads cached for licensed users
pgina 3.1.8.001 [Approved] Downloads cached for licensed users
pginafork 3.9.9.12 [Approved] Downloads cached for licensed users
phalanger-4.0-tools 1.16.7925 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
phalcon 2.0.9 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
PhantomJS 2.1.1 [Approved] Downloads cached for licensed users
philea 0.0.14 [Approved]
phonerlite 2.72 [Approved]
phonerlite.install 2.72 [Approved]
phonerlite.portable 2.72 [Approved]
photofiltre-studio-x 10.14.0.20190629 [Approved] Downloads cached for licensed users
photofiltre7 7.2.1 [Approved] Downloads cached for licensed users
photofiltre7-en 7.2.1 [Approved] Downloads cached for licensed users
photoguru 4.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
photorec 6.14.20130804
php 7.3.8 [Approved]
php-manager 2.3.0 [Approved] Downloads cached for licensed users
php-service 7.3.8 [Approved]
phpstorm 2019.2 [Approved] Downloads cached for licensed users
phraseapp 1.15.0 [Approved] Downloads cached for licensed users
PhraseExpress 14.0.145 [Approved]
phraseexpress.install 14.0.145 [Approved] Downloads cached for licensed users
phraseexpress.portable 14.0.145 [Approved] Downloads cached for licensed users
Physx. Legacy 9.13.0604 [Approved] Downloads cached for licensed users
pia 133.0 [Approved] Downloads cached for licensed users
pibakery 0.3.4 [Approved] Downloads cached for licensed users
picard 2.1.3 [Approved]
picassio 0.12.0 [Approved] Downloads cached for licensed users
pickles 2.20.1 [Approved]
picklesui 2.20.1 [Approved]
picoscope 6.13.15 [Approved] Downloads cached for licensed users
picotorrent 0.15.0 [Approved]
picotorrent.install 0.15.0 [Approved]
picotorrent.portable 0.15.0 [Approved]
picpick.portable 5.0.4 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
pidgin 2.13.0 [Approved] Downloads cached for licensed users
pidgin-otr 4.0.2.20190617 [Approved] Downloads cached for licensed users
PidginOtrPlugin 4.0.1.20190619 [Approved]
pik 0.3.0 [Approved]
pinginfoview 1.85 [Approved] Downloads cached for licensed users
pingmonitorfree 6.3 [Approved] Downloads cached for licensed users
pingplotter 5.11.3 [Approved] Downloads cached for licensed users
Pinta 1.5.0.20130501
pip 1.2.0 [Approved] - Possibly broken
pipelist 1.01 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
pitchfunk 1.14 [Approved]
pixelshop 1.0.0.20180711 [Approved] Downloads cached for licensed users
pixie 4.1 [Approved] Downloads cached for licensed users
pixivutil2 2019.07.12 [Approved] Downloads cached for licensed users
pjw.autopackages 1.1.20140628 - Possibly broken
pkgconfiglite 0.28
plane9 2.5.1.3 [Approved] Downloads cached for licensed users
PlanExplorerSsmsAddin 2.0
plantronicshub 3.11.52084.17287 [Approved] - Possibly broken
plantuml 1.2019.8 [Approved]
plaso 2017.09.30 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
plasso 9.0.0.456 [Approved] - Possibly broken
plaster 1.1.3 [Approved]
platonnetwork 0.6.0 [Approved]
platonnetwork-all 0.6.0 [Approved]
platonnetwork-mpclib 0.5.0 [Approved]
platyps 0.14.0 [Approved]
Play 2.3.6 [Approved]
playlist-creator 3.6.2 [Approved]
playlist-creator.install 3.6.2 [Approved] Downloads cached for licensed users
playlist-creator.portable 3.6.2 [Approved] Downloads cached for licensed users
playnite 5.4 [Approved] Downloads cached for licensed users
plentymarkets-client 229.3 [Approved] Downloads cached for licensed users
plex-chrome 2.12.8.0020180103 [Approved]
plex-home-theater 1.4.1.469001 [Approved]
plexamp 1.1.0 [Approved] Downloads cached for licensed users
plexmediaplayer 2.39.0.1005 [Approved] Downloads cached for licensed users
plexmediaserver 1.16.4.1469 [Approved] Downloads cached for licensed users
plexpy 1.4.21.0020180402 [Approved]
pluralsight-transcripter 1.0.0 [Approved] Downloads cached for licensed users
pmd 6.17.0.20190809 [Approved] Downloads cached for licensed users
pmetro 2019.08.12 [Approved] Downloads cached for licensed users
pmpagent 6.0.116 - Possibly broken
pneumatictube.portable 1.3.0.0 [Approved] Downloads cached for licensed users
png2ico 2008.12.08 [Approved]
pngcheck 2.3.0 [Approved] Downloads cached for licensed users
PngGauntlet 3.1.2.20171027 [Approved]
pnggauntlet.install 3.1.2.20171027 [Approved]
pngoo 0.1.1 [Approved] Downloads cached for licensed users
pngoptimizer 2.5.1 [Approved]
pngoptimizer.commandline 2.5 [Approved]
pngquant 2.12.3 [Approved] Downloads cached for licensed users
pngyu 1.0.1 [Approved] Downloads cached for licensed users
pocketsoap 1.5.5.20171030 [Approved] Downloads cached for licensed users
pode 0.32.0 [Approved]
poderosa-terminal-net35 5.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
poderosa-terminal-net40 5.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
poedit 2.2.3 [Approved] Downloads cached for licensed users
poi 10.3.0 [Approved]
pokemon-tcg 2.65.1.4419 [Approved] Downloads cached for licensed users
pokerth 1.1.1 - Possibly broken
polar 1.31.0 [Approved]
polipo 1.1.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
polleverywhere 2.10.1 [Approved] Downloads cached for licensed users
pomodoneapp 1.5.1534 [Approved] Downloads cached for licensed users
pomolectron 1.1.0 [Approved] Downloads cached for licensed users
PomoTime 1.8
poni 0.0.0.1
popcorn-time 0.3.10 [Approved] Downloads cached for licensed users
portable-library-tools-2 10.0.50828.20180323 [Approved] Downloads cached for licensed users
portexpert 1.7.6.16 [Approved] Downloads cached for licensed users
portfolio 0.40.1 [Approved] Downloads cached for licensed users
PortForward 1.0
portmon 3.03.0.20151228 [Approved] Downloads cached for licensed users
portqry 2.0 [Approved] Downloads cached for licensed users
posfordotnet.install 1.14 [Approved] Downloads cached for licensed users
posh-cde 0.1.0.0 [Approved]
posh-ci-git 0.0.1 [Approved]
Posh-GIT-HG 1.0.4 [Approved]
Posh-GitHub 0.0.2
Posh-HG 1.1.0.20120528 [Approved]
Posh-VsVars 0.0.3 - Possibly broken
poshadmin 1.1.0.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
PoshCode 4.0.1.5
poshdevops 0.0.72 [Approved]
poshdynargs 0.1.0.5 [Approved]
poshgit 0.7.3.1 [Approved]
poshhosts 0.2.0 [Approved]
PoshInternals 1.0.0.20 - Possibly broken
poshpuppetreports 0.9.55 [Approved]
PoshRunner 0.9.20130105.1
poshtools-visualstudio2012 1.0.5 [Approved]
poshtools-visualstudio2013 3.0.299 [Approved]
poshtools-visualstudio2015 3.0.299 [Approved]
poshwith 1.0.2.20190614 [Approved]
postbox 6.1.18 [Approved] Downloads cached for licensed users
posterazor.portable 1.5.2.20190317 [Approved]
postgis-9.3 2.1.5 [Approved] - Possibly broken
postgresql 10.6.0.20190131 [Approved]
postgresql-9.3 9.3.5.3 [Approved] Downloads cached for licensed users
postgresql10 10.6.0.0 [Approved]
postgresql9 9.6.9.20180721 [Approved]
postgresql93 9.3.5.1 - Possibly broken
postman 7.3.4 [Approved] Downloads cached for licensed users
potplayer 1.7.18958 [Approved] Downloads cached for licensed users
pov-ray 3.7.0.20161121 [Approved] Downloads cached for licensed users
powder-toy 94.1 [Approved]
powderplayer 1.20 [Approved] Downloads cached for licensed users
powerarchiver2016 16.10.24.20181017 [Approved]
PowerBI 2.72.5556.701 [Approved]
PowerBot 3.6
PowerDelivery 2.2.79 [Approved]
PowerDelivery-VSExtension-2010 1.0.2 - Possibly broken
PowerDelivery-VSExtension-2012 1.0.9 [Approved] - Possibly broken
PowerDelivery-VSExtension-2013 1.0.4 - Possibly broken
powerdelivery3 3.0.1 [Approved]
powerdelivery3node 3.0.1 [Approved]
powerdimmer 1.0 [Approved]
powergist 1.0.15 [Approved]
PowerGUI 3.8.0.129 [Approved] - Possibly broken
PowerGUIVSX 1.6.1.0 - Possibly broken
poweriso 7.4 [Approved] Downloads cached for licensed users
powerpanel-personal 1.6.2 [Approved] Downloads cached for licensed users
Powerpoint. Viewer 12.0.6219.1000 - Possibly broken
PowerPointViewer 1.0.1 - Possibly broken
powerquery 2.8.3443.101 - Possibly broken
powerresizer 0.0.1 [Approved] Downloads cached for licensed users
PowerShell 5.1.14409.20180811 [Approved]
powershell-core 6.2.2 [Approved] Downloads cached for licensed users
powershell-packagemanagement 10.0.10586.200 [Approved] Downloads cached for licensed users
powershell-preview 7.0.0.20190717 [Approved] Downloads cached for licensed users
powershell.portable 6.2.2 [Approved] Downloads cached for licensed users
powershell4 4.0.0.20140724 [Approved]
PowerShellExtension. SQL2012 11.0.2100.60 - Possibly broken
PowerShellGAC 1.1.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
PowerShellHere 0.0.3 [Approved]
powershellhere-elevated 1.0.0 [Approved]
powershellplus 11.50.0.42619 [Approved] Downloads cached for licensed users
ppdgr 1.4.11 [Approved] Downloads cached for licensed users
PProvost. DesktopUtils 2013.06.20 - Possibly broken
PProvost. DevTools 2013.06.13
PPSSPP 1.8.0 [Approved] Downloads cached for licensed users
praat 6.1 [Approved]
pragmaticworksworkbench 2018.2.4.504 [Approved] Downloads cached for licensed users
pragmaticworksworkbenchserver 2018.2.4.504 [Approved] Downloads cached for licensed users
PreCode. WLW 5.02 [Approved] - Possibly broken
prefix 3.0.28 [Approved] Downloads cached for licensed users
premake.portable 4.3 [Approved] Downloads cached for licensed users
prepros 4.2.0 - Possibly broken
presonusuniversalcontrol 1.7.2 [Approved] - Possibly broken
prettypaste 1.8.8 [Approved] Downloads cached for licensed users
pretzel 0.7.1 [Approved] Downloads cached for licensed users
pretzel.scriptcs 0.7.0 [Approved] Downloads cached for licensed users
previewconfig 1.2.0.0 [Approved] Downloads cached for licensed users
previewhandlerpack 1.0.0.0 - Possibly broken
previousfilesrecovery 1.00 [Approved] Downloads cached for licensed users
prey 1.9.1 [Approved]
Prig 2.3.2 [Approved] Downloads cached for licensed users
prime95 29.4 [Approved] Downloads cached for licensed users
prime95.portable 29.4.5 [Approved] Downloads cached for licensed users
primecoin 0.1.2 [Approved] Downloads cached for licensed users
primesieve 7.4 [Approved]
Prince 10.0 [Approved] Downloads cached for licensed users
PrintMaestro 4.1
printrun 2015.02.03 [Approved] Downloads cached for licensed users
pritunl-client 1.0.1632.42 [Approved] Downloads cached for licensed users
privazer 3.0.76 [Approved]
privazer.install 3.0.76 [Approved] Downloads cached for licensed users
privazer.portable 3.0.76 [Approved] Downloads cached for licensed users
privoxy 3.0.28 [Approved] Downloads cached for licensed users
procdump 9.00 [Approved] Downloads cached for licensed users
processactivityview 1.16 [Approved] Downloads cached for licensed users
processhacker 2.39 [Approved]
processhacker.install 2.39 [Approved] Downloads cached for licensed users
processhacker.portable 2.39 [Approved] Downloads cached for licensed users
Processing 3.5.3 [Approved] Downloads cached for licensed users
processing2 2.2.1 - Possibly broken
processthreadsview 1.29 [Approved] Downloads cached for licensed users
procexp 16.26 [Approved] Downloads cached for licensed users
procmon 3.52 [Approved] Downloads cached for licensed users
product666 0.0.5 [Approved]
ProduKey 1.92 [Approved] - Possibly broken
produkey.install 1.93 [Approved] Downloads cached for licensed users
produkey.portable 1.93 [Approved] Downloads cached for licensed users
proget 4.8.4 [Approved] Downloads cached for licensed users
program-install-and-uninstall-troubleshooter 1.0 [Approved] Downloads cached for licensed users
programmer-dvorak 1.2.7 [Approved] Downloads cached for licensed users
ProgrammersNotepad 2.4.2 [Approved]
programmersnotepad.install 2.4.2 [Approved] Downloads cached for licensed users
project.2010.sdk 12.0.0.1 - Possibly broken
project64 2.3.2.20190217 [Approved] Downloads cached for licensed users
projectlibre 1.5.9 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
projectlibre.portable 1.9.1 [Approved] Downloads cached for licensed users
ProjectMyScreen 1.0.0.0 - Possibly broken
projecttaskrunner 1.1.8 [Approved] Downloads cached for licensed users
prometheus 2.2.1 [Approved]
prometheus-blackbox-exporter 0.12.0 [Approved]
prometheus-wmi-exporter.install 0.8.1 [Approved]
Prompit 1.0
protectmychoices-chrome 1.2.4 [Approved]
protoc 3.8.0 [Approved] Downloads cached for licensed users
protonmailbridge 1.1.6 [Approved] Downloads cached for licensed users
protonvpn 1.9.2 [Approved] Downloads cached for licensed users
prototyper 5.6.0
ProxySwitcher 3.6.1.0 - Possibly broken
proxytrace 0.1.2.23 [Approved] - Possibly broken
prusaslicer 2.0.0 [Approved]
ps3mediaserver 1.90.1
psake 4.7.3 [Approved]
psc-package 0.5.1 [Approved] Downloads cached for licensed users
pscodehealth 0.2.26 [Approved]
psexec 2.20.20180914 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
psfile 1.03 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
psframework 1.0.33 [Approved]
PsGet 1.0.4.407 [Approved] - Possibly broken
psgetsid 1.45 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
psi 1.3 [Approved]
psi.install 1.3 [Approved]
psi.portable 1.4 [Approved]
psievm 0.2.7.29815 [Approved]
psinfo 1.78 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
psiphon 3.0.0.20150720 [Approved] Downloads cached for licensed users
pskill 1.16 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
pslist 1.40 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
psloggedon 1.35 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
psloglist 2.81 [Approved] Downloads cached for licensed users
psmsi 2.3.0.1 [Approved]
pspad 5.0.1 [Approved] Downloads cached for licensed users
pspad.portable 5.0.1 [Approved] Downloads cached for licensed users
pspasswd 1.24 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
psping 2.10 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
pspp 1.2.0 [Approved]
pspv 1.63 [Approved]
psqlodbc 09.06.0500 [Approved]
PSScriptAnalyzer 1.18.1 [Approved]
psservice 2.25 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
psshutdown 2.52 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
psstringtemplate 0.2.0 [Approved]
pssuspend 1.07 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
pst-merger 1.03.5016 [Approved] Downloads cached for licensed users
pstools 1.2012.04.12 [Approved] Downloads cached for licensed users
pstpassword 1.20 [Approved]
pstpassword.install 1.20 [Approved]
pstpassword.portable 1.20 [Approved]
PsVso 0.6 [Approved]
PsVsts 1.0.0 [Approved]
PSWindowsUpdate 1.5.1
PSWinUpdate 1.5.2 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
pt 2.2.0 [Approved] Downloads cached for licensed users
ptime 1.0.0.20170103 [Approved] Downloads cached for licensed users
ptimer 1.0.2 [Approved] Downloads cached for licensed users
PublicDNS 2.0
PublishedApplications 2.2.0.0 [Approved]
pullrequestreleasenotes 1.2.8 [Approved]
pulse 0.1.4 [Approved] - Possibly broken
pulseaudio 1.1 [Approved]
pulseway 4.7.0 [Approved]
pulseway-dashboard 4.7.0 [Approved]
puntoswitcher 4.4 [Approved] Downloads cached for licensed users
puppet 3.8.7 [Approved] Downloads cached for licensed users
puppet-agent 6.7.2 [Approved] Downloads cached for licensed users
puppet-agent.portable 1.10.4 [Approved] Downloads cached for licensed users
puppet-bolt 1.28.0 [Approved]
puredata 0.49.0 [Approved] Downloads cached for licensed users
pureref.portable 1.9.2 [Approved] Downloads cached for licensed users
purescript 0.12.5 [Approved] Downloads cached for licensed users
puretext 6.2 [Approved] Downloads cached for licensed users
PureTextPlus 3.0.6.2
purple-facebook 0.9.6.166 [Approved]
pushbullet 1.0
pushbullet-chrome 336.0.20170115 [Approved]
pushbulletconsole 1.1
pushcsv 1.4 [Approved] Downloads cached for licensed users
pushmonitoff 1.0.48.5 [Approved] Downloads cached for licensed users
putty 0.72 [Approved]
putty-cac 0.71 [Approved] Downloads cached for licensed users
putty-d2ddw 2013.08.07
putty.install 0.72 [Approved]
putty.portable 0.72 [Approved]
PuttyTray 0.67.029 [Approved] Downloads cached for licensed users
puush 1.0.0 [Approved] Downloads cached for licensed users
Pvc 0.0.2.2
pViewer 1.3.1
pwgen 2.9.0 [Approved]
pwgen.install 2.9.0 [Approved] Downloads cached for licensed users
pwgen.portable 2.9.0 [Approved] Downloads cached for licensed users
pwsh 6.2.2 [Approved]
pxe-boot-tool 1.5 [Approved] Downloads cached for licensed users
Pycharm 2019.2 [Approved] Downloads cached for licensed users
PyCharm-community 2019.2 [Approved] Downloads cached for licensed users
pycharm-edu 2019.2 [Approved] Downloads cached for licensed users
pycharm-professional 2017.2.3.20171003 [Approved]
pydev 7.2.1 [Approved]
pydiosync 1.2.5 [Approved] Downloads cached for licensed users
pyexiftoolgui 0.5 [Approved] Downloads cached for licensed users
pygtk-all-in-one_win32_py2.7 2.24.2.2014021601 - Possibly broken
pyhoca-gui 0.5.0.4001 [Approved]
pypy3 7.1.0 [Approved] Downloads cached for licensed users
pyqt4 4.10.3.20130918
pyqt5 5.5.1 [Approved] Downloads cached for licensed users
pyrevit-cli 0.9.7.0 [Approved]
python 3.7.4 [Approved]
python-wxwidgets 2.8.12.1 [Approved] Downloads cached for licensed users
python-x86_32 3.5.2.20170425 [Approved] - Possibly broken
Python. Cheetah 2.4.4 - Possibly broken
python.pypy 7.1.0 [Approved] Downloads cached for licensed users
python.x86 3.4.1.20140609 [Approved] - Possibly broken
python2 2.7.16 [Approved]
python2-x86_32 2.7.11.20170425 [Approved] - Possibly broken
python3 3.7.4 [Approved]
python3-x86_32 3.5.2.20170425 [Approved] - Possibly broken
pythonnet 2.0.0 [Approved] Downloads cached for licensed users
pytivo-desktop 1.6.16.0020180601 [Approved] Downloads cached for licensed users
pytivo-lucasnz 11.13.2016 [Approved] Downloads cached for licensed users
pytivo-wmcbrine 2018.05.09 [Approved] Downloads cached for licensed users
PyWin32 219.0
pyzo 4.4.2 [Approved] Downloads cached for licensed users
q10.portable 1.2.21 [Approved]
qaac 2.68 [Approved] Downloads cached for licensed users
qalculate 3.3.0 [Approved] Downloads cached for licensed users
qap 9.5.2 [Approved] Downloads cached for licensed users
qbittorrent 4.1.7 [Approved]
qbs 1.13.1 [Approved] Downloads cached for licensed users
qcad 3.23.0 [Approved] Downloads cached for licensed users
qdir 7.73 [Approved]
Qemu 2019.08.13 [Approved] Downloads cached for licensed users
qemu-img 2.3.0 [Approved] Downloads cached for licensed users
QGIS 3.8.1 [Approved] Downloads cached for licensed users
QGIS-LTR 3.4.10 [Approved] Downloads cached for licensed users
qip2012 4.0.9380 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
QLCplus 4.10.4 [Approved]
qmmp 1.3.3 [Approved]
qmplay2 18.12.26 [Approved] Downloads cached for licensed users
qnapi 0.2.3 [Approved]
qnapi.install 0.2.3 [Approved]
qnapi.portable 0.2.3 [Approved]
qownnotes 19.8 [Approved]
qpdf 8.4.2 [Approved]
qpmx 1.6.0 [Approved] Downloads cached for licensed users
qt-creator-x64 3.2.1 - Possibly broken
qt-creator-x86 3.2.1 - Possibly broken
qt-sdk 1.6.0.5 - Possibly broken
qt-sdk-android-x86 5.3.2 - Possibly broken
qt-sdk-windows-x64-mingw_opengl_seh 5.3.2 - Possibly broken
qt-sdk-windows-x64-mingw_opengl_sjlj 5.3.2 - Possibly broken
qt-sdk-windows-x64-mingw_seh 5.3.2 - Possibly broken
qt-sdk-windows-x64-mingw_sjlj 5.3.2 - Possibly broken
qt-sdk-windows-x64-msvc2008 5.3.1.20140815 - Possibly broken
qt-sdk-windows-x64-msvc2008_opengl 5.3.1.20140815 - Possibly broken
qt-sdk-windows-x64-msvc2010 5.3.2 - Possibly broken
qt-sdk-windows-x64-msvc2010_opengl 5.3.2 - Possibly broken
qt-sdk-windows-x64-msvc2012 5.3.2 - Possibly broken
qt-sdk-windows-x64-msvc2012_opengl 5.3.2 - Possibly broken
qt-sdk-windows-x86-mingw_opengl 5.3.2 - Possibly broken
qt-sdk-windows-x86-msvc2010_opengl 5.3.2 - Possibly broken
qt-sdk-windows-x86-msvc2012_opengl 5.3.1 - Possibly broken
qt-sdk-windows-x86-msvc2013 5.3.2 - Possibly broken
qt-sdk-windows-x86-msvc2013_opengl 5.3.2 - Possibly broken
qt-sdk-windowsrt-x86 5.3.2 - Possibly broken
qt-vs-addin5 1.2.3 - Possibly broken
qtbinpatcher-x64 2.1.1 - Possibly broken
qtbinpatcher-x86 2.1.1 - Possibly broken
qtcreator 4.9.2 [Approved] Downloads cached for licensed users
qtox 1.16.3 [Approved]
qtpass 1.2.3 [Approved]
qtranslate 6.7.3 [Approved] Downloads cached for licensed users
QTTabBar 1038.0 [Approved] Downloads cached for licensed users
quamotion 0.1.1385 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
quantumdreams 0.1.20160513 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
QuantumGIS 1.8
quantumshooter 0.1.20160513 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
quassel 0.13.1 [Approved]
queryexplus 2.0.3.2
QueryMultiDb 1.0.119.0 [Approved]
QueueExplorer-Professional 3.3.1.1 [Approved] - Possibly broken
queueexplorer-standard 3.3.1 [Approved] - Possibly broken
quick-javascript-switcher-chrome 1.4.1.20170115 [Approved]
quicklook 3.6.5 [Approved] Downloads cached for licensed users
QuickPar 0.9.1.20181112 [Approved] Downloads cached for licensed users
quicksetdns 1.30 [Approved] Downloads cached for licensed users
quickstart. DefaultInstall 1.0.0 - Possibly broken
quickstart2 0.1.34 [Approved] Downloads cached for licensed users
Quicktime 7.7.9.20161124 [Approved] Downloads cached for licensed users
quickviewer 1.1.6 [Approved] Downloads cached for licensed users
quikpak 0.8.0 [Approved]
quiterss 0.18.12 [Approved]
quodlibet 4.2.1 [Approved]
quodlibet.install 4.2.1 [Approved] Downloads cached for licensed users
quodlibet.portable 4.1.0 [Approved] Downloads cached for licensed users
quollwriter 2.6.14 [Approved]
qutebrowser 1.7.0 [Approved]
qutebrowser.install 1.7.0 [Approved]
qutebrowser.portable 1.7.0 [Approved]
qutim 0.3.2.1 [Approved]
R 3.6.1 [Approved]
R. Latest 1.1 - Possibly broken
R. Project 3.6.1 [Approved]
R. Studio 1.2.1335 [Approved] Downloads cached for licensed users
rabbitmq 3.7.17 [Approved] Downloads cached for licensed users
rack 1.2.2016072901 [Approved]
racket 7.3 [Approved] Downloads cached for licensed users
radare 3.1.0 [Approved] Downloads cached for licensed users
radarr 0.2.0.1358 [Approved]
radiant 5.0.1 [Approved] Downloads cached for licensed users
radmin-server 3.5.2.1 [Approved] Downloads cached for licensed users
radmin-viewer 3.5.2.1 [Approved] Downloads cached for licensed users
radmin-viewer.portable 3.5.2.1 [Approved] Downloads cached for licensed users
radmin-vpn 1.1.3908.1 [Approved]
raidar 6.5 [Approved] Downloads cached for licensed users
raidcall 7.3.6 [Approved] - Possibly broken
raidrive 1.6.4.51801 [Approved]
railroadtycoon 1.0.0.0
railsinstaller 3.1.0 [Approved] Downloads cached for licensed users
rainmeter 4.2.0.3111 [Approved] Downloads cached for licensed users
rakudostar 2019.03.01 [Approved] Downloads cached for licensed users
rambox 0.6.9 [Approved]
rammap 1.52 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
ramme 3.2.5 [Approved] Downloads cached for licensed users
rander 5.0 [Approved] Downloads cached for licensed users
random-number-generator 3.0.0 [Approved] Downloads cached for licensed users
ransomfree 2.4.1.1 [Approved]
rapidcrc-unicode 0.3.16 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
RapidEE 9.2.937 [Approved]
rapidminer 5.3.005 - Possibly broken
RavenDB 4.2.2 [Approved]
RavenDB3 3.5.3 [Approved] Downloads cached for licensed users
ravensburgertiptoimanager 3.0.8 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
rawcap 0.1.5.0 [Approved] Downloads cached for licensed users
rawcopy 1.3.5.20190427 [Approved]
rawtherapee 5.6 [Approved]
rawwrite 0.7 [Approved] Downloads cached for licensed users
razer-synapse-2 2.21.24.1 [Approved] Downloads cached for licensed users
RBatchFiles 7.1.0.7
rbcmd 0.3.0.3 [Approved]
rbtray 4.8 [Approved] Downloads cached for licensed users
rclone 1.48.0 [Approved]
rclone.install 1.39 [Approved] Downloads cached for licensed users
rclone.portable 1.48.0 [Approved] Downloads cached for licensed users
rclonebrowser 1.2 [Approved] Downloads cached for licensed users
rdcman 2.7.1406.20160916 [Approved] Downloads cached for licensed users
rdiff-backup 1.2.8 [Approved]
rdm 2019.1.41.0 [Approved] Downloads cached for licensed users
rdmagent 1.3.3.0 [Approved] Downloads cached for licensed users
rdmfree 2019.1.41.0 [Approved] Downloads cached for licensed users
rdpguard 5.4.9 [Approved] Downloads cached for licensed users
rdpv 1.02 [Approved]
rdpwrapper 1.6.2 [Approved] Downloads cached for licensed users
rdtabs 3.0.12 [Approved] Downloads cached for licensed users
re2c 1.1.1 [Approved]
reactsnippetpack 1.2.14 [Approved] Downloads cached for licensed users
readycloud 1.17.1301.560 [Approved] Downloads cached for licensed users
readyshare-printer-utility 1.36 [Approved] Downloads cached for licensed users
readyshare-vault 1.0.50.500 [Approved] Downloads cached for licensed users
real-netstat 3.1 [Approved] Downloads cached for licensed users
realsense-sdk2 2.20.0 [Approved] Downloads cached for licensed users
realtek-card-reader-driver 10.0.370.188 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
realtek-ethernet-diagnostic-utility 2.0.3.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
realtek-hd-audio-driver 2.82.0020181008 [Approved]
realtemp 3.7.0 [Approved] - Possibly broken
realvnc 5.3.2 [Approved]
realvnc.install 5.3.2 [Approved] Downloads cached for licensed users
realvnc.portable 5.3.2 [Approved] Downloads cached for licensed users
reaper 5.981 [Approved] Downloads cached for licensed users
rebar3 3.9.0 [Approved] Downloads cached for licensed users
Rebus. Snoop 2.0.0 [Approved]
recentfilesview 1.33 [Approved] Downloads cached for licensed users
recime-cli 1.1.6 [Approved] Downloads cached for licensed users
Recuva 1.53.1087 [Approved] Downloads cached for licensed users
recuva.portable 1.52.1086 [Approved] Downloads cached for licensed users
red 0.6.4 [Approved] Downloads cached for licensed users
reddit-wallpaper-changer 1.0.13 [Approved] Downloads cached for licensed users
redeclipse 1.4.20141130 [Approved] - Possibly broken
redfox 52.0.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
redfox2in1 2.39 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
redfoxmail 52.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
redis 2.4.6.1 [Approved] - Possibly broken
redis-64 3.0.503 [Approved]
redis-desktop-manager 0.9.3 [Approved] Downloads cached for licensed users
RedisTray 0.1.0.1
rednotebook 2.8 [Approved] Downloads cached for licensed users
redrogue 1.0.7 [Approved] Downloads cached for licensed users
redshift 1.12 [Approved]
redshift-odbc 1.3.1.1000 [Approved] Downloads cached for licensed users
reflect-free 6.3.1734 [Approved] Downloads cached for licensed users
reflection 4.5.1
reflector 8.3 - Possibly broken
RegAlyzer 1.6.2.161 - Possibly broken
regard3d 1.0.0 [Approved] Downloads cached for licensed users
regcool.portable 1.106 [Approved] Downloads cached for licensed users
regdelnull 1.11 [Approved] Downloads cached for licensed users
regdllview 1.60 [Approved] Downloads cached for licensed users
regeditor 12.0.2172 [Approved]
regexcoach 0.9.2 [Approved] Downloads cached for licensed users
regexpeditor 2.0 [Approved] Downloads cached for licensed users
regexpixie 1.0.0 - Possibly broken
regextester 3.2.0.0 [Approved] Downloads cached for licensed users
regfileexport 1.11 [Approved] Downloads cached for licensed users
regfromapp 1.33 [Approved] Downloads cached for licensed users
registry-backup 3.5.3 [Approved]
registry-compressor 1.1.0 [Approved] Downloads cached for licensed users
registrychangesview 1.20 [Approved] Downloads cached for licensed users
registryexplorer 1.3.0.1 [Approved]
registrymanager 8.02 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
regjump 1.10 [Approved] Downloads cached for licensed users
regripper 2.8 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
RegScanner 2.30 [Approved] - Possibly broken
regscanner.install 2.35 [Approved] Downloads cached for licensed users
regscanner.portable 2.35 [Approved] Downloads cached for licensed users
RegShot 1.9.3 [Approved] Downloads cached for licensed users
regulator 2.0.3 [Approved] Downloads cached for licensed users
rehash 0.2 [Approved] Downloads cached for licensed users
remote-desktop-ip-monitor-and-blocker 1.0.0 [Approved] Downloads cached for licensed users
remote-syslog2 0.20 [Approved]
remotetestkit 7.2.1.1 [Approved] Downloads cached for licensed users
remy 1.0.7006 [Approved]
renamemaster 3.14 [Approved] Downloads cached for licensed users
renamemytvseries2 2.0.5.20190619 [Approved] Downloads cached for licensed users
renamer 7.1 [Approved]
renamer.install 7.1 [Approved] Downloads cached for licensed users
renamer.portable 7.1 [Approved] Downloads cached for licensed users
renderdoc 1.4 [Approved] Downloads cached for licensed users
renesas-usb-3-0-driver 2.1.28.1 [Approved] Downloads cached for licensed users
reportgenerator.portable 4.2.15 [Approved]
reportviewer2008 9.1.30729.4402 [Approved] - Possibly broken
reportviewer2008sp1kb971119 1.0.0
reportviewer2010sp1 10.1.40219.329 [Approved] Downloads cached for licensed users
reportviewer2010sp1kb2549864 10.0.40219.329
reportviewer2012 11.0.3452.0 [Approved] Downloads cached for licensed users
repoz 5.0 [Approved]
reprofiler 2.0 [Approved]
reprofiler.portable 2.0 [Approved]
republicanywhere 2.5.12.0 [Approved] Downloads cached for licensed users
repulicanywhere 1.3.2 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
reqrypt 1.4.1 [Approved] Downloads cached for licensed users
reqrypt.portable 1.4.1 [Approved] Downloads cached for licensed users
rescuetime 2.14.2.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
resedit 1.6.6 [Approved] Downloads cached for licensed users
reshack 5.1.7 [Approved]
reshack.portable 5.1.7 [Approved] Downloads cached for licensed users
reshade 4.3.0 [Approved]
resharper 2019.2 [Approved]
resharper-clt 2019.2 [Approved]
resharper-clt.portable 2019.2 [Approved] Downloads cached for licensed users
resharper-platform 192.0.20190807.123805 [Approved] Downloads cached for licensed users
resharper-ultimate-all 2019.2 [Approved]
ReSharperCpp 2019.2 [Approved]
ReSharperSDK 8.0.1086 [Approved]
ReSharperSDK-7 7.1.96 [Approved]
ReSharperSDK-7.app 7.1.96 [Approved]
ReSharperSDK-7.tool 7.1.96 [Approved]
ReSharperSDK.app 8.0.1086 [Approved]
ReSharperSDK.tool 8.0.1086 [Approved]
residualvm 0.2.1 [Approved]
resilio-sync-business 2.6.3.1340 [Approved] Downloads cached for licensed users
resilio-sync-home 2.6.3.1340 [Approved] Downloads cached for licensed users
ResolveAlias 2.4
resonic 0.9.1.1690 [Approved] - Possibly broken
resonic.install 0.9.1.1690 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
resonic.portable 0.9.1.1690 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
ResophNotes 1.7.0 [Approved] Downloads cached for licensed users
resourcehacker.portable 4.6.32 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
restart-to-uefi 1.0.5 [Approved] Downloads cached for licensed users
restic 0.9.5 [Approved] Downloads cached for licensed users
restler 0.1.0 [Approved]
resxdiff 0.1.0.20130121
resxtranslator 2.8 [Approved]
rethinkdb 2.3.6 [Approved]
retroarch 1.7.7.20190522 [Approved] Downloads cached for licensed users
retroshare 0.6.5 [Approved] Downloads cached for licensed users
Revalee. Service 2.3.1 [Approved] - Possibly broken
reveye-chrome 1.4.4 [Approved]
revo-uninstaller 2.1.0.0 [Approved]
Revo. Uninstaller 2.0.2.020180924 [Approved]
revouninstallerpro 3.1.1.20141201 [Approved]
RForTango 1.1 - Possibly broken
rgbfusiontool 0.9.2.0 [Approved] Downloads cached for licensed users
rhash 1.3.8 [Approved] Downloads cached for licensed users
ricochet 1.1.4 [Approved] Downloads cached for licensed users
riecoin 0.10.2 [Approved] Downloads cached for licensed users
riff 0.3.1 [Approved] Downloads cached for licensed users
right-st 1.9.3 [Approved] Downloads cached for licensed users
ring 2018.04.14 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
riot-web 1.0.8 [Approved] Downloads cached for licensed users
ripgrep 11.0.2 [Approved] Downloads cached for licensed users
ripgrep-all 0.9.2 [Approved] Downloads cached for licensed users
Ripple 2.0.0.108
Rivet 0.8.1 [Approved]
rktools.2003 5.2.121102 [Approved]
rlogin 2.24.4 [Approved] Downloads cached for licensed users
rm-glob 0.0.5 [Approved]
rmprepusb 2.1.722 - Possibly broken
rmstale 1.4.0 [Approved]
robo3t 1.3.1 [Approved]
robo3t.install 1.3.1 [Approved] Downloads cached for licensed users
robo3t.portable 1.3.1 [Approved] Downloads cached for licensed users
robocode 1.9.2.4 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
RoboForm 7.9.10.0
robomirror 2.0.20161009 [Approved]
RoboMongo 0.8.4.20190208 [Approved]
RobotoFonts 4.0.0.1 [Approved]
rockbox 1.4.0 [Approved] Downloads cached for licensed users
rocketchat 2.15.5 [Approved] Downloads cached for licensed users
RocketDock 1.3.5.20180721 [Approved]
rocrail 0.15873 [Approved]
rollbackrx 10.2 - Possibly broken
romp 1.7.1 [Approved]
roo 1.1.5 [Approved]
roomarranger 9.5.5 [Approved]
roomeqwizard 5.18 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
roost-desktop-notifier-for-nest 0.9.8.212 [Approved]
rootbeer 1.0.45 - Possibly broken
rosaimagewriter 2.6.2 [Approved] Downloads cached for licensed users
roundhouse 1.1.0 [Approved]
routerpassview 1.81 [Approved] - Possibly broken
royalserver 1.1.0.10527 [Approved] Downloads cached for licensed users
RoyalTS 4.3.61328.10000 [Approved] Downloads cached for licensed users
royalts-v5 5.00.61707.0 [Approved] Downloads cached for licensed users
rpc 6.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
rpgtkoolvx-rtp 202.0 [Approved] Downloads cached for licensed users
rpgtkoolvxace-rtp 100.0 [Approved] Downloads cached for licensed users
rs-deploy-web 1.3.0 [Approved]
rs-ssms-extension 1.5.0 [Approved]
RSAT 2.1809.0.20190205 [Approved]
RSAT. FeaturePack 1.0.1
rsc 7.0.0 [Approved] Downloads cached for licensed users
rss-builder 2.1.8 [Approved] Downloads cached for licensed users
rssguard 3.5.9 [Approved]
RSSOwl 2.2.1.20160620 [Approved] Downloads cached for licensed users
rstray 1.9.1 [Approved]
rsvg-convert 2.40.20 [Approved]
rsync 5.5.0.20190204 [Approved] Downloads cached for licensed users
rtlsdr-scanner 1.3.2 [Approved] Downloads cached for licensed users
RTMPDump 2.4 [Approved]
rtmpdumphelper 1.22 [Approved] Downloads cached for licensed users
rtools 3.5.0.4 [Approved] Downloads cached for licensed users
ru 1.20 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
rubberduck 1.4.3 [Approved] Downloads cached for licensed users
ruby 2.6.3.1 [Approved]
ruby.devkit 4.5.2.20120101 [Approved] - Possibly broken
ruby.devkit.ruby193 4.5.2
ruby.portable 2.3.0 [Approved] Downloads cached for licensed users
ruby1.9 1.9.3.54500
ruby2.devkit 4.7.2.2013022403 [Approved]
RubyMine 2019.2 [Approved] Downloads cached for licensed users
rufus 3.6 [Approved]
Run00. TeamCityChocolatey 0.0.0.12 - Possibly broken
Run00. TeamCityVersioning 0.0.0.4
runasdate 1.37 [Approved] Downloads cached for licensed users
runassystem 1.1 [Approved] Downloads cached for licensed users
rundeck 3.1.0 [Approved]
rundeck-cli 1.1.7 [Approved]
Runescape 29.11.13
runfromprocess 1.05 [Approved] Downloads cached for licensed users
runinbash 0.1.1 [Approved]
russian-grammatical-dictionary 13.06 [Approved] Downloads cached for licensed users
rust 1.36.0 [Approved] Downloads cached for licensed users
rust-ms 1.36.0 [Approved] Downloads cached for licensed users
rustup.install 1.18.3 [Approved] Downloads cached for licensed users
rutoken-driver-repair-tool 1.3.1.0 [Approved] Downloads cached for licensed users
rutoken-drivers 4.2.5.0 [Approved] Downloads cached for licensed users
rutoken-drivers-removal-tool 4.3.2.0 [Approved] Downloads cached for licensed users
rutoken-egais-drivers 4.3.2.0 [Approved] Downloads cached for licensed users
rutoken-magistra-drivers 1.06.00.0035 [Approved] Downloads cached for licensed users
rutoken-plugin 4.0.1.0 [Approved] Downloads cached for licensed users
rutoken-web-plugin 1.6.2.0 [Approved] Downloads cached for licensed users
rutoken-web-tool 1.4.0.42 [Approved] Downloads cached for licensed users
rutracker-proxy 0.2.3 [Approved] Downloads cached for licensed users
rvtools 3.11.9 [Approved] Downloads cached for licensed users
s2 1.8 [Approved] Downloads cached for licensed users
s3put 3.0.2 [Approved] Downloads cached for licensed users
SABnzbd 2.3.9 [Approved]
sackerel 0.0.3 [Approved] Downloads cached for licensed users
safari 5.1.7.2 [Approved] Downloads cached for licensed users
safaricacheview 1.11 [Approved] Downloads cached for licensed users
safarihistoryview 1.01 [Approved] Downloads cached for licensed users
SafeMonk 1.0.3 - Possibly broken
sagethumbs 2.0.0.23 [Approved] Downloads cached for licensed users
SakuraEditor 2.3.2.0 [Approved]
saltminion 2019.2.0 [Approved]
saml2aws 2.16.0 [Approved]
Sample 2.0.0
samsung-kies 3.2.16044.220161008 [Approved] Downloads cached for licensed users
samsung-magician 5.3.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
samsung-usb-driver 1.5.51.0 [Approved] Downloads cached for licensed users
sandboxie 5.30.0.20190801 [Approved]
sandboxie.install 5.30.0.20190801 [Approved] Downloads cached for licensed users
sandcastle 2019.6.24.0 [Approved]
sanerpersonal 1.1 - Possibly broken
sanetwain 1.37.0.0 [Approved] Downloads cached for licensed users
SapiClient 1.0.4
sapmachine 12.0.1 [Approved] Downloads cached for licensed users
sapmachine11 11.0.3 [Approved] Downloads cached for licensed users
saram.tools 0.2
sardu 3.3.0 [Approved] Downloads cached for licensed users
sass 1.22.9 [Approved]
sastarterkitvs2010 1.0.0.1 - Possibly broken
sastarterkitvs2012 1.0.0.1 - Possibly broken
sauce-connect 4.5.1 [Approved] Downloads cached for licensed users
sauerbraten 2013.02.03.20161112 [Approved] Downloads cached for licensed users
save-to-google-drive-chrome 2.1.1 [Approved]
save-to-pocket-chrome 2.1.17 [Approved]
save-to-tonido-chrome 1.1.0 [Approved]
SaxonHE 9.8.0.11 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
sbis-plugin 3.31.82.3 [Approved] Downloads cached for licensed users
sbt 1.2.8 [Approved]
sbz-switcher 1.9.6 [Approved] Downloads cached for licensed users
sc3plugins 3.9.0 [Approved] Downloads cached for licensed users
scala 2.11.4 [Approved]
scala.install 2.11.4 [Approved]
scala.portable 2.11.4 [Approved]
scalaide 4.0.0.0 [Approved] Downloads cached for licensed users
scaleway-cli 1.19 [Approved] Downloads cached for licensed users
scanner 2.13.0.20151227 [Approved] Downloads cached for licensed users
scansnapmanager 6.5.40 [Approved] Downloads cached for licensed users
scantailor 0.9.11.1 [Approved]
scarm 1.5.1 [Approved] Downloads cached for licensed users
SCCMCliCtr 1.0.3.9 [Approved] Downloads cached for licensed users
sccmtoolkit 5.0.7958.1000 [Approved] Downloads cached for licensed users
scenebuilder8 8.4.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
scenebuilder9 9.0.1 [Approved]
scheduled-shutdown 1.1.0 [Approved]
schemacrawler 15.06.01 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
scicoslab 4.4.2 [Approved]
scidavis 1.25 [Approved]
sciencefair 1.0.6 [Approved] Downloads cached for licensed users
scientificword 6.0.30 [Approved]
SciLab 6.0.2 [Approved] Downloads cached for licensed users
scite 4.1.7 [Approved] Downloads cached for licensed users
scite4autohotkey 3.0.06.20170428 [Approved]
scite4autoit3 19.102.1901.001 [Approved] Downloads cached for licensed users
SciTECO 0.6.4 [Approved] Downloads cached for licensed users
scla 2.0.0 [Approved] Downloads cached for licensed users
scp 4.0.9.88 [Approved]
scramble 2010.09.16 [Approved]
scrcpy 1.9.0 [Approved] Downloads cached for licensed users
Screamer 2018.09.23 [Approved] Downloads cached for licensed users
screen-resolution 1.0.0 [Approved]
screencloud 1.5.0 [Approved]
screenlogic-connect 5.2.738.0 [Approved] Downloads cached for licensed users
screenpixelruler 1.0.0.0 [Approved]
screenpresso 1.7.7.1 [Approved] Downloads cached for licensed users
screenruler 0.3.0 [Approved]
screenshotcaptor 5.0.0.2018120700 [Approved] Downloads cached for licensed users
screentogif 2.18 [Approved] Downloads cached for licensed users
scribus 1.4.8 [Approved]
ScriptCs 0.17.1 [Approved]
scummvm 2.0.0 [Approved] Downloads cached for licensed users
scut 1.1 [Approved]
sd 21.12 [Approved]
sd-card-formatter 5.0.0.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
sdbexplorer 0.6.0.1 [Approved]
sdelete 2.02 [Approved] Downloads cached for licensed users
sdfcli 19.1.2 [Approved] Downloads cached for licensed users
sdformatter 5.0.1 [Approved] Downloads cached for licensed users
sdio 1.5.3.702 [Approved] Downloads cached for licensed users
sdir 1.27 [Approved]
sdrsharp 1.0.0.1707 [Approved] Downloads cached for licensed users
seafile-client 7.0.2 [Approved]
seagate-drive-detect 3.1.1.1 [Approved] Downloads cached for licensed users
seamonkey 2.49.4 [Approved] Downloads cached for licensed users
search-by-image-chrome 1.5.2 [Approved]
searchfilterview 1.00 [Approved] Downloads cached for licensed users
searchmyfiles 2.92 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
SearchQueryTool 2.8.2 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
searchwithmybrowser 1.1.2 [Approved]
seatools 1.4.0.7 [Approved] Downloads cached for licensed users
secondstrategy.baseline.utilities 2013.10.10
secret-maryo-chronicles 1.9.0.20170428 [Approved]
section-9-regular-font 1.0 [Approved]
Secunia. PSI 3.0.0.9016 - Possibly broken
secure-file 1.0.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
securepointsslvpn 2.0.25 [Approved]
secureshell-chrome 0.8.43 [Approved]
securitygateway 5.0.0 [Approved] Downloads cached for licensed users
securityplus 5.5.0 [Approved] Downloads cached for licensed users
sed 4.5 [Approved]
seek-dsc 1.0.10 [Approved]
seek-dsc-appfabric-hosting 1.0.10 [Approved]
seek-dsc-database 1.0.10 [Approved]
seek-dsc-harddisk 1.0.10 [Approved]
seek-dsc-messagequeue 1.0.10 [Approved]
seek-dsc-networking 1.0.10 [Approved]
seek-dsc-nservicebus 1.0.10 [Approved]
seek-dsc-software 1.0.10 [Approved]
seek-dsc-topshelf 1.0.10 [Approved]
seek-dsc-webadministration 1.0.10 [Approved]
seer 0.7.4 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
selenium 3.141.59 [Approved]
selenium-all-drivers 4.0 [Approved]
selenium-chrome-driver 76.0.3809.68 [Approved] Downloads cached for licensed users
selenium-edge-driver 6.17134.20180630 [Approved] Downloads cached for licensed users
selenium-gecko-driver 0.24.0 [Approved] Downloads cached for licensed users
selenium-ie-driver 3.141.59 [Approved] Downloads cached for licensed users
selenium-opera-driver 75.0.3770.100 [Approved] Downloads cached for licensed users
SeleniumGridInABox. Node 1.9.1.6 [Approved]
SeleniumHub 2.43.1.3 [Approved]
SelfSSL7 1.0.1 - Possibly broken
SemanticMerge 0.9.17.0 - Possibly broken
semanticreleasenotes-parser 0.1.0 [Approved] Downloads cached for licensed users
sematadatastore 1.0.42.0 [Approved] Downloads cached for licensed users
sendmessage 1.1.2 [Approved] Downloads cached for licensed users
sendtokindle 1.0.1.246 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
sentinel 0.13.4.0 [Approved] Downloads cached for licensed users
seq 5.1.3093 [Approved] Downloads cached for licensed users
seq-import 0.1.16 [Approved]
seqdownload 1.26 [Approved]
seqdownload.install 1.26 [Approved] Downloads cached for licensed users
seqdownload.portable 1.26 [Approved] Downloads cached for licensed users
serf 0.8.1 [Approved] Downloads cached for licensed users
serialportmonitor 1.1.2 [Approved] Downloads cached for licensed users
serilog-generator 1.0.10 [Approved]
serva 3.2.0 [Approved] Downloads cached for licensed users
serve 0.3.0 [Approved]
serve.portable 0.3.0 [Approved]
server-backup-agent 6.10.1.29 [Approved] Downloads cached for licensed users
server-jre 8.0.192 [Approved] - Possibly broken
server-jre10 10.0.1 [Approved] - Possibly broken
server-jre8 8.0.202 [Approved] - Possibly broken
server-jre9 9.0.4 [Approved] - Possibly broken
service-fabric 5.6.220.9494 [Approved] Downloads cached for licensed users
service-fabric-sdk 2.6.220 [Approved] Downloads cached for licensed users
service-fabric-tools 1.6.50508.2 [Approved] Downloads cached for licensed users
ServiceBusExplorer 4.1.113 [Approved]
ServiceBusMQManager 4.14 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
servicecontrol 4.0.1 [Approved] Downloads cached for licensed users
serviceinsight 1.13.0 [Approved] Downloads cached for licensed users
servicepulse 1.20.4 [Approved] Downloads cached for licensed users
serviio 2.0 [Approved] Downloads cached for licensed users
serviwin 1.70 [Approved] - Possibly broken
serviwin.install 1.71 [Approved] Downloads cached for licensed users
serviwin.portable 1.71 [Approved] Downloads cached for licensed users
setacl 3.0.6.0 [Approved] Downloads cached for licensed users
setacl-studio 1.2.4 [Approved] Downloads cached for licensed users
setaffinity2 1.041.20140616 [Approved] - Possibly broken
setdefaultbrowser 1.3.0.20190427 [Approved]
SetDefaultPrinter 1.0.1 [Approved] Downloads cached for licensed users
setpoint 6.69.126 [Approved] Downloads cached for licensed users
SettingsManager 0.0.1
Setup-Assistant 1.9.0.34979
setuserfta 1.7.1.20190427 [Approved]
sfdx-cli 6.0.16 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
sgt-puzzles 2019.04.15 [Approved]
shadowcopyview 1.05 [Approved] Downloads cached for licensed users
shadowexplorer 0.9.462 [Approved] Downloads cached for licensed users
shadowexplorer.portable 0.9.462 [Approved] Downloads cached for licensed users
shadowsocks 4.1.7.1 [Approved] Downloads cached for licensed users
shadowsocks-qt5 2.9.0.20190623 [Approved] Downloads cached for licensed users
shadowspawn 0.2.2 [Approved]
shairport4w 1.0.8.3 [Approved] - Possibly broken
shaman-dokan-archive 1.0 [Approved] Downloads cached for licensed users
shaman-dokan-warc 1.0.1 [Approved] Downloads cached for licensed users
shamela 3.64 [Approved] Downloads cached for licensed users
shareaza 2.7.9.0 [Approved] Downloads cached for licensed users
sharebylink 0.4.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
shareenum 1.60 [Approved] Downloads cached for licensed users
sharemouse 4.0.46 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
sharepoint.2010.sdk 12.0.0.1 - Possibly broken
sharepoint.2013.sdk 15.4711.1001 [Approved] Downloads cached for licensed users
SharePoint. HiveShortcut. Desktop 1.0.0.0 - Possibly broken
SharePoint. HiveShortcut. Explorer 1.0.0.0 - Possibly broken
SharePointDesigner2010x32 14.0.4730.1010
SharePointDesigner2010x64 14.0.4730.1010
SharePointDesigner2013x32 15.0.4420.1017
SharePointDesigner2013x64 15.0.4420.1017
SharePointLogViewer 2.6.0.0
SharePointManager2007 0.9.9.0206
SharePointManager2010 0.9.11.0206
SharePointManager2013 1.0.12.1106
sharex 12.4.1 [Approved] Downloads cached for licensed users
sharpdevelop 4.4.1 - Possibly broken
sharpkeys 3.5.0.20180307 [Approved] Downloads cached for licensed users
sharpkeys.portable 3.9 [Approved] Downloads cached for licensed users
shazzam 1.3 - Possibly broken
sheepit-client 5.1647.3014 [Approved]
shell-x 1.0.0.0 [Approved] Downloads cached for licensed users
shellbagsexplorer 1.3.0.1 [Approved]
shellbagsview 1.21 [Approved] Downloads cached for licensed users
shellcheck 0.6.0 [Approved] Downloads cached for licensed users
shellmenunew 1.02 [Approved] Downloads cached for licensed users
shellrunas 1.01.0.20160210 [Approved] Downloads cached for licensed users
ShellTools 1.0.0.13 [Approved]
shellz 1.5.0 [Approved] Downloads cached for licensed users
shexview 2.01 [Approved]
shexview.install 2.01 [Approved] Downloads cached for licensed users
shexview.portable 2.01 [Approved] Downloads cached for licensed users
shimext 1.4.1 [Approved] Downloads cached for licensed users
shman 1.10 [Approved] Downloads cached for licensed users
shmnview 1.41 [Approved] Downloads cached for licensed users
shortcut 1.11 [Approved] Downloads cached for licensed users
shortcutexporter 1.2.16 [Approved] Downloads cached for licensed users
Shotcut 19.07.15 [Approved]
shotcut.install 19.07.15 [Approved] Downloads cached for licensed users
shotcut.portable 19.07.15 [Approved] Downloads cached for licensed users
Shotty 2.0.2
ShrewSoftVpn 2.2.2.0 - Possibly broken
shutdownguard 1.0.0.20160912 [Approved] Downloads cached for licensed users
shutup10 1.6.1402 [Approved]
SickBeard 2012.11.04.1 - Possibly broken
sidesync 4.7.5.203 [Approved] Downloads cached for licensed users
Sift 0.9.0 [Approved] Downloads cached for licensed users
sigcheck 2.72 [Approved] Downloads cached for licensed users
Sigil 0.9.16 [Approved] Downloads cached for licensed users
sigmac 0.1.3 [Approved]
signal 1.26.1 [Approved]
signcode.install 1.0.4 [Approved] - Possibly broken
signmaker 0.1.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
sil 1.3 [Approved] Downloads cached for licensed users
silentcmd 1.0.12.2019 [Approved]
Silk 0.2.0 [Approved]
Silverlight 5.1.50907.0 [Approved] Downloads cached for licensed users
Silverlight3SDK 3.0
Silverlight4SDK 4.0.50826.0
Silverlight5DeveloperRuntime 5.1.10411.20121024
Silverlight5SDK 5.0.61118.20121024
SilverlightSDK 4.0.50826.0
sim 1.5.0.202 [Approved]
simnetsa-adobereader-fr 11.0.7 - Possibly broken
simple-software-restriction-policy 2.2.0.0 [Approved]
simple-sticky-notes 4.6 [Approved]
simplednscrypt 0.6.6 [Approved] Downloads cached for licensed users
simplenote 1.7.0 [Approved] Downloads cached for licensed users
simpleprogramdebugger 1.05 [Approved] Downloads cached for licensed users
simpleradiorecorder 1.2.7.1 [Approved] Downloads cached for licensed users
simplesystemtweaker 2.0.0.20141201 [Approved]
simplewall 2.4.6 [Approved]
simplewall.install 2.4.6 [Approved]
simplewall.portable 2.4.6 [Approved]
SimpleWavSplitter-Avalonia 0.3.3 [Approved]
SimpleWavSplitter-Wpf 0.3.3 [Approved]
simply-weather 0.2.2 - Possibly broken
simulide 0.3.10.20190412 [Approved]
simutrans 0.120.0.1 [Approved]
simutrans-pak128 2.5.2 [Approved]
simutrans-pak64 0.120.1.2 [Approved]
sipfw 1.0.3.4 [Approved]
Site24x7-APMInsight-dotnet 1.2.0 [Approved] Downloads cached for licensed users
sitecore-courier 1.2.2 [Approved] Downloads cached for licensed users
sitecoreshipfunctions 1.1.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
siteshoter 1.42 [Approved] Downloads cached for licensed users
siv 5.40 [Approved]
siw 9.3.4.20190707 [Approved] Downloads cached for licensed users
siw.portable 7.8.1.20171111 [Approved]
SizeExplorer 1.0.4 [Approved] Downloads cached for licensed users
sizer 4.0.562 [Approved] Downloads cached for licensed users
skaffold 0.35.0 [Approved]
sketchup 2017.2.2555.20190408 [Approved]
sketchupfr 17.2.2555 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
SketchUpPro.install 2013.1.0.20160526 [Approved] - Possibly broken
sketchupviewer 17.0.18899 [Approved] Downloads cached for licensed users
skifree 1.04.0
skillpipereader 2.1.143.20160112 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
sktimestamp 1.3.5 [Approved] Downloads cached for licensed users
SkyDrive 16.4.20140630
skyfonts 5.9.5.1 [Approved] Downloads cached for licensed users
skylight 1.0.1
skympc 1.6.4.20190511 [Approved]
skype 8.51.0.72 [Approved] Downloads cached for licensed users
skype-chrome 8.5.0.91671 [Approved]
skype-disable-updates-winconfig 0.0.1 [Approved]
skype-utility-project 1.4.0 [Approved] - Possibly broken
skypecontactsview 1.05 [Approved] Downloads cached for licensed users
SkypeForBusiness 11107.33602 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
SkypeForBusinessBasic 11107.33602 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
skypelogview 1.55 [Approved] Downloads cached for licensed users
SkySiteFacilities 3.6.1.0 [Approved] Downloads cached for licensed users
slack 4.0.1 [Approved] Downloads cached for licensed users
sleeponlan 1.1 [Approved] Downloads cached for licensed users
sleuthkit 4.4.0 [Approved] Downloads cached for licensed users
slic3r 1.3.0 [Approved] Downloads cached for licensed users
slic3r-prusa 1.41.2.1 [Approved]
slickrss-chrome 2.993 [Approved]
Slickrun 4.3.0.0 [Approved] Downloads cached for licensed users
slik.svn 1.8.0 [Approved]
sliksvn 1.8.5.20140421 [Approved]
slm 9.3 [Approved] Downloads cached for licensed users
slntools 1.1.3.0 [Approved] Downloads cached for licensed users
slpolicy 1.0.5.0 - Possibly broken
smart-console-utility 3.00.10 [Approved] Downloads cached for licensed users
smart-control-center 1.1.3.4 [Approved] Downloads cached for licensed users
smartftp 9.0.2692.0 [Approved]
SmartGit 18.2.8 [Approved]
smartgit-with-jre 7.1.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
smartmontools 7.0 [Approved] Downloads cached for licensed users
smartpss 2.00.1.20170225 [Approved] Downloads cached for licensed users
smartsystemmenu 1.2.6904.24916 [Approved] Downloads cached for licensed users
smartty 1.1.0.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
smartty3 3.1.0.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
smf-player 1.0.0.0 [Approved] Downloads cached for licensed users
smillaenlarger 0.9.0 [Approved] Downloads cached for licensed users
smimesign 0.0.13 [Approved] Downloads cached for licensed users
sming.core 0.0.4 [Approved] Downloads cached for licensed users
smlnj 110.77 - Possibly broken
smplayer 19.5.0 [Approved]
smplayer2 0.7.3.20170101 [Approved]
sms 13.0.8 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
smsniff 2.27 [Approved] - Possibly broken
smsniff.install 2.29 [Approved] Downloads cached for licensed users
smsniff.portable 2.29 [Approved] Downloads cached for licensed users
smtp4dev 2.0.10 [Approved] Downloads cached for licensed users
smtube 19.6.0 [Approved]
snagit 2019.1.3 [Approved]
snake 2016.08.11 [Approved]
snake-java 1.7.0 [Approved] Downloads cached for licensed users
snaketail 1.9.4 [Approved]
snaketail.install 1.9.4 [Approved] Downloads cached for licensed users
snaketail.portable 1.9.4 [Approved] Downloads cached for licensed users
snapgene-viewer 4.2.11.20190125 [Approved] Downloads cached for licensed users
snaplr 0.1 [Approved] - Possibly broken
snappy-driver-installer 1.0.539.20170422 [Approved] Downloads cached for licensed users
snappy-driver-installer-origin 1.0.558 [Approved]
snarl 0.3.1.0 [Approved]
snes9x 1.53.0.20150220 [Approved]
sniffpass 1.13 [Approved]
sniffpass.install 1.13 [Approved]
sniffpass.portable 1.13 [Approved]
Snipe 1.0.2.0 - Possibly broken
SnippingToolPlusPlus 6.4.5 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
snips 1.1 [Approved] Downloads cached for licensed users
snmpb 0.8 [Approved]
snoop 2.11.0 [Approved]
snort 2.9.13 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
soapui 5.5.0 [Approved] Downloads cached for licensed users
socket-io-tester 1.2.3 [Approved] Downloads cached for licensed users
socketsniff 1.11 [Approved] Downloads cached for licensed users
sodaplayer 1.4.2 [Approved] Downloads cached for licensed users
soft-cleaner 1.2019.4.2 [Approved]
softerraldapbrowser 4.5.19808.0 [Approved] Downloads cached for licensed users
softkey-revealer.portable 2.8.0.20161009 [Approved] Downloads cached for licensed users
softsqueeze 3.9.20161009 [Approved] Downloads cached for licensed users
software-ideas-modeler 11.98 [Approved] Downloads cached for licensed users
software-ideas-viewer 11.98 [Approved] Downloads cached for licensed users
SoftwareCreations.devbox 0.04 - Possibly broken
SoftwareCreations.devset 0.07
softwareinformer 1.5.1321 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
Sogeti. WindowsAzure. Plugins. Endpoint. ACL 1.0.0
solarwinds-advanced-monitoring-agent 10.8.10 [Approved] Downloads cached for licensed users
solarwinds-automation-manager 2.4.0.43 [Approved] Downloads cached for licensed users
solarwinds-backup-manager 19.6.0.19171 [Approved] Downloads cached for licensed users
solarwinds-recovery-console 18.12.0.19042 [Approved] Downloads cached for licensed users
solarwinds-take-control-teamviewer 13.0.6447 [Approved] Downloads cached for licensed users
solarwinds-take-control-viewer 7.0.5.0 [Approved] Downloads cached for licensed users
solarwinds-tftp-server 11.0.4.101 [Approved] Downloads cached for licensed users
solfege 3.22.2.1
Solr 8.2.0 [Approved]
soluto 1.3.1497.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
solvespace 2.3 [Approved]
Sonar-runner 3.2
sonarlint-vs2015 4.12.0.0 [Approved]
sonarlint-vs2017 4.12.0.10191 [Approved]
sonarqube-scanner.portable 3.3.0.1492 [Approved] Downloads cached for licensed users
sonarr 2.0.0.5338 [Approved]
sonarscanner-msbuild-net46 4.6.2.2108 [Approved] Downloads cached for licensed users
sonarscanner-msbuild-netcoreapp2.0 4.6.2.2108 [Approved] Downloads cached for licensed users
songr 2.1.1 [Approved] Downloads cached for licensed users
sonicpi 3.1.0 [Approved] Downloads cached for licensed users
sonos-controller 10.3 [Approved]
sonyvegaspro 13.0.428 [Approved] - Possibly broken
sopcast 3.9.3 - Possibly broken
sortprojectitems 1.0.3 [Approved]
soulseek 2017.2.20 [Approved]
soundnode-app 0.6.5 [Approved] Downloads cached for licensed users
soundvolumeview 1.86 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
source-han-code-jp 2.011 [Approved] Downloads cached for licensed users
source-han-sans-cn 2.000 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
source-han-sans-sc 2.000 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
source-han-serif-cn 1.001 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
source-han-serif-sc 1.001 [Approved] - Possibly broken
SourceCodePro 2.030.0 [Approved] Downloads cached for licensed users
sourceinsight 3.5.0072.20140224 - Possibly broken
SourceLink 1.1.0 [Approved]
sourcemonitor 3.5.6.334 [Approved] Downloads cached for licensed users
SourcePreviewHandler 1.0.15 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
SourceTree 3.1.3 [Approved] Downloads cached for licensed users
sourcetree-disableautoupdate 1.0.0 [Approved] - Possibly broken
sox.portable 14.4.1
SP2013PreReqs 1.0.0.0 - Possibly broken
spacedesk-client 0.9.16 [Approved] Downloads cached for licensed users
spacedesk-server 0.9.18 [Approved]
spaceinvaders 2013.08.01 [Approved]
spacemacs 0.200.13 [Approved]
spaceradar 5.1.0 [Approved] Downloads cached for licensed users
spacesniffer 1.3.0.2 [Approved] Downloads cached for licensed users
Spark 2.8.3.20190106 [Approved] Downloads cached for licensed users
sparkcore-build 0.3 - Possibly broken
sparkleshare 1.5.0.20161115 [Approved] Downloads cached for licensed users
spatial 1.1.9 [Approved]
spawner 0.2.4 [Approved] Downloads cached for licensed users
spcomp 1.9.6281 [Approved] Downloads cached for licensed users
speccy 1.32.740 [Approved] Downloads cached for licensed users
specflow 1.8.1
specialfoldersview 1.26 [Approved] Downloads cached for licensed users
spectator 1.0.0 [Approved]
spectcl 0.1.2
spectrumviewer 2.0.1 [Approved] Downloads cached for licensed users
SpeedCrunch 0.12.20190615 [Approved]
speedcrunch.install 0.12 [Approved]
speedcrunch.portable 0.12 [Approved]
speedfan 4.52.0.20181220 [Approved] Downloads cached for licensed users
speedtest-chrome 1.0.7.20170115 [Approved]
speedyfox 2.0.26 [Approved] Downloads cached for licensed users
speex 1.0.4 [Approved] Downloads cached for licensed users
spek 0.8.2.20161221 [Approved] Downloads cached for licensed users
speq 3.4 [Approved] Downloads cached for licensed users
spf13-vim 3.0.3 [Approved]
SPH 2.1.1 - Possibly broken
spice-agent 0.9.0 [Approved] Downloads cached for licensed users
spiceworks 7.5.00104 [Approved] Downloads cached for licensed users
Spiceworks-Agent-Shell 0.2.23 [Approved] Downloads cached for licensed users
spiceworksnetmon 1.4.00268 [Approved] Downloads cached for licensed users
spideroak 5.1.8.20140925 - Possibly broken
SpiderOakGroups 7.5.0 [Approved] Downloads cached for licensed users
spideroakone 7.5.0 [Approved] Downloads cached for licensed users
splash 2.7.0 [Approved] Downloads cached for licensed users
splint 3.1.2 [Approved]
splint.install 3.1.2 [Approved]
splint.portable 3.1.2 [Approved]
split 1.0 [Approved] Downloads cached for licensed users
splunk 5.0.3
splunk-server 7.1.3 [Approved] Downloads cached for licensed users
splunk-universalforwarder 7.0.1 [Approved] Downloads cached for licensed users
splunkforwarder 6.5.1 [Approved] Downloads cached for licensed users
spotify 1.1.12.449 [Approved]
spotlight-desktop 2.0.1 [Approved]
spring-boot-cli 2.1.7 [Approved]
SpringToolSuite 3.9.6 [Approved] Downloads cached for licensed users
sprut-sms-client 3.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
sprut-universal-sprutconfig 2.04.4000 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
sprut-universal-update 2.72.60 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
SPSF 4.1.3.2705 - Possibly broken
spx 6.8.2 [Approved] Downloads cached for licensed users
spybot 2.4.40.20160327 [Approved] Downloads cached for licensed users
spydetectfree 1.0.0.0020180102 [Approved] Downloads cached for licensed users
spystudio 2.9.2.20161106 [Approved] Downloads cached for licensed users
SpywareBlaster 5.5 [Approved] Downloads cached for licensed users
sql-multi-select 4.3.0.142 [Approved] Downloads cached for licensed users
sql-operations-studio 0.32.8.20180929 [Approved]
sql-server-2016-developer-edition 13.1801.3958.1 [Approved] Downloads cached for licensed users
sql-server-2017 14.0.1000 [Approved]
sql-server-2017-cumulative-update 14.0.3223.3 [Approved] Downloads cached for licensed users
sql-server-express 14.1801.3958.1 [Approved] Downloads cached for licensed users
sql-server-management-studio 15.0.18131.0 [Approved] Downloads cached for licensed users
sql-workbench 124.0.0 [Approved] Downloads cached for licensed users
SQL2008. ClrTypes 10.00.2531.00
SQL2008. CmdLine 10.00.2531.00
SQL2008. NativeClient 10.00.2531.00
SQL2008. Powershell 10.00.2531.00 - Possibly broken
SQL2008. SMO 10.00.2531.01
SQL2008R2. ClrTypes 10.50.1600.1
SQL2008R2. CmdLine 10.50.1600.1
SQL2008R2. NativeClient 10.53.6560.0 [Approved] Downloads cached for licensed users
SQL2008R2. PowerShell 10.50.1600.1
SQL2008R2. SMO 10.50.1600.1
SQL2012. ClrTypes 2011.110.3000.1 [Approved] Downloads cached for licensed users
SQL2012. CmdLine 11.0.2270.0 - Possibly broken
SQL2012. DACFramework 11.1.2861.0 - Possibly broken
SQL2012. LocalDB 11.0.2100.61 - Possibly broken
SQL2012. NativeClient 2011.110.7001.0 [Approved] Downloads cached for licensed users
SQL2012. PowerShell 11.0.2100.61
SQL2012. SMO 11.0.2100.61 [Approved] Downloads cached for licensed users
SQL2012. SQLDom 11.1.2825.1 - Possibly broken
sql2014-dacframework 12.0.4100.1 [Approved] Downloads cached for licensed users
SQL2014-powershell 12.0.2000.8 [Approved] Downloads cached for licensed users
sql2014-sqldom 12.0.4100.1 [Approved]
SQL2014. ClrTypes 12.1.4100.1 [Approved]
SQL2014. SMO 12.0.2000.801 [Approved]
sql2016-clrtypes 13.0.1601.5 [Approved]
sql2016-dacframework 13.0.3485.1 [Approved] Downloads cached for licensed users
sql2016-smo 13.0.1601.5 [Approved] Downloads cached for licensed users
sql2016-sqldom 13.0.1601.5 [Approved] Downloads cached for licensed users
sql2017-dacframework 14.0.3757.2 [Approved] Downloads cached for licensed users
sqlanywhereclient 12.0.1 [Approved] Downloads cached for licensed users
sqlbpa.2008 8.0.0.1 - Possibly broken
sqlbpa.2012 12.0.0.1 - Possibly broken
sqlbulksync 1.1.0 [Approved]
sqldiagmanager 10.5.1.202 - Possibly broken
sqlgrep 0.5 [Approved]
sqlio 1.0
SQLite 3.29.0 [Approved]
sqlite-studio.portable 3.1.1 [Approved] Downloads cached for licensed users
sqlite.analyzer 3.10.1 [Approved] Downloads cached for licensed users
sqlite.shell 3.10.1 [Approved] Downloads cached for licensed users
sqliteadmin 0.8.3.201 [Approved] - Possibly broken
sqlitebrowser 3.11.2 [Approved]
sqlitebrowser.install 3.11.2 [Approved]
sqlitebrowser.portable 3.11.2 [Approved]
SQLiteCredit 1.0
sqliteexpert.install 3.5.33 - Possibly broken
SQLitePSProvider 1.0.0.1
sqljdbc 7.0.0.0 [Approved] Downloads cached for licensed users
SqlKerberosConfigMgr 3.0.0 [Approved] - Possibly broken
sqllocaldb 14.0.1000.169 [Approved] Downloads cached for licensed users
SQLMaintenanceSolution 0.6 - Possibly broken
sqlnexus 6.0.0.8 [Approved] Downloads cached for licensed users
sqlnotebook 0.6.0 [Approved] Downloads cached for licensed users
SQLPSX 2.3.2.1 - Possibly broken
SqlSearch 3.3.0.2405 [Approved]
SQLSentryPlanExplorer 2.0.0.2
sqlserver-cmdlineutils 14.0 [Approved] Downloads cached for licensed users
sqlserver-odbcdriver 13.1.4413.46 [Approved] Downloads cached for licensed users
SqlServer2008R2Express 10.50.4000.0
sqlserver2008r2express-engine 10.50.4000.20170521 [Approved] Downloads cached for licensed users
sqlserver2008r2express-managementstudio 10.50.4000.1 [Approved]
SqlServer2012Express 1.0.1 - Possibly broken
sqlserver2012express-engine 11.0.2100.20170521 [Approved] Downloads cached for licensed users
sqlserver2012express-managementstudio 11.0.2100.60 [Approved] Downloads cached for licensed users
SqlServer2014Express 1.0.1 - Possibly broken
SqlServerDataTools.2012 11.1.31203.1
sqlserverdatatools2012 11.1.50226 [Approved] Downloads cached for licensed users
SqlServerExpress 10.0.0.20130503 [Approved] - Possibly broken
SqlServerLocalDb 11.0.2318.0 [Approved] - Possibly broken
sqlstudio 13.0.16100.1 [Approved] - Possibly broken
SqlToolbelt 2.3.3.2644 [Approved]
sqlyog 13.1.5 [Approved] Downloads cached for licensed users
squashfs 4.3.1 [Approved]
squid 3.5.27 [Approved] Downloads cached for licensed users
squiggle 3.4.4.0020180331 [Approved] Downloads cached for licensed users
srcclr 3.4.3 [Approved] Downloads cached for licensed users
srcdemo2 2012.04.07 [Approved] Downloads cached for licensed users
sre 1.3.1.12 [Approved] Downloads cached for licensed users
SRWareIron 75.0.3900.000 [Approved]
srwareiron.install 75.0.3900.000 [Approved] Downloads cached for licensed users
srwareiron.portable 75.0.3900.000 [Approved] Downloads cached for licensed users
ssdt12 12.0.50512.0 [Approved] - Possibly broken
ssdt15 14.0.61712.20180510 [Approved]
ssdt17 14.0.16194.0 [Approved] Downloads cached for licensed users
ssdtbi.vs2012 11.0.3369.0
sshfs 2.7.17334 [Approved]
ssip 1.3.0.20170918 [Approved] Downloads cached for licensed users
ssip.portable 1.3.0 [Approved] Downloads cached for licensed users
ssis-multiple-hash 1.6.6.4 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
ssis-vs2019 3.0.0.20190622 [Approved] Downloads cached for licensed users
sslverifier 1.3 [Approved]
ssoperations 1.5.4 [Approved]
ssrs 14.0.600.1274 [Approved]
STACK 2.4.1.70545 [Approved] Downloads cached for licensed users
stardock-fences 3.0.9.11 [Approved] Downloads cached for licensed users
start10 1.0.0 [Approved] Downloads cached for licensed users
startbluescreen 1.00 [Approved] Downloads cached for licensed users
startisback 2.1.2 - Possibly broken
startisbackplus 1.6.2 - Possibly broken
startmenu8 1.6.0.20141130 [Approved] - Possibly broken
startmenureviver 2.5.0.18 [Approved]
startuplist.portable 2.02.20190115 [Approved]
StarUML 5.0
staruml2 2.8.1 [Approved] Downloads cached for licensed users
staruml3 3.1.0 [Approved] Downloads cached for licensed users
station 1.45.2 [Approved] Downloads cached for licensed users
statping 0.80.61 [Approved]
stayawake.powershell 2018.01.17 [Approved]
stdump 0.0.1 [Approved]
stduviewer 1.6.294 - Possibly broken
steam 3.0.1.20190215 [Approved] Downloads cached for licensed users
steam-cleaner 2.4 [Approved] Downloads cached for licensed users
steamcmd 3.65.77.95 [Approved] Downloads cached for licensed users
stellar 3.6 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
stellarium 0.19.1.20190623 [Approved] Downloads cached for licensed users
stepmania 5.0.12 [Approved] Downloads cached for licensed users
stexbar 1.10.2 [Approved] Downloads cached for licensed users
Stickies 9.0.5.0 [Approved] Downloads cached for licensed users
stigviewer 2.8 [Approved] Downloads cached for licensed users
stinger 12.1.0.3231 [Approved] Downloads cached for licensed users
stirling-jp 1.31 [Approved] Downloads cached for licensed users
storj 4.1.1 [Approved] Downloads cached for licensed users
storjshare 7.3.4 [Approved] Downloads cached for licensed users
StraceNT 0.8 - Possibly broken
stratos 0.7.1 [Approved]
StrawberryPerl 5.30.0.1 [Approved] Downloads cached for licensed users
streambaby 0.54.0.20190403 [Approved] Downloads cached for licensed users
streamdeck 4.3.0.11246 [Approved]
streaming-video-downloader 7.0.0 [Approved] Downloads cached for licensed users
streamlabs-obs 0.16.3 [Approved] Downloads cached for licensed users
streamlink 1.1.1 [Approved] Downloads cached for licensed users
streamlink-twitch-gui 1.8.1 [Approved] Downloads cached for licensed users
streams 1.60 [Approved] Downloads cached for licensed users
streamwhatyouhear 1.4.16069 [Approved] Downloads cached for licensed users
streamwriter 5.4.2.1 [Approved] Downloads cached for licensed users
stremio 4.4.77 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
Stress.portable 1.0.1 [Approved] Downloads cached for licensed users
stretchly 0.20.1 [Approved]
string-replicator 1.0.0.0 [Approved]
Strings 2.2.0.1
strokesplus 2.8.6.401 [Approved]
strokesplus.install 2.8.6.401 [Approved] Downloads cached for licensed users
strokesplus.portable 2.8.6.401 [Approved] Downloads cached for licensed users
stubby 0.2.6.0 [Approved]
stubby4net 1.0.0.3 [Approved]
studio 2.0.7.1 [Approved] Downloads cached for licensed users
studio3t 2019.4.1 [Approved] Downloads cached for licensed users
stunnel 5.44 [Approved] Downloads cached for licensed users
stunnel-msspi 5.55.0.144 [Approved] Downloads cached for licensed users
stunnel.beta 5.001.0.20131224 - Possibly broken
stylecop 4.7.55.0 [Approved]
stylecop-vsix 5.0.6419.20180518 [Approved]
sublimemerge 0.0.1116 [Approved] Downloads cached for licensed users
sublimetext2 2.0.2.2222 [Approved] Downloads cached for licensed users
SublimeText2.app 2.0.1.22171 [Approved] - Possibly broken
SublimeText2. PackageControl 1.6.3 - Possibly broken
SublimeText2. PowershellAlias 0.1.0
SublimeText3 3.2.1 [Approved] Downloads cached for licensed users
SublimeText3.app 3.0.0.3065 [Approved] - Possibly broken
SublimeText3. PackageControl 2.0.0.20140915 [Approved] - Possibly broken
sublimetext3.portable 3.2.1 [Approved] Downloads cached for licensed users
SublimeText3. PowershellAlias 0.1.0
subtitleedit 3.5.9 [Approved] Downloads cached for licensed users
subtitleedit.portable 3.5.9 [Approved] Downloads cached for licensed users
subtitleworkshop 6.0.131121 [Approved]
subtitleworkshop.install 6.0.131121 [Approved] Downloads cached for licensed users
subtitleworkshop.portable 6.0.131121 [Approved] - Possibly broken
Sudo 1.1.1 [Approved]
sugarsync 1.9.71.1 - Possibly broken
suggestedextensions 1.0.46 [Approved] Downloads cached for licensed users
sumatrapdf 3.1.2 [Approved]
sumatrapdf.commandline 3.1.2 [Approved] Downloads cached for licensed users
sumatrapdf.install 3.1.2 [Approved] Downloads cached for licensed users
Sumerics 2.0.0.0 [Approved] Downloads cached for licensed users
SummerFun 1.0.1
sumo 5.9.5.425 [Approved] Downloads cached for licensed users
sumologic 1.0 - Possibly broken
sundance 4.5.0.2
sundial 0.1.0 [Approved] Downloads cached for licensed users
sunset-screen 1.31 [Approved]
sunset-screen.install 1.31 [Approved] Downloads cached for licensed users
supd2 2.0.0 [Approved] Downloads cached for licensed users
super-mario-bros-java 2017.05.06 [Approved] Downloads cached for licensed users
superantispyware 6.0.1204 [Approved] - Possibly broken
SuperBenchmarker 4.5.1 [Approved]
superburgertime 2013.07.30 [Approved]
SuperCollider 3.9.3.0 [Approved] Downloads cached for licensed users
SuperCopier 4.0.1.005 - Possibly broken
superorca 11.0.0.0 [Approved] Downloads cached for licensed users
superpacman 2014.10.12 [Approved]
superputty 1.4.0.9 [Approved]
superputty.install 1.4.0.9 [Approved] Downloads cached for licensed users
superputty.portable 1.4.0.9 [Approved] Downloads cached for licensed users
supertuxkart 1.0 [Approved] Downloads cached for licensed users
supraball 0.2.10.1 [Approved] - Possibly broken
suricata 2.0.2.20140625
suwatchapp 0.1.0.0 - Possibly broken
svchost-lookup-tool 1.6.0 [Approved] Downloads cached for licensed users
svchost-process-analyzer.portable 1.0.20161106 [Approved] Downloads cached for licensed users
svg-explorer-extension 0.1.1.20170428 [Approved]
svgcleaner 0.6.2 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
svgo-gui 0.0.9
svn 1.8.17 [Approved] Downloads cached for licensed users
sweet-home-3d 6.2 [Approved]
swftools 0.9.0 [Approved] - Possibly broken
SWI-Prolog 8.0.3.1 [Approved] Downloads cached for licensed users
swift-im 4.0.2.20190627 [Approved]
swiftforwindows 2.0 [Approved] Downloads cached for licensed users
swig 4.0.0 [Approved] Downloads cached for licensed users
swish 0.7.3 - Possibly broken
SwissFileKnife 1.9.4.3 [Approved] Downloads cached for licensed users
switcheroo 0.9.2.111 [Approved]
switcheroo.install 0.9.2.111 [Approved] Downloads cached for licensed users
switcheroo.portable 0.9.2.111 [Approved] Downloads cached for licensed users
swtor 1.0.0.200 [Approved]
swyh 1.4.16069.0 [Approved] Downloads cached for licensed users
sylpheed 3.7.0 [Approved] Downloads cached for licensed users
sylpheed.portable 3.7.0 [Approved] Downloads cached for licensed users
SymbolSource. DemoApplication 1.0.0.0
SymbolSource. Integration. NuGet. CommandLine 1.3.4
sync 2.20 [Approved] Downloads cached for licensed users
syncback 7.6.36.0 [Approved] - Possibly broken
syncbackpro 6.5.4.0
syncless 2.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
syncovery 7.87.101 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
synctex 50155.50155 [Approved]
syncthing 1.2.1 [Approved] Downloads cached for licensed users
syncthing-gtk 0.9.2.7 [Approved] Downloads cached for licensed users
synctoday 15.03.27.2152 [Approved]
synctrayzor 1.1.24 [Approved] Downloads cached for licensed users
synergy 1.8.8 [Approved]
synfig 1.2.0 [Approved] Downloads cached for licensed users
synkron 1.6.2.20140909
synology-activebackup-for-business-agent 2.0.4.0621 [Approved] Downloads cached for licensed users
synologychat 1.1.1 [Approved]
synologydrive 1.1.2 [Approved] Downloads cached for licensed users
synth 1.0.3
syrem 3.0.0 [Approved] Downloads cached for licensed users
sysexp 1.75 [Approved] - Possibly broken
sysexp.install 1.76 [Approved] Downloads cached for licensed users
sysexp.portable 1.76 [Approved] Downloads cached for licensed users
sysinternals 2019.6.29 [Approved] Downloads cached for licensed users
sysmon 10.10 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
syspin 0.99.8.1 [Approved] Downloads cached for licensed users
system-monitor 1.2.1 [Approved] - Possibly broken
systemexplorer 7.0.0.20160118 [Approved]
systemninja 3.1.6 [Approved] - Possibly broken
systemninja.install 3.1.6 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
systemninja.portable 3.1.6 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
systraymeter 0.2.0.6 - Possibly broken
t-clock 2.4.4.492 [Approved]
tablacus 19.8.5 [Approved]
tabletextcompare 1.20 [Approved] Downloads cached for licensed users
tabspace 1.1.2 [Approved] Downloads cached for licensed users
tabula 1.2.1 [Approved]
tad 0.9.0 [Approved] Downloads cached for licensed users
TagainiJisho 1.0.1
tageditor 3.2.1 [Approved]
tagflow 0.5.1 [Approved] Downloads cached for licensed users
tagscanner 6.0.35 [Approved]
tagscanner.portable 6.0.35 [Approved] Downloads cached for licensed users
tagspaces 3.1.6 [Approved] Downloads cached for licensed users
tagsrep 1.00 [Approved] Downloads cached for licensed users
taiga 1.3.1 [Approved] Downloads cached for licensed users
tailblazer 0.9.0.536 [Approved] Downloads cached for licensed users
taildotnet 0.1.5 [Approved]
take-command 24.2.50.0 [Approved] Downloads cached for licensed users
tangible-t4-vs2013 2.3.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
tangible-t4-vs2017 2.4.0 [Approved]
tapwindows 9.21.2 [Approved] Downloads cached for licensed users
tartool 1.0.0 [Approved]
taskbar-never-combine 1.0.0 [Approved]
taskbar-winconfig 0.0.3 [Approved]
taskbarhider 1.2 [Approved]
TaskCoach 1.4.2 [Approved] Downloads cached for licensed users
taskfactory 2018.2.4.503 [Approved] Downloads cached for licensed users
taskinfo 10.0.0.3361678 [Approved] Downloads cached for licensed users
taskschedulerview 1.50 [Approved]
tautulli 2.1.14 [Approved] Downloads cached for licensed users
tbb 4.1.3 - Possibly broken
tbox 1.33.0.1 [Approved] - Possibly broken
tcc 24.2.50.0 [Approved] Downloads cached for licensed users
tccle 14.0.0.920161009 [Approved] Downloads cached for licensed users
tcp 0.1 [Approved]
tcp-qse 2.2.6 [Approved]
tcp-uninstaller 1.0.1 [Approved]
tcping 0.39.20180614 [Approved] Downloads cached for licensed users
tcplogview 1.30 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
TCPOptimizer 3.0.8 [Approved]
tcptrace 0.8.1.717 [Approved]
tcptunnel 0.8.0.20180614 [Approved] Downloads cached for licensed users
tcpvcon 3.05 [Approved] Downloads cached for licensed users
TcpView 3.05
tdesktop 0.7.20.20150319 [Approved]
tdict 1.1
teamcity 2019.1.2 [Approved] Downloads cached for licensed users
teamcity-openjdk8 2019.1.2 [Approved]
teamcity-preinstalledjre 2019.1.2 [Approved]
teamcity-vstest-customlogger 9.1.7 [Approved]
TeamCityAddin 2019.2 [Approved]
TeamCityAgent 4.0.0 [Approved]
teamspeak 3.3.0 [Approved] Downloads cached for licensed users
teamspeak-server 3.5.1 [Approved] Downloads cached for licensed users
teamviewer 14.4.2669 [Approved] Downloads cached for licensed users
teamviewer-chrome 13.0.281 [Approved]
teamviewer-qs 14.4.2669.0 [Approved] Downloads cached for licensed users
teamviewer.host 14.4.2669.0 [Approved] Downloads cached for licensed users
teamviewer.portable 14.2.8352 [Approved] Downloads cached for licensed users
teamviewer7 7.0.17271
teamviewer8 8.0.26038
teamviewer9 9.0.38846 [Approved] Downloads cached for licensed users
technicians-toolbox 1.2.0 [Approved] Downloads cached for licensed users
techsmithsnagit 12.3.1 [Approved] - Possibly broken
teeworlds 0.7.3.1 [Approved]
telegraf 1.11.4 [Approved] Downloads cached for licensed users
telegram 1.8.1 [Approved]
telegram.install 1.8.1 [Approved]
telegram.portable 1.8.1 [Approved]
TelerikControlPanel 2014.3.1017 [Approved] - Possibly broken
telnet 0.9.0 [Approved]
TempFileCleaner 4.5.0.0 [Approved]
TempFileCleaner.app 4.5.0.0 [Approved] Downloads cached for licensed users
TempFileCleaner.tool 4.3.0.0
TeraCopy 3.26.3.20190627 [Approved] Downloads cached for licensed users
terapad 1.09 [Approved] - Possibly broken
teraterm 4.103 [Approved] Downloads cached for licensed users
terminal-icons.powershell 0.1.1 [Approved]
terminals 4.0.1 [Approved] Downloads cached for licensed users
Terminals.app 3.3.0.24477 [Approved] - Possibly broken
terminus 1.0.77 [Approved] Downloads cached for licensed users
termite 3.4 [Approved]
terraform 0.12.6 [Approved] Downloads cached for licensed users
terraform-provider-sakuracloud 1.15.2.52 [Approved]
terragrunt 0.18.6 [Approved] Downloads cached for licensed users
test-oracleconnect.powershell 0.1.0 [Approved]
testcentric-experimental-gui 0.7.0 [Approved]
testcentric-gui 1.0.0 [Approved]
testdisk 6.14.20131012
testdisk-photorec 7.1 [Approved]
TestDriven. Net 3.9.2905 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
TestOneGetCS 1.5
tetris-java 1.13.0 [Approved] Downloads cached for licensed users
texmacs 1.99.11 [Approved]
texmaker 5.0.3 [Approved] - Possibly broken
texniccenter 2.02 [Approved]
texstudio 2.12.16 [Approved] Downloads cached for licensed users
text-to-mp3-converter 2.0.0 [Approved] Downloads cached for licensed users
textfilter 0.7.0.009 [Approved] Downloads cached for licensed users
textgenerator 1.2.10 [Approved] Downloads cached for licensed users
textify 1.6.2 [Approved] Downloads cached for licensed users
textpad 8.2.0 [Approved] Downloads cached for licensed users
Texts 1.5.20190524 [Approved] Downloads cached for licensed users
tflash 2.10 [Approved] Downloads cached for licensed users
tflint 0.9.3 [Approved] Downloads cached for licensed users
tfs2010objectmodel 10.0.0.1 [Approved] Downloads cached for licensed users
tfs2012objectmodel 11.0.61030.0 [Approved] - Possibly broken
tfs2012powertools 11.0.60507.0 - Possibly broken
tfs2013objectmodel 12.0.31101.1 [Approved] Downloads cached for licensed users
tfs2013powertools 12.1.00402.0 - Possibly broken
tfs2015powertools 14.0.23206.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
TfsDropDownloader 1.1.0.3
tfsexpress.build 1.0.0.4
tfsexpress.standard 1.0.0.4
TFSPowerTools2012 11.0.60507.1 - Possibly broken
tfsSidekicks 2.4.0 - Possibly broken
tfsSidekicks2010 3.1.1 - Possibly broken
tfsSidekicks2012 4.5 - Possibly broken
tfsSidekicks2013 5.0 - Possibly broken
tfsSidekicks2015 6.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
tftpd32 4.60 [Approved]
TheBat 6.8.8 [Approved]
thebrain 9.000 [Approved]
thebrain.install 9.100 [Approved] Downloads cached for licensed users
thebrain.portable 9.1 [Approved] Downloads cached for licensed users
thegiant.cleanup 1.0.20131022 - Possibly broken
thegiant.fonts 1.0
thegiant.freshinstall 1.2 - Possibly broken
thegiant.tools 1.3 - Possibly broken
themekit 1.0.0 [Approved] Downloads cached for licensed users
therenamer 7.69.20160812 [Approved] Downloads cached for licensed users
thonny 3.1.2 [Approved]
Thoughtworks. Go. Server 14.2.0.0 - Possibly broken
thrift 0.12.0 [Approved]
thumbnail-database-viewer 2.2 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
thumbs-viewer 1.0.2.8 [Approved]
thumbsremover 1.6.1.280 [Approved]
thunderbird 60.8.0 [Approved]
ti_cgt_tms470 18.1.4 [Approved] Downloads cached for licensed users
TidalCycles 0.9.9 [Approved]
tidewaysdaemon 4.0.1 [Approved]
TidyJson.portable 1.0.3 [Approved] Downloads cached for licensed users
tidypirate 1.0.5931.35767 [Approved]
tidystart.powershell 1.8 [Approved] Downloads cached for licensed users
tidytabs 1.3.5 [Approved] - Possibly broken
tidytabs.install 1.3.5 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
tidytabs.portable 1.3.5 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
tigervnc 1.9.0 [Approved] Downloads cached for licensed users
tigervnc-viewer 1.9.0 [Approved] Downloads cached for licensed users
tightvnc 2.8.23 [Approved]
tiled 1.0.2.20170627 [Approved] Downloads cached for licensed users
tim 2.3.2 [Approved] Downloads cached for licensed users
TimberWinR 1.4.17.0 [Approved]
time.txt.install 2.2.1 - Possibly broken
time4popcorn 0.5.0 [Approved] - Possibly broken
timeapp 1.3.2.1 [Approved]
timelineexplorer 0.8.11.1 [Approved]
timerle 1.0.4 [Approved] Downloads cached for licensed users
timestamp 1.1 [Approved] Downloads cached for licensed users
TimRayburn. GitAliases 1.2.0
tinc 1.0.35 [Approved] Downloads cached for licensed users
tineye-chrome 1.1.5 [Approved]
tinn-r 5.3.4.1 [Approved]
tinotefoliocreator 1.10 [Approved] Downloads cached for licensed users
tiny-pxe-server 1.0.0.23 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
tinycad 2.80.06.6260 [Approved] - Possibly broken
tinycc 0.9.26 [Approved] Downloads cached for licensed users
tinymediamanager 3.0.2 [Approved]
tinytask 1.50.20141130 [Approved] - Possibly broken
tinywall 2.1.20190316 [Approved] Downloads cached for licensed users
tipp10 2.1.0.20170126 [Approved]
titik 2.0.1 [Approved] Downloads cached for licensed users
tivo-desktop 2.8.3 [Approved] - Possibly broken
tivo-desktop-patch 2.8.3.20161125 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
tivo-desktop.install 2.8.3 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
tivotogo-plex 2016.12.30 [Approved] Downloads cached for licensed users
tixati 2.62 [Approved]
tixati.portable 2.62 [Approved] Downloads cached for licensed users
tktz 0.6.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
tmpgenc-karma 0.0.7.72 [Approved] Downloads cached for licensed users
toad.mysql 6.3.0.642 [Approved] - Possibly broken
toastify 1.8.3 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
toby-chrome 0.5.2 [Approved]
todobackup 11.5.0.20190815 [Approved]
todoist 2.7.6.20190524 [Approved] Downloads cached for licensed users
todoist-outlook 2.7.8 [Approved] Downloads cached for licensed users
todolist 7.0.12.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
todotxt.net 3.3.0 [Approved]
toff 2.5.8 [Approved] Downloads cached for licensed users
toggl 7.4.475 [Approved]
Tom 2.10.0.001 - Possibly broken
tomahawk 0.8.2.0 [Approved] - Possibly broken
tomatoad 0.6.0 [Approved] Downloads cached for licensed users
tomboy 1.15.7 [Approved] Downloads cached for licensed users
Tomcat 9.0.22 [Approved]
tome-editor 1.0 [Approved] Downloads cached for licensed users
tomighty 0.7.1.300 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
tomtom-mydrive-connect 4.2.5.3770 [Approved] Downloads cached for licensed users
tonelib 3.1.0.001 [Approved]
tonelib-gfx 3.9.7 [Approved] Downloads cached for licensed users
tonelib-zoom 3.8.5 [Approved] Downloads cached for licensed users
tonic 1.0.990 [Approved] Downloads cached for licensed users
tonido-drive 4.68 [Approved] Downloads cached for licensed users
tonido-server 14.90.0.34042 [Approved] Downloads cached for licensed users
tonido-sync 14.90.0.34362 [Approved] Downloads cached for licensed users
toolsroot 0.1.0
topbeat 1.3.1 [Approved] Downloads cached for licensed users
tor 0.3.5.8 [Approved] Downloads cached for licensed users
tor-browser 8.5.4 [Approved] Downloads cached for licensed users
tor-browser-dev 9.0.4 [Approved] Downloads cached for licensed users
torchat 0.9.9.553201803 [Approved] Downloads cached for licensed users
torguard-client 3.96.1 [Approved] Downloads cached for licensed users
torrent-file-editor 0.3.15 [Approved]
torrid 2.8.0 [Approved]
TortoiseGit 2.8.0.0 [Approved]
TortoiseGit.latest 1.7.15
tortoisehg 5.0.2 [Approved] Downloads cached for licensed users
tortoisemerge 1.6.7 - Possibly broken
tortoisesvn 1.12.2.28653 [Approved]
tortoisesvn-ipv6 1.10.1.28295 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
totalcmd 1.0.0 [Approved]
TotalCommander 9.22.1 [Approved]
totalcommanderpowerpack 2.0 [Approved] - Possibly broken
ToTypeScriptD 0.1.5081.42854
touchdesigner 88.62160 [Approved] Downloads cached for licensed users
trackchecker 1.0.13.455 [Approved] Downloads cached for licensed users
trackcomp 1.04 [Approved]
trackcontrol 1.03 [Approved]
trackds 1.03 [Approved]
trackgate 1.03 [Approved]
tracklimit 1.03 [Approved]
trackmeter 1.03 [Approved]
traefik 1.7.14 [Approved]
trafficlight-chrome 1.1.0.9 [Approved]
trafficwatcher 2.0.1 [Approved]
transgui 5.17.0 [Approved] Downloads cached for licensed users
transifex-client 0.13.6 [Approved]
transmission 2.92 [Approved] Downloads cached for licensed users
transmission-qt 2.84.9.20170506 [Approved]
trayit 4.6.5.5 [Approved]
traystatus 4.0 [Approved]
traystatus.install 4.0 [Approved]
traystatus.portable 4.0 [Approved] Downloads cached for licensed users
treesheets 2015.9.13 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
treesizefree 4.3.1.2 [Approved]
treesizefree.portable 4.3.1.2 [Approved] Downloads cached for licensed users
treetrim 1.0.3 - Possibly broken
trello-chrome 0.0.48.20170115 [Approved]
tribler 7.2.2 [Approved] Downloads cached for licensed users
trid 2.24.20190812 [Approved]
trilium-notes 0.33.7 [Approved] Downloads cached for licensed users
trillian 6.1.0.17 [Approved] Downloads cached for licensed users
trim 1.0 [Approved] Downloads cached for licensed users
trivy 0.1.4 [Approved]
trojan-remover 6.9.5.2963 [Approved]
trojita 0.7 [Approved] Downloads cached for licensed users
truecrypt 7.1.20150620 [Approved] Downloads cached for licensed users
truecrypt-langfiles 7.1.1
truepng 0.6.2.5 [Approved] Downloads cached for licensed users
tsedat 7.28.2686.20190627 [Approved] Downloads cached for licensed users
tsprint 2.0.0.8 [Approved]
tsqlflex 0.0.10 [Approved]
tukui 2.4.6.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
tuneuputilities 14.0.1000.881 - Possibly broken
Tunnelier 6.47.0.20160703 [Approved]
tunnelier.install 6.47.0.20160703 [Approved]
tunsafe 1.4 [Approved] Downloads cached for licensed users
turbo 1.0.0.20151117 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
turnedontimesview 1.41 [Approved] Downloads cached for licensed users
turnflash 1.00 [Approved] Downloads cached for licensed users
Tusk 0.23.0 [Approved]
tusk.install 0.23.0 [Approved]
tusk.portable 0.23.0 [Approved]
tux-of-math-command 2.0.2 [Approved]
tux-paint 0.9.23 [Approved]
tux-paint-stamps 2018.09.01 [Approved]
tux-typing 1.8.1 [Approved]
tuxboot 0.8.3 [Approved] Downloads cached for licensed users
tuxguitar 1.5.1 [Approved] Downloads cached for licensed users
tv-browser 4.0.1.20190117 [Approved]
tvrenamer 0.8 [Approved] Downloads cached for licensed users
tweetz-desktop 0.8.23 [Approved] - Possibly broken
twisted 15.4.0 [Approved] Downloads cached for licensed users
twister-webkit 0.9.28.0 [Approved] Downloads cached for licensed users
twitch 7.5.6746.20190803 [Approved] Downloads cached for licensed users
twitch-bandwidth-tester 1.510 [Approved] Downloads cached for licensed users
TypeGen 1.6.3 [Approved]
TypeMockIsolator. NET 7.5.2.0
typescript 3.5.3 [Approved]
typescript-vs2015 3.2.2.0 [Approved] Downloads cached for licensed users
typescript-vs2017 3.3.1 [Approved] Downloads cached for licensed users
typescript-vs2017-vs2019 3.5.2 [Approved] Downloads cached for licensed users
typescript.vs 1.0.1 [Approved] - Possibly broken
typescript.vs2013 1.8.5 [Approved] Downloads cached for licensed users
typora 0.9.73 [Approved] Downloads cached for licensed users
UAdevelopers.utils 1.9 - Possibly broken
uas-plex 2.4.1 [Approved] Downloads cached for licensed users
ubiquiti-unifi-controller 5.10.25 [Approved]
ublockorigin-chrome 1.19.6 [Approved]
uBlockOrigin-firefox 1.20.2 [Approved]
ubooquity 2.1.2 [Approved] Downloads cached for licensed users
ubuntu.font 0.80 - Possibly broken
uc 3.57.1425 [Approved] Downloads cached for licensed users
UCMA4 5.0.20150601.0 [Approved] Downloads cached for licensed users
ucon 1.0.0.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
uefitool 0.26.0 [Approved] Downloads cached for licensed users
ueli 8.0.1 [Approved]
uget 2.2.1 [Approved] Downloads cached for licensed users
ugetdm 2.0.8 [Approved] Downloads cached for licensed users
uhe-ace 1.4 [Approved] - Possibly broken
uhe-bazille 1.1 [Approved]
uhe-colourcopy 1.0.7675 [Approved]
uhe-diva 1.4.3.7422 [Approved]
uhe-hive 2.0.8676 [Approved]
uhe-presswerk 1.1.4.8347 [Approved] - Possibly broken
uhe-repro 1.1.6794 [Approved]
uhe-satin 1.3.1.7414 [Approved]
uhe-twangstrom 1.0.8189 [Approved]
uhe-uhbik 1.3.1 [Approved]
uhe-zebra2 2.8.7422 [Approved]
uhexen2 1.5.9 [Approved]
uiforetw 1.51 [Approved] Downloads cached for licensed users
ukinternationalkeyboard 2.0.0 [Approved] Downloads cached for licensed users
ulsviewer 16.0.3129.1000
ultimate-settings-panel 6.3 [Approved] Downloads cached for licensed users
ultimate-settings-panel-lite 5.1 [Approved] - Possibly broken
ultracopier 1.6.1.4 [Approved] Downloads cached for licensed users
ultradefrag 7.1.3 [Approved]
ultradmm 1.0.5.37035 [Approved] Downloads cached for licensed users
ultraiso 9.7.1.3519 [Approved] Downloads cached for licensed users
ultramon 3.4.1 [Approved] Downloads cached for licensed users
ultrasearch 2.3.2 [Approved]
ultrasearch.portable 2.3.2 [Approved]
ultravnc 1.2240.0.20190403 [Approved] Downloads cached for licensed users
umbrello 2.27.3.20190511 [Approved]
umbrello.install 2.27.3.20190511 [Approved]
umbrello.portable 2.27.3.20190511 [Approved]
umlet 14.3.0 [Approved]
ums 8.2.0 [Approved] Downloads cached for licensed users
unar 1.8.1 [Approved] Downloads cached for licensed users
unchecky 1.2 [Approved] Downloads cached for licensed users
uncrustify 0.69.0 [Approved]
underscore 1.0.0.20180212 [Approved] Downloads cached for licensed users
undo-winrmconfig-during-shutdown 1.2.0 [Approved]
unetbootin 6.6.1 [Approved] Downloads cached for licensed users
unfreez 2.1.20171104 [Approved] Downloads cached for licensed users
ungit 0.10.1 [Approved]
ungoogled-chromium 67.0.3396.87003 [Approved]
unicornify 0.0.0.1
unicreds 1.5.1 [Approved] Downloads cached for licensed users
uniextract 1.6.1 [Approved]
uniextract.install 1.6.1 [Approved] Downloads cached for licensed users
uniextract.portable 1.6.1 [Approved] Downloads cached for licensed users
unifiedremote 3.6.1.2342 [Approved] Downloads cached for licensed users
uniflash 5.0.0 [Approved] - Possibly broken
unifying 2.50.25.20161009 [Approved] Downloads cached for licensed users
unifying-fut 1.0.48 [Approved] Downloads cached for licensed users
UniHex 2.5.6 [Approved] Downloads cached for licensed users
Unikey 4.3.180714 [Approved]
uninstalltool 3.5.8.20190624 [Approved] Downloads cached for licensed users
uninstallview 1.31 [Approved] Downloads cached for licensed users
unison 2.48.4 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
unit-test-boilerplate-generator 2.0.1 [Approved]
unity 2019.2.1 [Approved]
unity-android 2019.2.0 [Approved] Downloads cached for licensed users
unity-appletv 2019.2.0 [Approved] Downloads cached for licensed users
unity-docs 2019.2.0 [Approved] Downloads cached for licensed users
unity-example-project 2018.1.7 [Approved] Downloads cached for licensed users
unity-facebook 2019.2.0 [Approved] Downloads cached for licensed users
unity-hub 2.0.4 [Approved] Downloads cached for licensed users
unity-il2cpp 2019.2.1 [Approved]
unity-ios 2019.2.1 [Approved]
unity-linux 2019.2.1 [Approved]
unity-lumin 2019.2.1 [Approved]
unity-mac 2019.2.1 [Approved]
unity-metro 2019.2.1 [Approved]
unity-samsungtv 2017.2.1.20180517 [Approved] Downloads cached for licensed users
unity-standard-assets 2018.1.7 [Approved] Downloads cached for licensed users
unity-tizen 2017.2.1.20180517 [Approved] Downloads cached for licensed users
unity-vuforia 2019.1.12 [Approved] Downloads cached for licensed users
unity-webgl 2019.2.1 [Approved]
unity-win-il2cpp 2019.2.1 [Approved]
unity4 4.5.5
UnityPackager 1.2.5 [Approved]
unitywebplayer 4.6.0 [Approved] - Possibly broken
universal-adb-drivers 1.0.4 [Approved]
universal-ctags 2019.07.25 [Approved] Downloads cached for licensed users
universal-extractor 1.6.1.20161126 [Approved] Downloads cached for licensed users
universal-firmware-updater 4.0.1.4 [Approved] Downloads cached for licensed users
universal-usb-installer 1.9.8.800 [Approved]
universalpausebutton 1.0.3 [Approved] Downloads cached for licensed users
uniws 1.03 [Approved] Downloads cached for licensed users
UnknownHorizons 2014.1 [Approved] Downloads cached for licensed users
unrar 5.30 [Approved] Downloads cached for licensed users
unreal-commander 3.57.1425 [Approved] Downloads cached for licensed users
unreal-speccy 0.0.57 [Approved]
UnreleasedGitHubHistory. Portable 1.1.1 [Approved]
unxUtils 1.0.0.0 [Approved] Downloads cached for licensed users
unzip 6.0 [Approved] Downloads cached for licensed users
upack 2.2.6 [Approved]
upackx 0.0.0.1 - Possibly broken
uplay 94.0.6332.0 [Approved]
uptodatedownloader.portable 1.2.0.10 [Approved] Downloads cached for licensed users
upx 3.95 [Approved]
urbackup-client 2.3.4 [Approved] Downloads cached for licensed users
urbackup-server 2.3.8 [Approved] Downloads cached for licensed users
urban-terror 4.3.4 [Approved] Downloads cached for licensed users
urlprotocolview 1.15 [Approved] Downloads cached for licensed users
UrlRewrite 2.1.20171010 [Approved] Downloads cached for licensed users
urlstringgrabber 1.11 [Approved] Downloads cached for licensed users
urw 3.52 [Approved] Downloads cached for licensed users
usacloud 0.26.0.75 [Approved]
usagestats 1.4.1.20140104 - Possibly broken
usamimi-hurricane 0.30 [Approved] Downloads cached for licensed users
usbdeview 2.80 [Approved] Downloads cached for licensed users
usbdlm 5.4.5 [Approved] Downloads cached for licensed users
usbimagetool 1.76 [Approved]
usbit 1.76 [Approved]
usblogon 1.8.1.2 [Approved] Downloads cached for licensed users
usblogview 1.25 [Approved] Downloads cached for licensed users
userassistview 1.02 [Approved] Downloads cached for licensed users
userprofilesview 1.10 [Approved] Downloads cached for licensed users
ussf 1.5.0 [Approved]
ut-launcher 0.3.6 - Possibly broken
util-linux-ng-getopt 2.14.1
util-linux-ng-libintl3 2.14.1
uTorrent 3.5.5.45271 [Approved] - Possibly broken
utorrent-easy-client-chrome 2.6.8 [Approved]
utorrent-link-sender-chrome 0.0.9 [Approved]
utorrent-webui 0.388 [Approved] - Possibly broken
utvideo 20.5.1 [Approved] Downloads cached for licensed users
UWS 2.0.21 - Possibly broken
vacuum-im 1.2.5 [Approved]
vagrant 2.2.5 [Approved] Downloads cached for licensed users
vagrant_plugins 1.0.0.1
vagrant-manager 1.0.0.6 [Approved] Downloads cached for licensed users
vagrant-vmware-utility 1.0.7 [Approved] Downloads cached for licensed users
vagrant-winrm-config 0.0.1 [Approved]
vale 0.8.1 [Approved] Downloads cached for licensed users
ValgrindParseTools 1.1.0 [Approved]
varpanel 1.1.0 [Approved]
vault 1.2.0 [Approved] Downloads cached for licensed users
vb5runtime 5.0 [Approved]
VBoxGuestAdditions.install 5.2.12 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
VBoxHeadlessTray 4.3.0.0 - Possibly broken
VBoxVmService 6.0 [Approved] Downloads cached for licensed users
vcbuildtools 2015.4 [Approved] Downloads cached for licensed users
VCExpress2010 0.1.0.20140915
vclip 2.0.0 [Approved] Downloads cached for licensed users
vcpython27 9.0.0.30729 [Approved] Downloads cached for licensed users
vcredist-all 1.0.0 [Approved]
vcredist140 14.22.27821 [Approved]
vcredist2005 8.1.0.20160118 [Approved] Downloads cached for licensed users
vcredist2008 9.0.30729.6163 [Approved] Downloads cached for licensed users
vcredist2010 10.0.40219.2 [Approved]
vcredist2012 11.0.61031 [Approved] Downloads cached for licensed users
vcredist2013 12.0.40660.20180427 [Approved]
vcredist2015 14.0.24215.20170201 [Approved]
vcredist2017 14.16.27033 [Approved]
vcxsrv 1.20.5.1 [Approved]
vdesk 1.2.0 [Approved] Downloads cached for licensed users
vdhcoapp 1.3.0 [Approved] Downloads cached for licensed users
veeam-agent 3.0.2.1170 [Approved] Downloads cached for licensed users
veeam-backup-and-replication-catalog 9.5.4.2753 [Approved]
veeam-backup-and-replication-console 9.5.4.2753 [Approved]
veeam-backup-and-replication-iso 9.5.4.2753 [Approved] Downloads cached for licensed users
veeam-backup-and-replication-management 9.5.4.2753 [Approved]
veeam-backup-and-replication-server 9.5.4.2753 [Approved]
veeam-endpoint-backup-free 1.5 [Approved] Downloads cached for licensed users
veeam-explorer-for-microsoft-active-directory 9.5.4.2753 [Approved]
veeam-explorer-for-microsoft-exchange 9.5.4.2753 [Approved]
veeam-explorer-for-microsoft-sharepoint 9.5.4.2753 [Approved]
veeam-explorer-for-microsoft-sql-server 9.5.4.2753 [Approved]
veeam-explorer-for-oracle 9.5.4.2753 [Approved]
velocity 1.1.14 [Approved] Downloads cached for licensed users
vera 1.3.0 [Approved]
veracity 2.5.0.11065 - Possibly broken
veracrypt 1.23.2 [Approved] Downloads cached for licensed users
VerizonMessagePlus 1.0.0.1 - Possibly broken
vet 1.4 [Approved]
veusz 3.0.1.1 [Approved]
veyon 4.2.3.0 [Approved]
vhdattach 4.21 [Approved]
viber 11.3.0.24 [Approved] Downloads cached for licensed users
vibrancegui 2.0.0.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
vidcoder 4.36 [Approved]
vidcutter 6.0.0.1 [Approved] Downloads cached for licensed users
video-card-stability-test 1.0.0.320161103 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
video-repair-software 3.1.0.1 [Approved] Downloads cached for licensed users
videocacheview 2.98 [Approved] - Possibly broken
videocacheview.install 3.05 [Approved] Downloads cached for licensed users
videocacheview.portable 3.05 [Approved] Downloads cached for licensed users
videostream 0.3.6.20190628 [Approved] Downloads cached for licensed users
vidi-dc 1.0.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
viemu-visualstudio2010 3.0.13 [Approved]
viemu-visualstudio2012 3.0.13 [Approved]
viemu-visualstudio2013 3.2.1 [Approved]
vifm 0.10.0 [Approved] Downloads cached for licensed users
vim 8.0.604 [Approved]
vim-console 8.1 [Approved]
vim-tux 8.1.1836 [Approved]
vim-tux.install 8.1.1836 [Approved]
vim-tux.portable 8.1.1836 [Approved]
vim-x64 7.4.1824 [Approved]
vim-x64.install 7.4.1824 [Approved]
vim-x64.portable 7.4.1824 [Approved]
vim-x86 7.4.1825 [Approved]
vim-x86.install 7.4.1825 [Approved]
vim-x86.portable 7.4.1825 [Approved]
viper4windows 1.0.5.1 [Approved] Downloads cached for licensed users
virt-dimension 0.94 [Approved] Downloads cached for licensed users
virt-viewer 8.0.256 [Approved] Downloads cached for licensed users
virtio-drivers 0.1.171 [Approved] Downloads cached for licensed users
virtualbox 6.0.10 [Approved]
virtualbox-guest-additions-guest.install 6.0.10 [Approved] Downloads cached for licensed users
VirtualBox. ExtensionPack 5.1.10.20161223 [Approved]
VirtualCloneDrive 5.5.0.20160317 [Approved] Downloads cached for licensed users
virtualdub 1.10.4.3549101 [Approved]
virtualdub2 0.0.43702 [Approved]
VirtualEngine-Compression 1.1.0.18 [Approved] Downloads cached for licensed users
virtualmachineconverter 3.1.0.20180613 [Approved] Downloads cached for licensed users
virtuawin 4.4
virustotaluploader 2.2.20150420 [Approved] Downloads cached for licensed users
viscosity 1.7.16 [Approved] Downloads cached for licensed users
visionapp 9.0.5222 [Approved] - Possibly broken
visioviewer 16.0 [Approved]
visioviewer2016 16.0 [Approved] Downloads cached for licensed users
visipics 1.31.1 [Approved] - Possibly broken
visual-studio-2015-tools-for-unity 3.3.0.2 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
visualassist 10.9.2341 [Approved] Downloads cached for licensed users
visualbasic6-kb896559 6.0.2800.1106 [Approved] Downloads cached for licensed users
visualbcd 0.9.3.1020190427 [Approved] Downloads cached for licensed users
VisualBoyAdvance 1.2.0.20140927
VisualCPlusPlusExpress2008 9.0.20140916
visualcpp-build-tools 15.0.26228.20170424 [Approved]
VisualCppBuildTools 14.0.25420.1 [Approved]
VisualCSharpExpress2008 9.0.20140916
visualfsharptools 4.0 [Approved] Downloads cached for licensed users
VisualHG 1.1.6.0 - Possibly broken
visualleakdetector 2.5.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
visualparadigm-ce 15.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
visualsfm 0.5.26 [Approved] Downloads cached for licensed users
visualstudio-codealignment 12.0 [Approved]
visualstudio-github 2.2.0.8 [Approved] - Possibly broken
visualstudio-installer 2.0.1 [Approved]
visualstudio-linepastefix 7.0 [Approved]
visualstudio2012-update 5.0.0.0 [Approved]
VisualStudio2012Premium 11.0.1.20151219 [Approved] Downloads cached for licensed users
VisualStudio2012PremWithWebTools 11.0.1
VisualStudio2012Professional 11.0.1.20151219 [Approved] Downloads cached for licensed users
VisualStudio2012ProfessionalWebTools 11.0.1
VisualStudio2012Ultimate 11.0.1 [Approved]
VisualStudio2012WDX 11.0 [Approved]
visualstudio2013-modelingsdk 1.0.0 - Possibly broken
visualstudio2013-sdk 1.0.0 - Possibly broken
visualstudio2013-update 5.0.0.0 [Approved]
visualstudio2013-update1 1.0.4 - Possibly broken
visualstudio2013-update2 1.0.5 - Possibly broken
visualstudio2013-update3 1.0.2 - Possibly broken
visualstudio2013-webessentials.vsix 1.0.1
VisualStudio2013ExpressWeb 12.0.21005.20150920 [Approved] Downloads cached for licensed users
VisualStudio2013Premium 12.0.40629.20150920 [Approved]
VisualStudio2013Professional 12.0.40629.20150920 [Approved] - Possibly broken
VisualStudio2013TeamExplorer 12.0.21005.1 [Approved]
visualstudio2013testagents 12.0.21005.20160105 [Approved] Downloads cached for licensed users
VisualStudio2013TestProfessional 12.0.21005.20150920 [Approved] Downloads cached for licensed users
VisualStudio2013Ultimate 12.0.40629.20150920 [Approved]
visualstudio2015-nugetpackagemanager 3.5.0 [Approved] Downloads cached for licensed users
visualstudio2015-powershelltools 3.0.539 [Approved] Downloads cached for licensed users
visualstudio2015-update 3.0.0.0 [Approved] - Possibly broken
VisualStudio2015Community 2015.03.03 [Approved]
VisualStudio2015Enterprise 2015.03.03 [Approved]
VisualStudio2015Professional 2015.03.03 [Approved]
visualstudio2015testagents 14.0.25420.1 [Approved] Downloads cached for licensed users
visualstudio2017-installer 2.0.1 [Approved]
visualstudio2017-performancetools 15.0.28010.0 [Approved]
visualstudio2017-powershelltools 3.0.569 [Approved]
visualstudio2017-remotetools 15.0.28010.0 [Approved]
visualstudio2017-workload-azure 1.2.2 [Approved]
visualstudio2017-workload-azurebuildtools 1.0.1 [Approved]
visualstudio2017-workload-data 1.2.2 [Approved]
visualstudio2017-workload-databuildtools 1.0.1 [Approved]
visualstudio2017-workload-datascience 1.0.1 [Approved]
visualstudio2017-workload-manageddesktop 1.2.2 [Approved]
visualstudio2017-workload-manageddesktopbuildtools 1.0.1 [Approved]
visualstudio2017-workload-managedgame 1.2.2 [Approved]
visualstudio2017-workload-nativecrossplat 1.2.2 [Approved]
visualstudio2017-workload-nativedesktop 1.2.2 [Approved]
visualstudio2017-workload-nativegame 1.2.2 [Approved]
visualstudio2017-workload-nativemobile 1.2.2 [Approved]
visualstudio2017-workload-netcorebuildtools 1.1.2 [Approved]
visualstudio2017-workload-netcoretools 1.2.2 [Approved]
visualstudio2017-workload-netcrossplat 1.2.2 [Approved]
visualstudio2017-workload-netweb 1.2.2 [Approved]
visualstudio2017-workload-node 1.2.2 [Approved]
visualstudio2017-workload-nodebuildtools 1.0.1 [Approved]
visualstudio2017-workload-office 1.2.2 [Approved]
visualstudio2017-workload-officebuildtools 1.0.1 [Approved]
visualstudio2017-workload-python 1.0.1 [Approved]
visualstudio2017-workload-universal 1.2.2 [Approved]
visualstudio2017-workload-universalbuildtools 1.0.1 [Approved]
visualstudio2017-workload-vctools 1.3.2 [Approved]
visualstudio2017-workload-visualstudioextension 1.2.2 [Approved]
visualstudio2017-workload-visualstudioextensionbuildtools 1.0.1 [Approved]
visualstudio2017-workload-webbuildtools 1.3.2 [Approved]
visualstudio2017-workload-webcrossplat 1.2.2 [Approved]
visualstudio2017-workload-xamarinbuildtools 1.0.1 [Approved]
visualstudio2017buildtools 15.9.11.0 [Approved]
VisualStudio2017Community 15.9.11.0 [Approved]
visualstudio2017enterprise 15.9.11.0 [Approved]
visualstudio2017feedbackclient 15.9.11.0 [Approved]
VisualStudio2017Professional 15.9.11.0 [Approved]
visualstudio2017sql 15.9.11.0 [Approved]
visualstudio2017teamexplorer 15.9.11.0 [Approved]
visualstudio2017testagent 15.9.11.0 [Approved]
visualstudio2017testcontroller 15.9.11.0 [Approved]
visualstudio2017testprofessional 15.9.11.0 [Approved]
visualstudio2019-workload-azure 1.0.0 [Approved]
visualstudio2019-workload-azurebuildtools 1.0.0 [Approved]
visualstudio2019-workload-data 1.0.0 [Approved]
visualstudio2019-workload-databuildtools 1.0.0 [Approved]
visualstudio2019-workload-datascience 1.0.0 [Approved]
visualstudio2019-workload-manageddesktop 1.0.1 [Approved]
visualstudio2019-workload-manageddesktopbuildtools 1.0.1 [Approved]
visualstudio2019-workload-managedgame 1.0.0 [Approved]
visualstudio2019-workload-nativecrossplat 1.0.0 [Approved]
visualstudio2019-workload-nativedesktop 1.0.0 [Approved]
visualstudio2019-workload-nativegame 1.0.0 [Approved]
visualstudio2019-workload-nativemobile 1.0.0 [Approved]
visualstudio2019-workload-netcorebuildtools 1.0.0 [Approved]
visualstudio2019-workload-netcoretools 1.0.0 [Approved] - Possibly broken
visualstudio2019-workload-netcrossplat 1.0.0 [Approved] - Possibly broken
visualstudio2019-workload-netweb 1.0.0 [Approved] - Possibly broken
visualstudio2019-workload-node 1.0.0 [Approved]
visualstudio2019-workload-nodebuildtools 1.0.0 [Approved]
visualstudio2019-workload-office 1.0.0 [Approved]
visualstudio2019-workload-officebuildtools 1.0.0 [Approved]
visualstudio2019-workload-python 1.0.0 [Approved]
visualstudio2019-workload-universal 1.0.0 [Approved]
visualstudio2019-workload-universalbuildtools 1.0.0 [Approved]
visualstudio2019-workload-vctools 1.0.0 [Approved]
visualstudio2019-workload-visualstudioextension 1.0.0 [Approved]
visualstudio2019-workload-visualstudioextensionbuildtools 1.0.0 [Approved]
visualstudio2019-workload-webbuildtools 1.0.0 [Approved]
visualstudio2019-workload-xamarinbuildtools 1.0.0 [Approved]
visualstudio2019buildtools 16.1.2.0 [Approved]
visualstudio2019community 16.1.2.0 [Approved]
visualstudio2019enterprise 16.1.2.0 [Approved]
visualstudio2019professional 16.1.2.0 [Approved]
visualstudio2019teamexplorer 16.1.2.0 [Approved]
visualstudio2019testagent 16.1.2.0 [Approved]
visualstudio2019testcontroller 16.1.2.0 [Approved]
VisualStudioCode 1.23.1.20180730 [Approved]
visualstudiocode-disableautoupdate 1.0.0.20180620 [Approved]
VisualStudioCommunity2013 12.0.21005.1 [Approved] - Possibly broken
VisualStudioExpress2008 9.0 - Possibly broken
VisualStudioExpress2012TeamExplorer 11.0.0.1
VisualStudioExpress2012TFS 11.0.0.1 - Possibly broken
VisualStudioExpress2012Web 11.0.1 [Approved]
VisualStudioExpress2012Windows8 11.0.0.1
VisualStudioExpress2012WindowsPhone 11.0.0.1
VisualStudioExpress2013Windows 12.0.21005.1
VisualStudioExpress2013WindowsDesktop 12.0.21005.1
VisualStudioTeamFoundationServerExpress2013 12.0.21005.1 [Approved]
VisualStudioTFSExpress2012 1.1.3 - Possibly broken
visualsubst 1.0.6
visualsvn 4.0.9 [Approved]
visualsvnserver 4.0.3 [Approved] Downloads cached for licensed users
visualsyslog 1.6.4.19 [Approved] Downloads cached for licensed users
Vivaldi 2.6.1566.49 [Approved] Downloads cached for licensed users
vjredist 2.0.0 [Approved] Downloads cached for licensed users
vkmessenger 4.4.2.20190701 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
vlc 3.0.7.1 [Approved]
vlc-nightly 4.0.0.20190815 [Approved]
vlc-skin-editor 0.8.5 [Approved]
vlc-skins 2017.01.13 [Approved]
vlc.portable 2.2.1 [Approved] Downloads cached for licensed users
vlmc 0.1.0 - Possibly broken
vmmap 3.25 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
vmware-horizon-client 5.1.0 [Approved] Downloads cached for licensed users
vmware-powercli-psmodule 11.3.0.13990089 [Approved]
vmware-tools 10.3.10.12406962 [Approved] Downloads cached for licensed users
vmware-workstation-player 15.1.0.13591040 [Approved] Downloads cached for licensed users
vmwareplayer 7.0.0.20161122 [Approved]
vmwarevsphereclient 6.0.0.9103891 [Approved] Downloads cached for licensed users
vmwareworkstation 15.1.0.13591040 [Approved] Downloads cached for licensed users
vnc-connect 6.5.0 [Approved] Downloads cached for licensed users
vnc-viewer 6.19.715 [Approved] Downloads cached for licensed users
vnc-viewer-chrome 1.2.2.15132 [Approved]
vnc-viewer-plus 1.2.11 [Approved] Downloads cached for licensed users
vncpassview 1.05 [Approved]
vnote.portable 2.7.2 [Approved] Downloads cached for licensed users
voicebot 3.5.1 [Approved] Downloads cached for licensed users
voicecommands 1.6.12 [Approved] Downloads cached for licensed users
voicemeeter 1.0.6.8 [Approved]
voicemeeter.install 1.0.6.8 [Approved]
voicemeeter.portable 1.0.6.8 [Approved]
volatility 2.6.0.20190425 [Approved]
volley 0.7.6 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
volume2 1.1.5.404 [Approved]
volume2.install 1.1.5.404 [Approved]
volume2.portable 1.1.5.404 [Approved] Downloads cached for licensed users
volumeid 2.10 [Approved] Downloads cached for licensed users
volumouse 2.03 [Approved]
volumouse.install 2.03 [Approved] Downloads cached for licensed users
volumouse.portable 2.03 [Approved] Downloads cached for licensed users
vortex 1.0.0 [Approved]
voxengo-anspec 1.3 [Approved]
voxengo-beeper 2.8 [Approved]
voxengo-bms 2.3 [Approved]
voxengo-boogex 2.3 [Approved] - Possibly broken
voxengo-correlometer 1.1 [Approved]
voxengo-crtiv-chorus 1.1 [Approved]
voxengo-crtiv-reverb-2 2.0 [Approved]
voxengo-crtiv-tape-bus 1.2 [Approved]
voxengo-crunchessor 2.11 [Approved]
voxengo-curveeq 3.7 [Approved]
voxengo-deftcompressor 1.7 [Approved] - Possibly broken
voxengo-drumformer 1.5 [Approved]
voxengo-ebuslim 1.2 [Approved]
voxengo-elephant 4.8 [Approved]
voxengo-glisseq 3.11 [Approved]
voxengo-harmonieq 2.4 [Approved]
voxengo-latency-delay 2.5 [Approved]
voxengo-lf-max-punch 1.8 [Approved]
voxengo-marquis-compressor 2.1 [Approved]
voxengo-marvel-geq 1.6 [Approved]
voxengo-msed 3.1 [Approved] - Possibly broken
voxengo-oldskoolverb 2.5 [Approved]
voxengo-oldskoolverb-plus 1.1 [Approved]
voxengo-ovc-128 1.2 [Approved]
voxengo-overtone-geq 1.13 [Approved]
voxengo-pha-979 2.7 [Approved]
voxengo-polysquasher3 3.1 [Approved]
voxengo-powershaper 1.1 [Approved]
voxengo-primeeq 1.1 [Approved] - Possibly broken
voxengo-shinechilla 1.1 [Approved]
voxengo-soniformer 3.10 [Approved]
voxengo-sound-delay 1.8 [Approved]
voxengo-span 3.4 [Approved]
voxengo-span-plus 1.7 [Approved]
voxengo-spatifier 1.2 [Approved]
voxengo-stereo-touch 2.10 [Approved]
voxengo-tempo-delay 2.2 [Approved]
voxengo-transgainer 1.7 [Approved] - Possibly broken
voxengo-tube-amp 2.6 [Approved]
voxengo-varisaturator 1.12 [Approved]
voxengo-voxformer 2.14 [Approved]
voxengo-warmifier 2.3 [Approved]
vp8-vfw 1.2.0.20170430 [Approved]
vpb-banking 5.6.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
vpnac 4.1.2 [Approved] Downloads cached for licensed users
vpnarea 2.1.0.20190311 [Approved] Downloads cached for licensed users
VS2010. ShellIntegratedRedist 10.0.30319.2 [Approved] - Possibly broken
VS2010SDK 1.0
VS2012.4 11.0.61030.0
vs2012.5 11.0.61219.0 [Approved] Downloads cached for licensed users
VS2012. ShellIntegratedRedist 1.0
VS2012. ShellIsolatedRedist 1.0
vs2012remotetools 1.0.8 [Approved] Downloads cached for licensed users
VS2012SDK 1.0 - Possibly broken
VS2013.1 1.0.0
VS2013.2 1.0.1 - Possibly broken
VS2013.3 1.0.2 - Possibly broken
VS2013.4 1.0.0 [Approved] - Possibly broken
VS2013.5 1.0.0 [Approved] Downloads cached for licensed users
VS2013. PowerTools 30129.00
VS2013. RemoteTools. Update1 1.0
VS2013. ShellIntegratedRedist 1.0
VS2013. ShellIsolatedRedist 1.0.1
VS2013Agents 1.5.9 [Approved] Downloads cached for licensed users
vs2013classicmenucasing 1.0.1
VS2013RemoteTools 12.0.31101.0 [Approved] Downloads cached for licensed users
VS2013SDK 1.0 - Possibly broken
vs2015-roaming-extension-manager 2.0.0.0 [Approved] Downloads cached for licensed users
vs2015.1 1.0.0.0 [Approved]
vs2015.2 2.0.0.0 [Approved]
vs2015.3 3.0.0.0 [Approved]
vs2015remotetools 14.0.25424.0 [Approved] Downloads cached for licensed users
vsautoupdater 1.6.50 [Approved] Downloads cached for licensed users
vscmount 0.5.2.1 [Approved]
vscode 1.37.1 [Approved]
vscode-ansible 0.5.2 [Approved]
vscode-appveyor 1.0.1 [Approved]
vscode-autofilename 1.0.0.20181011 [Approved]
vscode-autohotkey 0.2.2 [Approved]
vscode-azurerm-tools 1.0.0.20180620 [Approved]
vscode-cake 1.0.0.20181011 [Approved]
vscode-codespellchecker 1.0.0.20181011 [Approved]
vscode-codespellchecker-german 1.0.0.20181011 [Approved]
vscode-cortex-debug 0.3.1 [Approved]
vscode-cpptools 0.24.1 [Approved]
vscode-csharp 1.0.0.20181011 [Approved]
vscode-csharpextensions 1.0.0.20180620 [Approved]
vscode-docker 1.0.0.20181011 [Approved]
vscode-editorconfig 1.0.0.20181011 [Approved]
vscode-ember-cli 1.0.0.20180620 [Approved]
vscode-ember-frost 1.0.0.20180620 [Approved]
vscode-eslint 1.0.0.20181011 [Approved]
vscode-gitattributes 0.4.1.20190310 [Approved]
vscode-gitignore 0.6.0 [Approved]
vscode-gitlens 1.0.0.20181011 [Approved]
vscode-icons 1.0.0.20190314 [Approved]
vscode-insiders 1.34 [Approved] Downloads cached for licensed users
vscode-jscslinting 1.0.0.20181011 [Approved]
vscode-jshint 1.0.0.20181011 [Approved]
vscode-markdownlint 1.0.0.20181011 [Approved]
vscode-mssql 1.0.0.20181011 [Approved]
vscode-powershell 1.0.0.20181011 [Approved]
vscode-puppet 0.19.0 [Approved]
vscode-settingssync 1.0.0.0 [Approved]
vscode-tslint 1.0.0.20190730 [Approved]
vscode-vsliveshare 1.0.694 [Approved]
vscode-yaml 0.4.1 [Approved]
vscode.portable 1.37.0 [Approved] Downloads cached for licensed users
vscode.template 1.0 [Approved]
vscodium 1.37.0 [Approved]
VSColorOutput 1.4.3
vscommands2012 1.1
vstor2010 10.0.60828 [Approved] Downloads cached for licensed users
vsts-cli 0.1.4.20190126 [Approved] Downloads cached for licensed users
vsts-sync-migrator 7.5.71 [Approved] Downloads cached for licensed users
vsvim 2.0.1.0 [Approved]
vswhere 2.7.1 [Approved]
vuescan 9.6.45 [Approved] Downloads cached for licensed users
vut 0.0.1 [Approved]
vuzeclient 1.11.1
vvvv 29.2
vvvv-addonpack 36.1 [Approved] Downloads cached for licensed users
vvvv-addonpack.x64 29.2
vvvv-addonpack.x86 29.2
vvvv.x64 29.2.1
vvvv.x86 29.2.1
vyprvpn 2.16.4.9212 [Approved] Downloads cached for licensed users
wakemeonlan 1.84 [Approved] Downloads cached for licensed users
wakeuponstandby 1.7.20.6 [Approved] Downloads cached for licensed users
wallcat 1.0.4 [Approved] Downloads cached for licensed users
wamp-server 2.500 - Possibly broken
warmup 0.6.5.1 [Approved]
warzone2100 3.2.3.020190213 [Approved] Downloads cached for licensed users
wasp 2.5.0.1
wassapp 1.1.1.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
waterfox 56.2.12 [Approved]
wave-engine 2.5.0.20190125 [Approved] Downloads cached for licensed users
wavebox 4.11.1 [Approved] Downloads cached for licensed users
wavesurfer 1.8.84.20160822 [Approved] Downloads cached for licensed users
wavosaur 1.3.0.0 [Approved] Downloads cached for licensed users
wavpack 4.80.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
WAWSDeploy 1.10.0 [Approved]
waybackmachine-chrome 2.12 [Approved]
wazuh-agent 2.1.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
wcat 6.4.0 [Approved]
WcfService 1.0.0
WcfService1 2.0.0
weasel 0.14.3.0 [Approved]
weasel-pageant.portable 1.3 [Approved]
weather-chrome 4.2.97 [Approved]
web-platform-disable-prompt 1.0.0.0 [Approved]
webanalyzer 1.6.65 [Approved] Downloads cached for licensed users
webbrowserpassview 1.85 [Approved] - Possibly broken
webbrowserpassview.install 1.85 [Approved] - Possibly broken
webbrowserpassview.portable 1.85 [Approved] - Possibly broken
webcacheimageinfo 1.30 [Approved] Downloads cached for licensed users
webcamimagesave 1.11 [Approved] Downloads cached for licensed users
webcompiler 1.12.394 [Approved] Downloads cached for licensed users
webcookiessniffer 1.30 [Approved] Downloads cached for licensed users
webdeploy 3.6.20170627 [Approved] Downloads cached for licensed users
webessentials2015 1.0.203 [Approved] Downloads cached for licensed users
webexie 29.7.1.6
webextensionpack 1.6.51 [Approved] Downloads cached for licensed users
WebFlipScreenSaver 0.2.0.1 - Possibly broken
WebMailConverter 3.1
webmatrix 3.0.0.1
webmcam 2.4.1 [Approved] Downloads cached for licensed users
webp 1.0.0 [Approved]
webpacktaskrunner 1.4.51 [Approved] Downloads cached for licensed users
webpi 5.0
webpicmd 7.1.50430.20141001 [Approved]
webpicommandline 7.1.50430.0 [Approved]
WebQueries 1.1
webrecorderplayer 1.7.0 [Approved] Downloads cached for licensed users
websitesniffer 1.50 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
WebStorm 2019.2 [Approved] Downloads cached for licensed users
webswing 2.5.10 [Approved] Downloads cached for licensed users
webtorrent-desktop 0.20.0 [Approved] Downloads cached for licensed users
webvideocap 1.41 [Approved]
webvideocap.install 1.41 [Approved] Downloads cached for licensed users
webvideocap.portable 1.41 [Approved] Downloads cached for licensed users
wechat 2.6.8 [Approved] Downloads cached for licensed users
Weka 3.6.9.002
wesnoth 1.14.7 [Approved] Downloads cached for licensed users
WestwindHtmlHelpBuilder 5.17 [Approved] Downloads cached for licensed users
WestwindWebMonitor 3.50 [Approved] - Possibly broken
WestwindWebSurge 1.14.2 [Approved] Downloads cached for licensed users
wfilecheck 0.4 [Approved] Downloads cached for licensed users
Wget 1.20.3.20190531 [Approved]
whale 0.17.0 [Approved] Downloads cached for licensed users
whatinstartup 1.35 [Approved] Downloads cached for licensed users
whatishang 1.27 [Approved] Downloads cached for licensed users
whats-new 3.0.31 [Approved]
WhatsApp 0.3.4157 [Approved] Downloads cached for licensed users
whatsapptray 1.3.1 [Approved] Downloads cached for licensed users
which 1.11 [Approved]
whitebox.portable 3.4.0.20180608 [Approved] Downloads cached for licensed users
whocrashed 6.6.5 [Approved] Downloads cached for licensed users
whois 1.20 [Approved] Downloads cached for licensed users
whoiscl 1.90 [Approved] Downloads cached for licensed users
whoisconnectedsniffer 1.14 [Approved] Downloads cached for licensed users
whoistd 2.36 [Approved] - Possibly broken
whoistd.install 2.41 [Approved] Downloads cached for licensed users
whoistd.portable 2.41 [Approved] Downloads cached for licensed users
whosip 1.18 [Approved] Downloads cached for licensed users
whysoslow 1.00 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
wickr 5.28.6 [Approved] Downloads cached for licensed users
widelands 18.0 - Possibly broken
wifi-manager 0.2 [Approved]
wifichannelmonitor 1.59 [Approved] Downloads cached for licensed users
wifiguard 2.1.0.20190809 [Approved] Downloads cached for licensed users
wifiinfoview 2.46 [Approved] Downloads cached for licensed users
wildfly 16.0.0 [Approved] Downloads cached for licensed users
wimlib 1.13.1 [Approved] Downloads cached for licensed users
win-caffeinate 1.2 [Approved]
win-no-annoy 1.0.2 [Approved]
win-sshfs 0.0.1.5 - Possibly broken
win-xkill 1.0.0.20141024
win-youtube-dl 1.1.0 [Approved]
win10mct 10.0.18362.1 [Approved] Downloads cached for licensed users
win2003-mklink 1.6.0.20140724 [Approved]
win32-openssh 2016.05.30.20160922 [Approved]
win32diskimager 1.0.0.20181220 [Approved]
win32diskimager.install 1.0.0.20181220 [Approved] Downloads cached for licensed users
win32diskimager.portable 1.0.0.20181220 [Approved] Downloads cached for licensed users
win9xpv 1.1 [Approved] Downloads cached for licensed users
winaero-tweaker 0.15.1.0 [Approved] Downloads cached for licensed users
winamp 5.666 [Approved]
winapioverride 6.6.6 [Approved] Downloads cached for licensed users
winaudit 3.0.11.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
winauth 3.5.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
winbareos 15.2.2 [Approved]
winbareos.install 15.2.2 [Approved] Downloads cached for licensed users
WinBOLT 3.2 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
winbox 3.19 [Approved] Downloads cached for licensed users
winbtrfs 1.3.0 [Approved]
wincdemu 4.1.0.20171221 [Approved]
wincheat 1.7.4680.2 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
wincompose 0.9.0 [Approved]
wincompose.install 0.9.0 [Approved] Downloads cached for licensed users
wincompose.portable 0.9.0 [Approved] Downloads cached for licensed users
wincontig 1.35.03 [Approved]
wincrashreport 1.25 [Approved] Downloads cached for licensed users
wincvt 0.4.1 [Approved]
WinCy 1.0.0 - Possibly broken
WinCyApk 0.0.2 - Possibly broken
windbg 10.0.10586.15 [Approved] Downloads cached for licensed users
windirstat 1.1.2.20161210 [Approved]
windjview 2.1 [Approved] Downloads cached for licensed users
windowblinds 8.12.0 [Approved] Downloads cached for licensed users
windowclippings 3.1.131 - Possibly broken
windowdetective 3.2.1 [Approved] Downloads cached for licensed users
windows-10-update-assistant 1.4.9200.22808 [Approved] Downloads cached for licensed users
windows-adk 10.0.18362.1 [Approved] Downloads cached for licensed users
windows-adk-all 10.0.18362.1 [Approved] Downloads cached for licensed users
windows-adk-deploy 10.0.18362.1 [Approved] Downloads cached for licensed users
windows-adk-winpe 10.0.18362.1 [Approved] Downloads cached for licensed users
windows-admin-center 1.2.5635.0 [Approved]
windows-defender-browser-protection-chrome 1.62 [Approved]
windows-iso-downloader 8.16 [Approved] Downloads cached for licensed users
windows-kill 1.1.4 [Approved]
windows-performance-toolkit 8.1 [Approved] Downloads cached for licensed users
windows-repair-toolbox 3.0.0.4 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
windows-sandbox 0.0.1 [Approved]
windows-sdk-10 10.1.10586.15 [Approved] - Possibly broken
windows-sdk-10-version-1803-all 10.0.17134.12 [Approved] Downloads cached for licensed users
windows-sdk-10-version-1803-windbg 10.0.17134.12 [Approved] Downloads cached for licensed users
windows-sdk-10-version-1809-all 10.0.17763.132 [Approved] Downloads cached for licensed users
windows-sdk-10-version-1809-windbg 10.0.17763.132 [Approved] Downloads cached for licensed users
windows-sdk-10-version-1903-all 10.0.18362.0 [Approved] Downloads cached for licensed users
windows-sdk-10-version-1903-windbg 10.0.18362.0 [Approved] Downloads cached for licensed users
windows-sdk-10.0 10.0.26624 [Approved] Downloads cached for licensed users
windows-sdk-10.1 10.1.18362.1 [Approved] Downloads cached for licensed users
windows-sdk-6.0 6.1.6000.16384 [Approved]
windows-sdk-7.1 7.1.7600.30514 [Approved]
windows-sdk-8.0 8.59.29750.0 [Approved]
windows-sdk-8.1 8.100.26654.0 [Approved]
windows-tweaker 5.3.1 [Approved]
windows-tweaker.install 5.3.1 [Approved] Downloads cached for licensed users
windows-tweaker.portable 5.3.1 [Approved] Downloads cached for licensed users
windows10-media-creation-tool 10.0.18362.1 [Approved]
WindowsADK 2.0 [Approved]
WindowsADK. All 2.0 [Approved]
WindowsADK. WinPE 2.0 [Approved]
WindowsAzureLibrariesForNet 2.2.20140119 [Approved]
WindowsAzureLibsForNet 2.9 [Approved]
WindowsAzurePowershell 1.6.0.20180408 [Approved]
WindowsAzurePowershell_0871 0.8.7.1001 [Approved]
windowsdriverkit10 10.0.17763 [Approved] Downloads cached for licensed users
windowserrorlookuptool 3.0.7 [Approved] Downloads cached for licensed users
windowsessentials 16.4.3508.0209 - Possibly broken
windowsfirewallcontrol 6.0.2.0 [Approved]
WindowsLiveInstaller 2012.0.0.20151215 [Approved]
WindowsLiveMail 2011.0.0 - Possibly broken
WindowsLiveMesh 2011.0.0 [Approved] - Possibly broken
WindowsLiveWriter 2012.0.0.20160129 [Approved] - Possibly broken
WindowsPhone8SDK 8.0.0.20140227
windowsphonedevelopertools 1.0 [Approved] - Possibly broken
windowsrepair 4.5.3 [Approved]
windowsrepair.install 4.5.3 [Approved] Downloads cached for licensed users
windowsrepair.portable 4.5.3 [Approved] Downloads cached for licensed users
windowsspyblocker 4.15.0 [Approved]
WindowsSystemControlCenter 4.0.0.6 [Approved] Downloads cached for licensed users
windowstelnet 1.0.0
WindowsUpdate. DisableAutoRestart 0.0.1
windowsxappremover 1.02 [Approved] Downloads cached for licensed users
windscribe 1.83.20 [Approved] Downloads cached for licensed users
windv 1.2.3 [Approved] Downloads cached for licensed users
winedt 10.3 [Approved] Downloads cached for licensed users
winevdm 0.7.0 [Approved]
winexp 1.30 [Approved] Downloads cached for licensed users
winff 1.5.5 [Approved]
winfile 10.0.1901.1 [Approved]
winflector 3.9.6.5 [Approved] Downloads cached for licensed users
winflector-client 3.9.6.2 [Approved]
winflexbison 2.4.9.20170215 [Approved] Downloads cached for licensed users
winflexbison3 2.5.18.20190508 [Approved] Downloads cached for licensed users
winfontsview 1.10 [Approved] Downloads cached for licensed users
winfsp 1.4.19049 [Approved]
wingide 7.1.0 [Approved] Downloads cached for licensed users
wingide101 7.1.0 [Approved] Downloads cached for licensed users
wingidepersonal 7.1.0 [Approved] Downloads cached for licensed users
winginx 0.6.2 [Approved] Downloads cached for licensed users
wingrep 2.3 - Possibly broken
wingrub 0.02.6 [Approved] Downloads cached for licensed users
wings3d 2.2.4 [Approved]
winhotkey 0.70.0.1 [Approved] Downloads cached for licensed users
WinHttpCertCfg 1.0.0.0
winhue 3.0.3028.0 [Approved] Downloads cached for licensed users
WinImage 9.0 [Approved]
wink 2.0.1060.20120921 - Possibly broken
winlister 1.22 [Approved] Downloads cached for licensed users
winlldpservice 17.10.20.2236 [Approved] Downloads cached for licensed users
winlockless 0.3.20141129 [Approved] - Possibly broken
winlog32 7.3.32 [Approved]
winlogbeat 7.3.0 [Approved] Downloads cached for licensed users
winlogonview 1.32 [Approved] Downloads cached for licensed users
winmerge 2.16.2 [Approved] Downloads cached for licensed users
winmerge-7z 0028.465.920 [Approved]
winmerge-jp 2.14.0.77 [Approved] - Possibly broken
winmerge2011.portable 0.2011.007.44401 [Approved] Downloads cached for licensed users
winmtr-redux 1.00 [Approved] Downloads cached for licensed users
winmute 1.4.3.20160811 [Approved]
winobj 2.22 [Approved] Downloads cached for licensed users
winobjc-tools 0.2.180220 [Approved]
winpatrol 35.5.2017.800 [Approved] - Possibly broken
WinPcap 4.1.3.20161116 [Approved] Downloads cached for licensed users
winprefetchview 1.35 [Approved] Downloads cached for licensed users
winquicklook 1.1.31 [Approved] Downloads cached for licensed users
winrar 5.71 [Approved] Downloads cached for licensed users
winscan2pdf 4.93 [Approved]
winscp 5.15.2 [Approved]
winscp.install 5.15.3 [Approved]
winscp.portable 5.15.3 [Approved]
WinScreenfetch 0.5.1 [Approved]
winsockservicesview 1.00 [Approved] Downloads cached for licensed users
winspector 1.0.37 [Approved] Downloads cached for licensed users
winspy 1.7 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
winsshd 6.47.0.20160526 [Approved]
winsshd.install 6.47.0.20160526 [Approved]
winsshterm 2.7.0 [Approved]
winsys 2018.12.16.0 [Approved] Downloads cached for licensed users
wintail 2002.7 [Approved] Downloads cached for licensed users
WinThumbsPreloader 1.0.1 [Approved] Downloads cached for licensed users
WinVDIG 1.0.5
winvice 3.1 [Approved] Downloads cached for licensed users
winxcorners 1.1.0.320190708 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
winyl-player 3.3.1 [Approved] Downloads cached for licensed users
wire 3.9.2928 [Approved] Downloads cached for licensed users
wireedit 0.11.430 [Approved] - Possibly broken
wireframesketcher 6.1.0 [Approved] Downloads cached for licensed users
wirelessconnectioninfo 1.12 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
wirelesskeyview 1.72 [Approved] - Possibly broken
wirelessnetconsole 1.00 [Approved] Downloads cached for licensed users
wirelessnetview 1.75.0.20181224 [Approved]
wirelessnetview.install 1.75.0.20181224 [Approved] Downloads cached for licensed users
wirelessnetview.portable 1.75.0.20181224 [Approved] Downloads cached for licensed users
wiremockui 1.0.2 [Approved] Downloads cached for licensed users
wireshark 3.0.3 [Approved]
wisemo 3.51 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
wit 3.01.7464 [Approved] Downloads cached for licensed users
Wix35 3.5.2519.20130612 [Approved] - Possibly broken
wixedit 0.7.5 - Possibly broken
wixtoolset 3.11.1 [Approved]
wizemo 3.51 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
wizmouse 1.7.0.3 [Approved]
wiztools-rest-client-ui 3.7.1 [Approved] Downloads cached for licensed users
wiztree 3.29 [Approved]
wkhtmltopdf 0.12.5 [Approved]
wmicc 1.0.0 [Approved] Downloads cached for licensed users
wmiexplorer 2.0.0.0 [Approved]
wmisecurity 1.0.0.121620131 - Possibly broken
wms 11.0.3 [Approved] Downloads cached for licensed users
wnetwatcher 2.20 [Approved]
wnetwatcher.install 2.20 [Approved] Downloads cached for licensed users
wnetwatcher.portable 2.20 [Approved] Downloads cached for licensed users
Wolfpack 3.0.17
wop 1.6 [Approved] Downloads cached for licensed users
Word. Viewer 12.0.6219.1000 - Possibly broken
wordcontentcontroltoolkit 1.3 - Possibly broken
wordpress-com-for-desktop 4.2.0 [Approved] Downloads cached for licensed users
WordViewer 1.0.1 - Possibly broken
wordweb-free 8.23 [Approved]
workcad 2.0.0.35 - Possibly broken
workflowy 1.1.4 [Approved] Downloads cached for licensed users
workrave 1.10.1.6 [Approved] Downloads cached for licensed users
worldwide-telescope 5.5.0.3 [Approved]
wormies-au-helpers 0.3.2 [Approved]
wot 1.12.2014 - Possibly broken
wot-chrome 3.2.1 [Approved]
wot-firefox 20170206.0 [Approved] - Possibly broken
wow-stat 3.0.5 [Approved] Downloads cached for licensed users
wowcrypt 0.0.4 [Approved] Downloads cached for licensed users
wox 1.3.524.20180714 [Approved] Downloads cached for licensed users
wpd 1.3.1203 [Approved] Downloads cached for licensed users
wpfinspector 0.9.9 - Possibly broken
wps-office-free 11.2.0.8893 [Approved] Downloads cached for licensed users
wput 0.0.6
writage 1.12 [Approved] Downloads cached for licensed users
wsjtx 2.0.1 [Approved] Downloads cached for licensed users
wsl 1.0.1 [Approved]
wsl-alpine 3.9 [Approved]
wsl-archlinux 1.0.3.0 [Approved]
wsl-debiangnulinux 9.0.0.020180923 [Approved] Downloads cached for licensed users
wsl-fedoraremix 1.0.28.0 [Approved]
wsl-kalilinux 2018.3 [Approved]
wsl-opensuse 42.2.0.020181002 [Approved] Downloads cached for licensed users
wsl-sles 12.2.0.020181002 [Approved] Downloads cached for licensed users
wsl-ubuntu-1604 16.04.3.020181002 [Approved] Downloads cached for licensed users
wsl-ubuntu-1804 18.04.1.020181923 [Approved] Downloads cached for licensed users
wsltty 3.0.2.3 [Approved]
wsudo 1.0.2 [Approved]
wsus-offline-update 11.8 [Approved] Downloads cached for licensed users
wszst 1.58.7503 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
wtw 1.2.0.4424 [Approved]
wubi 12.04.20120921 - Possibly broken
wudt 1.0.30.20180515 [Approved] Downloads cached for licensed users
wuinstall 2.0.0.09172055
wuinstall.run 1.0.0.2014040406 - Possibly broken
wul 1.32 [Approved] - Possibly broken
wul.install 1.32 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
wul.portable 1.32 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
wumgr 0.7 [Approved] Downloads cached for licensed users
wumt 2016.12.20 [Approved] Downloads cached for licensed users
wunderlist 3.19.7.20190617 [Approved] Downloads cached for licensed users
wxmacmolplt 7.7 [Approved] Downloads cached for licensed users
wxmp3gain 4.0.0.20190427 [Approved]
wxpython 3.0.0.0 - Possibly broken
wxtcmd 0.3.20 [Approved]
wxwidgets 3.1.2 [Approved] Downloads cached for licensed users
wyam 2.2.5 [Approved]
wzgrapher 0.95.20160708 [Approved] Downloads cached for licensed users
x-lite 5.6.1.99142 [Approved] Downloads cached for licensed users
x-moto 0.5.11.20170430 [Approved]
x-mouse-button-control 2.18.7 [Approved] Downloads cached for licensed users
x264vfw 2017.07.30 [Approved]
x2go 4.1.2.0 [Approved]
x32-edit 3.2 [Approved] Downloads cached for licensed users
x64dbg.portable 20190811.1043 [Approved] Downloads cached for licensed users
Xamarin 4.0.0.20170104 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
xamarin-component 1.1.0.42 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
xamarin-interactive-aka-workbooks-inspector 1.0.0.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
xamarin-ios-simulator 0.10.1.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
xamarin-profiler 0.38.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
xamarin-studio 5.5.2.2014102200 - Possibly broken
xamarin-visualstudio 4.0.3.214 [Approved] Downloads cached for licensed users
xavtool 1.2.1 [Approved]
xbian-installer 1.4 [Approved] Downloads cached for licensed users
xbmc 13.2.0.20160121 [Approved]
xboot 1.0.14 [Approved] Downloads cached for licensed users
xbox-one-controller 1.0.0.0 - Possibly broken
xbox360-controller 1.200 - Possibly broken
xca 2.1.2 [Approved] Downloads cached for licensed users
xCmd 1.12.0 - Possibly broken
xdel 5.3.0 [Approved] Downloads cached for licensed users
xdelta3 3.0.8.0 - Possibly broken
xencenter 7.2.0 [Approved] Downloads cached for licensed users
xenserver-backup 2.0.1.5 [Approved]
xfinder 11.11 - Possibly broken
xidel 0.9.8 [Approved]
xiphqt 0.1.5 [Approved]
xmedia-recode 3.4.7.4 [Approved]
xmind 8.8 [Approved] Downloads cached for licensed users
Xming 6.9.0.31 [Approved]
xml-copy-editor 1.2.1.3 [Approved]
xml-notepad 2.8.0.0 [Approved]
XMLConverter 3.1
xmlexplorer 4.0.5 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
XmlFormatter 1.0.0.1 [Approved]
XmlNotepad 2007.0.0.1 [Approved]
xmlspy 2019.1.1 [Approved] Downloads cached for licensed users
xmlstarlet 1.6.1 [Approved]
xmlstarlet.portable 1.6.1 [Approved]
xna 4.0.20823.2017102101 [Approved] Downloads cached for licensed users
xna31 3.1.0.20160105 [Approved] Downloads cached for licensed users
xnconvert 1.80 [Approved]
xnconvert.install 1.80 [Approved] Downloads cached for licensed users
xnconvert.portable 1.80 [Approved] Downloads cached for licensed users
xnews 5.4.25 - Possibly broken
xnormal 3.19.3 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
XnView 2.48.20190326 [Approved] Downloads cached for licensed users
XnViewMP 0.93.1 [Approved]
xnviewmp.install 0.93.1 [Approved] Downloads cached for licensed users
xnviewmp.portable 0.93.1 [Approved] Downloads cached for licensed users
xonotic 0.8.2 [Approved] Downloads cached for licensed users
xournal 0.4.8 [Approved] Downloads cached for licensed users
xpdf-utils 3.4.0.20170430 [Approved]
xplorer2 4.2.0.1 [Approved] Downloads cached for licensed users
xplorer2pro 4.0.0.2 [Approved] - Possibly broken
xqilla 2.3.3 [Approved] Downloads cached for licensed users
xrecode3 1.54 [Approved] - Possibly broken
xrecode3.install 1.54 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
xrecode3.portable 1.54 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
xrepo 1.0.0 [Approved]
xsd2code 3.4.0 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
xsdextractor 1.2 [Approved]
xsltproc 1.1.28.0 [Approved] Downloads cached for licensed users
XSockets. PerformanceCounters 0.1
XSockets. Windows. Service 4.0.0
xtrmruntime 6.0 [Approved] - Possibly broken
XUnit 2.3.1 [Approved]
XUnit. VisualStudio 0.99.8.0 [Approved]
xUnit.vs2012 0.9.5
xvid 1.3.5 [Approved]
xvst 2.5.2.20141130 [Approved] - Possibly broken
xwfim 1.9.0.1 [Approved]
xyplorer 20.20.0200 [Approved] Downloads cached for licensed users
xyplorerfree 17.00.0100 [Approved] Downloads cached for licensed users
xysubfilter 3.1.0.752 [Approved] Downloads cached for licensed users
xyzzy 0.22.251
yabause 2.3.1 [Approved]
yacreader 9.5.0 [Approved] Downloads cached for licensed users
yacy 1.90 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
yakyak 1.5.4 [Approved] Downloads cached for licensed users
yandexdisk 1.0.0.6 [Approved]
yara 3.10.0 [Approved]
yarn 1.17.3 [Approved]
yasm 1.2.0
yatqa 3.9.7 [Approved] Downloads cached for licensed users
yed 3.19 [Approved]
Yeoman 1.1.2.20170217 [Approved]
ynote 3.4
yo 3.1.0 [Approved]
you-get 0.4.915 [Approved] Downloads cached for licensed users
you-need-a-budget 4.4.3.857 [Approved] Downloads cached for licensed users
youtube-dl 2019.08.13 [Approved]
youtube-dl-gui 0.4 [Approved]
youtube-dl-gui.install 0.4 [Approved]
youtube-dl-gui.portable 0.4 [Approved] Downloads cached for licensed users
youtube-downloader 1.3.1 [Approved] Downloads cached for licensed users
youtube-mp3 1.0.0 [Approved] Downloads cached for licensed users
yubico-authenticator 4.3.6 [Approved] Downloads cached for licensed users
yubikey-manager 1.1.2 [Approved] Downloads cached for licensed users
yubikey-neo-manager 1.4.0 [Approved] Downloads cached for licensed users
yubikey-personalization-tool 3.1.24 [Approved] Downloads cached for licensed users
yubikey-piv-manager 1.4.2.103 [Approved] Downloads cached for licensed users
yumi 2.0.6.7 [Approved]
yumi-uefi 0.0.1.6 [Approved]
z-cron 5.6.04 [Approved] Downloads cached for licensed users
z3 4.3.2 [Approved] - Possibly broken
zabbix-agent 4.2.4 [Approved]
zabbix-agent-tls 3.4.11 [Approved]
zabbix-agent.install 4.2.4 [Approved] Downloads cached for licensed users
zadig 2.4 [Approved] Downloads cached for licensed users
zandronum 3.0.0 [Approved] Downloads cached for licensed users
zap 2.8.0 [Approved] Downloads cached for licensed users
zazu 0.6.0 [Approved] Downloads cached for licensed users
zbar 0.10 [Approved] Downloads cached for licensed users
zeal 0.6.1 [Approved]
zeal.install 0.6.1 [Approved] Downloads cached for licensed users
zeal.portable 0.6.1 [Approved] Downloads cached for licensed users
zephyr-gnuarmemb 7.2.1.20170904 [Approved]
zeplin 1.4.0 [Approved] Downloads cached for licensed users
zerobrane-studio 1.80 [Approved]
zerobrane-studio.install 1.80 [Approved] Downloads cached for licensed users
zerobrane-studio.portable 1.80 [Approved] Downloads cached for licensed users
zerofill 1.06 [Approved] Downloads cached for licensed users
zeronet 0.6.5.20190704 [Approved] Downloads cached for licensed users
zerotier-one 1.4.0 [Approved]
zeta-test-management 3.6.17.0 [Approved] Downloads cached for licensed users
zettlr 1.3.0 [Approved]
zfs-win 0.21 [Approved] Downloads cached for licensed users
zig 0.4.0 [Approved] Downloads cached for licensed users
zim 0.68 [Approved] Downloads cached for licensed users
zimbra-desktop 7.3.1 [Approved] Downloads cached for licensed users - Possibly broken for FOSS users (due to original download location changes by vendor)
zip 3.0 [Approved] Downloads cached for licensed users
zip.template 1.0.0 [Approved]
zipinst 1.21 [Approved] Downloads cached for licensed users
znotes 0.4.5 [Approved]
Zoiper 5.2.28 [Approved] Downloads cached for licensed users
zola 0.8.0 [Approved] Downloads cached for licensed users
zona 2.0.3.3 [Approved] - Possibly broken
zoom 4.4.55389.0716 [Approved] Downloads cached for licensed users
zoomit 4.50.0.20160210 [Approved] Downloads cached for licensed users
zotero 5.0.73 [Approved]
zotero-standalone 5.0.55.20181119 [Approved]
zpaq 7.15 [Approved]
zsnes 1.51 [Approved]
zstandard 1.4.0 [Approved] Downloads cached for licensed users
zulu 12.3.11 [Approved] Downloads cached for licensed users
zulu10 10.3 [Approved] Downloads cached for licensed users
zulu11 11.33.15 [Approved] Downloads cached for licensed users
zulu12 12.3.11 [Approved] Downloads cached for licensed users
zulu6 6.22.0.3 [Approved] Downloads cached for licensed users
zulu7 7.31.0.5 [Approved] Downloads cached for licensed users
zulu8 8.40.0.25 [Approved] Downloads cached for licensed users
zulu9 9.0.7.1 [Approved] Downloads cached for licensed users
zvirtualdesktop 1.0.92.8 [Approved]
6863 packages found.
```

# オススメ
とりあえずChocolateyGUI入れて画面から管理できるようにすると捗ります。
そちらだと1ページずつ更新するたびに時間がかかってどうしようもないので、choco listで見た方が楽かもしれません。
なお、choco installとGUI間できちんと連携されていました。

# 読了後いいね！をお願いします。
どれだけの方に読んでもらっているか知りたいので、お手数をおかけしますがご協力いただけると嬉しいです。

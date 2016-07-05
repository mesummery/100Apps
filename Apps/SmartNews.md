# 📢 SmartNews

* OS 9.2.1 / App 3.1.8
* iPhone6

### Purpose
話題のニュースをサクサク読む

### UI / UX  
* チュートリアルでは横スワイプではなく、ボタンタップでページング
* 一覧画面での[めくれる演出](#smartnews_top)
* スクロールの方向によって、[上下タブが隠れる](#smartnews_tabs)
* [設定画面](#smartnews_setting)はGrouped設定のUITableViewでシンプル
* クレジットとして、[使用ライブラリの表示画面](#smartnews_credit)がある
* 起動時にオフラインでも、画像以外の文章コンテンツは閲覧できる

#### :triangular_flag_on_post: <a name="smartnews_top">めくれる演出</a>
UIPageViewController使用？   
他アプリでは、セグメント系はセグメントボタンタップもしくは横スワイプでページングすることが多いイメージです   
めくれる演出をそのまま使うアプリは珍しいかも

<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/smartnews_top.gif" width="320px">

#### :triangular_flag_on_post: <a name="smartnews_tabs">スクロールで上下タブが隠れる</a>
一覧画面の表示領域をすこしでも多く見せるためのUIと思われました

<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/smartnews_tabs.gif" width="320px">

#### :pushpin: <a name="smartnews_setting">設定画面</a>
Grouped設定のUITableViewと思われます

<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/smartnews_setting.jpg" width="320px">

#### :triangular_flag_on_post: <a name="smartnews_credit">使用ライブラリの表示画面</a>
設定アプリ内ではなく、アプリ内に画面を作っていました

* [pokeb/asi-http-request](https://github.com/pokeb/asi-http-request/)
* [MatthewLabs/MLTableAlert](https://github.com/MatthewLabs/MLTableAlert)
* [mattlawer/BButton](https://github.com/mattlawer/BButton)
* [chrisbanes/Android-PullToRefresh](https://github.com/chrisbanes/Android-PullToRefresh)

:tada: TIPS: 比較的古めのライブラリみたいです

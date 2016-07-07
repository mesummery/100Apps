# :high_heel: SHOPLIST

* OS 9.2.1 / App 1.10.0
* iPhone6

### Purpose
ファッション通販

### UI / UX  
* 配色はモノトーンでシンプル
* [スクロールでヘッダーバーとソートボタンが非表示になる](#shoplist_scroll)
* [ホームタブはスワイプとセグメントボタンタップで、ページング](#shoplist_segment)
* [商品名は表示しないグリッド配置の商品一覧](#shoplist_grid)
* [商品詳細はプルのジェスチャーで閉じられる](#shoplist_close)
* [検索タブではスクロールが停止した時だけボタンが表示される](#shoplist_filtering)
* [価格がフローティングしていて見やすい](#shoplist_price)
* [設定画面](#shoplist_setting)
* [ヘルプなどのWebViewの動き](#shoplist_webview)
* [オフライン表示はリロードボタン付きダイアログ](#shoplist_offline)

#### :triangular_flag_on_post: <a name="shoplist_scroll">スクロールでヘッダーバーとソートボタンが非表示</a>
<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/shoplist_scroll.gif" width="320px">

#### :triangular_flag_on_post: <a name="shoplist_segment">ホームタブのページング</a>
<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/shoplist_segment.gif" width="320px">

#### :triangular_flag_on_post: <a name="shoplist_grid">商品名は表示しないグリッド配置の商品一覧</a>
ファッションは見た目から探すことが多そうなので、商品名などの細々した情報は一覧時点では不要なのかもしれません   

<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/shoplist_grid.jpg" width="320px">

#### :triangular_flag_on_post: <a name="shoplist_close">商品詳細画面を閉じるときのジェスチャー/a>
画面の最上部でプルを行うと、画面のクローズが行われるようです（**プルクローズと命名したいです**）   
EdgeSwipeでもクローズできるので、プルクローズが本当に必要な遷移方法なのか、気になりました   
スクロール最下部で逆方向にプルしてクローズできた方が利便性は高そうな気がしています

<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/shoplist_close.gif" width="320px">

#### :triangular_flag_on_post: <a name="shoplist_filtering">検索タブではスクロールが停止した時だけボタンが表示される/a>
必要な時に必要なUIが動的に表示されるので、一覧の閲覧の妨げにならないです

<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/shoplist_filtering.gif" width="320px">

#### :triangular_flag_on_post: <a name="shoplist_price">商品詳細の価格表示/a>
フッター固定なので見やすいです   
:tada: TIPS: あと、細かいですがスクロールのIndicatorのoffsetが気になります

<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/shoplist_price.gif" width="320px">

#### :triangular_flag_on_post: <a name="shoplist_setting">設定画面/a>
<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/shoplist_setting.jpg" width="320px">

#### :triangular_flag_on_post: <a name="shoplist_webview">ヘルプなどのWebViewの動き/a>
WebView内のページはアプリ向けに表示されています（ページ内のヘッダーが非表示になっています）   
WebView内でページ遷移が起こると、ヘッダー左部分にナビゲーションバック用のボタンが表示されました

<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/shoplist_webview.gif" width="320px">

#### :triangular_flag_on_post: <a name="shoplist_offline">オフライン表示/a>
<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/shoplist_offline.jpg" width="320px">

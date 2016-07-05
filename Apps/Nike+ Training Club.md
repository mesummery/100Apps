# 👟 Nike+ Training Club

⚠️TODO ：実際にワークアウトしながら使ってみてUXを体感してみる

* OS 9.2.1 / App 5.0.2
* iPhone6

### Purpose
ユーザーのトレーニングをサポート
* ワークアウトの動画をみられる
* イベントに参加できる
* メッセージが閲覧できる

### UI / UX  
* チュートリアルは馴染みのあるベージング
* ワークアウト一覧はTableView利用と思われる
* [アコーディオン表示で動画の再生が開始](#ntc_accordion)
* [設定画面は、GrouptedタイプのUITableView](#ntc_setting)
* [エラーでダイアログが出ても、注目のワークアウトは表示されている](#ntc_error)

#### :triangular_flag_on_post: <a name="ntc_accordion">アコーディオン + 動画</a>
再生画面への遷移を行わないので、操作の手数が少なくて済みそうです   
ワークアウトを行いながらの操作が考慮されているようです

<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/ntc_accordion.gif" width="320px">

#### :triangular_flag_on_post: <a name="ntc_setting">設定画面</a>

<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/ntc_setting.jpg" width="320px">


#### :triangular_flag_on_post: <a name="ntc_error">起動時オフラインでもコンテンツの表示はあり</a>
**しかも更新されているっぽい**（Background Fetch？）

<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/ntc_error.jpg" width="320px">

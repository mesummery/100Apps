# :articulated_lorry:  Amazon

* OS 9.2.1 / App 6.6.0
* iPhone6

### Purpose
さくさくショッピング

### UI / UX  
* Safari上でリンクを踏むとアプリ起動される
* [WebView利用らしいが、アプリに最適化されている](#amazon_web)
* [WebViewのリンクナビゲーション時にPush遷移を行っている](#amazon_transition)
* [設定メニュー系はドロワー](#amazon_setting)
* [アニメーションで操作方法を表示](#anmazon_animation)
* [オフライン表示](#amazon_offline)

#### :triangular_flag_on_post: <a name="amazon_web">アプリに最適化されたWebページ</a>
ネイティブのヘッダーがあるため、Webページ内のヘッダーは非表示になっている  

<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/amazon_web.jpg" width="320px">

:tada: TIPS: 同じページをSafariでみたときにはヘッダーがついています  

<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/amazon_safari.jpg" width="320px">

#### :triangular_flag_on_post: <a name="amazon_transition">リンクナビゲーション時にPush遷移</a>
WebView内のページ遷移時にネイティブ側で別ViewControllerを生成して画面遷移を行っているようです   
:tada: TIPS: サインインや注文の確定など、前に戻るべきではない画面は、Modalを使用している

<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/amazon_transition.gif" width="320px">

#### :triangular_flag_on_post: <a name="amazon_setting">設定メニューのドロワー</a>
活きがいい

<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/amazon_setting.gif" width="320px">

#### :triangular_flag_on_post: <a name="anmazon_animation">アニメーションで操作方法を表示</a>
チュートリアル画面自体は存在しませんが、こういった演出がアプリ操作方法の説明になっていました   
チラ見せ加減も、ユーザーの興味を引くのだと思いました

<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/anmazon_animation.gif" width="320px">

#### :triangular_flag_on_post: <a name="amazon_offline">オフライン表示</a>
カートの中身も0件になっていました

<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/amazon_offline.jpg" width="320px">

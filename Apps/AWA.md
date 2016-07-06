# :headphones: AWA

* OS 9.2.1 / App 1.2.16
* iPhone6

### Purpose
ミュージックの検索、再生

### UI / UX  
* [START画面が動画でイカしてる](#awa_start)
* [「サービスを開始することで利用規約に同意したものとさせていただきます」](#awa_terms)
* [PageControlのインジケータが左上に配置（でもスワイプ操作はわかる）](#awa_pageControl)
* [スワイプ時とスクロール時のパララックスが気持ちいい](#awa_parallax)
* [長押ししたらページ切り替えできました（**たまたま見つけた**）](#awa_page)
* [アプリ全体で統一された画面遷移演出だが違和感がない](#awa_transition)
* [ハンバーガーからも最上部スワイプからもメニューができる](#awa_menu)
* [設定画面が凝っている](#awa_setting)
* [オフライン表示](#awa_offline)
* **全体的に使っていてテンションが上がる！かっこいい**
* [使用ライブラリ](#awa_library)

#### :triangular_flag_on_post: <a name="awa_start">START画面が動画</a>
動いてるけど端末熱くならない  

<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/awa_start.gif" width="320px">

#### :triangular_flag_on_post: <a name="awa_pageControl">PageControlのインジケータが左上に配置</a>
ページコントロールは横位置Centerの常識だと思っていました   
ページコントロールの位置が左上でも、ジェスチャーを表すアニメーションがあるので、スワイプ操作を行えることがわかりました

<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/awa_pageControl.gif" width="320px">

#### :triangular_flag_on_post: <a name="awa_terms">利用規約</a>
「サービスを開始することで利用規約に同意したものとさせていただきます」が極小Fontで記載    
**利用規約**をタップすると規約画面がモーダル表示されました

#### :triangular_flag_on_post: <a name="awa_parallax">パララックスかっこいい</a>
ちょっとした演出がいちいち格好良く感じます

<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/awa_parallax.gif" width="320px">

#### :triangular_flag_on_post: <a name="awa_page">長押しで直接ページ選択</a>
たまたま見つかりました

<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/awa_page.gif" width="320px">

#### :triangular_flag_on_post: <a name="awa_transition">画面遷移</a>
ImageViewのサイズが固定なので、どんなアスペクト比の画像が来ても、遷移時に違和感を感じないのかもしれないです
Popで前の画面に移動した時も画像が元に位置に戻るアニメーションが付いていました

<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/awa_transition.gif" width="320px">

#### :triangular_flag_on_post: <a name="awa_menu">メニュー表示</a>

<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/awa_menu.gif" width="320px">

#### :triangular_flag_on_post: <a name="awa_setting">設定画面</a>
設定とはいえ、動きに拘りがある

<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/awa_setting.gif" width="320px">

#### :triangular_flag_on_post: <a name="awa_offline">オフライン表示</a>
基本的には以前に取得したコンテンツがキャッシュされているようです   

<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/awa_offline.jpg" width="320px">

#### :triangular_flag_on_post: <a name="awa_library">使用ライブラリ</a>
設定アプリの*Licenses*より一部抜粋

* [Crashlytics](https://try.crashlytics.com/)
* [DeepLinkKit](https://github.com/button/DeepLinkKit)
* [fmdb](https://github.com/ccgus/fmdb)
* [FRDLivelyButton](https://github.com/sebastienwindal/FRDLivelyButton)
* [FBSDK](https://developers.facebook.com/docs/ios/)
* [Fabric](https://get.fabric.io/)
* [MarqueeLabel](https://github.com/cbpowell/MarqueeLabel)
* [Parse-SDK-iOS-OSX](https://github.com/ParsePlatform/Parse-SDK-iOS-OSX)
* [Realm](https://realm.io/jp/)
* [Shimmer](https://github.com/facebook/Shimmer)
* [UICKeyChainStore](https://github.com/kishikawakatsumi/UICKeyChainStore)
* [libwebp](https://github.com/webmproject/libwebp)
* [pop](https://github.com/facebook/pop)

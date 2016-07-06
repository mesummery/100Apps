# :airplane: skyticket

* OS 9.2.1 / App 1.31
* iPhone6

### Purpose
航空券の検索、予約

### UI / UX  
* [WebView表示のようです](#skyt_tabs)
* [アプリ最適化はされていない？](#skyt_footer)
* [各タブは専用の機能しか持たないシンプルな構造](#skyt_func)
* [ナビゲーションバックボタンがカスタマイズされている](#skyt_navBack)
* [設定画面](#skyt_setting)


#### :triangular_flag_on_post: <a name="skyt_tabs">WebView表示のようです</a>
WebView利用と思われます（Webページのヘッダーがそのまま表示されています）   
カスタムのタブは大きくて押しやすいです   
タブのすぐ上にはブラウザバック、フォワードボタンが配置されていました

<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/skyt_tabs.jpg" width="320px">

#### :triangular_flag_on_post: <a name="skyt_footer">アプリ最適化はされていない</a>
フッターの黒いエリアがページのコンテンツに被ってしまっているのが気になりました（**会社概要**の部分）   
insetを設定した方がよいかもしれないと思われました

<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/skyt_footer.jpg" width="320px">

#### :triangular_flag_on_post: <a name="skyt_func">各タブは専用の機能しか持たないシンプルな構造</a>
AppStoreアプリのようにどのタブからでもアプリインストール画面に遷移する構造とは違いました   
各タブには専用の目的しか持たせないように整理されていました   
時刻表閲覧では予約画面への動線がありますが、その場合は、**予約タブへのタブ切り替え**が起こりました

<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/skyt_func.gif" width="320px">

#### :triangular_flag_on_post: <a name="skyt_navBack">ナビゲーションバックボタンがカスタマイズ</a>
ヘッダー内ではなく、独自実装で配置されているようで新鮮でした（右利きにはありがたいと思ってしまいました）   
デフォルトのヘッダーを非表示にしている理由が気になりました

<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/skyt_navBack.gif" width="320px">

# 👕 ZanQy

* OS 9.2.1 / App 1.0
* iPhone6

### Purpose
衣類の枚数をカウントする（"_インナーファッションカウンター_"）

### UI / UX
* チュートリアルはページングだが、スワイプ時に[スケール変化の演出](#zq_tutorial)がある
* 目的自体はシンプルなアプリだが、[演出が多い](#zq_animation)
* カード風のUIはよくあるが、本当に[カードめくりの動き](#zq_card)の演出
* オフラインだとメッセージが[トースト表示](#zq_error)されてコンテンツの表示はなし
* 全体的にViewのサイズを__ぬるぬる__変える演出のアニメーションが多い気がする

#### :triangular_flag_on_post: <a name="zq_tutorial">チュートリアル演出</a>
スワイプ距離に合わせてスケールが変更されるので、操作感として気持ちが良いです  
ページ数も少なく、嫌にならない

<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/zq_tutorial.gif" width="320px">

#### :triangular_flag_on_post: <a name="zq_animation">演出が多い</a>
やたら動く

<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/zq_animation.gif" width="320px">


#### :triangular_flag_on_post: <a name="zq_card">カードめくり演出</a>
CollectionViewを利用したカード風のデザインはよく見ます   
このパターンではめくったカードが後ろに回って追加される演出がリアルで凝っていました

<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/zq_card.gif" width="320px">


#### :triangular_flag_on_post: <a name="zq_error">オフラインだとトースト</a>
<img src="https://github.com/mafmoff/100Apps/blob/master/Resources/Images/zq_error.jpg" width="320px">


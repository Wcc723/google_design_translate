# 響應式互動(動畫)設計

響應式互動(動畫)設計可以建立與使用者之間的信任感，同時也吸引他們的注意力。使用者與程式互動時，若出現漂亮且極具邏輯性的效果，使用者會感覺被滿足甚至是愉悅的，這樣的動畫設計是經過深思熟慮且具有目的性的,並不是隨機發生，可以有一點點異想天開，但從來不會是導致使用者分心的，它鼓舞使用者對應用程式更進一步探索：如果按了這個會有什麼事情發生？那這個呢？

在Material Design中，應用程式是會對使用者的輸入操作進行回饋，並且極其盼望使用者的輸入：

- 觸控，聲音，滑鼠和鍵盤都是首要的輸入方式。
- 雖然使用者介面元件是看得到的形體，但它們被鎖在一層玻璃後面(也就是電腦或任何裝置的螢幕後)
藉由即時識別輸入與指示操作方向，視覺和動畫效果的提示，彌補了使用者與裝置溝通的鴻溝。

響應式互動(動畫)設計將應用程式提升到另一個層次，從依照使用者要求顯示訊息的程式，變成以更具體的方式在溝通的軟體。

## 實例

<video width="360" height="405" controls="">
<source src="//material-design.storage.googleapis.com/videos/animation-responsiveinteraction-responsiveinteraction-2-celebratetouch-localized-ink-reaction2_large_xhdpi.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/videos/animation-responsiveinteraction-responsiveinteraction-2-celebratetouch-localized-ink-reaction2_large_xhdpi.mp4" type="video/mp4">
</video>

> 表象層的互動設計

<video width="360" height="405" controls="">
<source src="//material-design.storage.googleapis.com/videos/animation-responsiveinteraction-inkreactions-notouchripplepressandrelease_large_xhdpi.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/videos/animation-responsiveinteraction-inkreactions-notouchripplepressandrelease_large_xhdpi.mp4" type="video/mp4">
</video>

> 物體本身的反應

<video width="360" height="405" controls="">
<source src="//material-design.storage.googleapis.com/videos/animation-responsive-interation-radialReact-example_large_xhdpi.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/videos/animation-responsive-interation-radialReact-example_large_xhdpi.mp4" type="video/mp4">
</video>

> 放射狀的動畫

## 表象層的互動設計

當接收到一個輸入事件，系統即時在下列人機溝通的接觸點上，提供視覺化的(輸入)確認，例如手指觸控處之下，或者是語音輸入的麥克風圖示上，或者是在讓使用者用鍵盤輸入的適當區域。一種說法是這樣的確認方式暗喻了墨水的使用，墨水是覆蓋在每一張紙上的動態展示表象層。

最基礎簡單呈現人機溝通的視覺方法是觸控漣漪的效果，裝置可以明確地表達被觸控時的反應方式和時間長短，還有各方面的動態外觀，如：聲波的振幅或者觸控的力度。

### 最佳實例

(資料/訊息的)輸入是發生在特定位置的，例如在手指觸控的接觸點，或是傳入聲音的麥克風圖示，從這個位置，產生放射狀的視覺化動畫效果。

<video width="360" height="640" controls="">
<source src="//material-design.storage.googleapis.com/videos/animation-responsiveinteraction-inkreactions-touchripplepressandrelease_large_xhdpi.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/videos/animation-responsiveinteraction-inkreactions-touchripplepressandrelease_large_xhdpi.mp4" type="video/mp4">
</video>

> 觸控漣漪 - 按壓/釋放

<video width="360" height="640" controls="">
<source src="//material-design.storage.googleapis.com/videos/animation-responsiveinteraction-inkreactions-touchrippledragindragout_large_xhdpi.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/videos/animation-responsiveinteraction-inkreactions-touchrippledragindragout_large_xhdpi.mp4" type="video/mp4">
</video>

> 觸控漣漪 - 拖進/拉出

## 物體本身的回饋

除了在表象層呈現像墨水渲染般的動畫效果，物體本身也可以做出回饋。當被觸控或點選的時候，物體可以往上移動，表示是啟用的狀態，使用者透過觸控或點選，產生新的物體或改變物體現有的狀態，或是透過拖曳或者撥動的方式直接操作這些物體。

### 最佳實例

### 原點

當程式與使用者互動之下產生新物體時，物體表象層的擴展效果必須從輸入點開始。

<video width="360" height="405" controls="">
<source src="//material-design.storage.googleapis.com/videos/animation-responsive-surfaceresponse-pointorigin-do_example_large_xhdpi.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/videos/animation-responsive-surfaceresponse-pointorigin-do_example_large_xhdpi.mp4" type="video/mp4">
</video>

> 這樣做吧
>
> 物體從觸控點出現，視覺上可看到物體與觸控點是繫結在一起的。

<video width="360" height="450" controls="">
<source src="//material-design.storage.googleapis.com/videos/animation-responsive-surfaceresponse-pointorigin-dont_example_large_xhdpi.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/videos/animation-responsive-surfaceresponse-pointorigin-dont_example_large_xhdpi.mp4" type="video/mp4">
</video>

> 請不要這樣做
>
> 紙卡從螢幕的中心點出現，切斷了與輸入點之間的關係。


### 觸控時的上升效果

當一張卡片或可分離元素啟用時，它的位置會向上移動表示是啟用的狀態。

<video width="360" height="405" controls="">
<source src="//material-design.storage.googleapis.com/videos/animation-responsiveinteraction-inkreactions-notouchripplepressandrelease_large_xhdpi.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/videos/animation-responsiveinteraction-inkreactions-notouchripplepressandrelease_large_xhdpi.mp4" type="video/mp4">
</video>

> 觸控時的上升效果

## 放射狀的動畫效果

使用者的操作行為會有一個中心點，透過這個中心點，使用者將他們的操作意圖輸入這個系統。與使用者的輸入點建立強烈視覺連結，可以讓使用者更清楚知道他所做的動作，不論是從手指觸控螢幕或是從麥克風輸入聲音。橫跨螢幕的動畫效果，應該隨著與中心點的距離增加，前進式地引發動畫，就像建立一個漣漪動畫。

使用者的輸入會有一個中心點，他們在觸控點上進行觸控動作，透過麥克風圖示傳入聲音，經由虛擬按鍵打字輸入。

每一個動畫都應該在視覺上與它們各自的輸入中心點進行連結，與中心點較近的動畫效果比與中心點較遠的動畫效果快出現，建立一個漣漪動畫(從中心點根據距離產生移動的動畫效果)。

> *翻譯：[Charlene](https://www.facebook.com/charlene.feng.7)*




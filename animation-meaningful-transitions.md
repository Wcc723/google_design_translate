# 有意義的動畫

有時候使用者不易專注於應用程式本身，或迷失於元素A變換到元素B的過程，
當使用者在多重程序或多步驟的狀態下時，審慎安排動線設計能有效地導引使用者的注意力。當佈局或元素重新排列時，要避免造成使用者困惑，並改善整個使用者體驗的美感。動線的設計不但使產品更漂亮，更應該考量到功能性的目的。

範例

<video controls="" width="622" height="360" >
<source src="//material-design.storage.googleapis.com/videos/animations-meaningfultransitions-hierarchical_transitions_topLevel_large_xhdpi.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/videos/animations-meaningfultransitions-hierarchical_transitions_topLevel_large_xhdpi.mp4" type="video/mp4">
</video>

<video controls=""  width="320" height="568" >
<source src="//material-design.storage.googleapis.com/videos/animation-meaningfultransitions-view_contact_large_xhdpi.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/videos/animation-meaningfultransitions-view_contact_large_xhdpi.mp4" type="video/mp4">
</video>

## 視流的連續性

兩個不同狀態的視覺漸變必須是流暢、輕鬆而不間斷的。
最重要的是讓使用者更清晰而非困惑。設計良好的動畫，能幫助使用者清楚了解現在應該要專注在哪個地方。

漸變動畫的範疇包含三個元素：

- **進入的元素。** 可能是直接新增的元素或從其他位置轉變過來的，這些元素有各自被引進或再製造的方式。
- **離開的元素。** 與新內容不再相關的元素必須透過適當的方式移除。
- **存留元素。** 從漸變動畫開始到結束都持續存在的元素，可能是細小的icon圖示或顯眼的大型圖片，透過動畫改變成符合螢幕的尺寸。


### 注意

當你在設計你的動畫時，請注意以下幾件事：

- 思考使用者的注意力應該如何被引導？什麼元素或動作能夠支持這個目標？動畫過程中，要進入、離開或共用的元素，要如何安排強調或弱化？
- 設計畫面時，思考動畫前後的狀態，找出機會創造色彩上或存留元素的視覺關聯性。
- 審慎地加入動作：思考如何透過移動一個元素，使動畫漸變的過程更加清晰流暢。

範例

<video controls=""  width="960" height="350" >
<source src="//material-design.storage.googleapis.com/videos/meaningfultransitions-visualcontinuity2_large_xhdpi.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/videos/meaningfultransitions-visualcontinuity2_large_xhdpi.mp4" type="video/mp4">
</video>

> 你該這麼做：
>
> 圖層式的紙張元素是常用的設計，紙張元素常常以滑入的方式進入畫面，而墨水元素則較常使用淡出的方式進入畫面。不建議使用全螢幕的淡出效果，但是至少比直接切換畫面好。

<video controls=""  width="960" height="350" >
<source src="//material-design.storage.googleapis.com/videos/meaningfultransitions-visualcontinuity1_large_xhdpi.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/videos/meaningfultransitions-visualcontinuity1_large_xhdpi.mp4" type="video/mp4">
</video>

> 不要這麼做：
>
> 避免直接切換畫面。直接切換畫面的突兀感，導致使用者難以理解動畫的運作。

## 講求結構順序的時間差

當你建置一個動畫，要考量該元素的的運動方式與運動的時間差。確保動畫能幫助你更有次序的顯示資訊，即透過動線的安排，告訴使用者，什麼是最重要的資訊。

然而，並沒有一個公式告訴你重要的東西最先出來，或最不要的東西最後出來。
動畫時間差的安排必須流暢且必須避免讓使用者覺得與產品脫節。



範例

<video controls=""  width="255" height="150" >
<source src="//material-design.storage.googleapis.com/videos/animation-meaningfultransitions-hierarchicaltiming4do_large_xhdpi.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/videos/animation-meaningfultransitions-hierarchicaltiming4do_large_xhdpi.mp4" type="video/mp4">
</video>

> 你該這麼做：
>
> 使用重疊的動線引導使用者的注意力。

<video controls="" width="255" height="150">
<source src="//material-design.storage.googleapis.com/videos/animation-meaningfultransitions-hierarchicaltiming1dont_large_xhdpi.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/videos/animation-meaningfultransitions-hierarchicaltiming1dont_large_xhdpi.mp4" type="video/mp4">
</video>

> 不要這麼做：
>
> 動畫時間差的安排並沒有暗示使用者什麼是重要的。
如果所有的元素都同等重要，你可以考慮使用一個大型動畫，暗示使用者它們屬於同一個群組。

## 編排規則的一致性

動畫元素在畫面中的移動順序應該要以協調的方式呈現，元素移動的路徑必須合理且有次序。
隨機的移動方式容易使人分心，規劃良好的應用程式能幫助使用者學習使用的方式，協調的動畫元素能提升使用者對於應用程式理解度，一旦使用者了解應用程式的設計原則，他們就不易在使用的過程迷失方向。

### 最佳典範

- 避免線性空間路徑，除非運動方式是沿著特定軸線、或與其他元素一起朝向特定目標或離開特定目標。
- 確保各個元素的路徑相互配合。避免有衝突或重疊的路徑。
- 考慮動畫故事性的深淺度：決定個路徑的上下順序，以及為何如此？
- 如果在螢幕上追蹤所有移動元素的路徑，看起來是否漂亮而有組織性？這些路徑是否有創造出清楚的畫面引導使用者該注意哪個位置？
- 套用一致的動畫設計規則到進入與離開的元素，強化各元素的空間關係。


範例

<video controls=""  width="960" height="350">
<source src="//material-design.storage.googleapis.com/videos/meaningfultransitions-consistentchoreography_do1_large_xhdpi.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/videos/meaningfultransitions-consistentchoreography_do1_large_xhdpi.mp4" type="video/mp4">
</video>

> 你該這麼做：
>
> 使用協調且俱有順序性的動線指引使用者的注意力。

<video controls="" width="360" height="422" >
<source src="//material-design.storage.googleapis.com/videos/meaningfultransitions-consistentchoreography_dont3_large_xhdpi.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/videos/meaningfultransitions-consistentchoreography_dont3_large_xhdpi.mp4" type="video/mp4">
</video>

> 不要這麼做：
>
> 避免使用無連續性或無順序性的動線，物件進出時也要避免看似隨機的出入動線。


> *翻譯： [Peter](https://www.facebook.com/viator75)*

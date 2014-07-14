# 進度與活動

當您使用應用程式載入內容時，是令人感到愉快並且無痛地透過減少視覺變化，在使用者看到之前及內容進行交互動作。每一次的操作只能由一個活動指標，例如：重新整理的操作不能顯示重新整理條及環狀型的旋轉



## 指標類型

對於操作，其中可以確定完成操作的百分比。使用一個較為確定的指標，讓使用者知道操作會需要花多長的時間。

對於操作，用戶被要求等待一段時間完成動作，它並不需要暴露背後端發生了什麼事情，多久會完成，可使用一個不定性的指標呈現。

有兩種指標類型：線性及環形。你可以使用一種確定或不確定的操作項目。

### 線性

線性進度指示應該總是 0% 至 100% 的進度百分比，並不會向後移動道更低的數值。如果有多個操作在序列中，使用進度指示器來顯示整體的延遲動作，這樣，當進度到達 100% 時，並不會退回到 0% 進度而再次讀取。

線性條應該在頁面上的標頭或片材上的邊緣顯示及消失。

<video width="739" height="565" src="http://material-design.storage.googleapis.com/videos/components-progressandactivity-progressandactivity-_20spec.linear_large_xhdpi.webm" controls=""></video>

<video width="360" height="640" src="http://material-design.storage.googleapis.com/videos/components-progressandactivitiy-progressandactivity-7-youtube.mobile-buffer_large_xhdpi.webm" controls=""></video>

<video width="360" height="639" src="http://material-design.storage.googleapis.com/videos/components-progressandactivity-progressandactivity-6-chrome.mobile.query.load_large_xhdpi.webm" controls=""></video>

### 環形

<video width="739" height="308" src="http://material-design.storage.googleapis.com/videos/components-progressandactivity-progressandactivity-_20spec.circular_201_large_xhdpi.webm" controls=""></video>

### 整合環形

<video width="739" height="154" src="http://material-design.storage.googleapis.com/videos/components-progressandactivity-progressandactivity-_20spec.circular_202_large_xhdpi.webm" controls=""></video>

> 環形旋轉的載入器可以整合在圖示或是一個重新整理的圖式

<video width="360" height="639" src="http://material-design.storage.googleapis.com/videos/components-progressandactivity-progressandactivity-5-pegman.fab-upload.photo_large_xhdpi.webm" controls=""></video>

<video width="740" height="555" src="http://material-design.storage.googleapis.com/videos/components-progressandactivity-progressandactivity-6-gallery.tablet-refresh.icon_large_xhdpi.webm" controls=""></video>


## 行為

### 階段式載入

<video width="359" height="639" src="http://material-design.storage.googleapis.com/videos/components-progressandactivity-progressandactivity-4-bigtop.mobile-swipe.down.to.refresh 2_large_xhdpi.webm" controls=""></video>

> **一階段載入**
>
> 在現有上載入油墨（複製及圖片），不改變容器

<video width="360" height="640" src="http://material-design.storage.googleapis.com/videos/components-progress-activity-behavior-load.content.from.bottom_large_xhdpi.webm" controls=""></video>

> **兩階段載入**
>
> 紙的容器裡產生，接著油墨也載入（複製及圖片）

<video width="360" height="640" src="http://material-design.storage.googleapis.com/videos/components-progressandactivity-progressandactivity-1-drive.mobile-initial.load_large_xhdpi.webm" controls=""></video>

> **初次載入內容**

<video width="360" height="639" src="http://material-design.storage.googleapis.com/videos/components-progressandactivity-progressandactivity-2-drive.mobile-load.folders_large_xhdpi.webm" controls=""></video>

> **在所有內容一次性載入及顯示**

<video width="740" height="555" src="http://material-design.storage.googleapis.com/videos/components-progressandactivity-progressandactivity-6-gallery.tablet-refresh.icon_large_xhdpi.webm" controls=""></video>

> **在兩個階段載入及顯示**

### 載入額外的內容

<video width="740" height="555" src="http://material-design.storage.googleapis.com/videos/components-progressandactivity-progressandactivity-4-bigtop.tablet-send.message_large_xhdpi.webm" controls=""></video>

> **範例 1: 卡片的擴展**
>
> 建議用在卡片的擴展上比較大的表面時，使用一個不定的線性指標呈現。

<video width="720" height="1280" src="http://material-design.storage.googleapis.com/videos/components-progressandactivity-behavior-scroll.up.to.refresh_large_xhdpi.webm" controls=""></video>

> **範例 2: 向上滾動刷新**
>
> 建議在從下方刷新一個列表時，可以使用一個不定的圓形旋轉指示燈與油墨散開的觸發

<video width="359" height="639" src="http://material-design.storage.googleapis.com/videos/components-progressandactivity-progressandactivity-4-bigtop.mobile-swipe.down.to.refresh_large_xhdpi.webm" controls=""></video>

> **範例 3: 向下滑動刷新**
>
> 建議在從上方刷新一個列表時，可以使用一個不定的環形旋轉指示燈與油墨散開的觸發

---

*翻譯：[Weiju](http://weijutu.blogspot.tw/)*
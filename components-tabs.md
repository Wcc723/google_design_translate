# 頁籤

頁籤利用切換的方式，讓app可以很方便的在不同內容或分類的資料集間瀏覽。


## 用法

頁籤提供一個介面，用來顯示相關的群組內容，頁籤文字簡潔的標註了該頁籤和內容的關連性。

### 行動裝置的頁籤種類

![](http://material-design.storage.googleapis.com/images/components-tabs-usage-tabs-spec-02_large_mdpi.png)

> 可延伸app bar+頁籤

![](http://material-design.storage.googleapis.com/images/components-tabs-usage-tabs-spec-03_large_mdpi.png)

> 嵌入搜尋框+app bar+頁籤

![](http://material-design.storage.googleapis.com/images/components-tabs-usage-tabs-spec-06_large_mdpi.png)

> 預設app bar+頁籤

![](http://material-design.storage.googleapis.com/images/components-tabs-usage-tabs-spec-08_large_mdpi.png)
 
> 預設app bar+可滑動頁籤
 
![](http://material-design.storage.googleapis.com/images/components-tabs-usage-tabs-spec-07_large_mdpi.png) 

> 文字顏色和選取指示線相同

![](http://material-design.storage.googleapis.com/images/components-tabs-usage-tabs-spec-17_large_mdpi.png) 
 
> 滑動時鎖定頁籤

### 桌上型電腦的頁籤種類

![](http://material-design.storage.googleapis.com/images/components-tabs-usage-tabs-spec-09_large_mdpi.png)
 
> 預設app bar+頁籤

![](http://material-design.storage.googleapis.com/images/components-tabs-usage-tabs-spec-15_large_mdpi.png)

> 更多項目的下拉選單

![](http://material-design.storage.googleapis.com/images/components-tabs-usage-tabs-spec-12_large_mdpi.png)

> 分頁式頁籤
 
![](http://material-design.storage.googleapis.com/images/components-tabs-usage-tabs-spec-13_large_mdpi.png)

![](http://material-design.storage.googleapis.com/images/components-tabs-usage-tabs-spec-16_large_mdpi.png)
 
> 展開式選單

![](http://material-design.storage.googleapis.com/images/components-tabs-usage-tabs-spec-14_large_mdpi.png)

> 置中頁籤

### 使用時機

使用頁籤，將大量相關資料或選項分割，成為較高易讀性。目標放在輔助內容導覽和內容組織，而不用從目前的內容中導向別的地方。

雖然頁籤內容可能有導覽特性(例：地圖路徑選項改變地圖顯示畫面，搜尋結果導向其他站台)，但本身並不用在導覽上。

頁籤也不應用在滑動或分頁的內容(例：app中的滑動換頁)。

![](http://material-design.storage.googleapis.com/images/components-tabs-usage-tabs_do_10_large_mdpi.png)
 
> Do.
 
![](http://material-design.storage.googleapis.com/images/components-tabs-usage-tabs_dont_10_large_mdpi.png)

> Don't.

### Tab characteristics

用一橫列來表示。

不可巢狀，頁籤中的內容不可由其他頁籤所構成。

一組頁籤至少有2個頁籤，最多不超過6個。

頁籤控制內容的顯示在一致性的位置。

目前顯示內容所對應的頁籤需要特別標示。

頁籤會被群組在一起，然後每一組頁籤依次和其內容做連結。

讓頁籤和其內容保持相連，可以維持二者關連性。當它們分的太開，二者的對應就會模糊不清。
 
![](http://material-design.storage.googleapis.com/images/components-tabs-usage-tabs_do_06_large_mdpi.png)

> Do.

![](http://material-design.storage.googleapis.com/images/components-tabs-usage-tabs_dont_06_large_mdpi.png)
 
> Don't.

![](http://material-design.storage.googleapis.com/images/components-tabs-usage-tabs_do_08_large_mdpi.png)
 
> Do.

![](http://material-design.storage.googleapis.com/images/components-tabs-usage-tabs_dont_08_large_mdpi.png)
 
> Don't.



## 內容

### 頁籤內容

不同頁籤之間和顯示在頁籤中的內容都可以包羅萬像。例，在一個頁籤中顯示不同年份的資料或不同的設定類型。

在一組頁籤中的內容應該建構在一個比較大的規則下（例，設定，方向），每個頁籤內容都是不同的。頁籤應該提供有意義的標籤，用來有邏輯的明確區分相關內容。

標籤可以使用圖示或文字，且文字不能被縮減。

避免需要跨頁籤的內容比較，顯著的跨頁籤內容對照，
可能會需要從不同的區塊中指示出內容。

![](http://material-design.storage.googleapis.com/images/components-tabs-content-tabs_15_large_mdpi.png)

> 不要縮減文字，如果使用固定式頁籤，文字太長，改用滑動式頁籤。
>
> 不要改變標籤大小，如果標籤太長，使用滑動式頁籤代替。
>
> 標籤不要使用二行文字，如果標籤太長，使用滑動式頁籤代替。
>
> 標籤不要混用文字和圖示，使用全部文字，或是全部圖示的標籤。

## 頁籤類型

依據裝置和使用情境不同，可以使用固定式頁籤或是滑動式頁籤。

### 固定式頁籤

固定式頁籤顯示全部的頁籤，需要從不同頁籤間快速切換內容時，是種最佳使用方式，例如：在地圖導航中切換不同交通工具。

頁籤的最大數量受限於可視寬度。每個頁籤有固定寬度，此寬度取決於標籤中的最大寬度。切換方式為觸碰該頁籤或是在內容區向左或向右滑動。

![](http://material-design.storage.googleapis.com/images/components-tabs-typesoftabs-tabs-spec-06_large_mdpi.png)

### 滑動式頁籤

在每次會顯示所有頁籤的其中一部份，可以包含較長的標籤和較多頁籤，
當使用者在瀏覽切換內容，不需直接對照標籤的時候，是種最佳使用方式。

切換方式為觸碰該頁籤，向左或向右滑動頁籤，或是向左或向右滑動內容區。

![](http://material-design.storage.googleapis.com/images/components-tabs-usage-tabs-spec-12_large_mdpi.png)

![](http://material-design.storage.googleapis.com/images/components-tabs-usage-tabs-spec-13_large_mdpi.png)

---

## 規格標準

### 固定式和全螢幕寬度

頁籤寬度：⅓ 螢幕寬度

頁籤指示：2 d p高

文字: 14 sp Roboto Medium 

文字在頁籤格裹置中

目前所在頁籤文字顏色： #fff 或次要顏色

不可點選的頁籤文字顏色：#fff 60%

![](http://material-design.storage.googleapis.com/images/components-tabs-typesoftabs-tabs-spec-04_large_mdpi.png)

### 可滑動式

頁籤寬度：12dp＋文字長度＋12dp

頁籤指示：2 d p高

文字: 14 sp Roboto Medium  

文字在頁籤格裹置中

目前所在頁籤文字顏色： #fff 或次要顏色

不可點選的頁籤文字顏色：#fff 60%

![](http://material-design.storage.googleapis.com/images/components-tabs-typesoftabs-tabs-spec-05_large_mdpi.png)

### 桌上型電腦/平版電腦

頁籤寬度：24dp＋文字長度＋24dp

頁籤指示：2 d p高

文字: 14 sp Tablet, 13 sp Desktop Roboto Medium 

目前所在頁籤文字顏色： #fff 或次要顏色

不可點選的頁籤文字顏色：#fff 60%

![](http://material-design.storage.googleapis.com/images/components-tabs-typesoftabs-tabs-spec-10_large_mdpi.png)

### 頁籤觸控的動畫

<video width="456" height="115" src="http://material-design.storage.googleapis.com/videos/components-tabs-spec-tabtouch-example_large_xhdpi.webm" controls=""></video>

> *翻譯：[Mkdodos](https://www.facebook.com/mkdodos)*
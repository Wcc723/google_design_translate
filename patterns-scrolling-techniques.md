# 捲動方式

## 捲動

### 以區塊為基礎

在設計捲動行為時，以區塊作為基礎來思考是有幫助的。這只是在腦海中的模型，並不會以任何看得到的互動方式呈現。

下面四個主要的區塊是用來協助建構捲動架構的應用程式列：

- 狀態列: 24dp
- 導覽列: 手機上是56dp，平板和桌上電腦是64dp
- 頁籤列/搜尋列: 48dp
- 彈性空間: 用來容納具有理想的長寬比例的圖片或延伸的應用程式列的空間


![](images/patterns/patterns_scrolling_scroll1.png)

![](images/patterns/patterns_scrolling_video1.png)

### 標準應用程式列

標準應用程式列的高度在手機上是56dp，而在較大的螢幕上是64dp。當捲動的時候有兩個選擇。

1. 應用程式列與內容可以捲動到螢幕之外，當用戶反方向捲動時則回到螢幕內。
2. 應用程式列可以固定在上方，讓內容在其下方捲動。

![](images/patterns/patterns_scrolling_scroll2.png)

<video controls="" width="360" height="640">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWV2x1WF9Wb29NX2c/patterns-scrollingtech-scrolling-070801_Standard_AppBar_xhdpi_003.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWbGpsUDgxN1VwX0U/patterns-scrollingtech-scrolling-070801_Standard_AppBar_xhdpi_003.mp4" type="video/mp4">
</video>

### 頁籤

標準應用程式列可以加以延伸來容納頁籤和一個搜尋輸入框。在腦海中使用區塊模型在決定捲動行為時是有幫助的。在這個例子中，你有兩個選擇：

1. 導覽列捲動到螢幕之外，頁籤列停留在最上方。
2. 應用程式列留在原地，內容在其下方捲動。

![](images/patterns/patterns_scrolling_scroll3.png)

<video controls="" width="360" height="640">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWV2x1WF9Wb29NX2c/patterns-scrollingtech-scrolling-070801_Standard_AppBar_xhdpi_003.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWbGpsUDgxN1VwX0U/patterns-scrollingtech-scrolling-070801_Standard_AppBar_xhdpi_003.mp4" type="video/mp4">
</video>

### 彈性空間

應用程式列是具彈性的，而且可以延伸以容納較大的版面或圖片。要延伸應用程式列的話，需要加上一個彈性空間。

1. 當只有導覽列存在的時候，彈性空間會縮小。導覽列內的標題也應該縮小到20sp。當捲動回去時，彈性空間與標題也再次回復原先位置。
2. 整個應用程式列捲動出螢幕之外。當用戶回捲時，導覽列回復成固定在頂部。當完全捲動回去時，彈性空間與標題也再次回復原先位置。

![](images/patterns/patterns_scrolling_scroll4.png)

<video controls="" width="360" height="640">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWcFhaV1hiSlB4aFU/patterns-scrollingtech-scrolling-070801_Flexible_Space_xhdpi_003.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWUGZzYXdKZWpDNWM/patterns-scrollingtech-scrolling-070801_Flexible_Space_xhdpi_003.mp4" type="video/mp4">
</video>


### 彈性空間與圖片

在應用程式列中使用圖片時，你可以使用彈性空間來容納想要的長寬比例。在此範例中長寬比是4:3。當捲動時，內容把圖片上推，因此彈性空間縮減了。圖片的最後20%彈性空間的顏色為加深後的應用程式主顏色。

![](images/patterns/patterns_scrolling_scroll5.png)

<video controls="" width="360" height="640">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWZ1F2b1pUOGFiZHc/patterns-scrollingtech-scrolling-070801_Flexible_Space_with_Image_xhdpi_002.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWWHR2eG5ITnZlMmM/patterns-scrollingtech-scrolling-070801_Flexible_Space_with_Image_xhdpi_002.mp4" type="video/mp4">
</video>






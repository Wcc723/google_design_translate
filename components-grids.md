# 網格
網格列表是基本視覺列表的其中一種，是用於表現不一樣的視覺呈現和排版。

>內容
>
>使用
>
>內容
>
>行為
>
>關鍵對齊線

## 使用

網格列表是最適合用於介紹**同性質的檔案**、典型的圖片，這樣的編排方式，有效提昇使用者在視覺上的閱讀和區分資料間的不同之處。

![](images/components/components-grids-usage-spec_grid_drawings_01_large_mdpi.png)

**網格列表**是一種棋盤狀的連續元素，每一個部分是由**資料框(cells)**內包含**資料塊(tiles)**

**資料框(Cells)** 垂直和水平排列在往格內。

**資料塊(Tiles)** 儲存內容，可在內部再劃分單個或多個資料框(Cells)。

![](images/components/components-grids-usage-spec_grid_drawings_02a_large_mdpi.png)
![](images/components/components-grids-usage-spec_grid_drawings_02b_large_mdpi.png)

如果在資料塊內的文字，需要跟主要內容做特別的區分，應該考慮使用不同的容器結構去包裝它，像是**列表(Lists)**或**區塊(Cards)**，那樣可以優化你的文字視覺，並在閱讀上更好理解。

**列表(Lists):** 讓閱讀上更好理解，特別在比較一組包含多種型態資料時。

**區塊(Cards):** 當內容與格式不一致的時候使用，舉個例子，圖片的標題長度、多樣化的資料集合，例如：可能也是圖片、影片、書籍的混在一起的內容。

---

## 內容
### 資料塊(tiles)內的內容

資料塊內容由主要內容和次要內容構成。主要內容是主要的區分元素，通常是圖片。次要內容可以是一段文字或是功能。

在主要內容避免缺少圖案的情況下，應該要有一個基本的預設圖案。

![](images/components/components-grids-content-spec_grid_drawings_03_large_mdpi.png)

### 資料塊內的功能

在主要或次要內容裡的功能執行時，放大、刪除或著是選擇，通常是不會有子選單在網格列表中出現(在動作執行時)。

動作執行後，可以開啟一個顯示區塊，例如懸浮的區塊或滑入區塊來做視覺上的呈現。

**主要動作:**

* 針對整個資料塊區域，而且不經由圖標(icon)或文字來觸發這個動作。
* 在特定網格區域內，針對相同的資料塊元素執行。例如，在網格內的所有資料塊的主要動作，皆是觀看內容圖片的相關訊息。

**輔助操作或內容:**

 * 代表在資料格內的圖標和文字。
 * 在特定網格區域內，針對相同的資料塊元素執行。
 * 在網格內所有的資料格下，但在定位上沒有一樣(在邊角或邊線內)，例如：所有的標題對齊格線的左下角

![](images/components/components-grids-content-spec_grid_drawings_04_large_mdpi.png)

---

## 行為
### 滾動

網格通常只做垂直滾動

水平滾動不是很好的一個方式，因為這種方式並不符合一般人的閱讀方式，很容易影響使用者體驗。

將超過滾動方向的溢出內容截掉。

![](images/components/components-grids-behavior-spec_grid_drawings_06_large_mdpi.png)

*截斷*
這是將溢出內容截斷的方式

![](images/components/components-grids-behavior-spec_grid_drawings_05_large_mdpi.png)

*未截斷*


### 手勢移動

資料塊滑動是不被允許的。整塊幅浮起來之後移動不是一個好的做法。

### 資料塊的篩選和排序

內容在網格裡可以用程式的方式去依照資料、檔案大小、字母順序或其他參數進行篩選或分類。

第一項從左上角開始，排列方式為由左至右，由上到下。

### 尺寸和大小調整

調整大小可為每列創造更多的空間，但資料塊沒有辦法填滿可用的左右空白。

網格列表在橫向的狀態下，並不會轉變成列表。網格列表和列表不同的資料型態各是不同的結構:圖像的優先權會大於文字。

---

## 關鍵對齊線
### 網格列表 表頭/表尾

#### 單列 表頭/表尾

高: 48 dp

文字內距: 16 dp

文字大小(預設): 16 sp

輔助操作是對齊右邊的表尾

#### 雙列 表頭/表尾

高: 68 dp

文字內距: 16 dp

字體大小(每行預設): 16sp/12sp or 14sp/14sp

![](images/components/components-grids-keylines-Grid_footer_overview_01a_large_mdpi.png)
![](images/components/components-grids-keylines-Grid_footer_overview_01b_large_mdpi.png)


### 只有圖片的網格列表

網格內距: 4 dp

資料格在網格表內可跨越多欄。

仔細考慮輔助文字是不是要在網格列表中出現，因為它會佔去非常多的空間，讓圖片得空間變小，單張圖片所呈現出來的視覺效果較為空曠舒適，比較不會有壓迫感。

![](images/components/components-grids-keylines-imageOnlyGrid_01_large_mdpi.png)

*元素*

![](images/components/components-grids-keylines-imageOnlyGrid_03_large_mdpi.png)

### 單行的網格列表

#### 只有文字

高: 48 dp

文字內距: 16 dp

文字大小(預設): 16sp

網格內距: 4 dp

![](images/components/components-grids-keylines-SingleLineGrid_01a_large_mdpi.png)

![](images/components/components-grids-keylines-SingleLineGrid_01b_large_mdpi.png)

*元素*

![](images/components/components-grids-keylines-SingleLineGrid_02_large_mdpi.png) 

*內容*

#### 文字和圖標

高: 48 dp

文字內距: 16 dp

文字大小(預設): 16sp

網格內距: 4 dp

輔助操作可以對齊右邊或左邊的表頭或表尾

![](images/components/components-grids-keylines-SingleLineGrid_03a_large_mdpi.png)

![](images/components/components-grids-keylines-SingleLineGrid_03b_large_mdpi.png)

![](images/components/components-grids-keylines-SingleLineGrid_03c_large_mdpi.png)

![](images/components/components-grids-keylines-SingleLineGrid_03d_large_mdpi.png)

*元素*

![](images/components/components-grids-keylines-SingleLineGrid_04_large_mdpi.png)


### 兩行的網格列表

#### 只有文字

高: 68 dp

文字內距: 16 dp

字體大小(每行預設):16sp/12sp or 14sp/14sp

網格內距: 4 dp

![](images/components/components-grids-keylines-TwoLineGrid_01a_large_mdpi.png)

![](images/components/components-grids-keylines-TwoLineGrid_01b_large_mdpi.png)

*元素*

![](images/components/components-grids-keylines-TwoLineGrid_02_large_mdpi.png)
 
*內容*

#### 文字和圖標

高: 68 dp

文字內距: 16 dp

字體大小(每行預設): 16sp/12sp or 14sp/14sp

這輔助操作可以對齊右邊或左邊的表頭或表尾

網格內距是 4 dp

![](images/components/components-grids-keylines-TwoLineGrid_03a_large_mdpi.png)

![](images/components/components-grids-keylines-TwoLineGrid_03b_large_mdpi.png)

![](images/components/components-grids-keylines-TwoLineGrid_03c_large_mdpi.png)

![](images/components/components-grids-keylines-TwoLineGrid_03d_large_mdpi.png)

*元素*

![](images/components/components-grids-keylines-TwoLineGrid_04_large_mdpi.png)

*內容*

#清單

清單是用來將多個項目，以垂直排列的方式，顯示成一個單一且連續的元素。

---
## 用法

一個**「清單」**是由一欄連續格狀化的子區塊 -- **「列」**所構成，而「列」的功能是當作**「磁磚」**的容器。

**「磁磚」**用來放置內容，且在一個清單中，每個「磁磚」的高度屬性可以不等。

![](images/components/components-lists-1_large_mdpi.png) 

![](images/components/components-lists-2_large_mdpi.png)

清單最適合用來呈現為了閱讀理解而進行最佳化的**「同性質資料或集合型資料」** -- 例如：多個圖片或文字，其目的是為了區分不同的資料類型或區分單一類型資料中不同的性質。

如果清單的磁磚裡的文字超過三行，則應使用「卡片」。

如果做為主要的識別內容是圖片，則應使用「網格清單」。

![](images/components/components-lists-3_large_mdpi.png)

---

## 內容

### 磁磚的內容

一個清單中的每個磁磚，可將具有關聯性的內容群組，以統一的格式呈現，並且透過提高同類型內容或者同群組內容的重要性，利用階層，加強內容可讀性。例如：將大頭照和文字描述的重要性，設定的比時間戳記高。這麼做可以幫助使用者更容易找到一個內容群組中的顯著資訊。

清單中的每個磁磚最多可放三行文字，同一個清單中，各個磁磚的字數可以不等。若要顯示三行文字以上，應使用「卡片」。

最具識別性的內容方向性，是向著磁磚的左側，且向著多行內容的第一行。

![](images/components/components-lists-4_large_mdpi.png)

### 磁磚的動作

一個清單的磁磚表面上的大部分面積，應該被用來執行主要動作。

因為動作並非清單磁磚中的可識別元素，所以輔助動作應該放置於磁磚的右側。

主要動作與輔助動作，例如：播放、放大、刪除和選擇，因為會被立即執行，所以一般並不會再顯示一個包含數個選項的子選單 (溢出清單的動作)。

動作可以打開一個後續的「檢視」，例如：「卡片」或者「滑入滑出卡片」。

![](images/components/components-lists-5_large_mdpi.png)

### 主要動作 

- 會佔滿整個磁磚，且不透過圖示或文字...等 (元素) 呈現。
- 在一個特定的清單中所有磁磚的動作是一樣的。例如，在一個音樂清單中，所有的磁磚的主要動作是播放歌曲；在郵件清單中，則是開啟並閱讀郵件。

### 輔助動作 

- 會透過磁磚中的圖示或次要文字...等 (元素) 呈現。
- 在一個特定清單的所有磁磚中，輔助動作的運作方式是一樣的。例如，可以從一個圖示看出某人是否處於上線狀態。
- 在一個特定清單的所有磁磚中，輔助動作的放置處也是一致的。

應避免在磁磚中利用輔助動作的重複性製造出 「視覺噪音」(譯註：煩人的)。例如在每個磁磚中都顯示「分享」動作。但是「切換開關」動作，例如星星圖示或大頭釘圖示可以被視為例外。因為他們顯示的狀態，可以提供有意義的資訊。

---

## 行為

### 捲動

清單只能垂直捲動。

### 手勢

清單中的各個磁磚，其「滑推」動作應該是一致的。  
當操作適當時，磁磚可以在清單和拖放目標之間移動（例如，將一個檔案移動到一個資料夾中）。  
當操作適當時，磁磚可以被抓起，並且在一個清單中手動重新排列順序。  

### 磁磚的過濾與排序

清單中的磁磚可以透過程式，以日期、檔案大小、字母順序或其他參數進行過濾和排序。

![](images/components/components-lists-6_large_mdpi.png)

可以這樣做。 (譯註：依照人名第一個字母排序。)

![](images/components/components-lists-7_large_mdpi.png)

不要這樣做。 (譯註：介面上看不出來排序的條件依據。)

---

## 排版線

在一個**「單行文字」**清單中，每個磁磚都包含單行文字。在同一個清單中，各個磁磚內的字數是可以不等的。

![](images/components/components-keylinesinlists-1_large_mdpi.png)

**元素**

![](images/components/components-keylinesinlists-2_large_mdpi.png)

**使用情境**

在一個**「雙行文字」**清單中，每個磁磚最多可包含兩行文字。在同一個清單中，各個磁磚內的字數是可以不等的。

![](images/components/components-keylinesinlists-3_large_mdpi.png)

**元素**

![](images/components/components-keylinesinlists-4_large_mdpi.png)

**使用情境**

在一個三行文字清單中，每個磁磚最多可包含三行文字。

在同一個清單中，各個磁磚內的字數是可以不等的。

![](images/components/components-keylinesinlists-5_large_mdpi.png)

**元素**

![](images/components/components-keylinesinlists-6_large_mdpi.png)

**使用情境**

### 單行文字清單

#### 僅有文字

字體: Roboto Regular 16 sp

磁磚高度: 48 dp

文字內間距: 16 dp

在清單的頂部和底部會(自動)增加 8 dp 的內距。唯一的例外是在清單頂部使用子標題，因為子標題已經有他們自己的內距了。

![](images/components/components-singlelinelists-1_large_mdpi.png)

**元素**

![](images/components/components-singlelinelists-2_large_mdpi.png)

**元素**

![](images/components/components-singlelinelists-6_large_mdpi.png)

**使用情境**

#### 帶有文字的圖示

字體: Roboto Regular 16 sp

磁磚高度: 48 dp

(畫面)左邊界到圖示的距離: 16 dp

(畫面)左邊界到文字的距離: 72 dp

文字上方與下方的內距: 16 dp

在清單的頂部和底部會(自動)增加 8 dp 的內距。唯一的例外是在清單頂部使用子標題，因為子標題已經有他們自己的內距了。

![](images/components/components-singlelinelists-7_large_mdpi.png)

**元素**

![](images/components/components-singlelinelists-8_large_mdpi.png)

**元素**

![](images/components/components-singlelinelists-3_large_mdpi.png)

**使用情境**

#### 帶有文字的大頭照

字體: Roboto Regular 16 sp

磁磚高度: 56 dp

(畫面)左邊界到大頭照的距離: 16 dp

(畫面)左邊界到文字的距離: 72 dp

文字上方與下方的內距: 20 dp

在清單的頂部和底部會(自動)增加 8 dp 的內距。唯一的例外是在清單頂部使用子標題，因為子標題已經有他們自己的內距了。

![](images/components/components-singlelinelists-7_large_mdpi.png)

**元素**

![](images/components/components-singlelinelists-8_large_mdpi.png)

**元素**

![](images/components/components-singlelinelists-11_large_mdpi.png)

**使用情境**

### 雙行文字清單

#### 僅有文字

主要文字字體: Roboto Regular 16 sp

次要文字字體: Roboto Regular 14 sp

磁磚高度: 72 dp

文字內距: 16 dp

在清單的頂部和底部會(自動)增加 8 dp 的內距。唯一的例外是在清單頂部使用子標題，因為子標題已經有他們自己的內距了。

![](images/components/components-recommendedtwolinelists-1_large_mdpi.png)

**元素**

![](images/components/components-recommendedtwolinelists-2_large_mdpi.png)

**元素**

![](images/components/components-recommendedtwolinelists-3_large_mdpi.png)

**使用情境**

#### 帶有文字的大頭照

主要文字字體: Roboto Regular 16 sp

次要文字字體: Roboto Regular 14 sp

磁磚高度: 72 dp

(畫面)左邊界到大頭照的距離: 16 dp

(畫面)左邊界到文字的距離: 72 dp

文字上方與下方的內距: 16 dp

圖示對準文字區域垂直置中。

在清單的頂部和底部會(自動)增加 8 dp 的內距。唯一的例外是在清單頂部使用子標題，因為子標題已經有他們自己的內距了。

![](images/components/components-recommendedtwolinelists-6_large_mdpi.png)

**元素**

![](images/components/components-recommendedtwolinelists-7_large_mdpi.png)

**元素**

![](images/components/components-recommendedtwolinelists-8_large_mdpi.png)

**使用情境**

#### 帶有文字和圖示的大頭照

主要文字字體: Roboto Regular 16 sp

次要文字字體: Roboto Regular 14 sp

磁磚高度: 72 dp

(畫面)左邊界到大頭照的距離: 16 dp

(畫面)左邊界到文字的距離: 72 dp

文字上方與下方的內距: 16 dp

(畫面)右邊界到圖示的距離: 16 dp

在清單的頂部和底部會(自動)增加 8 dp 的內距。唯一的例外是在清單頂部使用子標題，因為子標題已經有他們自己的內距了。

![](images/components/components-recommendedtwolinelists-9_large_mdpi.png)

**元素**

![](images/components/components-recommendedtwolinelists-10_large_mdpi.png)

**元素**

![](images/components/components-recommendedtwolinelists-11_large_mdpi.png)

**使用情境**

### 三行文字清單

#### 僅有文字

主要文字字體: Roboto Regular 16 sp

次要文字字體: Roboto Regular 14 sp

磁磚高度: 88 dp

文字內距: 16 dp

在清單的頂部和底部會(自動)增加 8 dp 的內距。唯一的例外是在清單頂部使用子標題，因為子標題已經有他們自己的內距了。

![](images/components/components-recommendedthreelinelists-1_large_mdpi.png)

**元素**

![](images/components/components-recommendedthreelinelists-2_large_mdpi.png)

**元素**

![](images/components/components-recommendedthreelinelists-3_large_mdpi.png)

**使用情境**

#### 帶有文字的大頭貼

主要文字字體: Roboto Regular 16 sp

次要文字字體: Roboto Regular 14 sp

磁磚高度: 88 dp

(畫面)左邊界到大頭照的距離: 16 dp

(畫面)右邊界到圖示的距離: 72 dp

大頭貼對齊主要文字上方。

在清單的頂部和底部會(自動)增加 8 dp 的內距。唯一的例外是在清單頂部使用子標題，因為子標題已經有他們自己的內距了。

![](images/components/components-recommendedthreelinelists-6_large_mdpi.png)

**元素**

![](images/components/components-recommendedthreelinelists-7_large_mdpi.png)

**元素**

![](images/components/components-recommendedthreelinelists-10_large_mdpi.png)

**使用情境**

#### 帶有文字和圖示的大頭貼

主要文字字體: Roboto Regular 16 sp

次要文字字體: Roboto Regular 14 sp

磁磚高度: 88 dp

(畫面)左邊界到大頭照的距離: 16 dp

(畫面)左邊界到文字的距離: 72 dp

文字上方與下方的內距: 16 dp

(畫面)右邊界到圖示的距離: 16 dp

大頭貼和圖示對齊主要文字上方。

在清單的頂部和底部會(自動)增加 8 dp 的內距。唯一的例外是在清單頂部使用子標題，因為子標題已經有他們自己的內距了。

![](images/components/components-recommendedthreelinelists-8_large_mdpi.png)

**元素**

![](images/components/components-recommendedthreelinelists-9_large_mdpi.png)

**元素**

![](images/components/components-recommendedthreelinelists-12_large_mdpi.png)

**使用情境**

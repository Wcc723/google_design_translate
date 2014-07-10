#清單

清單是用來將多個項目，以垂直排列的方式，顯示成一個單一且連續的元素。

---
## 用法

一個**「清單」**是由一欄連續格子化的子區塊 -- **「列」**所構成，而「列」的功能是作為**「磁磚」**的容器。

**「磁磚」**是用來放置內容，且在一個清單中，每個「磁磚」的高度屬性可以不等。

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

最顯著內容的方向性，是向著磁磚的左側，且向著多行內容的第一行。

![](images/components/components-lists-4_large_mdpi.png)

### 磁磚的動作

一個清單的磁磚表面上的大部分面積，應該被分配用來執行主要的動作。

因為動作並非清單磁磚中的顯著元素，所以輔助動作應該放置於磁磚的右側。

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

應避免在磁磚中利用輔助動作的重複性製造出 (煩人的)「視覺噪音」。例如在每個磁磚中都顯示「分享」動作。但是「切換開關」動作，例如星星圖示或大頭釘圖示可以被視為例外。因為他們顯示的狀態，可以提供有意義的資訊。

---

## 行為

### 捲動

清單只能垂直捲動。

### 手勢

清單中的各個磁磚，其「滑推」動作應該是一致的。
當操作適當時，磁磚可以在清單和拖放目標之間移動（例如，將一個檔案移動到一個資料夾中）。
當操作適當時，磁磚可以被抓起，並且在一個清單中手動重新排列順序。

### Tile filtering and sorting

List tiles can be programmatically sorted or filtered by date, file size, alphabetical order, or other parameters

![](images/components/components-lists-6_large_mdpi.png)

Do.

![](images/components/components-lists-7_large_mdpi.png)

Don't.

---

## Keylines

In a **single-line** list, each tile contains a single line of text. The amount of text can vary between tiles within the same list.

![](images/components/components-keylinesinlists-1_large_mdpi.png)

**Element**

![](images/components/components-keylinesinlists-2_large_mdpi.png)

**Context**

In a **two-line** list, each tile contains a maximum of two lines of text. The amount of text can vary between tiles within the same list.

![](images/components/components-keylinesinlists-3_large_mdpi.png)

**Element**

![](images/components/components-keylinesinlists-4_large_mdpi.png)

**Context**

In a three-line list, each tile contains a maximum of three lines of text.

The amount of text can vary between tiles within the same list.

![](images/components/components-keylinesinlists-5_large_mdpi.png)

**Element**

![](images/components/components-keylinesinlists-6_large_mdpi.png)

**Context**

### Single-line list

#### Text only

Font: Roboto Regular 16 sp

Tile height: 48 dp

Text padding: 16 dp

Add 8 dp padding at the top and bottom of a list. One exception is at the top of a list with a subheader, because subheaders contain their own padding.

![](images/components/components-singlelinelists-1_large_mdpi.png)

**Element**

![](images/components/components-singlelinelists-2_large_mdpi.png)

**Element**

![](images/components/components-singlelinelists-6_large_mdpi.png)

**Context**

#### Icon with text

Font: Roboto Regular 16 sp

Tile height: 48 dp

Left icon padding: 16 dp

Text left padding: 72 dp

Text top and bottom padding: 16 dp

Add 8 dp padding at the top and bottom of a list. One exception is at the top of a list with a subheader, because subheaders contain their own padding.

![](images/components/components-singlelinelists-7_large_mdpi.png)

**Element**

![](images/components/components-singlelinelists-8_large_mdpi.png)

**Element**

![](images/components/components-singlelinelists-3_large_mdpi.png)

**Context**

#### Avatar with text

Font: Roboto Regular 16 sp

Tile height: 56 dp

Left avatar padding: 16 dp

Text left padding: 72 dp

Text top and bottom padding: 20 dp

Add 8 dp padding at the top and bottom of a list. One exception is at the top of a list with a subheader, because subheaders contain their own padding.

![](images/components/components-singlelinelists-7_large_mdpi.png)

**Element**

![](images/components/components-singlelinelists-8_large_mdpi.png)

**Element**

![](images/components/components-singlelinelists-11_large_mdpi.png)

**Context**

### Two-line list

#### Text only

Primary text font: Roboto Regular 16 sp

Secondary text font: Roboto Regular 14 sp

Tile height: 72 dp

Text padding: 16 dp

Add 8 dp padding at the top and bottom of a list. One exception is at the top of a list with a subheader, because subheaders contain their own padding.

![](images/components/components-recommendedtwolinelists-1_large_mdpi.png)

**Element**

![](images/components/components-recommendedtwolinelists-2_large_mdpi.png)

**Element**

![](images/components/components-recommendedtwolinelists-3_large_mdpi.png)

**Context**

#### Avatar with text

Primary text font: Roboto Regular 16 sp

Secondary text font: Roboto Regular 14 sp

Tile height: 72 dp

Left avatar padding: 16 dp

Text left padding: 72 dp

Text top and bottom padding: 16 dp

Center-align icon with text area.

Add 8 dp padding at the top and bottom of a list. One exception is at the top of a list with a subheader, because subheaders contain their own padding.

![](images/components/components-recommendedtwolinelists-6_large_mdpi.png)

**Element**

![](images/components/components-recommendedtwolinelists-7_large_mdpi.png)

**Element**

![](images/components/components-recommendedtwolinelists-8_large_mdpi.png)

**Context**

#### Avatar with text and icon

Primary text font: Roboto Regular 16 sp

Secondary text font: Roboto Regular 14 sp

Tile height: 72 dp

Left avatar padding: 16 dp

Text left padding: 72 dp

Text top and bottom padding: 16 dp

Right icon padding: 16 dp

Add 8 dp padding at the top and bottom of a list. One exception is at the top of a list with a subheader, because subheaders contain their own padding.

![](images/components/components-recommendedtwolinelists-9_large_mdpi.png)

**Element**

![](images/components/components-recommendedtwolinelists-10_large_mdpi.png)

**Element**

![](images/components/components-recommendedtwolinelists-11_large_mdpi.png)

**Context**

### Three-line list

#### Text only

Primary text font: Roboto Regular 16 sp

Secondary text font: Roboto Regular 14 sp

Tile height: 88 dp

Text padding: 16 dp

Add 8 dp padding at the top and bottom of a list. One exception is at the top of a list with a subheader, because subheaders contain their own padding.

![](images/components/components-recommendedthreelinelists-1_large_mdpi.png)

**Element**

![](images/components/components-recommendedthreelinelists-2_large_mdpi.png)

**Element**

![](images/components/components-recommendedthreelinelists-3_large_mdpi.png)

**Context**

#### Avatar with text

Primary text font: Roboto Regular 16 sp

Secondary text font: Roboto Regular 14 sp

Tile height: 88 dp

Left avatar padding: 16 dp

Left text padding: 72 dp

Top-align avatar with primary text.

Add 8 dp padding at the top and bottom of a list. One exception is at the top of a list with a subheader, because subheaders contain their own padding.

![](images/components/components-recommendedthreelinelists-6_large_mdpi.png)

**Element**

![](images/components/components-recommendedthreelinelists-7_large_mdpi.png)

**Element**

![](images/components/components-recommendedthreelinelists-10_large_mdpi.png)

**Context**

#### Avatar with text and icon

Primary text font: Roboto Regular 16 sp

Secondary text font: Roboto Regular 14 sp

Tile height: 88 dp

Left avatar padding: 16 dp

Text left padding: 72 dp

Text top and bottom padding: 16 dp

Right icon padding: 16 dp

Top-align avatar and icon with primary text.

Add 8 dp padding at the top and bottom of a list. One exception is at the top of a list with a subheader, because subheaders contain their own padding.

![](images/components/components-recommendedthreelinelists-8_large_mdpi.png)

**Element**

![](images/components/components-recommendedthreelinelists-9_large_mdpi.png)

**Element**

![](images/components/components-recommendedthreelinelists-12_large_mdpi.png)

**Context**

#清單

清單是用來將多個項目，以垂直排列的方式，顯示成一個單一且連續的元素。

---
## 用法

一個**「清單」**是由一欄連續格狀化的子區塊 -- **「列」**所構成，而「列」的功能是作為**「磚塊」**的容器。


**Tiles** hold content, and can vary in height within a list.

**「磚塊」**是用來放制內容的，且在一個清單中，每個「磚塊」的高度屬性可以不等。

![](images/components/components-lists-1_large_mdpi.png) 

![](images/components/components-lists-2_large_mdpi.png)

Lists are best suited to presenting a **homogeneous data type or sets of data types**, such as images and text, optimized for reading comprehension, with the goal of differentiating between like data types or qualities within a single type of data.

If more than three lines of text needs to be shown in list tiles, use cards instead.

If the primary distinguishing content consists of images, use a grid list.

![](images/components/components-lists-3_large_mdpi.png)

---

## Content

### Tile content

List tiles present collections of related content in a consistent format, using hierarchy to enhance readability by prioritizing a consistent type or set of content. For example, emphasizing an avatar and text snippet over a time stamp. This helps users more easily find the distinguishing information they are looking for within the collection of content.

List tiles can contain up to three lines of text, and the amount of text can vary between tiles within the same list. To display more than 3 lines of text, use a card.

Bias the most distinguishing content in a tile towards the left side of the tile, and to the first line in a tile with multi-line content.

![](images/components/components-lists-4_large_mdpi.png)

### Tile actions

The majority of space on a list tile should be dedicated to the primary action.

Because actions are not distinguishing elements of list tiles, place supplemental actions on the right-hand side of the tile.

Primary and supplemental actions, such as play, zoom in, delete, and select, are immediate and typically do not have a submenu of options (action overflow) within the list.

Actions can open a subsequent view such as a card or hovercard.

![](images/components/components-lists-5_large_mdpi.png)

### Primary actions 

- Fill the entire tile, and therefore are not represented via icons, text, etc.
- Are consistent throughout tiles in a specific list. For example, the primary action for all tiles in a single list of music would be to play a song, or in a list of emails, to open to read an email.

### Supplemental actions 

- Are represented in tiles with icons, secondary text, etc.
- Are functionally consistent throughout tiles in a specific list, for example, an icon that indicates whether someone is online.
- Are placed in a consistent location within the tiles of a specific list.

Avoid creating visual noise by repeatedly using supplemental actions in tiles, for example, by displaying a share action in every tile. Toggles, such as stars or pins, are an exception because they provide meaningful information by displaying state.

---

## Behavior

### Scrolling

Lists scroll only vertically.

### Gestures

Per-tile swipe actions should be consistent within lists.
Where appropriate, tiles can be moved between a list and a drop target (for example, moving a file into a folder).
Where appropriate, tiles can be picked up and manually reordered within a list.

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

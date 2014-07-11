# 文字輸入框

Text fields allow the user to input text. They can be single line, with or without scrolling, or multi-line, and can have an icon. Touching a text field places the cursor and automatically displays the keyboard. In addition to typing, text fields allow for a variety of other tasks, such as text selection (cut, copy, paste) and data lookup via auto-completion. See Patterns > Selection for text selection design.

Text fields can have different types. The type determines what kind of characters are allowed inside the field and may prompt the virtual keyboard to optimize its layout for frequently used characters. Common types include number, text, email address, phone number, person’s name, username, URL, street address, credit card number, PIN, and search query.

--- 

## 單行文字框

Single-line fields automatically scroll their content to the left as the text input cursor reaches the right edge of the input field.

![](images/components/components-textfields-singlelinetextfields-textfields_single_03_large_mdpi.png)

![](images/components/components-textfields-singlelinetextfields-textfields_single_04_large_mdpi.png)

### 亮色主題 

- Hint and input font: Roboto Regular 16 sp
- Tile height: 48 dp
- Text top and bottom padding: 16 dp
- Text field divider padding: 8 dp

![](images/components/components-textfields-singlelinetextfields-textfields_single_06_large_mdpi.png)

### 暗色主題

![](images/components/components-textfields-singlelinetextfields-textfields_single_08_large_mdpi.png)

### 紅線

![](images/components/components-textfields-singlelinetextfields-textfields_redlines_03_large_mdpi.png)

### 包含圖示的亮色主題

- Hint and input font: Roboto Regular 16 sp
- Tile height: 48 dp
- Text top and bottom padding: 16 dp
- Text field divider padding: 8dp

![](images/components/components-textfields-singlelinetextfields-textfields_single_10_large_mdpi.png)

### 包含圖示的暗色主題

![](images/components/components-textfields-singlelinetextfields-textfields_single_12_large_mdpi.png)

### 紅線

![](images/components/components-textfields-singleline-redline_06_large_mdpi.png)

---

## 包含滾動的單行文字框

### Single-Line with Scrolling

When text input in a single-line field is long and spans multiple lines, the text field should scroll to accommodate the text.

In the scrolling text field, a graphical indicator appears below the line. Touching the ellipsis jumps the cursor back to the beginning of the string.

### 亮色主題

![](images/components/components-textfields-singlelinewithscrolling-textfields_single_scroll_03_large_mdpi.png)

### 暗色主題

![](images/components/components-textfields-singlelinewithscrolling-textfields_single_scroll_06_large_mdpi.png)

---

## 浮動文字

### 浮動的文字

With floating inline labels, when the user engages with the text input field, the labels move to float above the field.

![](images/components/components-textfields-floatinglabels-textfields_single_14_large_mdpi.png)

### 亮色主題

- Hint and input font: Roboto Regular 16 sp
- Label font: Roboto Regular 12 sp
- Tile height: 72dp
- Text top and bottom padding: 16dp
- Text field divider padding: 8dp

![](images/components/components-textfields-floatinglabels-textfields_single_17_large_mdpi.png)

### 暗色主題

![](images/components/components-textfields-floatinglabels-textfields_single_21_large_mdpi.png)

### 紅線

![](images/components/components-textfields-floatinglabels-redlines_08_large_mdpi.png)

---

## 多行輸入框

Multi-line text fields automatically break to a new line for overflow text and scroll vertically when the cursor reaches the lower edge.

![](images/components/components-textfields-multilinetextfield-textfields_multi_03a_large_mdpi.png)

![](images/components/components-textfields-multilinetextfield-textfields_multi_03b_large_mdpi.png)

### 亮色主題

- Hint and input font: Roboto Regular 16 sp
- Label font: Roboto Regular 12 sp
- Text top and bottom padding: 16 dp
- Text field divider padding: 8 dp

![](images/components/components-textfields-multilinetextfield-textfields_multi_06_large_mdpi.png)

### 暗色主題

![](images/components/components-textfields-multilinetextfield-textfields_multi_08_large_mdpi.png)

### 紅線

![](images/components/components-textfields-fullwidthtextfield-textfields_redlines_12_large_mdpi.png)

---

## 全寬輸入筐

Full-width text fields are useful for more in-depth tasks.

![](images/components/components-textfields-fullwidthtextfield-textfields_multi_10a_large_mdpi.png)

![](images/components/components-textfields-fullwidthtextfield-textfields_multi_10b_large_mdpi.png)

### 單行與多行輸入框

- Hint and input font: Roboto Regular 16 sp
- Top and bottom padding for text: 20 dp

![](images/components/components-textfields-fullwidthtextfield-textfields_multi_12_large_mdpi.png)

### 紅線

![](images/components/components-textfields-fullwidthtextfield-textfields_redlines_12_large_mdpi.png)

---

## 字元數

Use a character counter in fields where a character restriction is in place.

### 包含字元數的單行輸入框

Counter is Roboto Regular 12sp

![](images/components/components-textfields-charactercounter-textfields_counter_03a_large_mdpi.png)

![](images/components/components-textfields-charactercounter-textfields_counter_03b_large_mdpi.png)

### 包含字元數的多行輸入框

- Counter text: Roboto Regular 12 sp

![](images/components/components-textfields-charactercounter-textfields_counter_06a_large_mdpi.png)

![](images/components/components-textfields-charactercounter-textfields_counter_06b_large_mdpi.png)

![](images/components/components-textfields-charactercounter-textfields_counter_08_large_mdpi.png)

### 包含字元數的全寬輸入框

![](images/components/components-textfields-charactercounter-textfields_counter_14_large_mdpi.png)

![](images/components/components-textfields-charactercounter-textfields_counter_14b_large_mdpi.png)

![](images/components/components-textfields-charactercounter-textfields_counter_16_large_mdpi.png)

---

## 自動輸入文字輸入框

Use auto-complete text fields to present real-time suggestions or completions in popups, so users can enter information more accurately and efficiently.

![](images/components/components-textfields-autocompletetextfield-textfields_autocomplete_03a_large_mdpi.png)

![](images/components/components-textfields-autocompletetextfield-textfields_autocomplete_03b_large_mdpi.png)

### 全寬自動輸入框

![](images/components/components-textfields-autocompletetextfield-textfields_autocomplete_06_large_mdpi.png)

### 插入自動完成

![](images/components/components-textfields-autocompletetextfield-textfields_autocomplete_08a_large_mdpi.png)

![](images/components/components-textfields-autocompletetextfield-textfields_autocomplete_08b_large_mdpi.png)

![](images/components/components-textfields-autocompletetextfield-textfields_autocomplete_10_large_mdpi.png)

### Full-width inline auto-complete

![](images/components/components-textfields-autocompletetextfield-textfields_autocomplete_12a_large_mdpi.png)

![](images/components/components-textfields-autocompletetextfield-textfields_autocomplete_12b_large_mdpi.png)

![](images/components/components-textfields-autocompletetextfield-textfields_autocomplete_15_large_mdpi.png)

### In-line auto-complete

![](images/components/components-textfields-autocompletetextfield-textfields_autocomplete_18_large_mdpi.png)

---

## Search Filter

The app bar can act as a text input field. As the user types, the content underneath it is filtered and sorted.

![](images/components/components.textfields_search_filtering_A_large_mdpi.png)

![](images/components/components.textfields_search_filtering_B_large_mdpi.png)

### Full-width text field in app bar

![](images/components/components-textfields-searchfilter-textfields_filter_06_large_mdpi.png)
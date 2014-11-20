# 排版樣式

## Roboto

從Ice Cream Sandwich公開發佈消息後，Roboto一直是Android的標準字體，在這個版本中，Roboto更著重於廣泛地應用在各種不同的平台，將字體變得稍寬、稍圓了些，使它更加清晰，並使其閱讀更為舒適。Noto is also the standard typeface for all languages on Chrome OS.

To support all languages worldwide, Google recommends using Roboto for languages that use the Latin, Greek, and Cyrillic scripts and Noto for all other languages.

> [Roboto font](http://material-design.storage.googleapis.com/downloads/RobotoTTF.zip)
>
> *1.21 MB (.zip)*

> [Get Noto](http://www.google.com/get/noto)
> 
> Downloads are available for all languages in the Noto font family.

Roboto has been refined extensively to work across the wider set of supported platforms. It is slightly wider and rounder, giving it greater clarity and making it more optimistic.

![](images/style/style-typography-roboto-typography.roboto2_specimen_large_mdpi.png)

> Examples of Roboto


![](images/style/style_typography_roboto2.png)

> Roboto A-Z and numerals

Noto’s vertical metrics are compatible with Roboto.

![](http://material-design.storage.googleapis.com/publish/v_2/material_ext_publish/0Bx4BSt6jniD7dkhPdGplSzZhMnc/style_typography_noto1.png)

> Noto Sans CJK

![](http://material-design.storage.googleapis.com/publish/v_2/material_ext_publish/0Bx4BSt6jniD7TUFyTVc3SXRvNDQ/style_typography_noto2.png)

> Noto Sans Thai and Devanagari


### Language coverage

Roboto supports languages that use the Latin, Greek, and Cyrillic scripts, such as English, French, Greek, and Russian. In addition, Roboto has been extended to completely cover all Latin, Greek, and Cyrillic characters as defined in Unicode 7.0. The number of supported characters has doubled from previous releases, from about 2000 to about 4000 characters.

Noto covers all major living languages languages, including English, Greek, Russian, Arabic, Hebrew, Chinese, Japanese, and Korean (CJK), Hindi, Bengali, Georgian, Armenian, Thai, Lao, Khmer, and many others.


### Font weights

Roboto has six weights: Thin, Light, Regular, Medium, Bold, and Black.

![](http://material-design.storage.googleapis.com/publish/v_2/material_ext_publish/0Bx4BSt6jniD7ZHlGSHpsMjU5YmM/style_typography_weights1.png)

> Roboto font weights

Noto Sans CJK has seven weights: Thin, Light, DemiLight, Regular, Medium, Bold, and Black. The weight of Noto Sans CJK Regular is the same as Roboto Regular.

![](http://material-design.storage.googleapis.com/publish/v_2/material_ext_publish/0Bx4BSt6jniD7cTEyRlJubG4xVU0/style_typography_weights2.png)

> Noto Sans CJK font weights

Noto fonts for Thai, Devanagari, and all other major living languages have Regular and Bold weights.

![](http://material-design.storage.googleapis.com/publish/v_2/material_ext_publish/0Bx4BSt6jniD7cFNSY2RmY1VTa1E/style_typography_weights3.png)

> Noto Thai and Devanagari font weights


### Hinted fonts

Hints are the instructions embedded in a font on how to modify (distort) a glyph to look better on low-resolution displays. As a tradeoff, a hinted font consumes more space than the unhinted version.

Both Roboto and Noto have hinted and unhinted versions. Google recommends:

- Use the unhinted versions on Android and on Mac OS X, which doesn’t implement hints.
- Use hinted fonts on Chrome OS, Windows, and Linux.

### Font Stack

For both Android and web properties, the font stack should specify Roboto, Noto, and then sans-serif.


----

## 標準樣式

Typographic guidelines are provided for three categories of language scripts:

- **English and English-like**: Latin (except Vietnamese), Greek, Cyrillic, Hebrew, Armenian and Georgian
- **Tall**: Language scripts that require extra line height to accommodate larger glyphs. Includes South and Southeast Asian and Middle-Eastern languages, like Arabic, Hindi, Telugu, Thai, Vietnamese.
- **Dense**: Language scripts that require extra line height to accommodate larger glyphs but have different metrics from tall scripts. Includes Chinese, Japanese, and Korean.


### 文字大小與基本樣式


太多的文字尺寸與樣式可以摧毀任何一個版面，文字比例應該限制幾種大小使其在版面的隱藏格線中互相配合、對齊，基本的字體尺寸為12, 14, 16, 20, 以及 34。


**English-like**: 在文字使用的條件下，這些尺寸與樣式平衡了內文的密度以及閱讀的舒適，
文字尺寸指定伸縮像素(SP)可以使大尺寸的文字提高 [可訪問性](http://www.google.com/design/spec/usability/accessibility.html)。

**Tall**:

- Weight: Use Regular weight, as Medium weight is unavailable in Noto. In addition, Google recommends avoiding Bold weight, based on feedback from native speakers that Bold is too heavy.
- Font size: For Title through Caption styles, font size is 1 px larger than that specified for English. For styles larger than Title, the English type size is suitable.

**Dense**:

- Weight: Since Noto CJK has seven weights that match Roboto, use the same weight settings as English.
- Font size: For Title through Caption styles, the font size is 1 px larger than that specified for English. For styles larger than Title, the English type size is suitable.








![](images/style/style-typography1_large_mdpi.png)

![](images/style/style-typography2_large_mdpi.png)



> 使用 Display  樣式的範例

![](images/style/style-typography-8_large_mdpi.png)

![](images/style/style-typography4_large_mdpi.png)

> 使用 Headline 樣式的範例

![](images/style/style-typography5_large_mdpi.png)

English and English-like: Across form factors, text that appears in the app bar should use the Title style, Medium 20sp.

![](images/style/style-typography6_large_mdpi.png)



> 使用 Title 樣式的範例

![](images/style/style-typography7_large_mdpi.png)

有些時候大的 Subhead 樣式會使用較小的Body樣式來替代，
這些範例包括當資訊是介紹用途的一個小片段；
或當標題與 Body-styled 這行的文字是互相配對的時候。

![](images/style/style-typography-23_large_mdpi.png)


> 使用 Subhead  樣式的範例

![](images/style/style-typography9_large_mdpi.png)

![](images/style/style-typography10_large_mdpi.png)

> 使用 Body  樣式的範例

![](images/style/style-typography11_large_mdpi.png)

![](images/style/style-typography12_large_mdpi.png)

> 使用 Body  樣式的範例

![](images/style/style-typography13_large_mdpi.png)

Button style (Medium 14sp, all caps) is used for all buttons, whether they are ink or material.

![](images/style/style-typography14_large_mdpi.png)

> 使用 Button 樣式的範例

![](images/style/style-typography15_large_mdpi.png)

### 基本顏色/顏色對比

如果文字使用與背景相似的顏色，會非常難以閱讀，
使用太多高對比、奪目的顏色也會使文字不明顯，甚至難以閱讀，
尤其是針對黑色背景...

文字應該維持在4:5:1的最低限度比率對比(基於亮度值做計算)，針對易讀性，7:1的對比比率是最適合閱讀的。

這些顏色的組合都有經過對比比率的考慮，
為了非典型使用者的回應。

![](images/style/style-typography-16_large_mdpi.png)

![](images/style/style-typography-17_large_mdpi.png)

![](images/style/style-typography-18_large_mdpi.png)

![](images/style/style-typography-19_large_mdpi.png)

![](images/style/style-typography-20_large_mdpi.png)

### 大型字/流動文字

當正當的使用情況下，大型字可以使應用程式更有趣，在不同的版面當中，能夠幫助使用者更快的理解文章傳達的內容。

流動文字的大小樣式使用在專案來說文章的長度是未知的，流動文字的字型大小取決於可用的空間以及文字間距的計算。

強烈不建議慣用小型文字去符合一個糟糕的專案，
並依靠其作為退而求其次的最後手段。

![](images/style/style-typography-21_large_mdpi.png)

> 搭配 的範例

![](images/style/style-typography-22_large_mdpi.png)

![](images/style/style-typography-23_large_mdpi.png)

![](images/style/style-typography-24_large_mdpi.png)

### 行高

行高取決於各種獨特風格的樣式以及粗細，去呈現良好的可讀性以及適當的留白。
換行只適合用在內文、條目、首行文字，還有更小的顯示樣式，
其他的樣式則應該以單行的文字顯示。
 
English and English-like: see image.

- **Tall**:
	Line height is 0.1 em larger for Body 1 and Subhead 1. In English and English-like scripts, a gap between lines is an obvious straight white space. In the tall group of scripts, this gap is not sufficient. For Body 1 and Subhead 1, which have a relatively small line height in English, the lack of space is obvious. Therefore, the gap needs to be increased to ensure a line gap that is visually similar to English-like scripts.
- Very small line heights for Title and larger styles are adjusted to avoid clipping between characters with low descenders in one line and character with tall ascenders in the next line.

**Dense**:

Line height is 0.1 em larger for all styles. CJK ideographic characters use the entire em box, while English mostly uses a portion of the em box—often the lower portion below the x-height. Therefore, the actual gap between lines is smaller for CJK when the same line height is set. To achieve the same design intention as English for CJK, the line height needs to be larger than in English.

![](images/style/style_typography_styles_lineheight1.png)

> English and English-like type and leading


![](images/style/style_typography_styles_lineheight2.png)

> Pairing examples

![](images/style/style_typography_styles_lineheight3.png)

> Isolated examples — Increased line height


### 斷行規則/斷字

![](images/style/style_typography_styles_linebreaks1.png)

> 可行

![](images/style/style_typography_styles_linebreaks2.png)

> 不可行

### 單行字符長度

從Baymard學院我們在可讀性和行高考量了這些建議：

如果你希望有更好的閱讀體驗的話，
你應該要將每行的文字侷限在60個字以內，
控制每行文字在適當的量是良好閱讀性的最佳關鍵。

太寬 - 如果一行的文字太長，使用者必須長時間聚焦在文字上，
這是因為那樣的長度很難讓人快速領會哪邊是開頭、哪邊是結尾，
此外他可能會使在大區塊裡正確行內的文字裡連續性上變得困難。

太窄 - 如果單行文字太短，會使得使用者的眼睛必須時常來回閱讀，
打斷了閱讀的良好韻律，短行的文字也趨向壓迫閱讀者，
使他們在閱讀完重要的部分之前就開始下一段。
(因此反而跳過了隱含重要的關鍵字)

來源：[Readability: the Optimal Line Length](http://baymard.com/blog/line-length-readability)

![](images/style/style-typography-34_large_mdpi.png)

> - 太窄
> - 理想範圍
> - 太寬

![](images/style/style_typography_styles_linelengths2.png)

> - 太窄
> - 理想範圍
> - 太寬

### 和字距調整

![](images/style/style-typography-36_large_mdpi.png)

> *翻譯： Tillonter*

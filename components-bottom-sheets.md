#底部工作表

呈現在按鈕下方一組操作動作的工作表，從畫面下方邊緣向上滑動。按鈕工作表在顯示上提供更彈性清楚及簡單的操作。

**內容**

>[用法](#usage)
>
>[內容](#content)
>
>[行為](#behavior)
>
>[規格](#specs)


<h2 id='usage'>用法<h4>

底部工作表特別適用於在三個以上的操作，並且此操作功能不需要描述很多細節。如果功能只有兩個或更少的操作或者細節描述，請考慮使用菜單或對話框代替。

底部工作表可以當作是 `列表樣式` 或 `網格樣式`。以網格形式佈局增加了視覺有避免含糊不清的現象。

您可以使用底部工作表顯示與其他應用程式的關係，或者允許進入到其他應用程式 （透過應用程式圖示）

---

<h2 id='content'>內容<h4>

在標準的列表形式的底部工作表，每個動作應該要有一個文字描述以及靠左對齊的圖示。必要時你可以使用分隔符號分類群組的動作。你也可以選擇使用副標題或標題定義上下文

網格形式的底部工作表是一種可滾動捲軸方式，其中是包含標準的操作圖示。

![components-bottomsheet-for-mobile-1a_large_mdpi](images/components/components-bottomsheet-for-mobile-1a_large_mdpi.png)

![components-bottomsheet-for-mobile-1b_large_mdpi.png](images/components/components-bottomsheet-for-mobile-1b_large_mdpi.png)

---

<h2 id='behavior'>行為<h4>

當顯示底部工作表時，它應該是從螢幕底部邊緣向上滑動的動畫。在使用者選擇底部工作表中的上下文及模組的時候，原先的畫面將變暗淡。輕擊變暗的區域將關閉工作表，並且從工作表上向下滑動回去。若工作表初始項目顯示許多操作，此工作表是可滾動捲軸的方式呈現。滾動時將拉起工作表容器，最終將覆蓋整個螢幕。當此動作覆蓋了整個螢幕時，將會在標頭的左方增加一個關閉按鈕。

---

<h2 id='specs'>規格<h4>

提供字體和顏色的規格以及紅線輔助於行動裝置應用程式。

![images/components/components-bottomsheets-content-actionsheet_12_large_mdpi](images/components/components-bottomsheets-content-actionsheet_12_large_mdpi.png)

紅線為列表樣式表頭

![components-bottomsheets-content-actionsheet_12b_large_mdpi](images/components/components-bottomsheets-content-actionsheet_12b_large_mdpi.png)

![components-bottomsheets-content-bottomsheet_10a_large_mdpi](images/components/components-bottomsheets-content-bottomsheet_10a_large_mdpi.png)

![components-bottomsheets-content-bottomsheet_10b_large_mdpi](images/components/components-bottomsheets-content-bottomsheet_10b_large_mdpi.png)

![components-bottomsheets-content-actionsheet_20_large_mdpi](images/components/components-bottomsheets-content-actionsheet_20_large_mdpi.png)

紅線為網格樣式底部工作表，此包含一套標準動作提供給不同應用程式使用。

![](images/components/components-bottomsheets-content-actionsheet_20b_large_mdpi.png)
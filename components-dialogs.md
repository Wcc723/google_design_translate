# 對話框

對話框的提示是讓使用者決定或者在完成一個任務所需要的額外訊息。這樣的請求範圍從簡單的 取消/確定 的決定到更複雜的佈局要求使用者調整設定或者輸入文字。

> 內容
>
> 使用
>
> 內容
> 
> 動作
> 
> 行為

## 使用

對話框通常用於提示使用者做出一個具體的決定或者一個任務或處理。它們可以用來通知使用者具體的問題，以確定重要的操作，或者允許使用者繼續之前所交代的事件。

若是有複雜的操作是需要有特別描述，可能就不適合使用對話框。

![](images/components/components-dialogs-usage-dialog_03_large_mdpi.png)

對話框包含一個可選的 **標題**，對話框內容以及動作。

標題需要簡要的描述目前被選擇的類型。標題是可選擇的，應該在必要時的時候使用它。

**內容** 作為可以做決定的描述。

**動作** 使用者能夠透過確認一個選擇並且繼續進行處理。

![](images/components/components-dialogs-usage-dialogs_07_large_mdpi.png)

### 按鈕寬度及內距的指南

![](images/components/components-buttons-buttonsindialogs_large_mdpi.png)

![](images/components/components-dialogs-usage-dialogs_07a_large_mdpi.png)

![](images/components/components-dialogs-usage-dialogs_07b_large_mdpi.png)

### 全寬按鈕的堆疊

當文字標籤在按鈕上超過最大寬度，您可以使用堆疊的方式將按鈕擺放以容納文字。

![](images/components/components-dialogs-usage-stackedfullwidthbuttonsa_large_mdpi.png)

### 並排的按鈕

如果每一個文字沒有超過全寬的按鈕，那麼建議使用並排的方式排列，就像常用的確定/取消按鈕。

![](images/components/components-dialogs-usage-sidebysidebuttonsa_large_mdpi.png)

![](images/components/components-dialogs-usage-sidebysidebuttonsb_large_mdpi.png)

---

## 內容

### 對話框標題

對話框的標題是可選擇的，並且可以清楚地描述正在做的決定。例如，指示對話框或透過識別哪些將會受到的決定，例如，設定。

對話框的標題應該總是被顯示出來。

### 對話框內容

對話框的內容是可以廣泛的，不過通常包括本文 和/或 UI 控制元件，並且在特定的任務聚焦或者是處理的部分。就像是確認資料是否刪除或者選擇一個設定。

![](images/components/components-dialogs-content-dialogs_03a_large_mdpi.png)

![](images/components/components-dialogs-content-dialogs_03b_large_mdpi.png)

---

## 動作

### 對話框動作

對話框呈現出一種集中及有限度的一套動作。也就是一般在肯定或否定的選擇。

肯定的動作通常放在右側，並且是會持續的處理該過程。肯定的動作也可能是破壞性的，就像是刪除或移除。

否定的動作通常放在左側，並將使用者退回到過程中的初始化畫面或者前一個步驟。

動作可以是並排的方式擺放，或者如果需要更大的空間可以使用垂直的方式堆疊按鈕。

否定或是肯定動作的文字可以是 取消/確定，也可以是更具體的動詞或動詞詞組來表示決定的結果。
 
![](images/components/components-dialogs-actions-dialogs_11_large_mdpi.png)

--- 

## 行為

### 滾動

對話框是主要文件的內容及沒有滾動的主要文件是分開的。

如果可能的話，在對話框中應該是不滾動的。過多的滾動可能表示內容會有與不同的容器及呈現上有更多的服務，不過如果內容不滾動，也代表著內文及 UI 元件是被切斷的。

![](images/components/components-dialogs-behavior-dialogs_12_large_mdpi.png)

### 手勢

手勢接觸到對話框的外部，將關閉對話框

### 對話框焦點

對話框總是完全在螢幕上。對話框總是保持的焦點的目標，直到被確認或是被否定的要求動作。（比如選擇一個設定）

---

> *翻譯：[Weiju Tu](https://www.facebook.com/weiju516)*
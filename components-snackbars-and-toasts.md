# Snackbars and Toasts

Snackcbars是使用者在進行一項操作後，螢幕提供的簡短回饋，出現在行動裝置螢幕底部，或桌上型電腦螢幕左下方的小型彈出式視窗中。他們位在所有螢幕元素-包括浮動式動作按鈕-之上。

Snackcbars在出現一段時間後，或是使用者於螢幕其他位置進行操作時會自動消失，亦可以滑動螢幕來進行刪除。他們不會阻擋所在螢幕的資訊輸入，且無法接收焦點輸入(input focus)。建議一次在螢幕上只顯示一個Snackbar。

Android系統也提供了膠囊形狀的toast，主要用來呈現系統訊息。Toasts和snackbars相似，但前者不包含動態功能，亦無法透過滑動從螢幕上去除。

## 用法

### 非常簡短的文字字串

Snackbars通常應該維持在足以容納一行字串的高度即可，且字串內容應與使用者進行的操作直接相關。它們不應該包含一般或動態的icons。動作以文字的方式呈現。

![](images/components/components-toasts-usage-spec_toast_do_20_large_mdpi.png)

> 請這麼做

![](images/components/components-toasts-usage-spec_toast_dont_20_large_mdpi.png)

> 別這麼做

### 暫時性

為了達到可用性，snackbars不應包含進入主要使用步驟(use case)的唯一路徑。因為snackbars位於螢幕所有元素之上，因此他們不應該持續出現於螢幕或產生堆疊的情形。

![](images/components/components-toasts-usage-spec_toast_do_22_large_mdpi.png)

> 請這麼做

![](images/components/components-toasts-usage-spec_toast_dont_22_large_mdpi.png)

> 別這麼做

### 無或有的動作訊息(0-1 actions)，不出現解除或取消

如果在螢幕上呈現一個動作訊息，遵循對話方塊的空間配置及支援規則。當有兩個或更多動作時，即便其中有解除的動作(dismiss action)，應使用對話方塊而非snackbar。如果snackbars中描述的動作訊息，其重要性需要阻擋到螢幕的使用，它應該以對話方塊呈現。

![](images/components/components-toasts-usage-spec_toast_do_24_large_mdpi.png)

> 請這麼做

![](images/components/components-toasts-usage-spec_toast_dont_24_large_mdpi.png)

> 別這麼做

### 不要阻擋到浮動式的動作按鈕

垂直移動浮動式的動作按鈕，提供足以容納snackbar高度的空間。

![](images/components/components-toasts-usage-spec_toast_do_26_large_mdpi.png)

> 請這麼做

![](images/components/components-toasts-usage-spec_toast_dont_26_large_mdpi.png)

> 別這麼做



## 設計說明

### 行動裝置的snackbar

- 單行snackbar高度：48dp
- 多行snackbar高度：80dp
- 文字內容：Roboto字體 Regular 14 sp
- 動作按鈕：Roboto字體 Medium 14 sp, 文字以全大寫呈現
- 預設背景填色：#323232 100%

![](images/components/components-toasts-specs-spec_toast_03_1_large_mdpi.png)

![](images/components/components-toasts-specs-spec_toast_03_2_large_mdpi.png)

<video width="360" height="640" src="http://material-design.storage.googleapis.com/videos/components-snackbars-and-toasts-specs-snackbar.single.line-dismissal_large_xhdpi.webm" controls=""></video>

![](images/components/components-toasts-3-spec_toast_06_large_mdpi.png)

### 平板/桌上型電腦的snackbar

- 單行snackbar高度：48dp
- 最小寬度：288dp
- 最大寬度：568dp
- 2dp的圓角
- 文字內容：Roboto字體 Regular 14 sp
- 動作按鈕：Roboto字體 Medium 14 sp, 文字以全大寫呈現
- 預設背景填色：#323232 100%

![](images/components/components-toasts-specs-snackbar_toast_08_large_mdpi.png)

![](images/components/components-toasts-specs-snackbar_toast_10_large_mdpi.png)

![](images/components/components-toasts-specs-spec_toast_12_large_mdpi.png)

<video controls="" width="512" height="284" >
<source src="//material-design.storage.googleapis.com/videos/components-snackbars-and-toasts-specs-snackbar.tablet-time.out_large_xhdpi.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/videos/components-snackbars-and-toasts-specs-snackbar.tablet-time.out_large_xhdpi.mp4" type="video/mp4">
</video>

### Android toast

開發者可以製作自訂的toasts，及(或)自訂的螢幕配置方式。如果要製作自訂的toast，強烈鼓勵您依照上述提供的snackbar樣式進行製作。

![](images/components/components-toasts--specs-snackbar_toast_14_large_mdpi.png)

![](images/components/components-toasts-specs-snackbar_toast_16_large_mdpi.png)

![](images/components/components-toasts-specs-spec_toast_18_large_mdpi.png)

 > 翻譯：Xunyi

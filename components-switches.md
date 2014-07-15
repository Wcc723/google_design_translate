# 開關

開關提供選項以便讓使用者進行選擇的動作。共有三種類型的開關：核取方塊、選項按鈕和切換開關。

注意：在接下來的例子中的(半透明的)圓形，是代表一個(操作)動畫，並非按鈕實際的外觀。

---

## 核取方塊

核取方塊可以讓使用者從一組選項中進行多選。

假如您必須在一個清單中顯示多個「開/關」選項，使用核取方塊是一個節省空間的好方法。

但是如果您只有一個「開/關」選項，請避免使用核取方塊，而應該使用切換開關就好。

透過將一個方框換成一個勾選記號，這種操作勾選的動作，令人感到更滿意、更直接。

核取方塊使用動畫來表示是否取得焦點以及被按下的狀態。

<video width="360" height="640" src="http://material-design.storage.googleapis.com/videos/components-switches-checkbox-spec_checkbox_large_xhdpi.webm" controls=""></video>

> Checkbox motion

![](images/components/components-switches-checkbox-switches_07a_large_mdpi.png)

![](images/components/components-switches-checkbox-switches_07b_large_mdpi.png)

---

## 選項按鈕

選項按鈕可以讓使用者從一組選項中進行單選。如果您認為使用者需要一口氣看到所有選項展開排列，請使用選項按鈕提供單一選擇。

否則，請考慮使用一個下拉元件，其佔用的空間比把所有選項展開顯示來得少。

選項按鈕使用動畫來表示是否取得焦點以及被按下的狀態。

<video width="360" height="640" src="http://material-design.storage.googleapis.com/videos/components-switches-radiobutton-spec_radio_large_xhdpi.webm" controls=""></video>

> Radio motion

![](images/components/components-switches-radio_02_large_mdpi.png)

![](images/components/components-switches-radiobutton-radio_spec_12a_large_mdpi.png)

---

## 切換開關

切換開關可以反覆地切換單一選項的狀態。該開關控制的選項及它所切換的狀態，必須很明確地與行內標籤一致。此外，切換開關也採用了與選項按鈕相同的外觀屬性。(譯註：都是圓形)

切換開關使用動畫來表示是否取得焦點以及被按下的狀態。

在切換開關滑桿旁顯示 “on” 和 “off” 字樣的做法已經被廢除，請以下圖所示的開關取代。

![](images/components/components-switches-switch-switches_spec_03_large_mdpi.png)

![](images/components/components-switches-radio_switches_spec_03_dark_large_mdpi.png)

<video width="360" height="640" src="http://material-design.storage.googleapis.com/videos/components-switches-switch-switches_spec_03_large_xhdpi.webm" controls=""></video>

![](images/components/components-switches-switch-switches_spec_10a_large_mdpi.png)

![](images/components/components-switches-switch-switches_spec_10b_large_mdpi.png)

Use the outer radial expansion only on form factors that favor finger touch, where interaction may obstruct the element completely. For desktop usage with a mouse, you do not need this extra indication.

![](images/components/components-switches-switch-mobile-fingertouch_large_mdpi.png)

![](images/components/components-switches-switch-desktop-fingertouch_large_mdpi.png)

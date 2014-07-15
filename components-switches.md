# 開關

開關提供選項以便讓使用者進行選擇的動作。共有三種類型的開關：核取方塊、選項按鈕和 on/off 開關。

注意：在接下來的例子中的(半透明的)圓形，是代表一個(操作)動畫，並非按鈕實際的外觀。

---

## 核取方塊

核取方塊可以讓使用者從一組選項中進行多選。

假如您必須在一個清單中顯示多個「開/關」選項，使用核取方塊是一個節省空間的好方法。

但是如果您只有一個「開/關」選項，請避免使用核取方塊，而應該使用 on/off 開關就好。

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

On/off switches toggle the state of a single settings option. The option that the switch controls, as well as the state it’s in, should be made clear from the corresponding inline label. Switches will take on the same visual properties of the radio button.

Switches use animation to communicate focus and pressed states.

The on/off slide toggle with the words “on” and “off” baked within the asset is deprecated. Use the switch shown here instead.

![](images/components/components-switches-switch-switches_spec_03_large_mdpi.png)

![](images/components/components-switches-radio_switches_spec_03_dark_large_mdpi.png)

<video width="360" height="640" src="http://material-design.storage.googleapis.com/videos/components-switches-switch-switches_spec_03_large_xhdpi.webm" controls=""></video>

![](images/components/components-switches-switch-switches_spec_10a_large_mdpi.png)

![](images/components/components-switches-switch-switches_spec_10b_large_mdpi.png)

Use the outer radial expansion only on form factors that favor finger touch, where interaction may obstruct the element completely. For desktop usage with a mouse, you do not need this extra indication.

![](images/components/components-switches-switch-mobile-fingertouch_large_mdpi.png)

![](images/components/components-switches-switch-desktop-fingertouch_large_mdpi.png)

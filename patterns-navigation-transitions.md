# 導覽式動畫

導覽式動畫只有當用戶在應用程式中從某一狀態被帶領到另一個狀態才會發生，像是從縱觀的視角轉換到細節的視角或是任務完成的視角。大部份的動畫自然而然地是階層式的，但是非階層式的動畫也會發生。

這些短暫的時間對於用戶經驗來說是很重要的。仔細的考量用戶的使用過程來決定什麼動畫在什麼時候使用。不同的動畫在不同情形下都是合適的。

## 從parent到child

一個最重要的動畫是當用戶"往下鑽探"到內容時。這可以想成是從parent到child的動畫，因為這很自然是階層式的。

在material design中，一個從parent到child的動畫是以高度的變化來做顯示。用戶觸碰的表面或表面所在的區域應該從它本來的位置上昇並且擴展。此動作帶領用戶從A點到B點，同時應該強調原來位置和目的位置。利用material動作曲線來實作，這一切應該感覺上要是自然與熟悉的，因為從原來位置擴展和移動感覺上很符合邏輯。


<video id="1-None_0B2wX4iIvu8L6OG5GWnBqWFFRdVU" width="760" height="420" controls="">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B2wX4iIvu8L6UjZvd0w1MmdQVWs/patterns_navigational-transitions_parent-to-child_list-01_xhdpi.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B2wX4iIvu8L6OG5GWnBqWFFRdVU/patterns_navigational-transitions_parent-to-child_list-01_xhdpi.mp4" type="video/mp4">
</video>


## 從sibling到sibling

非階層式的動畫與階層式動畫的表現方式不同。你可以把非階層式動畫想成從sibling到sibling。

一個這類動畫的範例是當用戶在一排頁籤中移動時。這時候沒有高度變化，頁籤的內容、表面都停留在同一個高度。新的內容從右邊滑進來並且把它的sibling推出畫面左側。

<video id="1-None_0B2wX4iIvu8L6bDNpdXBkdElHWDg" width="760" height="420" controls="">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B2wX4iIvu8L6bXdoMlplMWtMeWs/patterns_navigational-transitions_sibling-to-sibling_tabs-01_xhdpi.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B2wX4iIvu8L6bDNpdXBkdElHWDg/patterns_navigational-transitions_sibling-to-sibling_tabs-01_xhdpi.mp4" type="video/mp4">
</video>

> Sibling動畫

> *翻譯： [Sean Chen](https://www.facebook.com/shihneng.chen)*

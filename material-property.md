# Material特性

<h2>Material有特定不可變動的特性與繼承來的行為。了解這些特質可以幫助你在material design的觀點下一致性地操作material。</h2>

**內容**

>[物理特性](#physicalproperties)
>
>[Material的變形](#transformingmaterial)
>
>[Material的動作](#movementofmaterial)

<h2 id='physicalproperties'>物理特性</h2>

Material有<b>兩個不同的維度x與y</b>（以dps為單位）和一個<b>統一的厚度</b>（1dp）。Material絕對不會有厚度為0的情況。

![components-whatismaterial_environment_3d_mdpi](../images/components/components-whatismaterial_environment_3d_mdpi.png)

![components-whatismaterial_materialproperties_physicalproperties_thickness_01_yes_mdpi](../images/components/components-whatismaterial_materialproperties_physicalproperties_thickness_01_yes_mdpi.png)
Do.
Material的寬與高可以不同

![components-whatismaterial_materialproperties_physicalproperties_thickness_02_no_mdpi](../images/components/components-whatismaterial_materialproperties_physicalproperties_thickness_02_no_mdpi.png)
Don't.
Material永遠都是1dp厚

Material會投射陰影。

陰影是因為material元素間在z軸上的不同高度自然產生的。

<video id="1-None_0B0NGgBg38lWWRWJfTERvdnM1bGc" crossorigin="anonymous" preload="metadata" loop tabindex="0" width="760" height="360">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWSE9IaUpqYzlpSW8/whatismaterial-materialprop-physicalprop-020201_PaperShadow_Do_xhdpi_007.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWRWJfTERvdnM1bGc/whatismaterial-materialprop-physicalprop-020201_PaperShadow_Do_xhdpi_007.mp4" type="video/mp4">
</video>
Do.
Material投射陰影

Don't
陰影大小永遠不會用material來做估計

內容以不同形狀與顏色顯示在material上。內容不會增加material的厚度。

內容的行為可以和material的行為分離。然而material的邊界可以限制內容的呈現範圍。

Material是固體。

輸入的事件不會穿透material。

多個material元素不能同時佔據空間上的同一點。

Material不能穿透其他material。

舉例來說，一個material表單不能在變換高度時穿透另一個material表單。



<h2 id='transformingmaterial'>Material的變形</h2>



<h2 id='movementofmaterial'>Material的動作</h2>

# Material特性

**內容**

>[物理特性](#physicalproperties)
>
>[Material的變形](#transformingmaterial)
>
>[Material的動作](#movementofmaterial)

<h2 id='physicalproperties'>物理特性</h2>

Material有兩個不同的**維度x與y**（以dps為單位）和一個**統一的厚度**（1dp）。Material**絕對不會**有厚度為0的情況。

![whatismaterial_materialproperties_physicalproperties_thickness_01_yes](images/whats-material/whatismaterial_materialproperties_physicalproperties_thickness_01_yes.png)
> Do.
>
> Material的寬與高可以不同

![whatismaterial_materialproperties_physicalproperties_thickness_02_no](images/whats-material/whatismaterial_materialproperties_physicalproperties_thickness_02_no.png)
> Don't.
>
> Material永遠都是1dp厚

Material會投射陰影。

陰影是因為material元素間在z軸上的不同高度自然產生的。

<video id="whatismaterial-materialprop-physicalprop-020201_PaperShadow_Do_xhdpi_007" width="760" height="360" controls="">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWSE9IaUpqYzlpSW8/whatismaterial-materialprop-physicalprop-020201_PaperShadow_Do_xhdpi_007.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWRWJfTERvdnM1bGc/whatismaterial-materialprop-physicalprop-020201_PaperShadow_Do_xhdpi_007.mp4" type="video/mp4">
</video>

> Do.
>
> Material投射陰影

<video id="whatismaterial-materialprop-physicalprop-020201_PaperShadow_Dont_xhdpi_007" width="760" height="360" controls="">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWYU5lQ1VXQjA3NnM/whatismaterial-materialprop-physicalprop-020201_PaperShadow_Dont_xhdpi_007.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWM0xqQms4LWRkMVE/whatismaterial-materialprop-physicalprop-020201_PaperShadow_Dont_xhdpi_007.mp4" type="video/mp4">
</video>

> Don't.
>
> 陰影大小永遠不會用material來做估計

內容以不同形狀與顏色顯示在material上。內容不會增加material的厚度。

<video id="whatismaterial-materialprop-physicalprop-020201_InkDisplay_xhdpi_005" width="760" height="360" controls="">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWTG41Rk9fT19qUXc/whatismaterial-materialprop-physicalprop-020201_InkDisplay_xhdpi_005.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWSGQycHdwcTdyRk0/whatismaterial-materialprop-physicalprop-020201_InkDisplay_xhdpi_005.mp4" type="video/mp4">
</video>

> Do.
>
> Material 可以顯示各種形狀與顏色。

內容的行為可以被從 material 中抽離。但是， material 的邊界可以限制內容的顯示。

<video id="whatismaterial-materialprop-physicalprop-020201_InkBehavior_xhdpi_005" width="760" height="360" controls="">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWeVBlbExGYjlTeEE/whatismaterial-materialprop-physicalprop-020201_InkBehavior_xhdpi_005.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWVzltT01CSHpaNXM/whatismaterial-materialprop-physicalprop-020201_InkBehavior_xhdpi_005.mp4" type="video/mp4">
</video>

> Do.

Material是固體。

輸入的事件不會穿透material。

![whatismaterial_properties_physical3](images/whats-material/whatismaterial_properties_physical3.png)

> Do.

![whatismaterial_properties_physical4](images/whats-material/whatismaterial_properties_physical4.png)

> Don't.

多個material元素不能同時佔據空間上的同一點。

![whatismaterial_properties_physical5](images/whats-material/whatismaterial_properties_physical5.png)

> Do.

![whatismaterial_properties_physical6](images/whats-material/whatismaterial_properties_physical6.png)

> Don't.

Material不能穿透其他material。

舉例來說，一個material表單不能在變換高度時穿透另一個material表單。

![whatismaterial_properties_physical7](images/whats-material/whatismaterial_properties_physical7.png)
Don't.

<h2 id='transformingmaterial'>Material的變形</h2>

Material可以改變形狀。

<video id="whatismaterial-materialprop-transformingmaterial-020202_PaperShape_xhdpi_004" width="760" height="360" controls="">
    <source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWd2N5R1lqeUFwWkk/whatismaterial-materialprop-transformingmaterial-020202_PaperShape_xhdpi_004.webm" type="video/webm">
    <source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWSkpqVG1NajV6MjA/whatismaterial-materialprop-transformingmaterial-020202_PaperShape_xhdpi_004.mp4" type="video/mp4">
</video>

Material只和它所在的平面一起變大與縮小。

<video id="whatismaterial-materialprop-transformingmaterial-020202_PaperShapeLinear_xhdpi_004" width="760" height="360" controls="">
    <source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWWFFOVGp2UFVNZzg/whatismaterial-materialprop-transformingmaterial-020202_PaperShapeLinear_xhdpi_004.webm" type="video/webm">
    <source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWenFrem90Wlk4MFk/whatismaterial-materialprop-transformingmaterial-020202_PaperShapeLinear_xhdpi_004.mp4" type="video/mp4">
</video>

> Do.

Material絕對不會彎曲或對折。

<video id="whatismaterial-materialprop-transformingmaterial-020202_PaperBendFold_xhdpi_005" width="760" height="360" controls="">
    <source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWNktzeE04V0ZGNzg/whatismaterial-materialprop-transformingmaterial-020202_PaperBendFold_xhdpi_005.webm" type="video/webm">
    <source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWUHg1YkxJMXJXZ2s/whatismaterial-materialprop-transformingmaterial-020202_PaperBendFold_xhdpi_005.mp4" type="video/mp4">
</video>

> Don't.

Material表單可以結合在一起成為一個單一的 material 表單。

<video id="whatismaterial-materialprop-transformingmaterial-020202_PaperHeal_xhdpi_003" width="760" height="360" controls="">
    <source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWbE1WWExWSURmTDg/whatismaterial-materialprop-transformingmaterial-020202_PaperHeal_xhdpi_003.webm" type="video/webm">
    <source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWeUNMSk02cnYtc1k/whatismaterial-materialprop-transformingmaterial-020202_PaperHeal_xhdpi_003.mp4" type="video/mp4">
</video>

當分裂後，material會回復。例如如果你從一個material表單上移除了一部份，那個material表單會再一次回復成一個完整的表單。

<video id="whatismaterial-materialprop-transformingmaterial-020202_PaperSplitHeal_xhdpi_004" width="760" height="360" controls="">
    <source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWX0dIVXh2QzlwcVU/whatismaterial-materialprop-transformingmaterial-020202_PaperSplitHeal_xhdpi_004.webm" type="video/webm">
    <source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWc2Y2QTRmbUFLLUE/whatismaterial-materialprop-transformingmaterial-020202_PaperSplitHeal_xhdpi_004.mp4" type="video/mp4">
</video>

<h2 id='movementofmaterial'>Material的動作</h2>

Material可以自發地在環境中的任何地方產生或消滅。

<video id="whatismaterial-materialprop-movementmaterial-020203_PaperPointExpand_xhdpi_004" width="760" height="360" controls="">
    <source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWWWhMRFVudjl4bTQ/whatismaterial-materialprop-movementmaterial-020203_PaperPointExpand_xhdpi_004.webm" type="video/webm">
    <source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWQml4UFAxREJEQVE/whatismaterial-materialprop-movementmaterial-020203_PaperPointExpand_xhdpi_004.mp4" type="video/mp4">
</video>

Material可以沿著任何軸線移動。

<video id="whatismaterial-materialprop-movementmaterial-020203_PaperMove_xhdpi_007" width="760" height="360" controls="">
    <source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B2wX4iIvu8L6Y2Z1NUlzMWczaHc/whatismaterial-materialprop-movementmaterial-020203_PaperMove_xhdpi_007.webm" type="video/webm">
    <source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B2wX4iIvu8L6eDRlc0E2MWd0SlU/whatismaterial-materialprop-movementmaterial-020203_PaperMove_xhdpi_007.mp4" type="video/mp4">
</video>

z軸上的移動是一個典型的用戶與material互動的結果。

<video id="whatismaterial-materialprop-movementmaterial-020203_Material_Response_xhdpi_002" width="760" height="360" controls="">
    <source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWNW5xUERVcEd1bm8/whatismaterial-materialprop-movementmaterial-020203_Material_Response_xhdpi_002.webm" type="video/webm">
    <source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWRWROZkxDS2JySG8/whatismaterial-materialprop-movementmaterial-020203_Material_Response_xhdpi_002.mp4" type="video/mp4">
</video>

> *翻譯： [Sean Chen](https://www.facebook.com/shihneng.chen)*

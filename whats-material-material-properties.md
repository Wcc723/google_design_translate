# Material properties

Material has certain immutable characteristics and inherent behaviors. Understanding these qualities will help you manipulate material in a way that’s consistent with the vision of material design.

## Physical properties

Material has **varying x & y dimensions** (measured in dps) and a **uniform thickness** (1dp). Material **never** has a thickness of 0.

![](images/whats-material/whatismaterial_materialproperties_physicalproperties_thickness_01_yes.png)

> Do.
>
> The height and width of material can vary.

![](images/whats-material/whatismaterial_materialproperties_physicalproperties_thickness_02_no.png)

> Don't.
>
> Material is always 1dp thick.

Material casts shadows.

Shadows result naturally from the relative elevation (z-position) between material elements.

<video id="1-None_0B0NGgBg38lWWRWJfTERvdnM1bGc" width="760" height="360" controls="">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWSE9IaUpqYzlpSW8/whatismaterial-materialprop-physicalprop-020201_PaperShadow_Do_xhdpi_007.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWRWJfTERvdnM1bGc/whatismaterial-materialprop-physicalprop-020201_PaperShadow_Do_xhdpi_007.mp4" type="video/mp4">
</video>

> Do.
>
> Material casts shadows.

<video id="1-None_0B0NGgBg38lWWM0xqQms4LWRkMVE" width="760" height="360" controls="">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWYU5lQ1VXQjA3NnM/whatismaterial-materialprop-physicalprop-020201_PaperShadow_Dont_xhdpi_007.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWM0xqQms4LWRkMVE/whatismaterial-materialprop-physicalprop-020201_PaperShadow_Dont_xhdpi_007.mp4" type="video/mp4">
</video>

> Don't.
> 
> Shadows are never approximated using material.

Content is displayed on material, in any shape and color. Content does not add thickness to material.

<video id="1-None_0B0NGgBg38lWWSGQycHdwcTdyRk0" width="760" height="360" controls="">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWTG41Rk9fT19qUXc/whatismaterial-materialprop-physicalprop-020201_InkDisplay_xhdpi_005.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWSGQycHdwcTdyRk0/whatismaterial-materialprop-physicalprop-020201_InkDisplay_xhdpi_005.mp4" type="video/mp4">
</video>

> Do.
>
> Material can display any shape and color.

Content behavior can be decoupled from the behavior of material. However, the bounds of the material can limit the display of the content.


<video id="1-None_0B0NGgBg38lWWVzltT01CSHpaNXM" width="760" height="360" controls="">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWeVBlbExGYjlTeEE/whatismaterial-materialprop-physicalprop-020201_InkBehavior_xhdpi_005.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWVzltT01CSHpaNXM/whatismaterial-materialprop-physicalprop-020201_InkBehavior_xhdpi_005.mp4" type="video/mp4">
</video>

> Do.

Material is solid.

Input events cannot pass through material.

![](images/whats-material/whatismaterial_properties_physical3.png)

> Do.

![](images/whats-material/whatismaterial_properties_physical4.png)

> Don't.

Multiple material elements cannot occupy the same point in space simultaneously.

![](images/whats-material/whatismaterial_properties_physical5.png)

> Do.

![](images/whats-material/whatismaterial_properties_physical6.png)

> Don't.

Material cannot pass through other material.

For example, one sheet of material cannot pass through another sheet of material when changing elevation.

![](images/whats-material/whatismaterial_properties_physical7.png)

> Don't.

----

## Transforming material

Material can change shape.

<video id="1-None_0B0NGgBg38lWWSkpqVG1NajV6MjA" width="760" height="360" controls="">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWd2N5R1lqeUFwWkk/whatismaterial-materialprop-transformingmaterial-020202_PaperShape_xhdpi_004.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWSkpqVG1NajV6MjA/whatismaterial-materialprop-transformingmaterial-020202_PaperShape_xhdpi_004.mp4" type="video/mp4">
</video>

Material grows and shrinks along only its plane.

<video id="1-None_0B0NGgBg38lWWenFrem90Wlk4MFk" width="760" height="360" controls="">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWWFFOVGp2UFVNZzg/whatismaterial-materialprop-transformingmaterial-020202_PaperShapeLinear_xhdpi_004.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWenFrem90Wlk4MFk/whatismaterial-materialprop-transformingmaterial-020202_PaperShapeLinear_xhdpi_004.mp4" type="video/mp4">
</video>

> Do.

Material never bends or folds.

<video id="1-None_0B0NGgBg38lWWUHg1YkxJMXJXZ2s" width="760" height="360" controls="">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWNktzeE04V0ZGNzg/whatismaterial-materialprop-transformingmaterial-020202_PaperBendFold_xhdpi_005.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWUHg1YkxJMXJXZ2s/whatismaterial-materialprop-transformingmaterial-020202_PaperBendFold_xhdpi_005.mp4" type="video/mp4">
</video>

> Don't.

Sheets of material can join together to become a single sheet of material.

<video id="1-None_0B0NGgBg38lWWeUNMSk02cnYtc1k" width="760" height="480" controls="">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWbE1WWExWSURmTDg/whatismaterial-materialprop-transformingmaterial-020202_PaperHeal_xhdpi_003.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWeUNMSk02cnYtc1k/whatismaterial-materialprop-transformingmaterial-020202_PaperHeal_xhdpi_003.mp4" type="video/mp4">
</video>

When split, material can heal. For example, if you remove a portion of material from a sheet of material, the sheet of material will become a whole sheet again.

<video id="1-None_0B0NGgBg38lWWc2Y2QTRmbUFLLUE" width="760" height="480" controls="">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWX0dIVXh2QzlwcVU/whatismaterial-materialprop-transformingmaterial-020202_PaperSplitHeal_xhdpi_004.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWc2Y2QTRmbUFLLUE/whatismaterial-materialprop-transformingmaterial-020202_PaperSplitHeal_xhdpi_004.mp4" type="video/mp4">
</video>

-----


## Movement of material

Material can be spontaneously generated or destroyed anywhere in the environment.

<video id="1-None_0B0NGgBg38lWWQml4UFAxREJEQVE" width="760" height="350" controls="">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWWWhMRFVudjl4bTQ/whatismaterial-materialprop-movementmaterial-020203_PaperPointExpand_xhdpi_004.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWQml4UFAxREJEQVE/whatismaterial-materialprop-movementmaterial-020203_PaperPointExpand_xhdpi_004.mp4" type="video/mp4">
</video>

Material can move along any axis.

<video id="1-None_0B2wX4iIvu8L6eDRlc0E2MWd0SlU" width="760" height="480" controls="">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B2wX4iIvu8L6Y2Z1NUlzMWczaHc/whatismaterial-materialprop-movementmaterial-020203_PaperMove_xhdpi_007.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B2wX4iIvu8L6eDRlc0E2MWd0SlU/whatismaterial-materialprop-movementmaterial-020203_PaperMove_xhdpi_007.mp4" type="video/mp4">
</video>

Z-axis motion is typically a result of user interaction with material.

<video id="1-None_0B0NGgBg38lWWRWROZkxDS2JySG8" width="760" height="350" controls="">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWNW5xUERVcEd1bm8/whatismaterial-materialprop-movementmaterial-020203_Material_Response_xhdpi_002.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B0NGgBg38lWWRWROZkxDS2JySG8/whatismaterial-materialprop-movementmaterial-020203_Material_Response_xhdpi_002.mp4" type="video/mp4">
</video>


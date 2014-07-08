#Grids
Grid lists are an alternative to standard list views. Grid lists are distinct from grids used for layouts and other visual presentations.


>Contents
>
>Usage
>
>Content
>
>Behavior
>
>Keylines

##Usage

A grid list is best suited to presenting a **homogeneous data type**, typically images, and is optimized for **visual comprehension** and differentiating between like data types.

![](images/components/components-grids-usage-spec_grid_drawings_01_large_mdpi.png)

A **grid list** is a continuous element consisting of tessellated, regular subdivisions called **cells** that contain **tiles**.

**Cells** are arrayed vertically and horizontally within the grid.

**Tiles** hold content, and can span one or more cells vertically or horizontally.

![](images/components/components-grids-usage-spec_grid_drawings_02a_large_mdpi.png)
![](images/components/components-grids-usage-spec_grid_drawings_02b_large_mdpi.png)

If the text in tiles needs to be prominent enough to distinguish between primary content pieces, consider using a different container, like a list or cards, that is optimized for displaying text and facilitating reading comprehension.

**Lists:** Optimized for reading comprehension, particularly when comparing a set of data containing multiple data types.

**Cards:** Used for content with inconsistent formatting, for example, photos with captions of variable length, or data sets with heterogeneous content, for example, a mixed collection of photos and videos and books.

---

##Content
###Content in tiles

Tile content consists of primary content and secondary content. Primary content is the main differentiating element, typically an image. Secondary content can be an action or text.

Provide a default image for tiles that lack an image for primary content.

![](images/components/components-grids-content-spec_grid_drawings_03_large_mdpi.png)

###Actions in tiles

Actions on both primary and secondary content—such as play, zoom in, delete, or select—are immediate and typically do not result in a submenu of options (action overflow) within the grid list.

Actions can open a subsequent view such as a card or hovercard.

**Primary actions:**

* Fill the entire tile and therefore are not represented via icons or text
* Are consistent throughout tiles in a specific grid. For example, the primary action for all tiles in a single grid could be to view details for an image.

**Secondary actions or content:**

 * Are represented in tiles with icons or text.
 * Are consistent throughout tiles in a specific grid.
 * Are placed in a consistent location within the tiles of a specific grid, but that consistent location may vary between grids (at corners or edges). For example, all titles in a grid could be located at the bottom left corner.

![](images/components/components-grids-content-spec_grid_drawings_04_large_mdpi.png)

---

##Behavior
###Scrolling

Grids typically scroll only vertically.

Horizontally scrolling grids are discouraged because the scrolling interferes with typical reading patterns, impacting comprehension.

Cut off grid tiles to communicate the scroll direction for content overflow.

![](images/components/components-grids-behavior-spec_grid_drawings_06_large_mdpi.png)

*Do.*
Indicate content overflow by cutting off grid tiles.

![](images/components/components-grids-behavior-spec_grid_drawings_05_large_mdpi.png)

*Don't.*


###Gestures

Per-tile swipe actions are not permitted. Pick-up-and-move actions are discouraged.

###Tile filtering and sorting

Content in a grid list can be programmatically filtered or sorted by date, file size, alphabetical order, or other parameters.

The first item in the grid is positioned in the top left of the grid and the order proceeds left to right and top to bottom.

###Dimensions and resizing

Resizing a grid list will cause the tiles to re-sort as horizontal space becomes available. Tiles do not scale to fill available horizontal space.

A grid list does not transform into a list when horizontal space contracts. Grid lists and lists are separate structures for emphasizing different data types: prioritizing images over text versus prioritizing text over images.

---

##Keylines
###Grid list header/footers

####Single-line header/footer

Height: 48 dp

Text padding: 16 dp

Default font size: 16 sp

Secondary action is flush right to the footer.

####Two-line header/footer

Height: 68 dp

Text padding: 16 dp

Default font size for each line: 16sp/12sp or 14sp/14sp

![](images/components/components-grids-keylines-Grid_footer_overview_01a_large_mdpi.png)
![](images/components/components-grids-keylines-Grid_footer_overview_01b_large_mdpi.png)


###Image-only grid list

Grid padding: 4 dp

Tiles in grid lists can span multiple columns.

Carefully consider whether secondary text is needed in grid lists that use multi-column tiles, as larger tiles can develop significant empty space.

![](images/components/components-grids-keylines-imageOnlyGrid_01_large_mdpi.png)

*Element*

![](images/components/components-grids-keylines-imageOnlyGrid_03_large_mdpi.png)

###Single-line grid list

####Text only

Height: 48 dp

Text padding: 16 dp

Default font size: 16sp

Grid padding: 4 dp

![](images/components/components-grids-keylines-SingleLineGrid_01a_large_mdpi.png)

![](images/components/components-grids-keylines-SingleLineGrid_01b_large_mdpi.png)

*Element*

![](images/components/components-grids-keylines-SingleLineGrid_02_large_mdpi.png) 

*Context*

####Text with icon

Height: 48 dp

Text padding: 16 dp

Default font size: 16sp

Grid padding: 4 dp

The secondary action can be flush right or flush left within the footer or header.

![](images/components/components-grids-keylines-SingleLineGrid_03a_large_mdpi.png)

![](images/components/components-grids-keylines-SingleLineGrid_03b_large_mdpi.png)

![](images/components/components-grids-keylines-SingleLineGrid_03c_large_mdpi.png)

![](images/components/components-grids-keylines-SingleLineGrid_03d_large_mdpi.png)

*Element*

![](images/components/components-grids-keylines-SingleLineGrid_04_large_mdpi.png)


###Two-line grid list

####Text only

Height: 68 dp

Text padding: 16 dp

Default font size for each line:16sp/12sp or 14sp/14sp

Grid padding: 4 dp

![](images/components/components-grids-keylines-TwoLineGrid_01a_large_mdpi.png)

![](images/components/components-grids-keylines-TwoLineGrid_01b_large_mdpi.png)

*Element*

![](images/components/components-grids-keylines-TwoLineGrid_02_large_mdpi.png)
 
*Context*

####Text with icon

Height: 68 dp

Text padding: 16 dp

Default font size for each line: 16sp/12sp or 14sp/14sp

The secondary action can be flush right or flush left within the footer or header.

Grid padding is 4 dp

![](images/components/components-grids-keylines-TwoLineGrid_03a_large_mdpi.png)

![](images/components/components-grids-keylines-TwoLineGrid_03b_large_mdpi.png)

![](images/components/components-grids-keylines-TwoLineGrid_03c_large_mdpi.png)

![](images/components/components-grids-keylines-TwoLineGrid_03d_large_mdpi.png)

*Element*

![](images/components/components-grids-keylines-TwoLineGrid_04_large_mdpi.png)

*Context*

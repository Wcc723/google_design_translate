# 結構

## UI 區域及導覽


這個章節包含手機到桌面應用程式其中的幾點指導方針。

應用程式的款式相當多，是為了滿足不同的需求，舉例來說：


應用程序，其主要目的是沒有更深的導航不同的活動之間切換（如電話撥號器提供收藏，最近和聯繫人）

- 專門處理單一個行為的應用程式(像是計算機、相機、還有一些遊戲)
- 主要用來處理不同行為的應用程式，而並沒有更深入的操作(像是電話簿、聯絡人、最近的通話)
- 包含一個廣泛的數據以及深度的導覽(像是有不同資料夾的郵件工具或是購物的應用程式)

你的應用程式結構，是來自於內容以及想要呈現給使用者的功能。

### 從上方開始

啟動畫面的佈局需要格外注意，這是人們在啟動應用程式所看到的第一個畫面，所以要讓新舊訪客擁有相同的使用者體驗。

試問你自己：“一般的使用者將怎樣去使用我的應用程式”，而這將會是你開始畫面的依據。


將內容轉發。許多應用程序集中的內容顯示。避免導航僅屏幕，而是讓人們通過使內容的開始屏幕的中心找到您的應用程序的核心體驗的時候了。選擇佈局，在視覺上具有吸引力和適當的數據類型和屏幕尺寸。

**將內容擺前面。**許多應用程式專注在內容的顯示。避免螢幕只有顯示導覽，而是讓人們透過啟動畫面就了解你們的應用程式核心概念。以具吸引力的視覺、適合的數據及不同螢幕尺寸來選擇畫面的佈局。

**導航及操作。**像是任何的工具列，工具欄可以整合各種重要的功能。理想呈現導覽選項的位置，就是將它放在螢幕的頂端。如果你的內容可以被搜索，工具欄內就包含搜尋功能吧，這樣人們可以透過導航快速切換不同的層級

**重視的功能。**，當你的應用程式擁有大量的功能及內容，指引用戶去關注產品重要的環節。突顯內容的重點，把最有特色功能放在浮動功能的按鈕。別強調應用程式少用的功能。


### 索引頁策略 (TOP-LEVEL VIEW STRATEGIES)

*譯者：TOP-LEVEL VIEW 是應用程式進入後的第一個階層[參考](http://developer.android.com/design/patterns/app-structure.html)，雖然和索引頁意思並不相同，但為了翻譯順暢，這裡翻譯做"索引頁"*

索引頁是主要介紹應用程式功能的區域，有些應用程式容易被關注，且有適度的導航；其他應用程式索引頁會存在許多的畫面，而你必須確保使用者可以透過這些導覽找到他們的需求。

選擇最好的且符合你應用程式的導航。

**專注一個被嵌入的導覽視點。**所有必要的連結都放置在導覽上，提高導航的可見度。當應用程式導覽很簡單的情況下，這或許是適當的，然而，在大量的連結顯示在導覽時，這可能會減少內容顯示的空間；而且這些路徑可能被分佈在整個螢幕，而不是容易被預測和方便的位置。


以下情形請用上下文的導覽：

- 應用程式有強烈的主視覺，且沒有(甚至很少)的替代方案。

- 透過主要的畫面，使用者能夠完成大部份常用工作。

- 你期待使用者會是不常使用這應用程式，而是注重這些連結。

**使用頁籤來切換數量不多，且同等重要的內容。**如果應用程式只有少數的功能區，每個功能的層次也不多，就使用頁籤來切換每個不同的索引頁內容。不僅可以快速切換不同的內容，且能透過點擊或是滑動來將內容顯示出來。然而這些頁籤，小顯示器上也要夠為顯著，且適用在少數且簡潔外觀的標簽上。

以下情況建議使用頁籤：

- 你期待使用者會很頻繁的切換內容。
- 索引頁內容總數是有被限制住的。
- 你想要使用者會關注這些交互的內容。

**透過左方導覽面板來管理複雜的結構。**在左方導覽面板能夠同時顯示大量的導航目標。在應用程式中有種單一功能的特別有用，"回首頁"，還有側欄面板還能作為一個較少使用的索引。如果應用程式需要直接從另一個重要的區塊切換過來，從應用程式的左方滑動面版，來切換不同的內容是很有效率的。然而，由於它沒有一個直覺的提示，它需要使用者花些時間去熟悉它。

以下情況建議使用側面導覽面板(navigation drawer)：

- 應用程式有大量的索引頁內容
- 你希望應用程式能夠在不同的內容中切換，即使他們沒有直接關係
- 應用程式中有較深層的架構，需要加速回到應用程式的頂層。
- 你希望降低一些不常使用的連結能見度。


無論你選擇怎樣的索引頁，導覽都是有效在不同資料中切換。有些範例是提供連結在一首音樂與同歌手的不同音樂中切換，或者是在最近的項目以及完整歷史資料中切換，或者是從一篇文章中連結其他相關資料。這些連結提供一個平台，使內容延伸到另一個相關的。

### 手機

手機的結構上包含一個總是存在的應用程式列，以及浮動操作按鈕。而底部可以增加一個按鈕來附加額外的功能。側欄選單當使用者使用時，它可以覆蓋其他的元素。

![](http://material-design.storage.googleapis.com/images/layout-structure-uiregions-uiregions-01_large_xhdpi.png)

### 平板

平板的結構總是會存在浮動操作按鈕，而工具欄是繼承平板和手機的元素，底部可以增加一個按鈕來附加額外的功能。側欄選單當使用者使用時，它可以覆蓋其他的元素。右方的導覽可以暫時或是永久固定的呈現。


![](http://material-design.storage.googleapis.com/images/layout-structure-uiregions-uiregions-02_large_xhdpi.png)

### 桌面

這個結構總是會存在著浮動操作按鈕，而工具欄是繼承平板和手機的底部元素。視窗的的功能鍵可以被併入工具欄。側邊的導覽選單可以暫時或是永久固定的呈現。側邊選單針對內容可以有它們第二個工具欄，用來顯示標籤、樣式、或是次級的操作。


![](http://material-design.storage.googleapis.com/images/layout-structure-uiregions-uiregions-03_large_xhdpi.png)

### UI 規範

定義一個主要的水平或垂直線。

![](http://material-design.storage.googleapis.com/images/layout-structure-uiregions-uiregions-04_large_xhdpi.png)

> 避免分割過多的區域，這樣可能會導致L型佈局。而我們可以用空白去規劃次要的區域。

![](http://material-design.storage.googleapis.com/images/layout-structure-uiregions-uiregions-05_large_xhdpi.png)


> 利用卡片及懸浮操作按鈕來突破邊線。

![](http://material-design.storage.googleapis.com/images/layout-structure-uiregions-uiregions-06_large_xhdpi.png)

> 當需要特定的行為或是資訊內容需要明顯的分割時，
可以利用卡片去組織內容，這會比分割線或空白更為適合。

![](http://material-design.storage.googleapis.com/images/layout-structure-uiregions-uiregions-07_large_xhdpi.png)

## 工具欄

工具欄的用途很多，可以應用在各種地方，已是可以參考一些工具欄的使用範例。


![](http://material-design.storage.googleapis.com/images/layout-structure-toolbars-toolbars-01_large_xhdpi.png)

> 全寬，預設高度的工具欄

![](http://material-design.storage.googleapis.com/images/layout-structure-toolbars-toolbars-02_large_xhdpi.png)


> 全寬, 高度延伸超過複數的欄寬

![](http://material-design.storage.googleapis.com/images/layout-structure-toolbars-toolbars-03_large_xhdpi.png)

> 再多層次結構的欄寬工具欄

![](http://material-design.storage.googleapis.com/images/layout-structure-toolbars-toolbars-04_large_xhdpi.png)

> 可伸縮的工具欄及卡片式工具欄

![](http://material-design.storage.googleapis.com/images/layout-structure-toolbars-toolbars-05_large_xhdpi.png)

> 浮動工具欄

![](http://material-design.storage.googleapis.com/images/layout-structure-toolbars-toolbars-06_large_xhdpi.png)

> 分離的樣式工具欄

![](http://material-design.storage.googleapis.com/images/layout-structure-toolbars-toolbars-07a_large_xhdpi.png)

> 底部的工具欄，他緊貼在鍵盤或是其他底部元件的上方。

![](http://material-design.storage.googleapis.com/images/layout-structure-toolbars-toolbars-08a_large_xhdpi.png)

> 底部工具欄

## 應用程式工具欄

### 應用程式工具欄的結構


應用程式欄，是之前Android的操作欄，被用來放Branding、導覽、搜尋以及其他操作。

如果你的應用程式欄用的是開合側欄，那麼它的圖示在開啟時必須轉換成倒退的箭頭圖示。標題可以當作應用程式的標題、頁面的標題或是頁面的過濾器。

右邊的圖示必須和應用程式的操作有關，選單的圖示可以展開選單，選單的項目包含幫助、設定、回饋。

![](http://material-design.storage.googleapis.com/images/layout-structure-appbar-appbar-01_large_xhdpi.png)

![](http://material-design.storage.googleapis.com/images/layout-structure-appbar-appbar-02_large_xhdpi.png)

> 亮色

![](http://material-design.storage.googleapis.com/images/layout-structure-appbar-appbar-03_large_xhdpi.png)

> 暗色

![](http://material-design.storage.googleapis.com/images/layout-structure-appbar-appbar-04_large_xhdpi.png)

> 彩色

![](http://material-design.storage.googleapis.com/images/layout-structure-appbar-appbar-05_large_xhdpi.png)

> 透明

### 標準

**預設高度**

手機垂直狀態: 48dp

手機水平狀態: 56dp

平板、桌面: 64dp

如果要延伸應用程式欄，他的高度等於預設高度加上內容的高度。

![](http://material-design.storage.googleapis.com/images/layout-structure-appbar-appbar-06_large_xhdpi.png)

![](http://material-design.storage.googleapis.com/images/layout-structure-appbar-appbar-07_large_xhdpi.png)


![](http://material-design.storage.googleapis.com/images/layout-structure-appbar-appbar-08_large_xhdpi.png)

![](http://material-design.storage.googleapis.com/images/layout-structure-appbar-appbar-09_large_xhdpi.png)

![](http://material-design.storage.googleapis.com/images/layout-structure-appbar-appbar-10_large_xhdpi.png)

![](http://material-design.storage.googleapis.com/images/layout-structure-appbar-appbar-11_large_xhdpi.png)

![](http://material-design.storage.googleapis.com/images/layout-structure-appbar-appbar-12_large_xhdpi.png)

![](http://material-design.storage.googleapis.com/images/layout-structure-appbar-appbar-13_large_xhdpi.png)

![](http://material-design.storage.googleapis.com/images/layout-structure-appbar-appbar-14_large_xhdpi.png)

## 選單

選單像是一張臨時擺放的圖紙，他總是覆蓋在應用程式欄上方，而不是應用程式欄的延伸。

![](http://material-design.storage.googleapis.com/images/layout-structure-appbar-appbar-15_large_xhdpi.png)

![](http://material-design.storage.googleapis.com/images/layout-structure-appbar-appbar-16_large_xhdpi.png)

![](http://material-design.storage.googleapis.com/images/layout-structure-appbar-appbar-17_large_xhdpi.png)

![](http://material-design.storage.googleapis.com/images/layout-structure-appbar-appbar-18_large_xhdpi.png)

![](http://material-design.storage.googleapis.com/images/layout-structure-appbar-appbar-19_large_xhdpi.png)

## 側欄

左邊和右邊的側欄可以被固定用來永久顯示，或者它們可以暫時覆蓋在上方。左邊的側欄，主要是用來導覽或是顯示身份的。右邊的側欄，則是用在更深的階層資訊，或是頁面次要的內容。


![](http://material-design.storage.googleapis.com/images/layout-structure-sidenav-sidenav-01_large_xhdpi.png)

![](http://material-design.storage.googleapis.com/images/layout-structure-sidenav-sidenav-02_large_xhdpi.png)

## 結構

側欄暫時展開時會覆蓋內容，如果它固定的狀態則會緊貼內容的邊緣，或是在內容的下方。

**標準**

手機: 側欄寬 = 螢幕寬 - 工具欄高度

範例:

Nexus 4: 304 dp

Nexus 5: 288 dp

iPhone: 264 dp

桌面: 左方最大寬度是400dp，右邊的尺寸則是依據內容。

桌面、平板: 固定，寬度需要對齊欄。

浮動最大寬度: 304 dp

![](http://material-design.storage.googleapis.com/images/layout-structure-sidenav-sidenav-03_large_xhdpi.png)

> 手機

![](http://material-design.storage.googleapis.com/images/layout-structure-sidenav-sidenav-04_large_xhdpi.png)


![](http://material-design.storage.googleapis.com/images/layout-structure-drive_chrome-04_large_xhdpi.png)

> 桌面左方側欄

![](http://material-design.storage.googleapis.com/images/layout-structure-drive_chrome-02_large_xhdpi.png)

> 桌面右方側欄

## 基本框架

基本框架提供了各種佈局結構，利用相同的方式表現圖層、陰影及表現區域。

> [基本框架](http://material-design.storage.googleapis.com/downloads/Whiteframes.ai)

![](http://material-design.storage.googleapis.com/images/layout-structure-whiteframe_bigtop_large_xhdpi.png)

> 卡片式的內容擴展及收合

![](http://material-design.storage.googleapis.com/images/layout-structure-whiteframe_calendar_large_xhdpi.png)

> Overlaid content details and focused app bar on mobile

![](http://material-design.storage.googleapis.com/images/layout-structure-whiteframe_contacts_large_xhdpi.png)

> Overlapping content card with multiple toolbars and background image on mobile

![](http://material-design.storage.googleapis.com/images/layout-structure-whiteframe_drive_large_xhdpi.png)

> Extended app bar and right nav drawer

![](http://material-design.storage.googleapis.com/images/layout-structure-whiteframe_gallery_large_xhdpi.png)

> Left nav drawer and 1-up stream on mobile

![](http://material-design.storage.googleapis.com/images/layout-structure-whiteframe_mail_large_xhdpi.png)

> Source list

![](http://material-design.storage.googleapis.com/images/layout-structure-whiteframe_maps_large_xhdpi.png)

> Fullscreen background image with inset search field and carded search results

![](http://material-design.storage.googleapis.com/images/layout-structure-whiteframe_music_large_xhdpi.png)

> Expandable footer drawer








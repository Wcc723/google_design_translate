#Progress and Activity

Make loading content in your app as delightful and painless as possible by minimizing the amount of visual change a user sees before they can view and interact with content. Each operation should only be represented by one activity indicator—for example, one refresh operation should not display both a refresh bar and an activity circle.

---

## Types of Indicators

For operations where the percentage of the operation completed can be determined, use a determinate indicator. They give users a quick sense of how long an operation will take.

For operations where the user is asked to wait a moment while something finishes up, and it’s not necessary to expose what's happening behind the scenes and how long it will take, use an indeterminate indicator.

There are two types of indicators: linear and circular. You can use either one for determinate and indeterminate operations.

### Linear

A linear progress indicator should always fill from 0% to 100% and never move backwards to a lower value. If multiple operations are happening in sequence, use the progress indicator to represent the delay as a whole, so that when the bar reaches 100%, it doesn't return back to 0%.

Linear bars should appear and disappear on the edge of a header or sheet.

<video width="739" height="565" src="http://material-design.storage.googleapis.com/videos/components-progressandactivity-progressandactivity-_20spec.linear_large_xhdpi.webm" controls=""></video>

<video width="360" height="640" src="http://material-design.storage.googleapis.com/videos/components-progressandactivitiy-progressandactivity-7-youtube.mobile-buffer_large_xhdpi.webm" controls=""></video>

<video width="360" height="639" src="http://material-design.storage.googleapis.com/videos/components-progressandactivity-progressandactivity-6-chrome.mobile.query.load_large_xhdpi.webm" controls=""></video>

### Circular

<video width="739" height="308" src="http://material-design.storage.googleapis.com/videos/components-progressandactivity-progressandactivity-_20spec.circular_201_large_xhdpi.webm" controls=""></video>

### Circular with integration

<video width="739" height="154" src="http://material-design.storage.googleapis.com/videos/components-progressandactivity-progressandactivity-_20spec.circular_202_large_xhdpi.webm" controls=""></video>

> A circular loader may be integrated with a fab or a refresh icon.

<video width="360" height="639" src="http://material-design.storage.googleapis.com/videos/components-progressandactivity-progressandactivity-5-pegman.fab-upload.photo_large_xhdpi.webm" controls=""></video>

<video width="740" height="555" src="http://material-design.storage.googleapis.com/videos/components-progressandactivity-progressandactivity-6-gallery.tablet-refresh.icon_large_xhdpi.webm" controls=""></video>

---

## Behavior

### Loading in phases

<video width="359" height="639" src="http://material-design.storage.googleapis.com/videos/components-progressandactivity-progressandactivity-4-bigtop.mobile-swipe.down.to.refresh 2_large_xhdpi.webm" controls=""></video>

#### One-phased Loads

> Ink (copy and images) loads within an existing, unchanging container.

<video width="360" height="640" src="http://material-design.storage.googleapis.com/videos/components-progress-activity-behavior-load.content.from.bottom_large_xhdpi.webm" controls=""></video>

#### Two-phased-Loads

The paper container is generated, then the ink (copy and images) load within it.

<video width="360" height="640" src="http://material-design.storage.googleapis.com/videos/components-progressandactivity-progressandactivity-1-drive.mobile-initial.load_large_xhdpi.webm" controls=""></video>

#### Loading content for the first time

<video width="360" height="639" src="http://material-design.storage.googleapis.com/videos/components-progressandactivity-progressandactivity-2-drive.mobile-load.folders_large_xhdpi.webm" controls=""></video>

#### Load and display all content at once

<video width="740" height="555" src="http://material-design.storage.googleapis.com/videos/components-progressandactivity-progressandactivity-6-gallery.tablet-refresh.icon_large_xhdpi.webm" controls=""></video>

#### Load and display in two phases

### Loading additional content

<video width="740" height="555" src="http://material-design.storage.googleapis.com/videos/components-progressandactivity-progressandactivity-4-bigtop.tablet-send.message_large_xhdpi.webm" controls=""></video>

#### Example 1: Card expansion

> An indeterminate linear indicator is recommended for a card expansion on larger surfaces such as desktop.

<video width="720" height="1280" src="http://material-design.storage.googleapis.com/videos/components-progressandactivity-behavior-scroll.up.to.refresh_large_xhdpi.webm" controls=""></video>

#### Example 2: Scroll up to refresh

> An indeterminate circular indicator with an ink explosion initiation is recommended when refreshing a list from below.

<video width="359" height="639" src="http://material-design.storage.googleapis.com/videos/components-progressandactivity-progressandactivity-4-bigtop.mobile-swipe.down.to.refresh_large_xhdpi.webm" controls=""></video>

#### Example 3: Swipe down to refresh

> An indeterminate circular indicator with an ink explosion initiation is recommended when refreshing a list from above.
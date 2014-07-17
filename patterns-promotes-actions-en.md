# Promoted Actions

## Floating Action Button


Floating action buttons are a special case of promoted actions. They are distinguished by a circled icon floating above the UI and have special motion behaviors, related to morphing, launching, and its transferring anchor point.

There are two sizes of floating action buttons: the default size and the mini, which should only be used to create visual continuity with other elements on the screen.
 
![](images/patterns/patterns-promotedactions-floatingactionbuttonFAB02b_large_mdpi.png) 
 
![](images/patterns/patterns-promotedactions-floatingactionbuttonFAB02a_large_mdpi.png)

![](images/patterns/patterns-promotedactions-floatingactionbuttonFAB3_large_mdpi.png)

![](images/patterns/patterns-promotedactions-floatingactionbuttonFAB4_large_mdpi.png)

### Associated Content

Not every screen needs a floating action button. A floating action button should represent the primary action in an application. In the screen on the left, the primary action is to touch and open images in a gallery, so no floating action button is needed. On the right, the primary action is to add files. A floating action buton is appropriate.

![](images/patterns/patterns-promotedactions-associatedcontent-FAB03do1_large_mdpi.png)
 
> Do.

![](images/patterns/patterns-promotedactions-associatedcontent-FAB03do2_large_mdpi.png)
 
> Do.


Try to use only one floating action button per screen, as it is the most prominent button on the screen.
 
![](images/patterns/patterns-promotedactions-associatedcontent-FAB04dont1_large_mdpi.png)

> Don't.
 
![](images/patterns/patterns-promotedactions-associatedcontent-FAB04dont2_large_mdpi.png)

> Don't.

Don’t use floating action buttons in dialogs. Use a flat button.

![](images/patterns/patterns-promotedactions-associatedcontentFAB05do_large_mdpi.png)

> Do.
 
![](images/patterns/patterns-promotedactions-associatedcontentFAB05do_large_mdpi.png)

> Don't.

Don’t attach a floating action button to a side drawer; it could distract a user from the task they want to accomplish. Side drawers are for navigation.
 
![](images/patterns/patterns-promotedactions-associatedcontentFAB07do_large_mdpi.png)

> Do.
 
![](images/patterns/patterns-promotedactions-associatedcontentFAB07dont_large_mdpi.png)

> Don't.

Don’t associate floating action buttons with pulldown menus.

![](images/patterns/patterns-promotedactions-associatedcontentFAB08do_large_mdpi.png)

> Do.

![](images/patterns/patterns-promotedactions-associatedcontentFAB08dont_large_mdpi.png)

> Don't.

### Related Actions

Put overflow actions in the overflow menu in toolbars, not in floating action buttons.

![](images/patterns/patterns-promotedactions-relatedactionsFAB09do1_large_mdpi.png)

> Do.

![](images/patterns/patterns-promotedactions-relatedactionsFAB09do2_large_mdpi.png)

> Do.

![](images/patterns/patterns-promotedactions-relatedactionsFAB10dont1_large_mdpi.png)
 
> Don't.

![](images/patterns/patterns-promotedactions-relatedactionsFAB10dont2_large_mdpi.png)

> Don't.

If the hallmark of the app is adding filetypes, a floating action button can morph into related actions after it is initially touched.

![](images/patterns/patterns-promotedactions-relatedactionsFAB11do1_large_mdpi.png)

> Do.

![](images/patterns/patterns-promotedactions-relatedactionsFAB11do2_large_mdpi.png)
 
> Do.

However, if a set of actions that appear after touching a floating action button are unrelated to the button and are not a natural extension of it, then the actions should probably go into an overflow menu.

![](images/patterns/patterns-promotedactions-relatedactionsFAB12dont1_large_mdpi.png)

> Don't.

![](images/patterns/patterns-promotedactions-relatedactionsFAB12dont2_large_mdpi.png)
 
> Don't.

If a floating action button morphs into a toolbar, that toolbar should contain related actions. In this example, the button lets the user select the media type to add.

![](images/patterns/patterns-promotedactions-relatedactionsFAB13do1_large_mdpi.png)
 
> Do.

![](images/patterns/patterns-promotedactions-relatedactionsFAB13do2_large_mdpi.png)

> Do.

Don’t morph floating action buttons into a toolbar that contains unrelated or confusing actions.

![](images/patterns/patterns-promotedactions-relatedactionsFAB14dont1_large_mdpi.png) 

> Don't.

![](images/patterns/patterns-promotedactions-relatedactionsFAB14dont2_large_mdpi.png)
 
> Don't.

A floating action button can contain a list of contacts.

![](images/patterns/patterns-promotedactions-relatedactionsFAB15do1_large_mdpi.png)

> Do.

![](images/patterns/patterns-promotedactions-relatedactionsFAB15do2_large_mdpi.png) 

> Do.

It shouldn’t contain unrelated actions.

![](images/patterns/patterns-promotedactions-relatedactionsFAB16dont1_large_mdpi.png)
 
> Don't.

![](images/patterns/patterns-promotedactions-relatedactionsFAB16dont2_large_mdpi.png)
 
> Don't.

### Qualities

Make floating action buttons positive actions like Create, Favorite, Share, Navigate, and Explore.

![](images/patterns/patterns-promotedactions-qualitiesFAB17_large_mdpi.png)

> Do.

In general, avoid using floating action buttons for destructive actions like Archive or Trash; unspecific actions; alerts or errors; limited tasks like cutting text; or controls that should be in a toolbar, like volume control or changing a font color. Floating action buttons don’t contain app bar icons or status bar info like notifications. Don’t layer badges or other elements over a floating action button.

![](images/patterns/patterns-promotedactions-qualitiesFAB18_large_mdpi.png)
 
> Don't.

Use the circle-shaped icon consistently so as not to confuse users.

![](images/patterns/patterns-promotedactions-qualitiesFAB20do_large_mdpi.png) 

> Do.

![](images/patterns/patterns-promotedactions-qualitiesFAB20dont_large_mdpi.png)

> Don't.

Don’t make floating action buttons bounce.

![](images/patterns/patterns-promotedactions-qualitiesFAB21do_large_mdpi.png)
 
> Do.

![](images/patterns/patterns-promotedactions-qualitiesFAB21dont_large_mdpi.png)
 
Don't.

### Placement

A floating action button can be placed according to the keyline spacing rules or attached to an extended app bar.

![](images/patterns/patterns-promotedactions-placementFAB23do1_large_mdpi.png)
 
> Do.

![](images/patterns/patterns-promotedactions-placementFAB23do2_large_mdpi.png)
 
> Do.

A floating action button can attach to a footer or to an extended sheet.

![](images/patterns/patterns-promotedactions-placementFAB24do1_large_mdpi.png)
 
> Do.

![](images/patterns/patterns-promotedactions-placementFAB24do2_large_mdpi.png)
 
> Do.

A floating action button shouldn’t float in a random location. Take care when attaching floating action buttons to a toolbar, where it might overlap with or cover other touch targets.

![](images/patterns/patterns-promotedactions-placementFAB25dont1_large_mdpi.png)
 
> Don't.

![](images/patterns/patterns-promotedactions-placementFAB25dont2_large_mdpi.png)
 
> Don't.

A floating action button can attach to an extended head.

![](images/patterns/patterns-promotedactions-placementFAB26_large_mdpi.png)
 
> Do.

A floating action button can be attached to a toolbar or structural element within a sheet (as long as it’s not blocking other elements).

![](images/patterns/patterns-promotedactions-placementFAB27_large_mdpi.png)
 
> Do.

A floating action button can be attached to the edge of a sheet.

![](images/patterns/patterns-promotedactions-placementFAB28_large_mdpi.png)
 
> Do.

Don’t have more than one floating action button per screen.
 
![](images/patterns/patterns-promotedactions-placementFAB29_large_mdpi.png)

> Don't.

Don’t place floating action buttons inside a drawer or attached to a drawer.

![](images/patterns/patterns-promotedactions-placementFAB30_large_mdpi.png)
 
> Don't.

Don’t associate floating action buttons with every element on a screen.

![](images/patterns/patterns-promotedactions-placementFAB31_large_mdpi.png)
 
> Don't.

Don’t block floating action buttons with snackbars or toasts.
 
![](images/patterns/patterns-promotedactions-placement13do1_large_mdpi.png)
 
> Do.

![](images/patterns/patterns-promotedactions-placement14dont1_large_mdpi.png)
 
> Don't.



# Menus

---

## Usage

A menu is a temporary piece of paper emitted from a button, an action, a pointer, or another control that contains at least two menu items.

Each menu item is a discrete option or action that can affect the app, the view, or selected elements within a view.

Menus should not be used as a primary method for navigation within an app.

![](images/components/components-menus-menus-menus-01a_large_mdpi.png)

![](images/components/components-menus-menus-menus-01b_large_mdpi.png)

The label of an emitting button or control concisely and accurately reflects the menu items contained within the menu. Menu bars typically use single words as labels, like “file”, “format”, “edit”, and “view”, while other contexts may have more verbose labels.

Menus display a consistent set of menu items, each of which may be enabled or disabled based on the current state of the application.

![](images/components/components-menus-menus-menus-02_large_mdpi.png)

Contextual menus dynamically change their available and enabled menu items based on the current state of the application.

Generally, remove menu items that are irrelevant to the current context, and disable menu items which are relevant but need certain conditions to be met (for example, Copy becomes enabled when text is selected).

Certain application states may result in a contextual menu containing only a single menu item. For example, when highlighting text on a web page, Android reveals only Copy, since users cannot cut or paste text.

![](images/components/components-menus-menus-menus-03_large_mdpi.png)

Reposition menus vertically and horizontally based on their proximity to screen edges.

![](images/components/components-menus-menus-menus-04_large_mdpi.png)

If the height of a menu prevents all menu items from being displayed, the menu can scroll internally. One example is when viewing a menu on a phone in landscape orientation.

![](images/components/components-menus-menus-menus-05_large_mdpi.png)

A menu can also cascade.

![](images/components/components-menus-menus-menus-06_large_mdpi.png)

These animations show scrolling and cascading menus in action.

<video width="739" height="762" src="http://material-design.storage.googleapis.com/videos/components-menus-menus-textfield_toolbar_large_xhdpi.webm" controls=""></video>

> Drop down 

<video width="740" height="555" src="http://material-design.storage.googleapis.com/videos/components-menus-menus-cascading_dropdown_spec_large_xhdpi.webm" controls=""></video>

> Cascading drop down

---

## Menu Items

Each menu item is limited to a single line of text that describes the action it will perform when selected.

The text is generally a single word or short phrase, but it can include icons and helper text, like keyboard shortcuts, as well as controls like checkmarks to indicate multiple selected items or states. See also [List Controls](components-listcontrols-en.html).

Menus with static content should have the most frequently used menu items placed at the top of the menu.

Menus with dynamic content may have other behavior, such as placing previously used fonts at the top of the menu. The order can change based on user actions.

Menu items can reveal nested submenus. Try to limit nesting to one level deep, as it can be difficult to navigate multiple nested submenus.

![](images/components/components-menus-menuitems-menu-items-01_large_mdpi.png)

Displaying actions as disabled, rather than removing them, lets the user know they exist under the right conditions.

For example, Redo is disabled when there is nothing to Redo. Cut and Copy are disabled until content is selected.

![](images/components/components-menus-menuitems-menu-items-02_large_mdpi.png)

---

## Behavior

Menus appear above all other in-app UI elements.

Dismiss a menu by tapping outside of the menu, or by tapping the emitting button (if visible)

Generally, selecting a menu item will also dismiss the menu. An exception is when a menu allows for multiple items to be chosen, for example, by using checkmarks.

![](images/components/components-menus-behavior-menus-08_large_mdpi.png)

Menus are positioned over their emitting elements such that the currently selected menu item appears on top of the emitting element.

Do not display a duplicate of the selected menu item.

![](images/components/components-menus-behavior-menus-p-01_large_mdpi.png)

Do.

![](images/components/components-menus-behavior-menus-p-02_large_mdpi.png)

Don't.

Menus do not horizontally align based on touch location.

![](images/components/components-menus-behavior-menus-p-03a_large_mdpi.png)

Do.

![](images/components/components-menus-behavior-menus-p-03b_large_mdpi.png)

Do.

![](images/components/components-menus-behavior-menus-p-04a_large_mdpi.png)

Don't.

![](images/components/components-menus-behavior-menus-p-04b_large_mdpi.png)

Don't.

---

## Metrics

Metrics are provided for various sizes and types of menus and for different platforms.

### Mobile

![](images/components/components-menus-metrics-menus-redlines-01_large_mdpi.png)

### Various widths

![](images/components/components-menus-metrics-menus-redlines-02_large_mdpi.png)

### Cascading menu

![](images/components/components-menus-metrics-menus-redlines-03_large_mdpi.png)

### Cascading redlines

![](images/components/components-menus-metrics-menus-redlines-04_large_mdpi.png)
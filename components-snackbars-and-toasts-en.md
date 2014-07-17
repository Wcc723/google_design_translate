# Snackbars and Toasts

Snackbars provide lightweight feedback about an operation in a small popup at the base of the screen on mobile and at the lower left on desktop. They are above all over elements on screen, including the floating action button.

They automatically disappear after a timeout or after user interaction elsewhere on the screen, whichever comes first. Snackbars can be swiped off screen. They do not block input on the screens they appear on and cannot receive input focus. Show only one snackbar on screen at a time.

Android also provides a capsule-shaped toast, primarily used for system messaging. Toasts are similar to snackbars but do not contain actions and cannot be swiped off screen.

---

## Usage

### Very short text strings

Snackbars should generally only be tall enough to accommodate one string, and the string should be directly related to the operation performed. They cannot contain icons or action icons. Actions are in the form of text.

![](images/components/components-toasts-usage-spec_toast_do_20_large_mdpi.png) 

> Do.

![](images/components/components-toasts-usage-spec_toast_dont_20_large_mdpi.png)
 
> Don't.

### Transient

For usability, snackbars should not contain the only way to access a core use case. They should not be persistent and stack, as they are above other elements on screen.
 
![](images/components/components-toasts-usage-spec_toast_do_22_large_mdpi.png)
 
> Do.

![](images/components/components-toasts-usage-spec_toast_dont_22_large_mdpi.png) 

> Don't.

### 0-1 actions, not dismiss or cancel

If an action is present, comply with dialog spacing and affordance rules. For two or more actions, use a dialog, not a snackbar, even when one of the actions is a dismiss action. If the action(s) described in the snackbar are important enough to block usage of the screen, it should be a dialog.

![](images/components/components-toasts-usage-spec_toast_do_24_large_mdpi.png) 

> Do.
 
![](images/components/components-toasts-usage-spec_toast_dont_24_large_mdpi.png)

> Don't.

### Don’t block the floating action button

Move your floating action button vertically to accommodate the snackbar height.

![](images/components/components-toasts-usage-spec_toast_do_26_large_mdpi.png) 

> Do.

![](images/components/components-toasts-usage-spec_toast_dont_26_large_mdpi.png)

> Don't.

---

## Specs

### Mobile snackbar

- Single-line snackbar height: 48 dp
- Multi-line snackbar height: 80 dp
- Text: Roboto Regular 14 sp
- Action button: Roboto Medium 14 sp, all-caps text
- Default background fill: #323232 100%
 
![](images/components/components-toasts-specs-spec_toast_03_1_large_mdpi.png)

![](images/components/components-toasts-specs-spec_toast_03_2_large_mdpi.png)
 
<video width="360" height="640" src="http://material-design.storage.googleapis.com/videos/components-snackbars-and-toasts-specs-snackbar.single.line-dismissal_large_xhdpi.webm" controls=""></video>

![](images/components/components-toasts-3-spec_toast_06_large_mdpi.png)
 
### Tablet/Desktop snackbar

- Single-line snackbar height: 48 dp tall
- Minimum width: 288 dp
- Maximum width: 568 dp
- 2 dp rounded corner
- Text: Roboto Regular 14 sp
- Action button: Roboto Medium 14 sp, all-caps text
- Default background fill: #323232 100%
 
![](images/components/components-toasts-specs-snackbar_toast_08_large_mdpi.png)

![](images/components/components-toasts-specs-snackbar_toast_10_large_mdpi.png)

![](images/components/components-toasts-specs-spec_toast_12_large_mdpi.png)

<video width="512" height="284" src="http://material-design.storage.googleapis.com/videos/components-snackbars-and-toasts-specs-snackbar.tablet-time.out_large_xhdpi.webm" controls=""></video>
 
### Android toast

Developers can create custom toasts and/or custom screen placements for them. If making a custom toast, you are strongly encouraged to adhere to the snackbar style provided above.
 
![](images/components/components-toasts--specs-snackbar_toast_14_large_mdpi.png)

![](images/components/components-toasts-specs-snackbar_toast_16_large_mdpi.png)

![](images/components/components-toasts-specs-spec_toast_18_large_mdpi.png)
 
 
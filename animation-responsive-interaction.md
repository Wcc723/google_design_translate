# Responsive Interaction

Responsive interaction builds trust with the user and engages them. When a user interacts with an app and beautiful yet perfectly logical things happen, the user feels satisfied—even delighted. It is thoughtful and purposeful, not random, and can be gently whimsical but never distracting. It encourages deeper exploration of an app: what will happen if I touch this? And then this?

In material design, apps are responsive to and eager for user input:

- Touch, voice, mouse and keyboard are all first-class input methods
- Although UI elements appear tangible, they are locked behind a layer of glass (the computer or device’s screen). Visual and motion cues help bridge that gap by immediately acknowledging input and implying direct manipulation.

Responsive interaction elevates an app from something that delivers information to the user upon request to something that communicates with the user in a tangible way.

## Examples

<video width="360" height="405" controls="">
<source src="//material-design.storage.googleapis.com/videos/animation-responsiveinteraction-responsiveinteraction-2-celebratetouch-localized-ink-reaction2_large_xhdpi.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/videos/animation-responsiveinteraction-responsiveinteraction-2-celebratetouch-localized-ink-reaction2_large_xhdpi.mp4" type="video/mp4">
</video>

> Surface reaction

<video width="360" height="405" controls="">
<source src="//material-design.storage.googleapis.com/videos/animation-responsiveinteraction-inkreactions-notouchripplepressandrelease_large_xhdpi.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/videos/animation-responsiveinteraction-inkreactions-notouchripplepressandrelease_large_xhdpi.mp4" type="video/mp4">
</video>

> Material response

<video width="360" height="405" controls="">
<source src="//material-design.storage.googleapis.com/videos/animation-responsive-interation-radialReact-example_large_xhdpi.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/videos/animation-responsive-interation-radialReact-example_large_xhdpi.mp4" type="video/mp4">
</video>

> Radial action

## Surface Reaction

Upon receiving an input event, the system provides an instantaneous visual confirmation at the point of contact: under the pad of a finger for touch, at the mic for voice, or in the appropriate field for a keyboard press. One way to express this acknowledgment is through the ink metaphor, the dynamic display surface that coats every sheet of paper.

The core visual mechanism to express this contact is the Touch Ripple. This device articulates the attack and duration of a touch event, as well as dynamic aspects such as the amplitude of voice or the interpreted pressure of a touch.

### Best Practices

Input occurs at specific points: at the contact point of a finger or at the mic icon for voice. From this point, make the visual reaction radial.

<video width="360" height="640" controls="">
<source src="//material-design.storage.googleapis.com/videos/animation-responsiveinteraction-inkreactions-touchripplepressandrelease_large_xhdpi.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/videos/animation-responsiveinteraction-inkreactions-touchripplepressandrelease_large_xhdpi.mp4" type="video/mp4">
</video>

> Touch ripple - press / release

<video width="360" height="640" controls="">
<source src="//material-design.storage.googleapis.com/videos/animation-responsiveinteraction-inkreactions-touchrippledragindragout_large_xhdpi.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/videos/animation-responsiveinteraction-inkreactions-touchrippledragindragout_large_xhdpi.mp4" type="video/mp4">
</video>

> ouch ripple - drag in/out

## Material Response

In addition to ink-like actions on the surface, the material itself can also respond to interaction. The material can lift up when touched or clicked, indicating an active state. The user can generate new or transform existing material upon touch or click, or directly manipulate sheets of material, dragging or flinging them.

### Best Practices

### Point of origin

When new material is generated as a result of direct user interaction, the motion of surface growth should originate from the point of input.

<video width="360" height="405" controls="">
<source src="//material-design.storage.googleapis.com/videos/animation-responsive-surfaceresponse-pointorigin-do_example_large_xhdpi.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/videos/animation-responsive-surfaceresponse-pointorigin-do_example_large_xhdpi.mp4" type="video/mp4">
</video>

> Do
>
> Material appears from touch point, visually tying the element to the point of touch.

<video width="360" height="450" controls="">
<source src="//material-design.storage.googleapis.com/videos/animation-responsive-surfaceresponse-pointorigin-dont_example_large_xhdpi.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/videos/animation-responsive-surfaceresponse-pointorigin-dont_example_large_xhdpi.mp4" type="video/mp4">
</video>

> Don't 
>
> Paper appears from center of screen, breaking relationship with input.


### Lift on touch

When a card or separable element is activated, the card should lift to indicate an active state.

<video width="360" height="405" controls="">
<source src="//material-design.storage.googleapis.com/videos/animation-responsiveinteraction-inkreactions-notouchripplepressandrelease_large_xhdpi.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/videos/animation-responsiveinteraction-inkreactions-notouchripplepressandrelease_large_xhdpi.mp4" type="video/mp4">
</video>

> Lift upon touch

## Radial Action

All user initiated actions have an epicenter; the place or places where their intent enters the system. Add clarity to user initiated events by creating strong visual connections from user input, whether from fingers on a touch screen or voice through a microphone. State changes across the screen should trigger progressively as their distance to the point of contact increases, creating a ripple of action.

Inputs have an epicenter. Touch occurs at the point of contact, voice enters through the mic icon, keyboard through the individual keys.

Actions should visually connect to their respective input epicenter. Closer actions occur sooner than more distant ones, creating a ripple of actions (movement occurs from the distance from the epicenter).






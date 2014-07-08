# Authentic Motion

Perceiving an object's tangible form helps us understand how to manipulate it. Observing an object's motion tells us whether it is light or heavy, flexible or rigid, small or large. Motion in the world of material design is not only beautiful, it builds meaning about the spatial relationships, functionality, and intention of the system.

## Mass and Weight

Physical objects have mass and move only when forces are applied to them. Consequently, objects can’t start or stop instantaneously. Animation with abrupt starts and stops or rapid changes in direction appears unnatural and can be an unexpected and unpleasant disruption for the user.

### Best Practices

A critical aspect of motion for material design is to retain the feeling of physicality without sacrificing elegance, simplicity, beauty, and the magic of a seamless user experience. Here are some guidelines to help translate these concepts into animations.

<video id="animation-authentic-motion-authenticMotion_massAndWeight_ex1-do-1" width="740" height="270" controls="">
<source src="//material-design.storage.googleapis.com/videos/animation-authentic-motion-authenticMotion_massAndWeight_ex1_large_xhdpi.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/videos/animation-authentic-motion-authenticMotion_massAndWeight_ex1_large_xhdpi.mp4" type="video/mp4">
</video>

> Do.
>
> Motion with swift acceleration and gentle deceleration feels natural and delightful.

<video id="animation-authentic-motion-authenticMotion_massAndWeight_ex2-dont-1" width="740" height="270" controls="">
<source src="//material-design.storage.googleapis.com/videos/animation-authentic-motion-authenticMotion_massAndWeight_ex2_large_xhdpi.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/videos/animation-authentic-motion-authenticMotion_massAndWeight_ex2_large_xhdpi.mp4" type="video/mp4">
</video>

> Don't
>
> Linear motion feels mechanical. An abrupt change in velocity at both the beginning and end of the animation curve means the object instantaneously starts and stops, which is unrealistic.

### Special Cases: Entering and Exiting Frame

When an object enters the frame, ensure it's moving at its peak velocity. This behavior emulates natural movement: a person entering the frame of vision does not begin walking at the edge of the frame but well before it. Similarly, when an object exits the frame, have it maintain its velocity, rather than slowing down as it exits the frame. Easing in when entering and slowing down when exiting draw the user's attention to that motion, which, in most cases, isn't the effect you want.

<video id="videos-authenticMotion_massAndWeight_ex3_do-do-1"  width="367" height="134" controls="">
<source src="//material-design.storage.googleapis.com/videos/videos-authenticMotion_massAndWeight_ex3_do_large_xhdpi.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/videos/videos-authenticMotion_massAndWeight_ex3_do_large_xhdpi.mp4" type="video/mp4">
</video>

> Do.
>
> Enter and exit frame at peak velocity. The ball enters and exits frame at peak velocity, creating a confident transition.

<video id="animation-authenticmotion-massandweight-authenticmotion_massandweight_example6-dont-2" width="740" height="270" controls="">
<source src="//material-design.storage.googleapis.com/videos/animation-authenticmotion-massandweight-authenticmotion_massandweight_example6_large_xhdpi.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/videos/animation-authenticmotion-massandweight-authenticmotion_massandweight_example6_large_xhdpi.mp4" type="video/mp4">
</video>

> Don't.
>
> Speed up when entering or slow down when exiting. Don’t distract the user with unnecessary changes in velocity.

### Making adjustments

Not all objects move the same way. Lighter/smaller objects may accelerate or decelerate faster, because they have less mass and require less force to do so. Larger/heavier objects may need more time to reach peak speed and come to rest. Think about how this applies to the various UI elements in your app and consider how their motion should be represented.


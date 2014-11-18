# Navigational transitions

Navigational transitions occur when the user is taken from one state to another within the app, such as moving from a high-level view to a detailed view or a task-completion view. Most transitions are hierarchical in nature, but non-hierarchical transitions also occur.

These brief moments are very important for the user experience. Consider the user’s journey carefully to determine which transition to use when. Different kinds of transitions are appropriate for various cases.

## Parent to child

One of the most important transitions is when the user “drills down” into content. It can be thought of as a parent-to-child transition, because it is hierarchical in nature.

In material design, a parent-to-child transition is indicated by a change in elevation. The surface or the area of the surface that the user touches should lift up and expand into place from its origin. This motion guides the user from point A to point B and should highlight both the origin as well as the destination. It should feel natural, using the material motion curves, and familiar, because the expansion and movement from the origin appears logical.


<video id="1-None_0B2wX4iIvu8L6OG5GWnBqWFFRdVU" width="760" height="420" controls="">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B2wX4iIvu8L6UjZvd0w1MmdQVWs/patterns_navigational-transitions_parent-to-child_list-01_xhdpi.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B2wX4iIvu8L6OG5GWnBqWFFRdVU/patterns_navigational-transitions_parent-to-child_list-01_xhdpi.mp4" type="video/mp4">
</video>


## Sibling to sibling

Transitions that are not hierarchical in nature behave differently than hierarchical transitions. You can think of non-hierarchical transitions as sibling transitions.

An example for this kind of transition is when a user navigates through a row of tabs. There is no elevation change; the content and surface of each tab stays on the same elevation level. New content slides in from the right and pushes its sibling off screen to the left.

<video id="1-None_0B2wX4iIvu8L6bDNpdXBkdElHWDg" width="760" height="420" controls="">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B2wX4iIvu8L6bXdoMlplMWtMeWs/patterns_navigational-transitions_sibling-to-sibling_tabs-01_xhdpi.webm" type="video/webm">
<source src="//material-design.storage.googleapis.com/publish/v_1/quantumexternal/0B2wX4iIvu8L6bDNpdXBkdElHWDg/patterns_navigational-transitions_sibling-to-sibling_tabs-01_xhdpi.mp4" type="video/mp4">
</video>

> Sibling transition
# Environment

## 3D world

The material environment is a 3D space, which means all objects have x, y, and z dimensions. The z-axis is perpendicularly aligned to the plane of the display, with the positive z-axis extending towards the viewer. Every sheet of material occupies a single position along the z-axis and has a standard 1dp thickness.

![](images/whats-material/whatismaterial_environment_3d.png)

## Light and shadow

Within the material environment, virtual lights illuminate the scene and allow objects to cast shadows. A key light creates directional shadows, while an ambient light creates consistent, soft shadows from all angles.

All shadows in the material environment are cast by these two light sources. Shadows are the absence of light resulting from the occlusion of these light sources by sheets of material at various positions along the z-axis.


![](images/whats-material/whatismaterial_environment_shadow1.png)

> Shadow cast by key light

![](images/whats-material/whatismaterial_environment_shadow2.png)

> Shadow cast by ambient light

![](images/whats-material/whatismaterial_environment_shadow3.png)

> Combined shadow from key and ambient lights


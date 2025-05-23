# Global Illumination

Authors: Abigail Starkweather, Kelly Feke

## Regular Assignments

### Assignment 1: Setting the Scene

Sphere 1: translation: [0,-.5,-5], scale: [2,2,2]

Sphere 2: translation: [1.4,-1.25,-6], scale: [1.6,1.6,1.6]

Floor: translation: [2,-3,-7], scale: [6,1,8]

Light Source: [-1,6,-2]

Camera: eye: [0,0,0], lookat: [0,0,-20], up: [0,1,0]

We used frustrum perspective for projection: [-6,6,-6,6,8,15]

![Setting the Scene](/GlobalIllum/image1.png)

### Assignment 2: Basic Ray Tracing

Basic Implementation:

![Basic Ray Tracing 1](/GlobalIllum/assn1-2.png)

Change Camera Location:

![Basic Ray Tracing 2](/GlobalIllum/assn1-2_1.png)

Add Cone and Cylinder Objects:

![Basic Ray Tracing 3](/GlobalIllum/assn1-2_2.png)

### Assignment 3: Illumination

Basic Implementation:

![Illumination 1](/GlobalIllum/assn3-1.png)

Multiple Light Sources:

![Illumination 2](/GlobalIllum/assn3-2.png)

Change Color of Sphere to Show Diffuse:

![Illumination 3](/GlobalIllum/assn3-1_color.png)

### Assignment 4: Procedural Shading

![Illumination 4](/GlobalIllum/assn4-1.png)

![Bonus 4](/GlobalIllum/assnspheal.png)

### Assignment 4: Reflection

![Illumination 5](/GlobalIllum/assn5-1.png)

800 Resolution:

![Illumination 6](/GlobalIllum/assn5_800.png)

### Assignment 5: Transmission

![Illumination 7](/GlobalIllum/assn6-1.png)

### Assignment 6: Tone Reproduction

Ward:

![Illumination 9](/GlobalIllum/assn6_ward_t.png)

| ![Ward low](/GlobalIllum/assn6_ward_t_low.png) | ![Ward med](/GlobalIllum/assn6_ward_t_med.png) | ![Ward high](/GlobalIllum/assn6_ward_t_high.png) |
|:------------------------------------------:|:---------------------------------------------:|:-----------------------------------------------:|
| Ward Low                                   | Ward Medium                                  | Ward High                                      |

Reinhard:

| ![rein low](/GlobalIllum/assn6_reinhard_t_low.png) | ![rein med](/GlobalIllum/assn6_reinhard_t_med.png) | ![rein high](/GlobalIllum/assn6_reinhard_t_high.png) |
|:------------------------------------------:|:---------------------------------------------:|:-----------------------------------------------:|
| Reinhard Low                                   | Reinhard Medium                                  | Reinhard High                                      |

## Extra Assignments

### Kd-Trees

![Illumination 8](/GlobalIllum/assn-bun.png)

time to construct kd-tree:  2.860426902770996  seconds

time to render with tree:  28.610138416290283  seconds

time without tree: TOO LONG

### Advanced Tone Reproduction

Adaptive Logarithmic Mapping 

| ![Adaptive Logarithmic Mapping Low](/GlobalIllum/assn_adaptlog.png) | ![Adaptive Logarithmic Mapping Medium](/GlobalIllum/assn_adaptlog_med.png) | ![Adaptive Logarithmic Mapping High](/GlobalIllum/assn_adaptlog_high.png) |
|:-------------------------------------------------------------------:|:--------------------------------------------------------------------------:|:-------------------------------------------------------------------------:|
| Adaptive Logarithmic Mapping Low                                   | Adaptive Logarithmic Mapping Medium                                        | Adaptive Logarithmic Mapping High                                        |

# Shader Composition Functions
Functions to help visual composition with shaders, with shadertoy, kodelife, glsl...

## Third rules
![Third rules](/images/third.PNG)
Probably one of the mosts important tool I use in my compositions.
Help you organize your picture in thirds.
The function needs a vec2 UVs not centered in screen space.
It returns a float so that you can add the value in your mainImage function

## Vignette
![Vignette](/images/vignette.PNG)
Certainly the most simple effect to know. It's like doing a circle.
Use centerd screenspace uvs and change force to have more or less vignette effect.
It can be use with background or by multiplying result color for an overlay effect.
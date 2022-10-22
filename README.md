# NoiseKit - Procedural Noise Generation and Baking

Procedural generation and baking of tileable noise textures in the Unity Editor using compute.  
Choose from available noise types, edit their properties using a realtime viewport, perform channel packing and export as textures:

<p align="center">
  <img width="100%" src="https://github.com/lerpingfx/noisekit/blob/main/.github/images/NoiseKit.gif?raw=true" alt="NoiseComposition">
</p>

## Requirements
NoiseKit is implemented using UIToolkit, and is supported in Unity 2023.x and later.

## Setup
Follow these steps for <a href="https://docs.unity3d.com/Manual/upm-ui-giturl.html"> installing a package from a git url</a>:
1. Go to `Window > Package Manager`
2. On the top left on the Package Manager window, click on `+ > Add package from git URL...`
3. Add the following URL `https://github.com/lerpingfx/noisekit.git`  

Once installed, start the NoiseKit panel from the main toolbar: `Window > NoiseKit > Open`

## Controls
`Noise Selection`: add or remove noise instances, and set the desired noise type.  
`Noise Editor`: control the availale noise properties (per instance).  
`Channels`: add or remove noise channels, and perform channel packing.  
`Viewport`: preview the generated noise texture and per-channel masks.  
`Export`: set the exported texture's precision (8/16 bit per channel), resolution and file path.  

<p align="left">
  <img width="50%" src="https://github.com/lerpingfx/noisekit/blob/main/.github/images/Controls.png?raw=true" alt="NoiseControls">
</p>

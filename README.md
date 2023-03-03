# URP-WaterShaders
## Procedural Water Surface and Underwater Caustics for Unity URP

### This project demonstrates two procedural shadergraphs, for creating immersive underwater caustics and water surface with distortion. Both shadergraphs are meant to be used as templates for your own shaders.

### Demo Video
<a href="http://www.youtube.com/watch?feature=player_embedded&v=1XAbvmTKjJI" target="_blank"><img src="http://img.youtube.com/vi/1XAbvmTKjJI/0.jpg" alt="URP-WaterShaders" width="240" height="180" border="10" /></a></p>
https://youtu.be/1XAbvmTKjJI

#### NOTE: In order to use the graphs in your own projects, export them as a unitypackage, rather than copying the shadergraph files. This will ensure the subgraph references are not lost

### Instructions
1. Open the project with Unity (2019.4.3f1 and URP/Shadergraph 7.3.1 or later recommended) and open SampleScene.unity in the Scenes folder
2. Make sure the render pipeline is set to URP in Project Settings> Graphics
3. Select the UniversalRenderPipelineAsset and make sure Opaque Texture and Depth Texture are both enabled.
4. Under Player settings, select Linear color space for best color representation
5. In the Asset>Graphs folder you can find two separate shadergraphs for Underwater Caustics and Water surface
6. These graphs have several customization options, such as:
    1. Adjustable Shorelines using the depth texture
    2. Water clarity, opacity, refraction (through distortion)
    3. Triplanar Underwater caustics
    4. Adjustable flow speeds for surface as well as caustics

### Instructions for HDRP
1. Make sure the project is properly set up and all graphs are working.
2. Remove URP completely from the project.
3. Install HDRP from the package manager. Use the HDRP wizard to fix any issues during setup.
4. In the WaterSurface Shadergraph, change the 'Scene Color' Node to 'HD Scene Color'. This will fix the overexposed water .
5. In the WaterUnder Shadergraph, find the Position node, and change the space to Absolute World. This will fix caustics moving with the camera.



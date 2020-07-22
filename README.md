# URP-WaterShaders
## Procedural Water Surface and Underwater Caustics for Unity URP

### This project demonstrates two procedural shadergraphs, for creating immersive underwater caustics and water surface with distortion. Both shadergraphs are meant to be used as templates for your own shaders.

### Demo Video
<a href="http://www.youtube.com/watch?feature=player_embedded&v=iY-JhXh99L0" target="_blank"><img src="http://img.youtube.com/vi/iY-JhXh99L0/0.jpg" alt="URP-WaterShaders" width="240" height="180" border="10" /></a>

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

Water Shader (Unity URP)

A stylized, Shader Graph–based water shader for Unity URP featuring refraction, depth blending, and shoreline foam.

<div align="center">








</div>
Showcase
<div align="center"> <img src="/Resources/showcase_live_demo.gif" width="800"> </div>
Shader Graph Preview
<div align="center"> <img src="/Resources/showcase_shaders.png" width="900"> </div>
Features
Stylized Depth-Based Color Blending

Smooth transition between shallow and deep areas, giving the water a clean stylized look:

Shallow → lighter hues

Deep → darker tones

Screen-Space Refraction

Adjustable refraction parameters exposed in the material:

Refraction scale

Distortion speed

Distortion strength

Ideal for both stylized and semi-realistic water surfaces.

Shoreline Foam

Foam intensity responds naturally to:

Scene depth

Viewer distance

Shore proximity

Produces clean shoreline roll-off without any real surf simulation.

How to Use
1. Import `Water.shadergraph` and the WaveUV subgraph.
2. Create a Material using the water shader.
3. Apply to a plane, water mesh, or custom geometry.
4. Adjust refraction, depth fade, foam, and color parameters in the Inspector.

<div align="center"> <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExMWIwMzZlNWQzMjVkdXZjbG0yZXQ4Z2Z6cWU2eXFiZTZqd3ZicWZlOCZlcD12MV9naWZzX3NlYXJjaCZjdD1n/3oz8xKaR836UJOYeOc/giphy.gif" width="200">

<em><b>Built with Unity, Shader Graph, and way too much tweaking.</b></em>

</div>
<div align="center">

Star the repo if you found it useful.
Maintained by @DeVBulut

</div>

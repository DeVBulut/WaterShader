🌊 Water Shader (Unity URP)

A custom Shader Graph–based stylized water shader for Unity URP.
Built to support refraction, depth-based color blending, shoreline foam, and wave-driven distortion, all while remaining lightweight and game-ready.

![Video Showcase](/Resources/showcase_live_demo.gif)

![URP Shader Graph](/Resources/showcase_shaders.png)

✨ Features
✔ Stylized Color Blending

Depth-based color transition lets shallow water fade into warm hues while deep areas shift into cooler tones.

✔ Screen-Space Refraction

Distorts the underlying geometry with:

Refraction Scale

Distortion Speed

Distortion Strength

All controllable via exposed material params.

✔ Shoreline Foam

Foam fades naturally as the camera approaches the water surface and interacts with scene depth.

✔ Lightweight Performance

The shader is authored entirely in Shader Graph—no custom HLSL needed—making it:

URP-friendly

Mobile/VR compatible

Easy to modify

✔ Fully Parametric

All major effects are adjustable in the Inspector:

Wave frequency & speed

Foam intensity

Shallow/Deep water color

Fade distance

Refraction behavior

Surface UV distortion

🛠 How to Use

Import the WaterShader.shadergraph file.

Create a new Material and assign the shader.

Apply to a Plane or Water Mesh.

Tweak:

Colors

Wave speed & scale

Refraction strength

Depth fade

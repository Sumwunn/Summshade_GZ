# Summshade_GZ (GZDoom/Zandronum/Others)
Most versions are similar, with tweaks to make them more performance friendly or less jarring on some maps.
The goal was to provide a satisfying modern visual upgrade for Classic DOOM without deviating too much from its original look.

- No depth effects are used due to how GZDoom/Zandronum renders the sprites and the world.
- v1-v3 were minor revisions or exclusion of one or two effects to make the preset less jarring on skies.
- v4 is tweaks and include Adaptive Tonemapper. My 2nd favourite.
- v5 is my favourite since it's the most performance friendly and doesn't blow out whites too much and isn't too dark. It also includes a tweaked CRT Shader. Sadly, though, it doesn't work on OpenGL (vort_hdr compile error).
- v6 is will switch from vort_hdr to something very similar.

Install:
- Copy ReShade.ini and Summshade-vX.ini to the engine folder.
- Use the latest ReShade setup to select Summshade-vX.ini and install the required effects.
- (v2 and higher) Copy [Glamayre_Fast_Effects.fx](https://github.com/92bfe6dc-93bb-45c2-a09f-939b12298174) to "reshade-shaders\Shaders" inside the engine folder.
- Play.
- Home brings up ReShade overlay, and Insert toggles effects.

Requirements
- Moderately demanding; GTX 1060 or RX 580 @ 1080p 60 will probably cut it.
- If lagging, try swapping CMAA2 for FXAA or SMAA. Can also disable Cathode (v5 swaps this for a performance friendly CRT shader).

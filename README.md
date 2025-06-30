# Summshade_GZ (GZDoom/Zandronum/Others)
The goal is/was to provide a satisfying modern visual upgrade for Classic DOOM without deviating too much from its original look.

- No depth effects are used by default since GZDoom/Zandronum render sprites outside of the depth buffer, causing effect clipping.
- Most versions are similar, with tweaks to make them more performance friendly or less jarring on some maps.
---
**Older versions moved to archive folder.**

- **v5c**: Effects tweaked and toned down a bit.
- **v7x**: Revised effects and order. A bit gritty. Lite includes just LUT + LXAA + GI, while full includes additional effects (see Effect List).
---
Install:
- Copy ReShade.ini and Summshade-vX.ini to the engine's folder.
- Use the latest ReShade setup to select Summshade-vX.ini and download the required effects.
- (**v2 and higher**) Download [Glamayre_Fast_Effects.fx](https://github.com/rj200/Glamarye_Fast_Effects_for_ReShade/blob/main/Shaders/Glamayre_Fast_Effects.fx) (as raw file) and copy to "reshade-shaders\Shaders", inside the engine folder.
- (**v7x-Lite**) Download [LXAA.fx](https://github.com/grebord/LXAA-Antialiasing-Shader/blob/main/LXAA.fx) (as raw file) and copy to "reshade-shaders\Shaders", inside the engine folder.
- Play.
- 'Home' brings up ReShade overlay, and 'Insert' toggles effects.

Requirements/Notes
- With **v7x**, Monocular_Cues & Deband are disabled by default (see [Commit](https://github.com/Sumwunn/Summshade_GZ/commit/f20c29beda0395f0844bb37d3c69553b121ce7a2)).
- Moderately demanding; GTX 1060 or RX 580 @ 1080p 60 should cut it.
- If lagging, try swapping CMAA2 for LXAA. Alternatively, **v7x_Lite** includes a minimal set of effects.
- LXAA can smear pixels a bit (a tuned FXAA might be better); use CMAA2 if you can.
- Looks good with Daggerfall Unity, as well (v5c, at least).

Effect List (**v5**)
- ![Effect List](Images/EffectList_v5.jpg?raw=true "")

Comparison (**v5**; Off -> On)
- ![v5 Off](Images/v5_Off.jpg?raw=true "")
- ![v5 On](Images/v5_On.jpg?raw=true "")

Effect List (**v7x**)
- ![Effect List](Images/EffectList_v7x.png?raw=true "")

Effect List (**v7x-Lite**)
- ![Effect List](Images/EffectList_v7x-Lite.png?raw=true "")

Comparison (**v7x-Lite**; Off -> On)
- ![v7x-Lite Off](Images/v7x-Lite_Off.png?raw=true "")
- ![v7x-Lite On](Images/v7x-Lite_On.png?raw=true "")

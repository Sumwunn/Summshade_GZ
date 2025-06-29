# Summshade_GZ (GZDoom/Zandronum/Others)
The goal is/was to provide a satisfying modern visual upgrade for Classic DOOM without deviating too much from its original look.

- No depth effects are used by default since GZDoom/Zandronum render sprites outside of the depth buffer, causing effect clipping.
- Most versions are similar, with tweaks to make them more performance friendly or less jarring on some maps.

- Older versions moved to archive folder.

- v5c: Effects tweaked and toned down a bit.
- v7x: Revised effects and order. A bit gritty. Lite includes just LUT + LXAA + GI, while full includes additional effects (see Effect List).

Install:
- Copy ReShade.ini and Summshade-vX.ini to the engine's folder.
- Use the latest ReShade setup to select Summshade-vX.ini and download the required effects.
- (v2 and higher) Download [Glamayre_Fast_Effects.fx](https://github.com/rj200/Glamarye_Fast_Effects_for_ReShade/blob/main/Shaders/Glamayre_Fast_Effects.fx) (as raw file) and copy to "reshade-shaders\Shaders", inside the engine folder.
- Play.
- 'Home' brings up ReShade overlay, and 'Insert' toggles effects.

Requirements/Notes
- Moderately demanding; GTX 1060 or RX 580 @ 1080p 60 should cut it.
- If lagging, try swapping CMAA2 for LXAA. Alternatively, v7x_Lite includes a minimal set of effects.
- Looks good with Daggerfall Unity, as well (v5c, at least).

Effect List (v5c)
- ![Effect List](Images/EffectList_v5c.jpg?raw=true "")

Comparison (v5c; Off -> On)
- ![v5 Off](Images/v5c_Off.jpg?raw=true "")
- ![v5 On](Images/v5c_On.jpg?raw=true "")

Effect List (v7x_Lite)
- ![Effect List](Images/EffectList_v7x-Lite.jpg?raw=true "")

Comparison (v7x-Lite; Off -> On)
- ![v5 Off](Images/v7x-Lite_Off.jpg?raw=true "")
- ![v5 On](Images/v7x-Lite_On.jpg?raw=true "")

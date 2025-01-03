# Summshade_GZ (GZDoom/Zandronum/Others)
The goal is/was to provide a satisfying modern visual upgrade for Classic DOOM without deviating too much from its original look.

- No depth effects are used by default since GZDoom/Zandronum render sprites outside of the depth buffer, causing effect clipping.
- Most versions are similar, with tweaks to make them more performance friendly or less jarring on some maps.

- v1-v3 were minor revisions to make the preset less jarring on skies.
- v4 is tweaks and includes Adaptive Tonemapper. My 2nd favourite.
- v5 is my favourite since it's the most performance friendly and doesn't blow out whites too much and isn't too dark. It also includes a tweaked CRT Shader. ~~Sadly, though, it doesn't work on OpenGL (vort_hdr compile error)~~.
- v6 switched shaders and works on OpenGL. It's visually similar to v5 and marginally more demanding.
- v5b: I discovered vort_hdr works again on OpenGL. It's a revised v5, with tweaks to bloom, saturation, and others. Glamayre_Fast_Effects depth effects are tweaked to make clipping less noticeable (disabled by default). If you enable it, I recommend enabling depth for flashlight, too.

Install:
- Copy ReShade.ini and Summshade-vX.ini to the engine folder.
- Use the latest ReShade setup to select Summshade-vX.ini and download the required effects.
- (v2 and higher) Download [Glamayre_Fast_Effects.fx](https://github.com/rj200/Glamarye_Fast_Effects_for_ReShade/blob/main/Shaders/Glamayre_Fast_Effects.fx) (as raw file) and copy to "reshade-shaders\Shaders", inside the engine folder.
- Play.
- Home brings up ReShade overlay, and Insert toggles effects.

Requirements/Notes
- "Doom", Bright", or "Classic (Faster)" sector light modes are my preferred ones for this (depends on the map, honestly).
- Moderately demanding; GTX 1060 or RX 580 @ 1080p 60 will probably cut it.
- If lagging, try swapping CMAA2 for FXAA or SMAA. Can also disable Cathode (v5 swaps this for a performance friendly CRT shader). CMAA2 is least destructive for pixel art, I've found.
- As of 12/17/24, CMAA2 shader doesn't function and needs this [fix](https://github.com/LordOfLunacy/Insane-Shaders/issues/13#issuecomment-2484781195) applied.
- FX Flashlight shader may need to be manually checked upon ReShade setup.
- Looks good with Daggerfall Unity, as well.

Effect List (v5)
- ![Effect List](Images/EffectList_v5.jpg?raw=true "")

Comparison (v5; Off -> On)
- ![v5 Off](Images/v5_Off.jpg?raw=true "")
- ![v5 On](Images/v5_On.jpg?raw=true "")

Effect List (v6)
- ![Effect List](Images/EffectList_v6.jpg?raw=true "")

Comparison (v6; Off -> On)
- ![v6 Off](Images/v6_Off.jpg?raw=true "")
- ![v6 On](Images/v6_On.jpg?raw=true "")

# Rendepth Reshade
![Rendepth_Reshade_Title](https://github.com/user-attachments/assets/ef0a839f-d640-4399-9f48-5f993e8d1248)

2D-to-3D Conversion Reshade Plug-In.

## Features
- Optimized to provide minimal artifacts, halos, or ghosting.
- Includes newly developed anaglyph filter with more accurate colors.
- Side-by-side mode (half width) works with popular XR glasses and 3D displays.
- Simple settings (only 3 sliders) for easy adjustment and minimal errors.
- Stereoscopic mouse cursor for using menus in SBS mode (press '+' key).

## 3D Screenshots

![ACShadows_Crouch_anaglyph](https://github.com/user-attachments/assets/c7ea9e1e-f611-40b7-8572-8e7e66d33eb3)

![ACShadows_Crouch_sbs](https://github.com/user-attachments/assets/166b49b1-2cc1-4fdb-b299-b82d6815ac7a)

![ACShadows_Blade_anaglyph](https://github.com/user-attachments/assets/c3499474-3d5e-4498-a20d-29d4509be2cd)

![ACShadows_Blade_sbs](https://github.com/user-attachments/assets/64ebdffe-7f25-4a63-b3ab-991fc0c6799f)

![ACShadows_Stereo_Cursor_anaglyph](https://github.com/user-attachments/assets/ab7f0c18-c9f3-457f-a38b-0d64d5435fa2)

![ACShadows_Stereo_Cursor_sbs](https://github.com/user-attachments/assets/351018ef-ec0e-4fda-bf66-e592232a2822)

## Installation

- Install Reshade from: https://reshade.me
- Run the Reshade executable and choose the game you wish to mod.
- Selected graphics API is usually correct, only the the standard effects are needed.
- Next download the folders from this Github, `Shaders` and `Textures`.
- Alternatively, download the latest release from the releases section.
- Launch the game and do the Reshade tutorial, if unfamiliar.
- In the Settings tab, add `Effect Search Path` for the `Shaders` folder you downloaded.
- Add `Texture Search Path` with the `Textures` folder you downloaded.
- Go back to the main Reshade tab and click `Relead`.

## Settings

After installation, press the Reshade key (default `Home` key) to access the menu. Check the box next to Rendepth to enable the 3D conversion shader. In the Rendepth menu, the top slider is the distance between your eyes. In most cases you can set the value to `100` for maximum 3D effect, though lowering the value can help mitigate artifacts. The middle option controls how strong the depth is evaluated to. It is typically safe to increase this value to `100` for a more extreme depth range. The bottom most slider is the parallax overlap. This shifts the images left or right to make the overlap more comfortable (plane of focus). This value is content dependent but usually acceptable near the center. For most games setting the values to `100` `100` `64` provides the best effect.

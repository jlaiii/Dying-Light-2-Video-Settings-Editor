# Dying Light 2 Video Settings Editor

A custom web-based editor for modifying your `video.scr` file in *Dying Light 2*. This tool allows you to drag and drop your configuration file and visually update your game's graphics settings with ease. Features include dark mode, real-time setting previews, and the ability to export updated config files.

🔗 **Live Page:**  
[https://jlaiii.github.io/Dying-Light-2-Video-Settings-Editor/](https://jlaiii.github.io/Dying-Light-2-Video-Settings-Editor/)

## Features

- Full UI for editing game video settings
- Dark mode toggle
- Drag-and-drop or manual file selection
- Default configuration loader
- Export `.scr` file for manual placement

<details>
  <summary>🛠 All Editable Settings</summary>

- **Display**
  - Window Mode
  - Resolution (Primary & Secondary)
  - Window Offset (X & Y)
  - Monitor Selection
  - Renderer Mode
  - Frame Rate / VSync
  - Variable Refresh Rate
  - Disable DWM
  - Extra Game FOV
- **Upscaling & Rendering**
  - 3D Scale
  - FSR Sharpness
  - Upscaler (DLSS, FSR, XeSS)
  - Upscaling Quality
  - Frame Amplification
  - Async Compute
- **Quality**
  - Texture Quality
  - Shadows (Quality, Preset, Map Size, Spot Light Quality)
  - Ambient Occlusion (+Quality)
  - Contact Shadows
  - LOD Quality & Multiplier
  - Grass Quality
  - Fog Quality
  - Reflections Quality
  - GPU FX Quality
  - Spot Lights Cast Shadows
  - Anisotropic Filtering (Toggle + Level)
- **Ray Tracing**
  - Ambient Occlusion
  - Soft Shadows
  - Flashlight
  - Global Illumination (Diffuse & Specular)
  - Voxel GI Quality
- **Post-Processing**
  - Gamma
  - Motion Blur (Quality, Intensity)
  - Bokeh
  - Glow Glare & Streaks
  - Lens Flare
  - SSSS Quality
  - Chromatic Aberration
  - Film Grain
  - Color Grading
  - Anti-Aliasing + Mode
  - Color Blind Mode
  - Reflex (Low Latency)

</details>

## How to Use

1. Open the live page linked above or load `index.html` locally in your browser.
2. Drag and drop your existing `video.scr` file into the drop area.
3. Adjust settings as needed using the interface.
4. Click “Download Config File” to export.
5. Replace the file at:
   ```
   C:\Users\<YourName>\Documents\dying light 2\out\settings\video.scr
   ```

## Disclaimer & Rights

- This project is **owned by jlaiii**.
- You **may not** reupload, modify, redistribute, or monetize this code or UI in any form.
- All rights reserved. No license granted.
- This is an unofficial fan-made utility and is not affiliated with Techland.


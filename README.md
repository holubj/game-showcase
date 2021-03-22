# Game Showcase

This document describes some **technical** aspects of my game that i am currently working on. All visual models below are just placeholders and **will not be present in the final version** of the game.

## Basic info

- Unity Engine
- 3D graphics
- Third person camera
- Target platforms:
  - PC and Mac
  - Consoles later

## Input support

- Mouse & Keyboard
- Gamepad (Xbox, PS, Switch)

## Motion capture

The final animations are created by combining three sources:

#### Facial motion capture using iOS ARKit (all blend shapes supported)

![Facial motion capture](https://github.com/holubj/game-showcase/raw/master/assets/faceTracking.gif)

#### Body motion capture using iOS ARKit (before denoising)

![Body motion capture](https://github.com/holubj/game-showcase/raw/master/assets/bodyTracking.gif)

#### Hand motion capture using Leap Motion Controller

![Hand motion capture](https://github.com/holubj/game-showcase/raw/master/assets/handTracking.gif)

## Dialogue/Cutscene system

Custom dialogue/cutscene system based on [Ink](https://github.com/inkle/ink).

Features:

- Integration with Unity Timeline
- Localization support
- Dialogue branching
- Multiple characters in a dialogue
- Multiple dynamic cameras, Cinemachine effects
- Character animations and gestures
- VFX
- BGM, SFX

## Desert shader

### Shader

Custom stylized desert terrain shader.

Features:

- Tessellation
- Multilayer heightmap
- Terrain holes
- Custom lighting

[![](https://github.com/holubj/game-showcase/raw/master/assets/desert2_preview.png)](https://github.com/holubj/game-showcase/raw/master/assets/desert2.png)

[![](https://github.com/holubj/game-showcase/raw/master/assets/desert1_preview.png)](https://github.com/holubj/game-showcase/raw/master/assets/desert1.png)

### Sand waves

![Sand Waves](https://github.com/holubj/game-showcase/raw/master/assets/desertWaves.gif)

### Tracks

Just a simple transparent circle used in a RenderTexture for now.

:: [https://www.youtube.com/watch?v=-tocd44Rcl8](https://www.youtube.com/watch?v=-tocd44Rcl8)

[![](https://github.com/holubj/game-showcase/raw/master/assets/desert_t_preview.png)](https://www.youtube.com/watch?v=-tocd44Rcl8)

### Effects

:: [https://www.youtube.com/watch?v=DbM0apr6NPU](https://www.youtube.com/watch?v=DbM0apr6NPU)

[![](https://github.com/holubj/game-showcase/raw/master/assets/desert_w_preview.png)](https://www.youtube.com/watch?v=DbM0apr6NPU)

## Transport/Mount system

:: [https://www.youtube.com/watch?v=--C7yvnBbeE](https://www.youtube.com/watch?v=--C7yvnBbeE)

[![](https://github.com/holubj/game-showcase/raw/master/assets/desert_p_preview.png)](https://www.youtube.com/watch?v=--C7yvnBbeE)

## Toolset

- Applications
  - Unity
  - VSCode
  - Blender
  - Substance Painter
  - Substance Designer
  - Procreate
  - Adobe Illustrator
  - FMOD
  - Logic Pro
    - M-Audio Code 49 MIDI Keyboard
  - iZotope RX
- Unity tools & extensions
  - Ink
  - Amplify Shader Editor
  - Dreamteck Splines
  - UniVRM
  - Final IK
  - Text Typer

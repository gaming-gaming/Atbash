<p align="center">
  <img src="https://raw.githubusercontent.com/gaming-gaming/Atbash/refs/heads/main/brand/gradient/logo_text_subtitle.png" width="75%">
</p>

# Atbash: The Universal Controller Adapter

[![License: GPL](https://img.shields.io/github/license/gaming-gaming/Atbash)](https://github.com/gaming-gaming/Atbash/blob/main/LICENSE)
[![Platform Support](https://img.shields.io/badge/platforms-windows%20%7C%20linux-blue)]()
[![Archs](https://img.shields.io/badge/archs-x86%20|%20x64%20|%20armv7%20|%20aarch64-lightgrey)]()
[![Version](https://img.shields.io/badge/version-v0.1.0-orange)]()

## Overview
Atbash is a controller input translation tool for using controllers otherwise unsupported on specific consoles. For example: Using a DualSense controller, emulating a wired Xbox 360 controller.

# Tutorial
To use Atbash, [download](https://github.com/gaming-gaming/Atbash/releases/latest) one of the compiled binaries in the releases of this project.

Before starting the script, connect the controller you wish to use to your computer. Upon running the script, you may select the controller you have connected. Afterwards, you must select a controller configuration from a list of json files in `./dat/input_presets/`. Input presets are commented and easily editable, for if you wish to remap your controllers input. After setting up the input controller, you must select what controller to output. Atbash works with various wireless controllers, but may require DIY setup for wired controllers.

# Compiling
To compile Atbash, you will need to download these these libraries:
- [SDL2](https://github.com/libsdl-org/SDL/releases/tag/release-2.32.8)

# Supported Controllers
<table>
  <tr>
    <th>Controller</th>
    <th>Input</th>
    <th>Output</th>
  </tr>
  <tr>
    <td>DualSense</td>
    <td>✅</td>
    <td>❌</td>
  </tr>
  <tr>
    <td>Xbox Series Controller</td>
    <td>✅</td>
    <td>❌</td>
  </tr>
  <tr>
    <td>Joy-Cons</td>
    <td>✅</td>
    <td>✅</td>
  </tr>
  <tr>
    <td>Switch Pro Controller</td>
    <td>✅</td>
    <td>✅</td>
  </tr>
  <tr>
    <td>Xbox 360 Controller</td>
    <td>❌</td>
    <td>✅ (WIRED ONLY)</td>
  </tr>
</table>

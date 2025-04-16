# RenderingSample-Unreal

The **Rendering** sample is a simple Unreal project that demonstrates how to use the YVR Unreal SDK and change rendering settings. You can use this project as a starting point for your own VR applications.

## Getting Started
Connect the YVR device and install the packaged apk, and click to run.

## Mode of operation

**Yvr Button (L) Thumbstick X** -> Player View rotation

**Yvr Button (R) Thumbstick Y** -> Player teleport position, release hand teleport

Yvr controller  is close to the small box/gun on the desktop, **Yvr Button (L/R) Hand Trigger** -> Hold to grab, release to release

For guns, the **Yvr Button (L/R) Index Trigger** -> fires the bullet

## Menu

The menu is on the left controller, you can turn it on and off through the menu Button, align the Settings button you want to click through the right controller, and press the **Yvr Button (R) Index Trigger** to apply this setting:

* Quad: Quadrilateral Stereo Layer
* Cylinder: Cylinder Stereo Layer
* Cubemap: Stereo Layer for cube maps
* Equirect: Spherical Stereo Layer
* AppSW: SpaceWarp
* FPS: Screen refresh rate
* FFR: resolution
* Restart: Resets the level
* Real life: Quit the game

If you open any Compositor Layer, you can click the **Yvr Button (R) B** to close it.

## Development Environment
| **Name** | **Version** |
| ----  |  ----      |
| Unreal Editor | 5.4.4 |
| YVR Unreal SDK | 3.0.0 |

## Licenses
This project is released under the [MIT License](https://github.com/YVRDeveloper/GetStarted-Unreal/blob/main/LICENSE)
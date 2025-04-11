# RenderingSample-Unreal

The **Rendering** sample is a simple Unreal project that demonstrates how to use the YVR Unreal SDK and change rendering settings. You can use this project as a starting point for your own VR applications.

## Getting Started
Connect the YVR device and install the packaged apk, and click to run.

Please note that the menu is on the left controller, you can use index trigger on right controller to change the settings. If you open any Compositor Layer, you can click the `B` button on right controller to close it. The path for the OS Splash Screen is the absolute path in device. Besides, the Application SpaceWarp and the Dynamic Resolution is only allowed on [Unreal Engine YVR Branch](https://github.com/YVRDevelopers/UnrealEngine) so they are not included in this demo. Some functions are relay on specific settings, please check the [document](https://developer.pfdm.cn/yvrdoc/unreal/manual/ApplicationSpaceWarp.html) for details.

## Mode of operation

Left handle rocker X axis control Angle rotation

The Y axis of the right handle rocker controls the position to be transferred and can be transferred by releasing the hand

The handle is close to the small cube of the desktop, holding down the side key can grab, and letting go can release

You can also grab the gun and press the trigger button to fire the bullet

## Development Environment
| **Name** | **Version** |
| ----  |  ----      |
| Unreal Editor | 4.27 |
| YVR Unreal SDK | 2.3.0 |

## Licenses
This project is released under the [MIT License](https://github.com/YVRDeveloper/GetStarted-Unreal/blob/main/LICENSE)
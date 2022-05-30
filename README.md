## What kind of function can it achieve?
It allows you to record 360 degree panoramic video in VRChat
 
## What principle?
The cube has 6 faces, so it has 6 cameras to obtain images in different directions and then combine them together through the shader~
 
## How will it affect me and other players?  
It's fine as long as it's not too close... After all, it's a shader, and if it's too close, it's a "blush-faced shader"  
Other than that, there is no negative impact, just enjoy it~  

## How do I add it to my avatar?
It's very simple, download *.unitypackage in [releases](https://github.com/tianrui233/VRChatSphereCam/releases), after importing, just drag "TrackingPoint" to the place you want to control the position and reset it to zero, and Add animation controllers and custom menus  
 
## How to operate in the game?
Controlled by the disc switch, first turn on the "panoramic camera", move the cube to the position you want to place, and then turn on the "position lock" switch  
![GIF动图](https://user-images.githubusercontent.com/37788769/162582757-9f89afaf-72f7-4e92-96bb-81104072732e.gif)  

Then open the official streaming camera of vrchat and change the position of the camera to the world position (world)
and stuff it into the cube  
![GIF动图](https://user-images.githubusercontent.com/37788769/162582699-d842f321-41c4-4fee-b2a4-fa6f4e63095b.gif)  
The inside of the cube is transparent, so it won't be occluded. After that, open the screen recording tool on your computer to record a panoramic video~  
 
It is recommended to use the program supporting the graphics card to record video, which can save a lot of performance overhead. It is recommended to set the bit rate to 50000kbp/s for 4k resolution
## I don't have a virtual reality (VR) device, and I can't open the camera when I play directly on the PC. Can I also record panoramic videos?
Yes, but.. you can only choose between recording video and playing games, because then the entire screen will be a tiled 360° panorama..  
 
## Anything else to watch out for?
### Clarity!
①The resolution of the recording depends on the resolution displayed by your computer (it can be super-resolution), I just recorded a 4k video with a 2k monitor  
![截图](https://img.gejiba.com/images/ac40e42b63a9eff422cea9cbccd6d7ad.png)  
Usually, there are related settings in the graphics card driver, don't adjust it too high, otherwise the hardware device will be overwhelmed.  
  
②In addition, it is necessary to modify the resolution of the front, rear, left, right, upper and lower surfaces in unity    
![我用的4096的清晰度..3070ti有点吃力了](https://s1.ax1x.com/2022/04/10/LFwD6P.png)
****
## Related tutorials can be found at [Github Wiki](https://github.com/tianrui233/VRChatSphereCam/wiki)
### ↓This tutorial is outdated, it is only for [v0.4beta](https://github.com/tianrui233/VRChatSphereCam/releases/tag/v0.4-beta)!
#### ~~Detailed video tutorials are available at [bilibili@欧阳大鸽子](https://www.bilibili.com/video/BV1bS4y127gC) release! At present, there is no plan to write a graphic tutorial. The video is very detailed.~~ 
****
## TODO list:  
✅Moveable and fixed panorama camera position in the current world  
✅More intuitive confirmation of the position of the main viewing angle (cube)  
✅Reduce the affected area (but don't get too close, it will trigger the blush buff  
✅ Simplify the append process  
☑️Stereo adaptation  
☑️Hide UI  
☑️Other control methods  

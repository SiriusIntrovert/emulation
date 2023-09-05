Source: [Link](https://github.com/quinton-ashley/Super_Mario_Sunshine_UHD_Texture_Pack)

Creator: [quinton-ashely GitHub](https://github.com/quinton-ashley) - [qashto](https://forums.dolphin-emu.org/User-qashto)

# Super Mario Sunshine UHD Texture Pack

![](https://raw.githubusercontent.com/quinton-ashley/Super_Mario_Sunshine_UHD_Texture_Pack/master/textures/GMS/gui/title/tex1_490x270_8173791dd11cea7c_5.png)

Check out these [comparison images](https://github.com/quinton-ashley/Super_Mario_Sunshine_UHD_Texture_Pack/wiki) and [in-game screenshots!](https://github.com/quinton-ashley/Super_Mario_Sunshine_UHD_Texture_Pack/wiki/Screenshots)

Don't download this GitHub repository to use in-game, use the download link above and download the `GMS.7z` file from the latest release. Put the textures in the Textures folder. `GMS` is Super Mario Sunshine's game id.  

Windows: `C:\Users\UserName\Documents\Dolphin Emulator\Load\Textures\GMS`  
Linux: `~/.local/share/dolphin-emu/Load/Textures/GMS`  
macOS: `/Users/qashto/Library/Application\ Support/Dolphin/Load/Textures/GMS`

## Recommended Settings

The latest 5.x Development build of Dolphin is required to use this DDS BC7 texture pack. Make sure to check "Prefetch Custom Textures" in the "Advanced" tab of the Graphics settings, this will cache the custom textures to RAM when Dolphin loads the game. This prevents stuttering. I also highly recommend using V-Sync to avoid tearing.

Look at the [Dolphin wiki page for Super Mario Sunshine](https://wiki.dolphin-emu.org/index.php?title=Super_Mario_Sunshine) and follow the graphics settings configurations. One deviation I make from that configuration is to enable Scaled EFB Copy because it makes bodies of water look way better. I do not use the widescreen code on the wiki because it causes problems for me, although I've heard it works fine for others. These are the only Gecko codes that I use:

$Remove Heatwave Effect Code NTSC-U  
0419F83C 4E800020

60FPS (NTSC-U) [gamemasterplc]  
044167B8 3F800000 
<br>
042FCB24 60000000 
<br>
04414904 3CA3D70A 
<br>
C20066EC 00000002 
<br>
C2C28028 EC2105B2 
<br>
FEC00890 00000000 

$16:9 Aspect Ratio (Widescreen) [NTSC-U]  
04416B74 3F9A7643

Download: [v2.1.1 October 4th 2020](https://github.com/quinton-ashley/Super_Mario_Sunshine_UHD_Texture_Pack/releases/latest/download/GMS.7z)

Download: [SMS UHD Update Patch 1](https://github.com/quinton-ashley/Super_Mario_Sunshine_UHD_Texture_Pack/releases/download/2.1.1/SMS_UHD_Update_Patch_1_DDS.7z)

Download this update patch (67MB) and add it to v2 of the pack! :)

This update adds M graffiti warp textures by cheatfreak47, a font texture fix by Scall, a new North American title texture by qashto (me) that was upscaled from the SMS title in Super Mario 3D All Stars, and an alternate North American title texture which is an original vector art style rendering made by twitter user [@WhaddupNico](https://twitter.com/WhaddupNico/status/1284291766305329152).

Download: [PS4 button textures add-on by Rocketboy95](https://github.com/quinton-ashley/Super_Mario_Sunshine_UHD_Texture_Pack/releases/download/2.1.1/SMS_PS4_Button_Textures.zip)


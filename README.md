The latest version includes RetroArch native presets. Reshade is not needed for these. </br></br>
Kyubus Shader is a collection of Reshade and RetroArch retro CRT presets using existing shaders such as CRT-Guest, CRT-Royale and CRT-Lottes. I do not take credit for creating these shaders, they are just included for convenience. The Look-Up-Texture (LUT) and preset settings are my work.

![screenshot](https://i.postimg.cc/4Nm7GD4X/assd.jpg)
[![Video Preview](https://i.postimg.cc/Pq497tpj/thumb.jpg)](https://youtu.be/O5lSHXT0TVg)

Preview video: https://youtu.be/O5lSHXT0TVg

These presets are mainly developed for a monitor resolution of 1440p. But presets for 1080p and 4k monitors are included.

Reshade shader installation: </br>
#1 To use the Reshade shaders, you need to download the latest version of Reshade from the official website: https://reshade.me/ </br>
#2 Open the .exe and follow the instructions, after chosing the the correct rendering API you can skip the remaining steps. </br>
#3 Copy the "reshade-shaders" folder and the "reshade.ini" from the zip file to the folder of the game or emulator's executable, and overwrite the .ini file. Then copy preset files from either the "1440p-" or "1080p-monitor-presets" folder to the same location. So the structure will look like this: </br>
📁game folder </br>
├─📁 reshade-shaders </br>
├─🎮Game.exe </br>
├─📄ReShade.ini </br>
├─📄kyubus-CRTguest-ntsc-mask-HD.ini </br>
├─📄kyubus-CRTguest-ntsc-scanline-SD.ini </br>
├─📄kyubus-... etc

RetroArch shader installation: </br>
#1 Place the files from the zip file "kyubus-extras/RetroArch-native-shader" folder in the "RetroArch root\shaders\" folder </br>
#2 Then in retroach while in game, open the Quickmenu with F1 > shaders > load > kyubus-crtguest.slangp

Reshade Hotkeys:</br>
Home 				: Brings up the ReShade interface </br>
` 					: Toggle the current preset </br>
Alt Gr + . 	: Next preset </br>
Alt Gr + , 	: Prevrious preset

To make the lower resolution shader display correctly RetroArch(or any emulator) integer scaling needs to be switched ON ( Settings>video>scaling).

Suggested apps to use Reshade with: </br>
ShaderGlass - System wide desktop shading </br>
MPC-BE - The only media player I know Reshade can be enabled with (dx9) </br>
RetroArch - Emulation.  ( Optional: Look up the WindowCast core for shading ANY application inside RetroArch. It is buggy though, and not a standard core included with the RetroArch installer at the moment of writing  )

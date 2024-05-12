Kyubus Shader is a collection of Reshade and RetroArch retro CRT presets using existing shaders such as CRT-Guest, CRT-Royale and CRT-Lottes. I do not take credit for creating these shaders, they are just included for convenience. The Look-Up-Texture (LUT) and preset settings are my work.

<img src="https://i.postimg.cc/ysF1bW0f/collag2e.jpg" href="https://i.postimg.cc/ysF1bW0f/collag2e.jpg" target="_blank">

Preview video: https://youtu.be/O5lSHXT0TVg

These presets are mainly developed for a monitor resolution of 1440p and 1080p (16:9)

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

For better results on low resolution scanline presets (like CRTguest-ntsc-scanline-SD) INTEGER scaling needs to be switched ON ( RetroArch>Settings>video>scaling).

(Optional) Native RetroArch shader installation:  </br>
#1 Place the files from the zip file "kyubus-extras/RetroArch-native-shader" folder in the "RetroArch root\shaders\" folder </br>
#2 Then in retroach while in game, open the Quickmenu with F1 > shaders > load > kyubus-crtguest.slangp

Reshade Hotkeys:</br>
Home 				: Brings up the ReShade interface </br>
` 					: Toggle the current preset </br>
Alt Gr + . 	: Next preset </br>
Alt Gr + , 	: Prevrious preset </br>

Suggested apps to use Reshade with: </br>
ShaderGlass - System wide desktop shading </br>
MPC-BE - The only media player I know Reshade can be enabled with (dx9) </br>
RetroArch - Emulation.  ( Optional: Look up the WindowCast core for shading ANY application inside RetroArch. It is buggy though, and not a standard core included with the RetroArch installer at the moment of writing  )

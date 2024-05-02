The latest version includes RetroArch native presets. Reshade is not needed for these. </br></br>
Kyubus Shader is a collection of Reshade and RetroArch retro CRT presets using existing shaders such as CRT-Guest, CRT-Royale and CRT-Lottes. I do not take credit for creating these shaders, they are just included for convenience. The Look-Up-Texture (LUT) and preset settings are my work. Shader presets that ar friendly for streaming and video encoding are included.

(https://i.postimg.cc/ZqnJX1XN/duckstation-qt-x64-Release-LTCG-2024-05-02-20-48-59.jpg)
[![Video Preview](https://i.postimg.cc/3x8k0GyN/thumb.jpg)](https://youtu.be/8yyFveYiMFg)

Preview video: https://youtu.be/8yyFveYiMFg

These presets are mainly developed for a monitor resolution of 1440p. But presets for 1080p and 4k monitors are included.

Reshade shader installation: </br>
#1 To use the Reshade shaders, you need to download the latest version of Reshade from the official website: https://reshade.me/ </br>
#2 Open the .exe and follow the instructions, after chosing the graphics API you can skip the remaining steps. </br>
#3 Copy the contents of this zip file to the game or emulator's executable, and overwrite the .ini file.

RetroArch shader installation: </br>
#1 Place the files from the zip file "/kyubus-extras/RetroArch-native-shader" folder in the "RetroArch base\shaders\" folder </br>
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
RetroArch - Emulation. Look up the WindowCast core for shading ANY application inside RetroArch! It is not a standard core included with the RetroArch installer at the moment of writing.

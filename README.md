Now the latest update includes a native RetraArch shader using crt-guest! </br></br>
Kyubus Shader is a collection of Reshade and RetroArch retro CRT presets using existing shaders such as CRT-Guest, CRT-Royale and CRT-Lottes.

[![Video Preview](https://i.postimg.cc/3x8k0GyN/thumb.jpg)](https://youtu.be/8yyFveYiMFg)

Preview video: https://youtu.be/8yyFveYiMFg

These presets are mainly developed for a monitor resolution of 1440p. But presets for 1080p and 4k monitors are included.

#1 To use this you need Reshade, download the latest version here: https://reshade.me/ </br>
#2 Open the .exe and follow the instructions, after chosing the graphics API you can skip the remaining steps. </br>
#3 Copy the contents of this zip file to the game or emulator's executable.

Hotkeys:</br>
Home 				: Brings up the ReShade interface </br>
` 					: Toggle the current preset </br>
Alt Gr + . 	: Next preset </br>
Alt Gr + , 	: Prevrious preset

To make the lower resolution shader display correctly RetroArch(or any emulator) integer scaling needs to be switched ON ( Settings>video>scaling). I also recommend trying RetroArch shaders underneath such as "/xbr/super-xbr-fast.slangp"(Set Input and Output gamma to 1.0 in shader parameters) and "/cubic/catmull-rom-fast.slangp". In case those aren't available I suggest setting the preset to one where GaussianBlur is enabled. GaussianBlur and LumaSharpen are probably the first parameters you might want to adjust depending on the resolution of the content and your preferences.

Suggested apps to use Reshade with: </br>
ShaderGlass - System wide desktop shading </br>
MPC-BE - The only media player I know Reshade can be enabled with (dx9) </br>
RetroArch - Emulation

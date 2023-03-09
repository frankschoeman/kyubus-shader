Kyubus Shader is a collection of Reshade retro CRT presets using existing shaders such as CRT-Royale and CRT-Lottes.

[![Video Preview](https://i.postimg.cc/DyyK5JpR/Screenshot-555.jpg)](https://youtu.be/FLy9ADAiZF8)

Preview video: https://youtu.be/FLy9ADAiZF8

These presets are developed for a monitor resolution of 1440p. A few 1080p monitor presets are included.

To make the lower resolution shader display correctly RetroArch(or any emulator) integer scaling needs to be switched ON ( Settings>video>scaling). I also recommend trying RetroArch shaders underneath such as "/xbr/super-xbr-fast.slangp"(Set Input and Output gamma to 1.0 in shader parameters) and "/cubic/catmull-rom-fast.slangp". In case those aren't available I suggest enabling GaussianBlur. If you find the image is "jittering" too much then find Deband and reduce the Range or disable entirely. GaussianBlur and LumaSharpen might need to be adjusted or disabled depending on how the original image is filtered.

#1 To use this you need Reshade, download the latest version here: https://reshade.me/

#2 Open the .exe and follow the instructions, after chosing the graphics API you can skip the remaining steps.

#3 Copy the contents of this zip file to the game or emulator's executable.

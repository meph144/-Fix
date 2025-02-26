# -Fix
If you already have the game, do a clean reinstall and make sure the entire documents\my games\nosgoth folder is removed

Then, you need to place dxvk in your SteamLibrary\steamapps\common\nosgoth\Binaries\Win32 folder  

https://github.com/doitsujin/dxvk/releases/download/v2.5.3/dxvk-2.5.3.tar.gz
To play safe apply all changes in this guide before launching the fresh install

# Set up the Video Driver Optimizations below 
# NVIDIA


Anisotropic filtering > off

Antialiasing > off

Low Latency mode > Ultra (this is a must)

Power management mode > Prefer maximum performance

Texture filtering - Anisotropic sample optimization > OFF

Texture filtering - Negative LOD bias > Allow

Texture filtering - Trilinear optimization > ON

Vertical sync > OFF (this is a must)

Virtual Reality pre-rendered frames > 1


# AMD

Same as NVIDIA but if they are named differently or missing google can help. 
Whatever lowers input lag and increases the performance of the game

# Replace the text in DefaultSystemSettings.ini with this 
https://github.com/meph144/-Fix/issues/1 or https://github.com/meph144/-Fix/issues/3
# And BaseSystemSettings.ini with this 
https://github.com/meph144/-Fix/issues/2 or https://github.com/meph144/-Fix/issues/4

## .ini File Locations

DefaultSystemSettings.ini is located in your SteamLibrary\steamapps\common\nosgoth\BCMPGame\Config folder

BaseSystemSettings is located in your SteamLibrary\steamapps\common\nosgoth\Engine\Config folder

# After launching the game
Go  to video settings and 

limit fps to 80

Make sure VSYNC is disabled

# To make your own
Do a backup of the .ini files before modifying them since it's not hard to make the game unplayable by changing those values.

TEXTUREGROUPs MaxLOD numbers you can use

2, 
8, 
16, 
32, 
64, 
128,  
256, 
512, 
1024, 
2048, 

Swapping True and False will Enable or Disable settings.

Optimize them to find what plays and looks best on your computer.


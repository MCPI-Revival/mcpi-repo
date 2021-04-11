# mcpi-texturepack
Code for adding texture packs into MCPI-Reborn.

> This repo is a upload of the code which was originally made by `NikZapp#6774` on Discord with minor tweaks to work with MCPI-Reborn. Here is a formatted version of the original README from NikZapp:

## MCPI Texturepack utility v1.1
Coded by NikZapp. This code is sadly not protected.

### Files not to touch:
 + `addpack.py`
 + `recoveryPack.mcpit`

`badgeFix.mcpit` changes the Minecon logo to an MCPI Approved logo, requested by @TheBrokenRail. `new_textures.mcpit` is a pack using `Bracket The Fox#6969`'s textures made from the newer version of Minecraft. `ZombiePigmanFix.mcpit` is a fix to the zombie pigman texture not showing the outside of heads.

### Features:
1. Install custom textures witout navigating in all the folders.
2. Every texture is fully customisable.
3. All textures are stored in one file.
4. Easy to use.

### Will be added soon:
 + [ ] HD Texture support!
 + [x] Autocompleting `gui_blocks.png` (how blocks look in your inventory)
 + [ ] More!

### How to use:
1. Execute the `addpack.py` file in the command line as root (using `sudo`, for example).
2. If you want to install a texturepack, input the path to it.
3. If you however want to remove all texturepacks, just press enter.

The `.mcpit` format is short for **M**ine**c**raft**PIT**exturepack.

To create a texturepack, follow these steps:
1. Put all of your textures in one folder. There should be no subfolders, like this:
 + Not to do:
```
/path/to/your/pack/gui/gui2.png
/path/to/your/pack/terrain.png
/path/to/your/pack/mob/creeper.png
```
 + To do:
```
/path/to/your/pack/gui2.png
/path/to/your/pack/terrain.png
/path/to/your/pack/creeper.png
```

2. Compress the textures using the `.zip` format:
```
/path/to/your/pack.zip/gui2.png
/path/to/your/pack.zip/terrain.png
/path/to/your/pack.zip/creeper.png
```
3. Rename the extension to `.mcpit`
```
/path/to/your/pack.mcpit/gui2.png
/path/to/your/pack.mcpit/terrain.png
/path/to/your/pack.mcpit/creeper.png
```

Done!

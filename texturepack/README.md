# mcpi-texturepack

Repo for Minecraft Pi texture packs. Designed for the MCPIL launcher.

## Texturepack descriptions

| Pack Name                                  | Pack Author/Uploader         |
| ------------------------------------------ | ---------------------------- |
| [new_textures](new_textures.zip)           | Added by RPi News            |
| [recoveryPack](recoveryPack.zip)           | Added by RPi News            |
| [badgeFix](badgeFix.zip)                   | Added by RPi News            |
| [ZombiePigmanFix](ZombiePigmanFix.zip)     | Added by RPi News            |
| [mcpi-plastic-pack](mcpi-plastic-pack.zip) | Created by [AbysssDevelopment](https://github.com/MCPI-Revival/mcpi-repo/commits?author=AbysssDevelopment)  |
| [MCPI-Xray v1.0](MCPI-Xray-v1.0.zip)       | Added by RPi News            |
| [Youdub-pack](Youdub-pack.zip)             | Created by Youdubham#3049    |

## MCPI Texturepack utility v1.1

> This repo is a upload of the code which was originally made by `NikZapp#6774` on Discord with minor tweaks to work with MCPI-Reborn. Here is a formatted version of the original README from NikZapp:

Coded by NikZapp. This code is sadly not protected.

### Files not to touch:
 + `addpack.py`
 + `recoveryPack.zip`

-`badgeFix.zip` changes the Minecon logo to an MCPI Approved logo, requested by @TheBrokenRail. 
-`new_textures.mcpit` is a pack using `Bracket The Fox#6969`'s textures made from the newer version of Minecraft. `ZombiePigmanFix.zip` is a fix to the zombie pigman texture not showing the outside of heads.
-`mcpi-plastic-pack.zip` is a pack made by [AbysssDevelopment](https://github.com/AbysssDevelopment), and is a recreation of the Minecraft Bedrock Plastic [texture pack](https://www.microsoft.com/en-us/p/minecraft-plastic-texture-pack/bxt9xgfbcb2g).

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

Done!
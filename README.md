# mcpi-central-repo
A repo for worlds and servers in MCPI-Central\MCPIL. MCPI-Repo is designed to serve as a "Minecraft Marketplace" of sorts for maps and worlds in MCPIL.

## [Worlds](/worlds/)
Worlds are stored in the `mcpiw` format, which is just a renamed zip file. It stands for:  
```
MineCraftPIWorld
^   ^    ^^^
```
To open a world just download it, and rename it to .zip (for example `coolworld.zip` > `coolworld.mcpiw`).
Move it to ~/.minecraft/games/com.mojang/minecraftWorlds/ if you are using MCPIL/MCPI-Reborn

### Submitting worlds
Worlds should be in a zip file, renamed to a `.mcpiw` file extension, and with a root directory containing the world files. Its root folder, and the `level.dat` file's world named inside it should have exactly the same name. To edit the `level.dat` file, see [MCPIedit](https://github.com/MCPI-Revival/MCPIedit). The root folder should not contain the following files or directories:
 + `player.dat`
 + `level.dat_old`
 + `players/`

An example of a submitted world looks like this:  
─ CoolWorld.mcpiw<br />
 │  
 CoolWorld(folder)  
  │─ chunks.dat  
  │─ entities.dat  
  │─ level.dat(Name must be the same as world folder when opened with [MCPIedit](https://github.com/MCPI-Revival/MCPIedit))  
  
Alongside your MCPIW file feel free to submit a LICENSE file for your world and a screenshot so people know what your world looks like!

## Servers
Servers are stored in a JSON format, with a IP address and a port number.

## [Seeds](/seeds/)
Seeds can be added to the table under the "Seed descriptions" heading of [README.md](https://github.com/MCPI-Revival/mcpi-repo/blob/main/seeds/README.md). Put your seed in the column labeled "Seed" and write a brief description about the world generated with your seed.

## Resource packs
Resource packs/texture packs are stored in the `mcpit` format, which is a renamed zip file. It is short for:  
```
MineCraftPITexturepack
^   ^    ^^^
```

More info can be found at [https://github.com/MCPI-Revival/mcpi-texturepack](https://github.com/MCPI-Revival/mcpi-texturepack).

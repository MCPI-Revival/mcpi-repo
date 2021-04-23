# MCPI-Repo
A repo for worlds and servers in MCPI-Central/MCPIL. MCPI-Repo is designed to serve as a "Minecraft Marketplace" of sorts for maps and worlds in MCPIL.

## [Worlds](worlds/)

### Importing Worlds
To open a world just download it.
Move it to ~/.minecraft/games/com.mojang/minecraftWorlds/ if you are using MCPIL/MCPI-Reborn

### Submitting Worlds
Worlds should be in a zip file, with a root directory containing the world files. it's root folder, and the `level.dat` file's world name should be exactly the same. To edit the `level.dat` file, use [MCPIedit](https://github.com/MCPI-Revival/MCPIedit).

The root folder should not contain the following files or directories:
- `player.dat`
- `level.dat_old`
- `players/`

An example of a submitted world looks like this:
```
.
└── CoolWorld.zip
    └── CoolWorld(folder)
        ├── chunks.dat
        ├── entities.dat
        └── level.dat
```
  
Alongside your .zip file you must add an entry to `worlds.json`, but feel free to submit a `LICENSE` file for your world and a screenshot so people know what your world looks like!(if you do submit a screenshot/license please make it in it's own folder instead of just uploading them to /worlds, like eg `/worlds/CoolWorld/CoolWorld.zip + other files` instead of `/worlds/CoolWorld.zip and other files`)

## [Servers](servers/)
Servers are stored in a JSON format, with a IP address and a port number.

## [Seeds](seeds/)
Seeds can be added to the table under the "Seed descriptions" heading of [README.md](https://github.com/MCPI-Revival/mcpi-repo/blob/main/seeds/README.md). Put your seed in the column labeled "Seed" and write a brief description about the world generated with your seed.

## [Resource Packs](texturepack/)
Resource packs/texture packs are stored in the zip format. MOTE: As of now the texturepacks system does NOT work with mcpi-reborn's overrides system.

More info can be found at [https://github.com/MCPI-Revival/mcpi-texturepack](https://github.com/MCPI-Revival/mcpi-texturepack).

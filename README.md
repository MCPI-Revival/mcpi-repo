# mcpi-central-repo
A repo for worlds and servers in MCPI-Central

## Worlds
Worlds are stored in the `mcpiw` format, which is just a renamed zip file. It stands for:  
```
MineCraftPIWorld
^   ^    ^^^
```

### Submitting worlds
Worlds should be in a zip file, with a root directory, and the zip file, its root folder, and the `level.dat` file inside it should have exactly the same name. To edit the `level.dat` file, see [MCPIedit](https://github.com/MCPI-Revival/MCPIedit). The root folder should not contain the following files or directories:
 + `player.dat`
 + `level.dat_old`
 + `players/`

## Servers
Servers are stored in a JSON format, with a IP address and a port number.

## Resource packs
Resource packs/texture packs are stored in the `mcpit` format, which is a renamed zip file. It is short for:  
```
MineCraftPITexturepack
^   ^    ^^^
```

More info can be found at [https://github.com/MCPI-Revival/mcpi-texturepack](https://github.com/MCPI-Revival/mcpi-texturepack).

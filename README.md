# mina

> (Min)ecraft packages for (A)rch Linux. Servers can be fun. Enter, install and play.

- Easy modding
- World backup when installing mods
- Always the latest versions of mods
- Automatically installing dependencies

## Quick Start

First you need to install the server. This repository currently only supports mods for Forge. Quilt and Fabric coming soon.

```sh
yay -S forge-server
```

## Modding

Do you want to install the mod? No problem.

### Format
```sh
yay -S forge-server-$modname
```

**Arguments:**

- `modname`: the name of the mod to be installed


### Example

> AOA [Advent of Ascension (Nevermine)](https://www.curseforge.com/minecraft/mc-mods/advent-of-ascension-nevermine)

```sh
yay -S forge-server-aoa
```

And that's all! When installing the mod, all the necessary dependencies will be installed and the world will be automatically backed up and the server restarted.

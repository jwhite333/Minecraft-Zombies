# Minecraft-Zombies

![alt text][gameplay]

[gameplay]: ./readme-resources/gameplay.png "Gameplay"

# Prerequisites
1. Minecraft: https://minecraft.net/en-us/

# 1. Installing
## 1.1. Clone this repository
>Note: If using the `"Download as .zip"` method, make sure to rename the folder to exclude the `-master` extension

![alt text](./readme-resources/rename.png "Extracting")

## 1.2 Copy the folder into the appropriate Minecraft save location
(Windows)

![alt text](./readme-resources/folder-location.png "Save Location")

(Linux)
```bash
# From command line:
cp -r ~/Downloads/Minecraft-Zombies ~/.minecraft/saves
```

# 2. Game Setup
Due to changes in the Minecraft 1.13 release, this game only works as of release 1.12.x. This isn't a problem though since we can use the launcher to select this release instead

## 2.1 Start the Minecraft Launcher and select `Launch options`

![alt text](./readme-resources/launcher-options.png "Launch Options")

## 2.2 Add release 1.12.x as an alternate option

![alt text](./readme-resources/release-12.2.png "Adding release 1.12.x")

## 2.3 Awesome, Now you just have to select release 1.12.x before you click play!
![alt text](./readme-resources/selecting-other-version.png "Selecting version 1.12.x")

# 3. Playing
Start Minecraft and check out the level you just added!

![alt text](./readme-resources/levels.png "Level")
>Note: If nothing shows up at this screen, check that you have copied the folder to the correct location, and that no parent folders exist

    (Desired file structure)
    .../minecraft/saves/
    └── Minecraft-Zombies/
       ├── advancements/
       ├── data/
       └── etc...

    (Possible incorrect file structure)
    .../minecraft/saves/
    └── Minecraft-Zombies-master/       <-- Incorrect parent folder
        └── Minecraft-Zombies-master
            ├── advancements/
            ├── data/
            └── etc...

## Ok I'm in game, now what?

### 1. You should have spawned in the main room. No Zombies will spawn yet, but that's a good thing
#### Locate the "Reset" and "Start" buttons (under the stairs) and press them in that order: Reset, then Start
![alt text](./readme-resources/start-reset.png "Start and Reset Buttons")

### 2. Cool! You just started the game!
#### You were just teleported to the center of the first room, given 3 Grenades and 200 points
#### Oh, also Zombies are spawning...
![alt text](./readme-resources/game-start.png "Initial Spawn")

>You will notice the gamemode is now "Adventure", so don't worry about breaking blocks

> Also you have a small health regeneration enchantment, but it's quite slow!

### 3. Use your points to buy weapons or open doors, just like the real game
![alt text](./readme-resources/sword-buying.png "First Sword")

### 4. Survive!
#### Tip: Grenades can help a lot, but don't give you any points
![alt text](./readme-resources/grenade.png "Grenade!")

# Editing
It is Minecraft after all, what if you want to make changes?
#### Go crazy! And submit a pull request if you make something you want to share
>The program structure is entirely made up of command blocks placed in and around the map. The core functions are outside:

![alt text](./readme-resources/creative.png "Main functions")

>But room/weapon purchases are built-in.

![alt text](./readme-resources/creative-outside.png "Weapon Purchasing")

#### Helpful links for using command blocks (Just remember it needs to be for release 1.12):
* https://minecraft.gamepedia.com/Commands
* https://minecraft.gamepedia.com/Scoreboard
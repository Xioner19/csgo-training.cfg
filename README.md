# CS:GO TRAINING.CFG by Xioner19

Best commands to train on a map of new grenades in one file!

Hello ! Recently, when I was running a map to practice, I was thinking whether or not to throw a file with my commands on the Internet. Why should I use such a good config to train myself? So I send a slightly modified version to the Internet.

## Table of contents
* [Installation](#installation)
* [Usage](#usage)
* [Support](#support)
* [Changelog](#changelog)
* [License](#license)

## Installation 

Merge the `/csgo/cfg` folder with your `/steamapps/common/Counter-Strike Global Offensive/csgo/` folder.

This adds only 1 file to your /csgo/cfg folder. It does not overwrite any game files and does not interfere in any way with the game. It is safe for VAC and remember that you can only use this file on your own server.

### Downloading

**Method 1.**
Manually download the repositorium by clicking [**HERE**](https://github.com/Xioner19/csgo-training.cfg./archive/master.zip). Then extract the folder.

**Method 2.**
On Windows 10 17063 or later, run the [`install_csgo-training.cfg.bat`](https://raw.githubusercontent.com/xioner19/csgo-training.cfg/master/install_csgo-training.cfg.bat) file to automatically download the script into your game files. It can also be used to update the script.

**Method 3.**
In bash, after changing the directory below to your Steam game library directory, use the following commands to install the script into your game files.
```
cd "C:/Program Files/Steam/steamapps/common/Counter-Strike Global Offensive/" && 
curl https://codeload.github.com/xioner19/csgo-training.cfg/tar.gz/master | tar -xz --strip=1 csgo-training.cfg/csgo
```

### IMPORTANT

You have to paste your viewfinder in the 115 line (`alias "-crosshairsmoke"`) of the cfg file. Otherwise, when you press the key responsible for this, it will set my crosshairsmoke :P

## Usage

Use the console commands to load and control the file. 

Button              | Description
------------------- | -------------------
`exec training`     | Load the file
---                 | ---
`F1`                | Makes BunnyHop mode switchable. The first mode is a normal Bhop as on normal servers and the second one is an automatic jump enabled when holding a spacebar
`F2`                | Will show you values for where exactly on the map you are located. This will appear in the top left of your screen by default. It also shows your velocity (run speed)
`F8`                | Changes the JumpThrow mode [See below](#jumpthrowmodes)
---                 | ---
`T`                 | It changes the speed of the game after the holding
`Y`                 | Extinguish smoke
`U`                 | It's throwing the last grenade we threw again
`I`                 | Makes it so that extra information, including the damage dealt, the distance the bullet travelled, etc is printed at bullet impact locations
`O`                 | Makes highlight through player walls and objects, creating a wall hack/X-Ray effect
`P`                 | Makes show live trajectories of the grenade flight when the pin is pulled out
`[`                 | Save a place to teleport
`]`                 | It teleports us to a previously saved position
---                 | ---
`CAPSLOCK`          | Shows the grenade crosshair on the screen
`H`                 | Makes display invisible walls in the map. Useful for looking for pixelwalk's
`K`                 | Makes show the bullet impacts (Default ON)
---                 | ---
`C`                 | When is on (noclip), you can fly and will pass through solid objects like walls
`/`                 | It adds all the grenades
---                 | ---
`MOUSE3`            | Makes stop the trajectory of the currently held grenade for a certain number of seconds
---                 | ---
`INSERT`            | Makes place a BOT on the server depending on where the player's crosshair is located
`HOME`              | Makes a BOT crouch
`PAGE UP`           | It adds BOT to TT
`DELETE`            | It kick all the BOTs out of the server
`END`               | Make the BOT start following the player
`PAGE DOWN`         | It adds BOT to CT


#### JUMPTHROWMODES

JumpThrow Modes     | Description
------------------- | -------------------
NORMAL              | Jump and throw
EXTENDED            | jump and throw with crouch. Slightly extends the range
EXTENDED+           | Jump, crouch and step forward. Extends the range considerably

### Changing map

Changing maps is very easy. Just write the name of the map in the console e.g. `mirage` and the map will change to `de_mirage`

## Support

#### How can you help me?

In private message `Xioner19#6215` write me what I could add to the current config, i.e. new binds, aliases or commands....

...or you can surprise me by sending some skin to the weapons here --> https://steamcommunity.com/tradeoffer/new/?partner=258608059&token=YHSUg6JU. - THANK YOU !

## Changelog

#### 2020-05-01 [v.1.0.0]
\- Public release


## License

You are free to use, modify and share this script under the terms of the GNU GPLv2.0 license. In short, you must keep the copyright notice, and make your modifications public under the same license if you distribute it.






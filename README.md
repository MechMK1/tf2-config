# tf2-config

These are [my](https://steamcommunity.com/id/mechmk1/) configuration files for Team Fortress 2. They are based on [configuration files](https://www.youtube.com/watch?v=cRGW4a1K_Io) by [a Woolen Sleevelet](https://www.youtube.com/channel/UCIKlNynwbTJVNH2M8i9yGhw).

According to his README.txt file, it is free to use and share. Exact text:
> Feel free to use any of these however you like.

## What does this include?
It includes launch options, network settings, crosshair settings, misc fixes, keybinds for all classes and a bit more.

## How do I install this?

Note, these instructions are based on Windows. If you use Linux, I assume that you know what you are doing.

1. **Important!** Set your configuration file as "read-only". To do this, open explorer and go to the directory of the game. The file you are looking for is found in `tf/cfg/config.cfg`. Right-click on it, then select "read-only". (On some locales, it might be more similar to "write-protected". Use your head.) This is done so that no permanent changes are done to your configuration in case you don't like the config.
2. Create a backup of the `tf/cfg/` directory. This only matters if you already use custom scripts.
3. Download or clone the repository.
4. Extract everything from `tf/cfg/` to the same directory in your Team Fortress 2 installation. It should be the same directory where `tf/cfg/config.cfg` resides in.
5. *Optional:* Extract everything from `tf/custom/` to the same directory in your Team Fortress 2 installation. This installs a custom hit- and killsound.

## How do I uninstall this?

1. Delete the `tf/cfg/` directory and replace it with the backup you made.

### But MechMK1, I didn't make a backup because backups are for noobs.

1. Delete `tf/cfg/autoexec.cfg`.
2. Remove the "read-only" flag from `tf/cfg/config.cfg`.
3. Stop being dumb.

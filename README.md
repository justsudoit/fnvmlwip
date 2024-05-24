# Title WIP

Wabbajack Modlist Installer by physicsgaming.

<table stlyle="border: none;">
<tr>
<td><a href="https://github.com/justsudoit/fnvmlwip/blob/main/Changelog.md">Changelog</a></td>
<td><a href="https://github.com/wabbajack-tools/wabbajack/releases">Download on Wabbajack</a></td>	
<td><a href="https://loadorderlibrary.com">Load Order Library</a></td>
<td><a href="https://discord.gg"><img alt="Discord" src="https://cdn.logojoy.com/wp-content/uploads/20210422095037/discord-mascot.png" width="64px" ></a></td>
</tr>
</table>

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

## Preamble

**Title WIP** is a Fallout New Vegas modlist that aims to freshen up the visuals and core gameplay for a modern audience, featuring:
 - Hundreds of high quality models and textures (very few vanilla assets remain in place)
 - A complete overhaul of weather and lighting
 - A revamped sound track, with many new songs and ambient sounds
 - Many new locations to explore
 - Many overhauls to existing locations
 - Modern, high quality reload/attack animations for every weapon in the game
 - New animations for many misc. actions, such as interacting with world objects, using ingestibles, etc.
 - New gameplay mechanics such as weapon bashing, sprinting and leaning
 - Picture in picture scopes
 - Fast paced, lethal combat
 - Extensive custom patching and balance tweaks to make the hundreds of included mods feel like a consistent, cohesive experience


## System Requirements

Only the english Steam and GOG versions of the game are supported. Any other versions of the game will not work.

Only, Windows 10 and 11 work with Wabbajack fully. LTSC, special variants, lightened editions or any other modified variant **WILL NOT WORK**. Your windows version **must be 21H2 or newer** to run Wabbajack.

Running the list from Hard Disk Drives or external drives is **STRONGLY ADVISED AGAINST**. A lot of high quality models and textures are used and, as a result, fast storage and RAM are needed.


### Recommended System Requirements

**Title WIP** requires a mid-tier modern system to run to its fullest potential.

| Component    | Recommendation | 
|:--------------:|:-------------:|
| CPU | 8th Generation i5 or better/equivalent
| Ram | 16GB DDR4 Ram  + 40GB Pagefile 
| Storage | 250GB Solid State Drive
| GPU | A card with 8GB VRAM or higher

Space required: ~30GB Download Size ~30GB install Size ~60GB Total

See how to setup a page file here: https://www.tomshardware.com/news/how-to-manage-virtual-memory-pagefile-windows-10,36929.html


## Installation

Installing **Title WIP** is relatively easy and, if you have Nexus Premium, will be a simple waiting game. If you are updating the modlist, you can safely skip to the [updating section](#updating-the-modlist).


### Pre-Installation

Prior to installing **Title WIP**, please complete the following steps.
_If you know that you have a completely unmodified game **and** it is NOT installed in a Windows Protected folder, you can safely skip steps 2 & 3_

1. Update you VC++ [Runtime Libraries](https://www.techpowerup.com/download/visual-c-redistributable-runtime-package-all-in-one/)
2. Fully uninstall New Vegas through Steam/GOG then delete the game folder and the FalloutNV folder inside \Documents\My Games\.
3. Reinstall New Vegas into a location that is not Program files. Somewhere like `C:\Games` is a good location. If you only have one drive, look into LostDragonist's [SteamLibrary tool](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide).
4. Fully disable OneDrive and any other programs which hook into user file areas.
5. Start the game once and let it do the graphics check. Do not worry about the settings as it will be replaced during installation.
6. Launch the game to the main menu then quit to desktop.
7. Remove/Disable any 3rd party antivirus such as MalwareBytes or Webroot. These **will** mess with the installation and, in the case of the latter, causes more problems than it solves.

***

### Wabbajack Installation

#### Installing Wabbajack

Once you have completed pre-installation, download the [latest version of Wabbajack]((https://github.com/wabbajack-tools/wabbajack/releases)) and place it in a folder such as `C:\Games\Wabbajack`. Do not place it in program files, on your desktop or in your downloads folder. I recommend placing it on an SSD as it will work quicker on there.

#### Downloading and Installing **Title WIP**

Downloading and installing **Title WIP** can take a while depending on your internet connection and computer. To install, complete the following steps.

1. Open Wabbajack and click on browse modlists.
2. Press the download button on **Title WIP** and wait for it to download.
3. Set the installation folder to be somewhere like C:\Title WIP. **Do not install it to your desktop or downloads folder.**
4. The download location does not need to be on a SSD but it makes installing a bit faster.
5. Press the play button to begin.
6. If the installation is successful, jump for joy and move onto [post installation](#post-installation). If the installation is unsuccessful, follow what is below.

***

##### Problems with installation

It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below.

- Could not download x:
	- Big files can fail to download due to connection issues. You can either run Wabbajack again or download the file manually. If you decide to manually download it, make sure to place it in the same place as the other downloads.

- Wabbajack could not find my game folder:

	- Either buy the game or go back to the [Pre-Installation](#pre-installation) step.

- Antivirus reports a virus:
	- You did not follow the steps in [Pre-Installation](#pre-installation). Go back and follow it.
	- If you have followed it then you can fix this by [adding an exclusion for Mod Organizer in Windows Defender](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## Post-Installation

### Stock Game

**Title WIP** utilizes a Wabbajack technology called Stock Game. What this essentially does is create a copy of your New Vegas installation within the installation location of the list. This enables greater compatibility with other mod-lists. You can find this folder in your installation directory, it is called **\[NoDelete\] Stock Game**

**Before running Mod Organizer, you MUST perform these steps**
1. Navigate to your game installation folder (where you installed the game through Steam or GOG)
   - Steam Users: Copy FalloutNV.exe, FalloutNVLauncher.exe and steam_api.dll and paste them in the Stock Game folder
   - GOG Users: Copy FalloutNV.exe, FalloutNVLauncher.exe, GalaxyWrp.dll and Galaxy.dll and paste them in the Stock Game folder
2. From the Stock Game folder, double click FNVpatch.exe
3. From the modlist folder, open the BSA Decompressor folder and run FNV BSA Decompressor.exe
   - For the path to your Fallout New Vegas installation, point it to the Stock Game Folder
   -  For the path where your decompressed BSAs should be stored, point it to \<modlist folder\>\\mods\\\[NoDelete\] Decompressed BSAs
   -  [Example](https://raw.githubusercontent.com/justsudoit/fnvmlwip/main/pictures/BSA%20Decompressor.png)

### OPTIONAL MODS - ULTRAWIDE SUPPORT

**DXVK is installed by default, it is required for AMD graphics cards. If you have an NVIDIA graphics card, you _may_ have better performance without it. To uninstall it, simply delete d3d9.dll from the Stock Game folder, and set bFull Screen = 1 in falloutcustom.ini**
_Without DXVK, you will lose the ability to alt-tab without crashing the game._

**Title WIP** comes with several list customization options. There is ultrawide support under the "Ultrawide Support" section of Mod Organizer 2.


### Starting up the list
Open the installation folder and double-click on the program called `ModOrganizer.exe`. 

Make sure the dropdown box on the right is set to `New Vegas` and press the `Run` button.

### In-game MCM options

All the MCM options are pre-configured for you, I advise against tweaking them other than to adjust the FOV in FOV Slider or to change the keybinds for B42 Bash, Visual Objectives (under Just Assorted Mods) or Sprinting (under Enhanced Movement).


### Character Build important information

1. The list uses [Charisma Tweaks,](https://www.nexusmods.com/newvegas/mods/71310) I recomend reading that mod page to understand what it does.
2. Read the description of each SPECIAL stat carefully, as they have updated descriptions to reflect how they behave in the list.
3. Your skills start lower than in vanilla.
4. Intelligence has NO EFFECT on your skill points when leveling, you will always get 10 points.
5. TAG skills increase at double the normal rate, meaning 1 point spent on a TAG skill will increase the skill level by 2.
6. You will not get the chance to revise your character when leaving Goodsprings.


### Default Hotkeys

To see the keybinds for mouse and keyboard, press 'k' while at the pause menu.

For controller, see the Control Map pdf in the modlist folder.

There are a couple of keybinds setup to use thumb buttons on a mouse (buttons 4 and 5, aka forward and backward). They are weapon bashing and walk/run toggle respectively. If you do not have a mouse with thumb buttons, you can rebind run in the settings/controls menu and the weapon bashing hot key is in the MCM under B42 Bash.


### Gameplay Tips

- The list was balanced around Normal difficulty and Hardcore mode.
- This list uses [Physics' Based Ballistics](https://www.nexusmods.com/newvegas/mods/82561) which means that you will need to compensate for bullet drop and travel time at longer ranges.
- Speech checks will appear as normal dialogue options and you will not be notified of a pass or failure of a speech check. This tweak is meant to enhance roleplay, simply pick the dialogue options you feel best fit your character.
- Power armour is extremely tough. To take someone down who is wearing it, you will want very high damage weapons, AP ammo, explosives, weapons with the EMP effect etc.


## Updating the modlist

Before updating, please check the changelog and back up your saves. You may need to start a new game after certain updates.

Updating is like installing the list, but you do NOT need to perform the Post Installation steps. Simply make sure your paths are the same as where you installed the list and tick the `overwrite existing modlist` button. **Note**: Any mods you have added will be deleted when updating. Also, your keybinds will be reset to the defaults that I set up for the list, so if you customize your keybinds you will need to redo that after an update.

## Removing the Modlist
Simply delete the folder, and you have uninstalled it.

## Credits and Thanks

- _YOU_ for reading this.
- Halgari and everyone on the WJ Team - Wabbajack is awesome and so are you.

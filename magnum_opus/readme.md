# Magnum Opus

- [Magnum Opus](#magnum-opus)
- [Preamble](#preamble)
- [Installation](#installation)
  - [Pre-Installation](#pre-installation)
    - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
    - [Steam Config](#steam-config)
      - [Disable the Steam Overlay](#disable-the-steam-overlay)
    - [Change Steams Update Behavior](#change-steams-update-behavior)
    - [Set the Game language to English](#set-the-game-language-to-english)
    - [Clean Fallout 4](#clean-fallout-4)
    - [Start Fallout 4](#start-fallout-4)
  - [Using Wabbajack](#using-wabbajack)
    - [Preparations](#preparations)
      - [Problems with Wabbajack](#problems-with-wabbajack)
  - [Post-Installation](#post-installation)
    - [Copy Game Folder Files](#copy-game-folder-files)
- [Updating](#updating)
- [BiRaitBec Texture Optimization](#biraitbec-texture-optimization)
- [Noteworthy Mods](#noteworthy-mods)
  - [Sim Settlements 2](#sim-settlements-2)
  - [Subway Runner](#subway-runner)
  - [This is Trash - A Scrapping Alternative](#this-is-trash---a-scrapping-alternative)
  - [Buffout 4](#buffout-4)
- [In-Game MCM Options](#in-game-mcm-options)
- [FAQ](#faq)
- [Widescreen Support](#widescreen-support)
- [Controller Support](#controller-support)
- [ENB](#enb)
- [Credits and Thanks](#credits-and-thanks)
- [Contact](#contact)

# Preamble

### Magnum Opus ![build-status](https://img.shields.io/endpoint?label=%20&url=https%3A%2F%2Fbuild.wabbajack.org%2Flists%2Fstatus%2Fmagnum_opus%2Fbadge.json)

Magnum Opus is what one would describe as a "kitchen sink list." There is no specific focus or aspect I really care about. There is no specific goal I'm trying to achieve. I just want to have fun.

This means if I like a mod, it's going in. There is no such thing as "it doesn't fit my aesthetic" or "it goes against the theme of the list." The theme is fun.

To that end, I like new content. I like new areas, new quests, new NPCs, new weapons, new outfits, new faces. You'll find all of that - and a whole lot more - in this list. I genuinely hope you enjoy it as much as I do.

This list is NOT built with Survival Mode in mind. I don't play it. I don't like it. If you want Survival, you should play [Fallout 4 Enhanced Edition](https://www.wabbajack.org/#/modlists/info?machineURL=fallout_4_enhanced_edition).

## Installation

### Pre-Installation

You need a legal copy of Fallout 4 through Steam, with all DLCs **EXCEPT** the High Definition DLC. This is garbage and should not be used in any case ever.

These steps are only needed if you install this Modlist for the first time. If you update the Modlist, jump straight to [Updating](#updating).

#### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. The package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

#### Steam Config

##### Disable the Steam Overlay

The Steam Overlay can cause issues with ENB and is recommended to be turned off.

Open the Properties window (right click the game in your Library->Properties), navigate to the _General_ tab and un-tick the _Enable the Steam Overlay while in-game_ checkbox.

#### Change Steams Update Behavior

Fallout 4 is still being updated by Bethesda (they only add Creation Club content). Whenever the game updates, the entire modding community goes silent for the next one or two weeks because some mods need to be updated to the latest game runtime version.

To ensure that Steam does not automatically updates the game for you, head over to the Properties window, navigate to the _Updates_ tab and change _Automatic updates_ to _Only update this game when I launch it_. You should also disable the Steam Cloud while you're at it.

#### Set the Game language to English

Just do it. This entire Modlist is in English and 99% of all mods you will find are also in English. I highly recommend playing the game in English and **I will not give support to people with a non-English game**. I really wish I could, but at this time, it simply isn't feasible.

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

#### Clean Fallout 4

I highly recommend uninstalling the game through Steam, deleting the game folder and reinstalling it. You should also clean up the `Fallout 4` folder in `Documents/My Games/`.

#### Start Fallout 4

After you have done everything above and got a clean Fallout 4 installation ready, start the Launcher and open the _Options_ menu.

1. Click on _High_
2. Set the _Aspect Ratio_ and _Resolution_ to your monitor's native values
3. Set _Antialiasing_ to _Off_
4. Check _Windowed Mode_ and _Borderless_

Start the game and exit once you're in the main menu.

### Using Wabbajack

#### Preparations

Let's get to the actual installation..

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases). You need to download the `Wabbajack.exe` file ONLY. Place the `Wabbajack.exe` file in a blank folder at the root of a drive, such as `C:/Wabbajack`.

Launch Wabbajack. When it is finished extracting and installing itself, select the `Browse Modlists` option. Click the Download arrow for Magnum Opus, and you will be forwarded to the next screen when it is finished.

Set the `Installation Location` to a blank folder at the root of a drive, such as `D:\Magnum Opus`. The `Download Location` will update automatically.

Click the `Play` arrow.

##### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you lose no progress.

**Could not download x**:

If a mod updated and the old files got deleted, it is impossible to download them. In this case just wait until I update the Modlist. I'm typically extremely quick to respond to a situation such as this.

Most commonly, this will happen if a mod is hidden from Nexus. Contact me in Discord if this happens, and I can force the list to show as Under Maintenance until it comes back, and then I can fix it when it's unhidden.

**x is not a whitelisted download**:

This can happen when I update the modlist. Check if a new update is available and wait if there is none.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

### Post-Installation

#### Copy Game Folder Files

After Wabbajack turns green and says Installation Complete, you can close it. Go to your installation folder (I will refer to this folder as the MO2 folder from now on) and you'll see a folder named `Game Folder Files`.

Copy the all of the files from the `MO2/Game Folder Files` directory into your game folder.

## Updating

If this Modlist receives an update, please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

If you wish for Wabbajack to ignore any additional mods you've installed, rename them to say `[NoDelete]` at the beginning of the name.

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

## BiRaitBec Texture Optimization

Go to [BiRaitBec’s Modding Guide](https://www.nexusmods.com/fallout4/mods/23556?tab=description).  
Manually download the **WorkBase** file.  
Manually download the **Main Repack** files (Part One, Part Two, and Part Three).  
  
Extract the WorkBase file with 7zip.  
You should have three folders inside of Workbase: OriginalBa2, PatchedBa2, and PatchedFiles.  
Navigate to your Fallout4/Data folder and **copy** these 15 files:  

'Fallout4 - Textures1.ba2'  
'Fallout4 - Textures2.ba2'  
'Fallout4 - Textures3.ba2'  
'Fallout4 - Textures4.ba2'  
'Fallout4 - Textures5.ba2'  
'Fallout4 - Textures6.ba2'  
'Fallout4 - Textures7.ba2'  
'Fallout4 - Textures8.ba2'  
'Fallout4 - Textures9.ba2'  
'DLCworkshop01 - Textures.ba2'  
'DLCworkshop02 - Textures.ba2'  
'DLCworkshop03 - Textures.ba2'  
'DLCRobot - Textures.ba2'  
'DLCCoast - Textures.ba2'  
'DLCNukaWorld - Textures.ba2'  

**Paste** these files into your **WorkBase/OriginalBa2** folder.
**Extract** Main Repack Part One into a new folder.
Inside the new folder, you should see another folder called “**textures**”. **Cut** this textures folder and **paste** it into **Workbase/PatchedFiles**.
**Repeat the previous two steps** for Part Two and Part Three of the Main Repack archives.
Run the **installer.bat** file inside of WorkBase.
When it is done, copy and paste all of the files inside of the PatchedBa2 folder into your Fallout4/Data folder AFTER WABBAJACK IS FINISHED INSTALLING.
  *  Alternatively, you can make a new folder inside Magnum Opus/mods and paste the archives into there, then activate the new mod in Mod Organizer 2. This will keep your Fallout 4 installation completely clean.  
  
After all of these steps are complete, you may delete the WorkBase folder. If you have the space, I advise making a backup of both the vanilla ba2 files as well as the patched ba2 files. It will save you the trouble of having to redownload them again later.

*Note that you CANNOT use the HD DLC for BiRaitBec’s texture optimization. You’ll see missing textures everywhere if you do.*

## Noteworthy Mods

### Sim Settlements 2

Rebuild the Commonwealth with a mysterious stranger in a brand new, fully voiced, and - quite frankly - absolutely amazing questline in this highly anticipated sequel-of-sorts to the original Sim Settlements. 

Read more about it [here](https://www.nexusmods.com/fallout4/mods/47976)!

### Subway Runner

Explore an expansive, deadly metro system that stretches the length of the entire Commonwealth. No quests here, folks; only loot, exploration, death, radiation, and a new way to travel across the city.

Read more about it [here](https://www.nexusmods.com/fallout4/mods/18639)!

### This is Trash - A Scrapping Alternative

I got tired of individually scrapping every single leaf and rubbish pile every time I started a new game, so I took some inspiration from Wabbajack and automated it. Each settlement will now have a trash can next to the workbench. Scrap it and watch as the area is miraculously cleaned of all those stupid looking shrubs and garbage decals.

Read more about it [here](https://www.nexusmods.com/fallout4/mods/42552)!

### Buffout 4

The equivalent of SSE Engine Fixes, Buffout basically makes lists like this possible. Memory patches, achievements enabler, memory leak warnings, and so much more. This is likely the single most important mod in the entire list.

Read more about it [here](https://www.nexusmods.com/fallout4/mods/47359)!

## In-Game MCM Options

*_Note: Anything involving hotkeys can be set up however you like. These are simply the way I have them set up for myself._

Companion Command Hotkeys  
![alt text](https://i.imgur.com/QMQqSSu.png)  

Custom Camera - Standard  
![alt text](https://i.imgur.com/UhgV6QN.png)  

Custom Camera - Power Armor  
![alt text](https://i.imgur.com/IwfxTSB.png)  

Custom Camera - Miscellaneous  
![alt text](https://i.imgur.com/ZTexP2Z.png)  

Custom Camera - Features  
![alt text](https://i.imgur.com/PuDef9C.png)  

FallUI - Coloring  
![alt text](https://i.imgur.com/liVn6zL.png)

FallUI - Text Style  
![alt text](https://i.imgur.com/JdY6CID.png)

FallUI Workbench - Generic Settings  
![alt text](https://i.imgur.com/FfZ7WHC.png)

FallUI Workbench - Workbench List  
![alt text](https://i.imgur.com/hS3nr3Z.png)

Faster Workshop Hotkey  
![alt text](https://i.imgur.com/kkgYNFT.png)  

More AGOMBz - More attacks - Swap the first two categories.  
![alt text](https://i.imgur.com/vdXySOe.png)

More AGOMBz - More...Disable - Disable Radstags.  
![alt text](https://i.imgur.com/VREBmyj.png)

QuickTrade  
![alt text](https://i.imgur.com/FF168gw.png)

Sim Settlements 2 - Respect Build Limit - Off  
![alt text](https://i.imgur.com/nTuRz20.png)

Wait Anywhere - Hotkey: T  
![alt text](https://i.imgur.com/YP6OOnl.png)

Workshop Framework - Turn off Allow Settlements to Leave (optional)  
![alt text](https://i.imgur.com/KaQWMZp.png)  

Workshop Plus - Options - Disable Clear Weather.  
![alt text](https://i.imgur.com/BGZnDBG.png)  

Workshop Plus - Hotkeys  
![alt text](https://i.imgur.com/aklZPWs.png)

You and What Army - BOS  
![alt text](https://i.imgur.com/SMYUY4x.png)

You and What Army - Railroad  
![alt text](https://i.imgur.com/2CNBPVY.png)

You and What Army - Institute  
![alt text](https://i.imgur.com/fJquOpK.png)

**Holotape Settings:**   
Open the Beantown Interiors Holotape in your Pipboy and select the following options:  

  *  Customize Options  
  *  Other Options  
  *  Mod Compatibility  
  *  Enable Inside Jobs

That's it! Have fun!  

## FAQ

- I am having random crashes.

  - Check Magnum Opus' Mod Organizer 2. Look at the top right corner for a red triangle with a yellow number. Click it. If one of the warnings says "incompatible plugins" and spits out an error about Buffout 4, then you're missing the memory patch. This can happen in some cases. Reinstall VCRedit, re-copy Game Folder Files, launch the game through MO2 once, and close it again. The warning should now be gone, Buffout should be loaded properly, and you can go on with your day.

- Is Creation Club content compatible?

  - No idea. I don't own it and I don't use it. CC content is not supported.

- Can I add more mods or remove some mods I don't want?

  - Can you? Yes. Will I help you? Maybe, but please discuss it in either general channels or my personal Discord server, and be sure to disclose the fact that you've edited the list before reporting any bugs or crashes. If you're open and honest with me, I'm honestly much more willing to help you through your issues.

- Why is my crosshair on my pipboy?

  - You can turn the Power Armor HUD Switcher holotape setting for [Hide Hud in Pipboy] to Off in order to hide the crosshair when not in power armor, but this also makes the pipboy look pretty terrible when using it inside power armor. Your call.


- Why can't I use multiple companions/why can't I use Dogmeat with a vanilla companion?

  - One follower is enough, and Heather (a modded follower from [here](https://www.nexusmods.com/fallout4/mods/23273)) doesn't occupy a "follower" slot, so you can have Heather + one other companion. Considering how overpowered that is, there is no reason I should add Dogmeat to the mix as well.

- I've been following along your [amazing and wonderful modding tutorials](https://github.com/LivelyDismay/Learn-To-Mod/blob/main/Main.md) and they're great! But my added mods are breaking precombines/previs/making shit flicker in and out of existence a lot. What the hell, man?

  - Load your mods ABOVE all the `* Previs.esp` files in the load order.

- I've been following along your [amazing and wonderful modding tutorials](https://github.com/LivelyDismay/Learn-To-Mod/blob/main/Main.md) and they suck! My game keeps crashing when I add stuff after following your instructions! What the hell, man?

  - That sucks. Post in general-f4-discussions in the Wabbajack server, or any channel my personal discord server. If you're not a dick, I'm genuinely more than happy to help if I can.

## Widescreen Support  

*Note that I did not write this. I don’t have ultrawide so I can’t help troubleshoot it. Another user left this here for others to possibly learn from.*

1) Install [TRUBY9](https://www.nexusmods.com/fallout4/mods/24630). Choose XDI when asked about Patches. Select nothing else.

2) Install [TRUBY9 DEF_UI Fix](https://www.nexusmods.com/fallout4/mods/43275)

2) Install [TRUBY9 DEF_INV Compatibility Fix](https://www.nexusmods.com/fallout4/mods/43278)

3) Install [DEF_UI HUDMenuSet Ultrawidescreen](https://www.nexusmods.com/fallout4/mods/43277)

4) Download a [standalone Adobe Flash Player from Adobe](https://fpdownload.macromedia.com/pub/flashplayer/updaters/32/flashplayer_32_sa_debug.exe)

5) Paste the "flashplayer_32_sa_debug.exe" in the same location as HUDMenuSet.swf  
  *  Note that Magnum Opus already has a custom Def UI preset, aptly titled Lively's HUD Preset. Disable this mod in MO2.  
6) Execute the standalone Adobe Flash Player(the .exe you just downloaded) and load HUDMenuSet.swf (from here it will work as the DEF_UI HUDMenuSet.exe)  
7) Move the UI elements to your liking (or leave as is). Once satisfied hit Ctrl+S  
8) Create a new folder DEF_CONF in the same location as HUDMenuSet.swf and save the new XML file inside the new folder  
  *  Note that removing the brackets from the loot menu will also break Hud Plus Plus. So maybe don't do that.
9) Open up Truby9 and delete the BarterMenu.swf and ContainerMenu.swf files from Truby9 and Truby9 Def UI for FallUI compatibility.

Please also note that some of the custom Power Armor huds may not work properly in Widescreen. I really just don't know.

## Controller Support

If you're playing with a controller (why?), your pipboy map won't work. Open the MO2 INI Editor, select fallout4prefs.ini, and scroll down until you see the `[Display]` section. At the bottom, you'll find two lines:  
`uPipboyTargetHeight=1400`  
`uPipboyTargetWidth=1752`  
Change these two lines to the following:  
`uPipboyTargetHeight=700`  
`uPipboyTargetWidth=876`  
Then find the `[General]` section and change `bGamepadEnable=` from a `0` to a `1`.

### ENB

I don't use an ENB. I never saw the need. If you want to try one, feel free.

## Credits and Thanks

- Erri120 - Repository template and NPC visuals
- AUGSpeed, Total, Kaethela, and the rest of the Wabbajack team for all of their ongoing advise and support.
- Halgari, creator of Wabbajack, without whom none of us would be here.

## Contact

I'm always available on the [Wabbajack Discord](https://discord.gg/wabbajack) and [my own personal Discord Server](https://discord.gg/yABEjwB).



# GMTB Locomotive Detailing Script
I need to think of a better name for this project. Until I do, you're stuck with this one.

![DRM Free](https://static.fsf.org/dbd/label/DRM-free%20label%20120.en.png)

[Keep it that way](https://www.defectivebydesign.org/what_is_drm_digital_restrictions_management)



### Written & Developed by:
[Cassandra "ZZ Cat" Robinson](https://bit.ly/ZZCatOnFacebook)

## Description:
 Written in Expression 2 & designed for Garrys Mod Train Build servers, this script (as the name suggests) kits your locomotive out with true-to-life levels of detail.

## Features:
 * Automatic Parenting.
 * Automatic Updates - When new updates are published to the repository, the E2 will automatically download & install these updates for you.
 * Multiplayer Lock - Anti-griefing feature. This stops someone from hijacking your locomotive in-game.
 * Smart Entity Discovery - Bogeys & locomotive crew seats are automatically spawned, when this E2 is attached to a locomotive body.

## What's next:
OK, now this project is starting to take off in the right direction. Now, I can get serious about what I have planned for this project.
All my plans for this project are listed here. Whether-or-not I choose to implement each & every item in this list is at my discretion & necessity will take priority.
 * Locomotive Details.
 * Compatibility with Metalodon's RattleCan 2.
 * Compatibility with Magnum MacKivler's RLC Platinum Gamma 2.
 * Simplified I/O structures - enables "plug & play" capabilities.

## Errata:
 What's an Alpha/Early Access release without bugs?
 I'll tell ya what:
 I am the only developer that's working on everything that is in my GitHub repositories. This gives me the luxury of having absolute control over the level of quality that goes into my coding & script work, at the expense of updates taking longer to be pushed out - coupled with the fact that I don't have internet access on most days.
 With that being said, as much as I strive to avoid it, even my own work isn't entirely 100% immune from pestilence.

 Currently, as of Kernel Version 0.1.5, I am having some issues with the Automatic Updates plugin falsely flagging license violations.
 So, I have temporarily disabled that feature until I have fixed it proper-like.
 There is also the slight chance of the CRC (Cyclic Redundancy Checksum) falsely flagging a corrupted App download. I have left this intact, because a.) It's a semi-rare occurrence; b.) Whenever I update the App, I sometimes forget to update the CRC in the 'VERSION.txt' file while I'm at it. This has a tendency to corrupt App downloads anyways; & c.) I'm still working on the script work for the Automatic Updates plugin. So, expect varying degrees of stability here.
 This IS an "Alpha/Early Access" status project, after all.

 You will also note the only detail that's been added to the SD40 so far (as of App Version 0.2.0), is in the bogeys.
 This will give you an idea of the level of detail that is going into this project, & as time marches forward, more detail will be added to the rest of this locomotive (& other locomotives) in future updates.

 That's about it for what I've encountered as far as bugs/glitches/errata is concerned.
 However, if ya notice something a outta kilter, consider opening an issue in this repository about it. Also, provide details about what you did to encounter the bug, so I can trace your steps & reproduce it on my end.
 'Cause my information is only as good as the resources that are available to me.

## Requirements:
 * An active internet connection.
   - This is only required to setup a valid Steam account; downloading-&-installing of Garrys Mod, Garrys Mod Addons; & automatic updates from this E2's GitHub servers. However, it is not essential to run Garrys Mod. This E2 can run without an internet connection, as it is entirely free from DRM.
 * [A valid Steam account](https://store.steampowered.com/about/)
 * [Garrys Mod](https://store.steampowered.com/app/4000/Garrys_Mod/)
 * [Wiremod](https://steamcommunity.com/sharedfiles/filedetails/?id=160250458)
 * [Advanced Duplicator 2](https://steamcommunity.com/sharedfiles/filedetails/?id=773402917)
 * Honestly, just get the FC&N Railroad's Official Add-on Pack for Garrys Mod. It contains everything you need, there.

## How to obtain & install:
 1. Download this repository, by clicking "Download Zip" under the green "Code" button, & save the zip file in an accessible directory.
 2. Extract everything from the zip file.
 3. **Backup your files before expediting this step.** Copy the 'expression2' folder to this directory -> 'steamapps/common/GarrysMod/garrysmod/data', & overwrite the existing folder(s) & file(s) with the same name(s).
 4. Fire up Garrys Mod & start a new sandbox session.
 5. In your Expression 2 Editor, click the "Update" button & everything should be there.
    - This script is divided into three types - "Main", "Updatable" & the "Plugins".
      The "Main" script is what you will need to have open, when you spawn this script as an E2 Chip in-game. You will also need it for handling updates.
      The "Updatable" script (as the name suggests) contains the primary functions of the entire E2 script what for bringing your locomotive to life. This is the script that gets the automatic updates, whenever said updates are released. **DO NOT SPAWN THIS SCRIPT IN-GAME!!!**
      The "Plugins" are actually a part of the "Main" script & contains a folder of two add-on scripts, that are an example of how third party plugins can be used to provide a little extra functionality to the entire E2 script. **DO NOT SPAWN ANY OF THE PLUGINS IN-GAME!!!**
    - The "Main" script will be located in the "expression2/Cassie Robinson/Locomotive Details" folder; & it is aptly called 'main.txt'.
    - The "Updatable" script will be located in the "expression2/e2shared/Locomotive Details" folder; & it is aptly called 'updatable.txt' to avoid confusion with the "Main" script.

## Quick Start Guide:
 1. Spawn in an EMD SD40 (NOT the SD40**-2**) locomotive body blank. You can find it in Grovestreetgman's Propper Trains, in your Add-Ons folder.
 2. Open up Garrys Mod's Expression 2 Editor & navigate to the 'main.txt' file, that's in the Locomotive Details sub-folder of "expression2/Cassie Robinson"; & open the file within the Expression 2 Editor. This is the "Main" script.
 3. Close the editor & spawn the "Main" script on the locomotive's body - preferably somewhere inconspicuous.
 4. It's as easy as that. You're done here. "Keep your dick in a vice." --Arduino versus Evil

## A Note on Updates:
 While this script is designed to ease the burden of "Dependency Hell", by automating the update processes as much as Expression 2 will allow. Here are a few steps to help you along the way...
 * For the "Updatable" script:
    1. Follow the chat prompts.
    2. When instructed to "Zap" the E2 chip with your tool gun, you **need** to have the "Main" script open in your Expression 2 editor.
    3. "Zap" the E2 chip by left-clicking on the chip, with Expression 2 loaded onto your tool gun.
        If you "Reload" the chip, **the newly downloaded updates will not be installed** & the E2 script will repeat the automatic update process.
 * For the "Main" script & the "plugins":
    1. This process, unfortunately, is a little more complex than the automatic process above. If Expression 2 had a way of automating this process, I would have done it already.
    2. When prompted about a new update, download the source code from this repository.
    3. Once you've extracted the files, copy both the 'Cassie Robinson' & 'plugins' folders from '[wherever you extracted this]/expression2' to
        this directory -> 'steamapps/common/GarrysMod/garrysmod/data/expression2'.
    4. Fire up Garrys Mod & start up a new session.
    5. Open up the Expression 2 Editor & click the "Update" button.
    6. The new updates should have been installed, by now. You can verify this by spawning in either your previously saved dupe (with this E2 in-tow), or follow the steps outline in the "Quick Start Guide". You'll know when the updates are successful, because you won't be bugged by the script about new updates... until the next updates get released.

## Duplicating this E2 using Advanced Duplicator 2:
 Like all of my E2 scripts, this is designed to be fully compatible with the latest duplicator tools (EG Advanced Duplicator 2). This E2 script can be duplicated in the exact same way as you would with any other contraption. Better yet, if you have this E2 saved as a dupe, you do NOT need to manually update the dupe, whenever updates to this E2 is released. The automations in this script takes care of that headache for you.

## Software License:
![GNU Affero GPL v3](https://www.gnu.org/graphics/agplv3-with-text-162x68.png)

GMTB Locomotive Detailing Script. Copyright © 2020-2021, Cassandra "ZZ Cat" Robinson.

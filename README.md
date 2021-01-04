# GMTB Locomotive Detailing Script
I need to think of a better name for this project. Until I do, you're stuck with this one.

![DRM Free](https://static.fsf.org/dbd/label/DRM-free%20label%20120.en.png)

[Keep it that way](https://www.defectivebydesign.org/what_is_drm_digital_restrictions_management)



### Written & Developed by:
[Cassandra "ZZ Cat" Robinson](https://bit.ly/ZZCatOnFacebook)

## Description:
 A locomotive detailing script for Garrys Mod Train Build.
 I also need to think of a way better description than that. It's a tad... blunt!

## Features:
 * Automatic Parenting.
   No need to manually parent this E2 to the locomotive's body. It does this all by itself.
 * Automatic updates.
   I took my Self-Updatable E2 script, made a plugin version of it & added it to this script.
   So, whenever I update this project, your versions will get automatically updated too. Yay! =^/,..,^=
 * Multiplayer Lock.
   **NOT TO BE CONFUSED WITH OR CONSTRUED AS DRM!** This is merely an anti-griefing measure, for when you're on a multiplayer train build server.
   Basically, what this does is, it will hide the E2 chip itself & other folk won't be able to dick about with the script work in-server.
   If they want the source code, they can come & get it from here. THEN, they can get up to their usual scumbaggery... & then, get kicked from the server. lel.
   Also, this is a plugin. If you want to exclude Multiplayer Lock from your copy of this script, I've made it easy for you to do so. Although, do it at your own risk... & don't come crying to me, when some bumblefuck has dicked about with your script work.
 * Smart Entity Discovery.
   The E2 automatically detects whatever it is attached to. If the attached prop is a valid (IE supported) locomotive body blank, then this script will run its course. As an added extra, you don't need to manually spawn in things like bogies, seats & consoles. Because this E2 script does all of that heavy lifting for you.
   Although, currently, only the bogies are automatically spawned in. All of those other things are on the to-do list.

## What's next:
 * Automatic Updates for the plugins!
   Especially as this project grows in both size & complexity. The last thing I want to do is burden you lot with dependency hell.
   The idea behind this is the same as the Automatic Updates feature of this E2 Script, where the source code is downloaded from my GitHub page to the E2 Shared folder in your Garrys Mod directory; & you zap this E2 in-game to apply the newly installed updates. Easy as!
   Perhaps I should put these plugins into a repository all on their own? IDK. One of these days, I might consider it... ONE OF THESE DAYS!
 * Details. Details **GALORE!**
   Over the years, I have been toying with Garrys Mod trains & Expression 2; & I think it's time that I start putting together my own public Expression 2 script, as my personal gift to the Garrys Mod Train Build community - Specifcally, the Flatgrass Construct & Northern Railroad. These folks have been absolutely wonderful in what they do, & I think that this is very well deserved.
   Starting off with "Ol' Reliable" - the GM-EMD SD40, I will implement as much detail into each locomotive as I possibly can, based on all of the resources that are available to me.
   The idea with this project is, all you need to do is spawn this E2 on a locomotive body blank & this script will work its magick to bring your locomotive to life.
 * Feature Creep!
   What's a good project without feature creep? With Fantail, I'm doing everything possible to avoid feature creep. But, for this project... honestly, this one is way less serious (& far less safety conscious) than Fantail. So, this project can afford all the feature creep & bumblefuckery one can throw at it.
   'Cause, it **is** Garrys Mod, after all. Even if GMTB is competing with (if not, better than) Train Simulator.
 * OpenControl compatible.
   This one is gonna be a bit of a challenging one, granted the interfaces aren't quite so universal as RLC. So, this one may not get implemented until a lot later on, down the track (pun intended).
 * Prop Spwaning.
   More specifically, your Engineer's Seat will automatically be spawned in your locomotive's cabin in a similar manner as to how this E2 script spawns in the bogeys.
   I will also have Smart Entity Discovery search for a parenting gate; automatically parent the seat to the gate; & the gate will automatically be parented to the locomotive's body. This should abstract away a lot of the heavy lifting that's required to get things moving. This is the main idea behind this project, after all.
   Another thing that will be done is your console(s), gauges & switches. They will all be fully functional & you will be able to interact with them in the ways that you can expect (IE from your Engineer's Seat).
 * RattleCan?
   Maybe. I ain't too familiar with RattleCan, as I prefer to do my own paint jobs. Apparently, RattleCan is quite the learning curve in & of itself. So, this one is also going into the "I'll cross that bridge when I get there" category.
 * RLC compatible.
   Yup! You read that right. This E2 script will eventually plug into Magnum MacKivler's Realistic Locomotive Controller, as this script will provide fully functional (as well as decorative) parts to your locomotive in an efficient manner.
 * Smart Entity Discovery - Make it a plugin!
   By doing this, it will make it even easier to implement Smart Entity Discovery into other projects as well as this one.
   Currently, Smart Entity Discovery is hard-coded into this E2 script. Because of that, it's not easily reusable in other stuff; & it's quite the headache to re-code every single time.
 * WireLink.
   Instead of having over9000 declared inputs & outputs, this E2 script will make extensive use of the WireLink protocol wherever possible.

## Errata:
 What's an Alpha release without bugs?
 I'll tell ya what: Those that are more interested in emphasizing quantity & meeting unrealistic deadlines, as opposed to placing emphasis on quality.
 I think me being the only developer what's working on my projects, I have the luxury of having absolute control over the quality of what goes into it.

 With that being said, even my own work isn't entirely 100% immune from pestilence.

 Currently, there aren't any known bugs/issues with the current release, that I can see.
 However, if ya notice something a tad outta kilter, consider opening an issue in this repository about it. Also, provide details about what you did to encounter the bug, so I can trace your steps & reproduce it on my end.
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
 Like all of my E2 scripts, this is designed to be fully compatible with the latest duplicator tools (EG Advanced Duplicator 2). This E2 script can be duplicated in the exact same way as you would with any other contraption. Better yet, if you have this E2 saved as a dupe, you do NOT need to manually update the dupe, whenever updates to this E2 is released. The automations in this script take care of that headache for you.

## Software License:
![GNU Affero GPL v3](https://www.gnu.org/graphics/agplv3-with-text-162x68.png)

GMTB Locomotive Detailing Script. Copyright © 2020-2021, Cassandra "ZZ Cat" Robinson.

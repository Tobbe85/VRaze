# A RazeXR fork from [domyoji81](https://github.com/domyoji81/VRaze) with Voxel Weapon support and some other improvements

**This is only a resigned version so that it runs on Pico devices. It is exactly the same build from Domyoji (1:1) and will work on Quest too**

## INSTALLATION INSTRUCTIONS
1. If upgrading from a previous version, uninstall VRaze from your headset first, then navigate to the /VRaze/ folder on your headset and delete `raze.pk3` and `commandline.txt`.
2. Install VRaze (if using Sidequest, click on the icon near the top right that has an arrow facing down and select the VRaze-xxxx.apk).
3. When done installing, make sure VRaze has read/write permissions. You can do this with Sidequest by clicking on the "Currently installed apps" icon near the top right (it's a 3x3 square grid). Then scroll down the list until you see "com.vraze" and click the gear icon to the right of it. A window will pop up, scroll down and look at the bottom right. Toggle READ_EXTERNAL_STORAGE and WRITE_EXTERNAL_STORAGE to on (the pip should be on the right side).
4. In your headset under the unknown sources apps, run VRaze. If this is your first time using VRaze you need to make sure all your game files are placed in the appropriate game folders.

Place game data in the following directories:
| Game                              | Path                      |
|:----------------------------------|:--------------------------|
| Duke Nukem 3D + Expansions        | VRaze/raze/duke/          |
| Blood + Expansions                | VRaze/raze/blood/         |
| Shadow Warrior + Expansions       | VRaze/raze/shadowwarrior/ |
| Redneck Rampage + Route 66        | VRaze/raze/rampage/       |
| Redneck Rampage Rides Again       | VRaze/raze/ridesagain/    |
| Exhumed / Powerslave              | VRaze/raze/exhumed/       |
| NAM                               | VRaze/raze/nam/           |
| WW2GI + Platoon Leader            | VRaze/raze/ww2gi/         |
| Mods                              | VRaze/raze/mods/          |

## SUPPORTED GAME FILES
| Game                              | Files          |
|:----------------------------------|:---------------|
| Blood + Expansions                | BLOOD.INI, BLOOD.RFF, GUI.RFF, SOUNDS.RFF, SURFACE.DAT, TILES000.ART–TILES017.ART, VOXEL.DAT, GTI.SMK, GTI.WAV, LOGO.SMK, LOGO811M.WAV, CS1.SMK, CS1822M.WAV, CS2.SMK, CS2822M.WAV, CS3.SMK, CS3822M.WAV, CS4.SMK, CS4822M.WAV, CS5.SMK, CS5822M.WAV, CS6.SMK, CS6822M.WAV, *Cryptic Passage files:* All .MAP files, CPART07.AR_, CPART15.AR_, CRYPTIC.INI, CRYPTIC.SMK, CRYPTIC.WAV *(can be zipped as `cryptic.zip`)*, MARROW.ZIP *(can be any name)*, DEATHWISH.ZIP *(can be any name)*, CD music files<br/><br/>*Note: ogv movie format not yet supported* |
| Duke Nukem 3D                     | DUKE3D.GRP, DUKEDC.GRP, VACATION.GRP, NWINTER.GRP, DUKEZONE2.GRP *(fixed version)*, WORLDORDER.GRP *(script extracted version)*, WORLDTOUR.ZIP *(zipped World Tour folder)* |
| Exhumed / Powerslave              | BOOK.MOV, STUFF.DAT, CD music files |
| NAM                               | NAM.GRP, GAME.CON |
| Redneck Rampage + Route 66        | REDNECK.GRP, *Route 66 files*: All *66*.ANM/.ART/.CON/.VOC files, all .MAP files, ASYAMB.VOC, G_BITE.VOC, G_SIT.VOC, NEON.VOC *(can be zipped as `route66.zip`)*, CD music files |
| Redneck Rampage Rides Again       | REDNECK.GRP/RIDES.GRP/RIDESAGAIN.GRP *(name may vary)*, CD music files |
| Shadow Warrior + Expansions       | SW.GRP, TD.GRP/TWINDRAG.GRP *(name may vary)*, WT.GRP, CD music files |
| WW2GI + Platoon Leader            | WW2GI.GRP, PLATOONL.DAT, PLATOONL.DEF |

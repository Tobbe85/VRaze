# A RazeXR fork from Domyoji with Voxel Weapon support and some other improvements

This is only a resigned version so that it runs on Pico devices. It is exactly the same build from Domyoji (1:1) and will work on Quest too

Filestructure:

\VRAZE
|   commandline.txt
|   grpcrccache.txt
|   raze.log
|   raze.pk3
|   raze.sf2
|   shadercache.zdsc
|   vraze.ini
|   
\---raze
    +---blood
    |   |   BLOOD.INI
    |   |   BLOOD.RFF
    |   |   blood02.ogg
    |   |   blood03.ogg
    |   |   blood04.ogg
    |   |   blood05.ogg
    |   |   blood06.ogg
    |   |   blood07.ogg
    |   |   blood08.ogg
    |   |   blood09.ogg
    |   |   blood31.ogg
    |   |   blood32.ogg
    |   |   blood33.ogg
    |   |   blood34.ogg
    |   |   blood35.ogg
    |   |   blood36.ogg
    |   |   blood37.ogg
    |   |   blood38.ogg
    |   |   blood39.ogg
    |   |   blood40.ogg
    |   |   blood41.ogg
    |   |   blood42.ogg
    |   |   COMMIT.DAT
    |   |   CP01.MAP
    |   |   CP02.MAP
    |   |   CP03.MAP
    |   |   CP04.MAP
    |   |   CP05.MAP
    |   |   CP06.MAP
    |   |   CP07.MAP
    |   |   CP08.MAP
    |   |   CP09.MAP
    |   |   CPART07.AR_
    |   |   CPART15.AR_
    |   |   CPBB01.MAP
    |   |   CPBB02.MAP
    |   |   CPBB03.MAP
    |   |   CPBB04.MAP
    |   |   CPSL.MAP
    |   |   CRYPTIC.INI
    |   |   CRYPTIC.SMK
    |   |   CRYPTIC.WAV
    |   |   deathwish.zip
    |   |   GTI.SMK
    |   |   GUI.RFF
    |   |   LOGO.SMK
    |   |   MARROW.zip
    |   |   SOUNDS.RFF
    |   |   SURFACE.DAT
    |   |   TABLES.DAT
    |   |   TILES000.ART
    |   |   TILES001.ART
    |   |   TILES002.ART
    |   |   TILES003.ART
    |   |   TILES004.ART
    |   |   TILES005.ART
    |   |   TILES006.ART
    |   |   TILES007.ART
    |   |   TILES008.ART
    |   |   TILES009.ART
    |   |   TILES010.ART
    |   |   TILES011.ART
    |   |   TILES012.ART
    |   |   TILES013.ART
    |   |   TILES014.ART
    |   |   TILES015.ART
    |   |   TILES016.ART
    |   |   TILES017.ART
    |   |   VOXEL.DAT
    |   |   
    |   \---movie
    |           cs1.smk
    |           cs1822m.wav
    |           cs2.smk
    |           cs2822m.wav
    |           cs3.smk
    |           cs3822m.wav
    |           cs4.smk
    |           cs4822m.wav
    |           cs5.smk
    |           cs5822m.wav
    |           cs6.smk
    |           cs6822m.wav
    |           gti.smk
    |           gti.WAV
    |           logo.smk
    |           logo811m.wav
    |           
    +---duke
    |       DUKE3D.GRP
    |       dukedc.grp
    |       dukezone2.grp
    |       nwinter.grp
    |       vacation.grp
    |       worldorder.grp
    |       WORLDTOUR.GRP
    |       worldtour.zip
    |       
    +---exhumed
    |   |   BOOK.MOV
    |   |   DEMO.VCR
    |   |   STUFF.DAT
    |   |   
    |   \---music
    |           Track02.ogg
    |           Track03.ogg
    |           Track04.ogg
    |           Track05.ogg
    |           Track06.ogg
    |           Track07.ogg
    |           Track08.ogg
    |           Track09.ogg
    |           Track10.ogg
    |           Track11.ogg
    |           Track12.ogg
    |           Track13.ogg
    |           Track14.ogg
    |           Track15.ogg
    |           Track16.ogg
    |           Track17.ogg
    |           Track18.ogg
    |           Track19.ogg
    |           
    +---mods
    |       bloodupscalepack.zip
    |       Blood_-_Coagulated.zip
    |       dukedc_midi.pk3
    |       dukeupscale.zip
    |       dw_music.zip
    |       nwupscale.zip
    |       swupscale.zip
    |       vacaupscale.zip
    |       voxel_duke3d.zip
    |       wtupscale.zip
    |       
    +---nam
    |       GAME.CON
    |       NAM.GRP
    |       
    +---rampage
    |   |   REDNECK.GRP
    |   |   route66.zip
    |   |   
    |   \---music
    |           redneck02.ogg
    |           redneck03.ogg
    |           redneck04.ogg
    |           redneck05.ogg
    |           redneck06.ogg
    |           redneck07.ogg
    |           redneck08.ogg
    |           redneck09.ogg
    |           
    +---ridesagain
    |   |   REDINT.MVE
    |   |   RIDES.GRP
    |   |   
    |   \---music
    |           redneckrides02.ogg
    |           redneckrides03.ogg
    |           redneckrides04.ogg
    |           redneckrides05.ogg
    |           redneckrides06.ogg
    |           redneckrides07.ogg
    |           redneckrides08.ogg
    |           redneckrides09.ogg
    |           redneckrides10.ogg
    |           
    +---saves
    +---shadowwarrior
    |   |   Sw.grp
    |   |   TWINDRAG.grp
    |   |   WT.GRP
    |   |   
    |   \---music
    |           shadow02.ogg
    |           shadow03.ogg
    |           shadow04.ogg
    |           shadow05.ogg
    |           shadow06.ogg
    |           shadow07.ogg
    |           shadow08.ogg
    |           shadow09.ogg
    |           shadow10.ogg
    |           shadow11.ogg
    |           shadow12.ogg
    |           shadow13.ogg
    |           shadow14.ogg
    |           
    \---ww2gi
            PLATOONL.DAT
            PLATOONL.DEF
            WW2GI.GRP

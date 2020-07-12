After extracting the files from the ISO here's the tree I ended up with

* DATA
	* 0FLISTDV.DIR
	* BK.AFS
	* BU.AFS
	* ED.SFD
	* FC.AFS
	* LG.SFD
	* LT.BIN
	* MOV_10.SFD
	* MOV_11.SFD
	* MV.AFS
	* OP.SFD
	* PB.SFD
	* PR.BIN
	* PT.AFS
	* SC.BIN
	* SE.ACX
	* SP.AFS
	* VO.AFS
* MODULES
	* CRI_ADXI.IRX
	* IOPRP310.IMG
	* LIBSD.IRX
	* MCMAN.IRX
	* MCSERV.IRX
	* PADMAN.IRX
	* SDRDRV.IRX
	* SIO2MAIN.IRX
* SLPM_668.73
* SYSTEM.CNF

# SYSTEM.CNF
Text file with basic information about the game. Shouldn't need to mess with this at all

# SLPM_668.73
This is the main executable file. The text is probably in here

# DATA

## DATA/0FLISTDV.DIR
Text file. Seems to be a table of contents for the rest of the folder. Guess if I needed to add something new to data. I'd do it here. Also a bit weird that it's out of order:
```
vo.afs
bk.afs
bu.afs
sp.afs
fc.afs
pt.afs
mv.afs
lt.bin
pr.bin
se.acx
sc.bin
pb.sfd
lg.sfd
ed.sfd
op.sfd
mov_10.sfd
mov_11.sfd
```

## DATA/BK.AFS
Contains a bunch of .obj files.

## DATA/BU.AFS
Contains a bunch of .obj files.

## DATA/ED.SFD
Credits movie in color. How many credits movies does this game need?

## DATA/FC.AFS
Contains a bunch of .obj files.

## DATA/LG.SFD
Criware intro movie.

## DATA/LT.BIN

## DATA/MOV_10.SFD
Credits movie. Black background with japanese text on top. My guess is images are behind it.
![./credits.PNG](credits.png)

## DATA/MOV_11.SFD
Credits with background. Guess they play this one instead?
![./credits with background.PNG](credits with background.png)

## DATA/MV.AFS
more movies

## DATA/OP.SFD
Opening movie

## DATA/PB.SFD
Kadokawa credits. My guess is this is along side the criware dredits.

## DATA/PR.BIN
Might be an elf file???

## DATA/PT.AFS
Contains a bunch of .obj files.

## DATA/SC.BIN

## DATA/SE.ACX
More sound files

## DATA/SP.AFS
Contains a bunch of .obj files.

## DATA/VO.AFS
Contains a bunch of adx files. From what I can tell this is characters speaking. Because I only want to translate the text, I'm going to leave this stuff here. If there's interest in doing a voice translation, this would probably be the file to replace.

Everything here is in the format of `ABR_0000.adx`.


# MODULES
 
## MODULES/CRI_ADXI.IRX
Criware adx driver. Responsible for playing sounds.

## MODULES/IOPRP310.IMG

## MODULES/LIBSD.IRX
Sound Device Library

## MODULES/MCMAN.IRX
Memory card utilities.

## MODULES/MCSERV.IRX
Memory card utilities.

## MODULES/PADMAN.IRX


## MODULES/SDRDRV.IRX
SDR driver (says so in the first couple of lines at least).

## MODULES/SIO2MAIN.IRX
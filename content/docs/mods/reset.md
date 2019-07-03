+++
title = "Backup and Restore"
description = "Oh shit, I broke everything!"
weight = 50
draft = false
toc = false
bref = "Let's learn how to extinguish a burning ffxiv installation"
+++
## Backup your index files

After installing the game or receiving a game patch it's important to backup your clean index files.

1. Create a backup of your clean index files

	```
	> ./FFMT-LINUX backup
	```

These are stored in the directory you've chosen in the configuration file (see first-time setup) or defined with argument (-b, --backupdirectory)



## Universal release (Including Windows)

1. Download and extract the universal release archive

2. Confirm that the executable runs through commandline: 

#### Mac/Linux:

Run `mono FFMT.exe` through commandline.

#### Windows:

Run `FFMT.exe` through commandline.

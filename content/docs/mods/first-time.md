+++
title = "First-time setup"
description = "Our recommended start"
weight = 5
draft = false
toc = false
bref = "Always keep your backups safe"
+++

This is only a recommended first time setup. 

You are not required to make use of the config file created by this application, as all required directories can be specified through commandline instead.

Note: Common directories will be displayed in the config file
#### GameDirectory examples:
- MacOS: `/Users/<USER_NAME>/Library/Application Support/FINAL FANTASY XIV ONLINE/Bottles/published_Final_Fantasy/drive_c/Program Files (x86)/SquareEnix/FINAL FANTASY XIV - A Realm Reborn`
- Linux: `/path/to/WINEBOTTLE/drive_c/Program Files (x86)/SquareEnix/FINAL FANTASY XIV - A Realm Reborn`
- Windows: `C:\Program Files (x86)\SquareEnix\FINAL FANTASY XIV - A Realm Reborn`

#### BackupDirectory
Wherever you want to save your index backups.

#### ConfigDirectory examples:
- MacOS: `/Users/<USER_NAME>/Documents/My Games/FINAL FANTASY XIV - A Realm Reborn`
- Linux: `/path/to/WINEBOTTLE/drive_c/users/<USER_NAME>/My Documents/My Games/FINAL FANTASY XIV - A Realm Reborn`
- Windows: `C:\users\<USER_NAME>\My Documents\My Games\FINAL FANTASY XIV - A Realm Reborn`

## First-time setup

1. The first run will create the application's config file

	```
	> ./FFMT-LINUX
	```

2. Edit the config file with your editor of choice

	```
	> nano ~/.config/FFMT/config.cfg
	```

3. Create a backup of your clean index files

	```
	> ./FFMT-LINUX backup
	```

You are now ready to start modding the game.

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

1. The first run will create the application's config file

	```
	> ./FFMT-LINUX
	```

2. Edit the config file with your editor of choice

	```
       # For MacOS GameDirectory needs to be set within the .app:
       # Example: /Applications/FINAL FANTASY XIV ONLINE.app/Contents/SharedSupport/finalfantasyxiv/support/published_Final_Fantasy/drive_c/Program Files (x86)/SquareEnix/FINAL FANTASY XIV - A Realm Reborn


	> nano ~/.config/FFMT/config.cfg
	```

3. Create a backup of your clean index files

	```
	> ./FFMT-LINUX backup
	```

You are now ready to start modding the game.

# Proper configuration makes later use much easier

This is only a recommended first time setup. 

You are not required to make use of the config file created by this application, as all required directories can be specified through commandline instead.

Note: Common directories will be displayed in the config file

#### GameDirectory examples
- MacOS: `/Users/<USER_NAME>/Library/Application Support/FINAL FANTASY XIV ONLINE/Bottles/published_Final_Fantasy/drive_c/Program Files (x86)/SquareEnix/FINAL FANTASY XIV - A Realm Reborn`
- Linux: `/path/to/WINEBOTTLE/drive_c/Program Files (x86)/SquareEnix/FINAL FANTASY XIV - A Realm Reborn`
- Windows: `C:\Program Files (x86)\SquareEnix\FINAL FANTASY XIV - A Realm Reborn`

#### BackupDirectory
Wherever you want to save your index backups. Keep these safe!

#### ConfigDirectory examples
- MacOS: `/Users/<USER_NAME>/Documents/My Games/FINAL FANTASY XIV - A Realm Reborn`
- Linux: `/path/to/WINEBOTTLE/drive_c/users/<USER_NAME>/My Documents/My Games/FINAL FANTASY XIV - A Realm Reborn`
- Windows: `C:\users\<USER_NAME>\My Documents\My Games\FINAL FANTASY XIV - A Realm Reborn`


## Option 1: Wizard First-time setup

1. Run:

	```shell
	> ffmt setup
	```

2. Follow the instructions on the screen. The wizard will try to suggest common folders!

3. Create a backup of your clean index files

	```shell
	> ffmt backup
	```
	


## Option 2: Manual First-time setup

1. The first run will create the application's config file

	```shell
	> ffmt
	```

2. Edit the config file with your editor of choice

	```shell
	> nano ~/.config/FFMT/config.cfg
	```

3. Create a backup of your clean index files

	```shell
	> ffmt backup
	```

You are now ready to start modding the game.

# FFXIV Game Update

FFXIV is often patched and certain operations are required!

Your game should **never be modded when applying a new patch**. We recommend resetting and reimporting!


##### Before game patch
You can either:

1. Disable all mods

	```
	> ffmt mods disable {-g /path/to/FINAL\ FANTASY\ XIV\ - A\ Realm\ Reborn}
	```

2. Reset the game's files entirely 

	```
	> ffmt reset {-g /path/to/FINAL\ FANTASY\ XIV\ - A\ Realm\ Reborn -b /path/to/index/backups}
	```

##### After game patch
Backup the new index files first
```
> ffmt backup {-g /path/to/FINAL\ FANTASY\ XIV\ - A\ Realm\ Reborn -b /path/to/index/backups}
```
Depending on the chosen step before patching, you now either:

1. Re-enable all mods
	
	```
	> ffmt mods enable {-g /path/to/FINAL\ FANTASY\ XIV\ - A\ Realm\ Reborn}
	```
2. Import your modpacks from scratch
	
	```
	> ffmt modpack import {-g /path/to/FINAL\ FANTASY\ XIV\ - A\ Realm\ Reborn /path/to/modpack.ttmp2}
	```

# FFXIV Game Update

FFXIV is often patched and certain operations are required!

Your game should **never be modded when applying a new patch**. We recommend resetting and reimporting!


##### Before game patch

1. Backup all mods 
	```
	> ffmt modpack create --output ~/mymodpack.ttmp2  {-g /path/to/FINAL\ FANTASY\ XIV\ - A\ Realm\ Reborn -b /path/to/index/backups}
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


1. Import your backup modpack
	
	```
	> ffmt modpack import ~/mymodpack.ttmp2 {-g /path/to/FINAL\ FANTASY\ XIV\ - A\ Realm\ Reborn}
	```

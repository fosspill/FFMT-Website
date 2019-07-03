+++
title = "FFXIV Game Update"
description = "FFXIV is often patched and certain operations are required"
weight = 25
draft = false
toc = false
bref = "Your game should be unmodded before applying a new patch. <br/>We recommend resetting and reimporting"
+++

##### Before game patch
You can either:

1. Disable all mods

	```
	> ./FFMT-LINUX mods disable -g /path/to/FINAL\ FANTASY\ XIV\ - A\ Realm\ Reborn
	```

2. Reset the game's files entirely 

	```
	> ./FFMT-LINUX reset -g /path/to/FINAL\ FANTASY\ XIV\ - A\ Realm\ Reborn -b /path/to/index/backups
	```

##### After game patch
Backup the new index files first
```
> ./FFMT-LINUX backup -g /path/to/FINAL\ FANTASY\ XIV\ - A\ Realm\ Reborn -b /path/to/index/backups
```
Depending on the chosen step before patching, you now either:

1. Re-enable all mods
	
	```
	> ./FFMT-LINUX mods enable -g /path/to/FINAL\ FANTASY\ XIV\ - A\ Realm\ Reborn
	```
2. Import your modpacks from scratch
	
	```
	> ./FFMT-LINUX modpack import -g /path/to/FINAL\ FANTASY\ XIV\ - A\ Realm\ Reborn -t /path/to/modpack.ttmp2
	```

# How to use the FFXIV Modding Tool

Check out the sidebar, we try to keep a list of the most common operations there.

Further, to give you an idea of what is possible, here is the output from `ffmt help`

```
Usage: ffmt [action] {arguments}

Available actions:
  modpack import, mpi      Import a modpack, requires a .ttmp(2) to be specified
  modpack info, mpinfo     Show info about a modpack, requires a .ttmp(2) to be specified
  modpack create, mpc      Create a modpack out of your currently active mods
  mods enable, me          Enable all installed mods
  mods disable, md         Disable all installed mods
  mods refresh, mr         Enable/disable mods as specified in modlist.cfg
  backup, b                Backup clean index files for use in resetting the game
  reset, r                 Reset game to clean state
  problemcheck, pc         Check if there are any problems with the game, mod or backup files
  version, v               Display current application and game version
  help, h                  Display this text
  setup, s                 Run First-time Setup Wizard

Available arguments:
  -g, --gamedirectory      Full path to game install, including 'FINAL FANTASY XIV - A Realm Reborn'
  -c, --configdirectory    Full path to directory where FFXIV.cfg and character data is saved, including 'FINAL FANTASY XIV - A Realm Reborn'
  -b, --backupdirectory    Full path to directory with your index backups
  -t, --ttmp               Will be deprecated - Full path to .ttmp(2) file (modpack import/info only)
  -w, --wizard             Use the modpack wizard to select what mods to import (modpack import only)
  -a, --all                Import all mods in a modpack immediately (modpack import only)
  -npc, --noproblemcheck   Skip the problem check after importing a modpack
  -o, --output             Path and filename to save .ttmp2 during Modpack Creation
  -v, --version            Display current application and game version
  -h, --help               Display this text
  path/to/modpack.ttmp     Full path to modpack(s). Imports in the order given.
```

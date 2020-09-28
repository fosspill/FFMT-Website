# Let's install ffmt!

You may need to [Download and install Dotnet Core](https://dotnet.microsoft.com/download/dotnet-core)

Note: We officially support the `ffmt-bin` aur package for arch-based linux distributions.


## Mac, Windows and Linux

1. [Download and install Dotnet Core](https://dotnet.microsoft.com/download/dotnet-core)
2. Download the relevant release [here](https://github.com/fosspill/FFXIV_Modding_Tool/releases).
  a. There is a Mac, Windows and Linux release available.
3. Extract the downloaded Zip-file
  a. This may happen automatically on certain set-ups.
4. Open your Terminal and use the `cd` command to change to the extracted folder
  a. E.x.: `cd /home/user/Downloads/FFXIV_Modding_Tool/ffmt/`
  b. Note: You can safely ignore the provided `ffmt.sh` file and `cd` into the next folder.
5. Your working directory should now be the one that the `ffmt` executable lives in.
5. Confirm that the executable runs through commandline: 

#### Mac/Linux

Run `./ffmt` through commandline.
There is also a bundled script: `ffmt.sh`

#### Windows

Run `ffmt.exe` through commandline.

```

> chmod +x ffmt.sh

> ./ffmt

Usage: ffmt [action] {arguments}



Available actions:

  modpack import, mpi      Import a modpack, requires a .ttmp(2) to be specified

  ...

```


Your next step should be [First-time setup](userguide/quickstart/setup)

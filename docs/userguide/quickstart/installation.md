# Let's install ffmt!

You may need to [Download and install Dotnet Core](https://dotnet.microsoft.com/download/dotnet-core)


## Option 1: Package managers (macOS and Linux)

### macOS
1.  [Install Homebrew](https://brew.sh).
2.  Run `brew cask install dotnet-sdk` or [Follow Microsoft's dotnet install guide](https://dotnet.microsoft.com/download/dotnet-core)
3.  Run `brew install fosspill/ffmt/ffmt`.

### Linux
Arch based: Install the `ffmt-bin` package from the aur. (Ex: `yay -S ffmt-bin`)


Your next step should be [First-time setup](userguide/quickstart/setup)

## Option 2: Manual
1. [Download and install Dotnet Core](https://dotnet.microsoft.com/download/dotnet-core)
2. Download the relevant release [here](https://github.com/fosspill/FFXIV_Modding_Tool/releases).
   1. There is a Mac, Windows and Linux release available.
3. Extract the downloaded Zip-file
   1. This may happen automatically on certain set-ups.
4. Open your Terminal and use the `cd` command to change to the extracted folder
   1. E.x.: `cd /home/user/Downloads/FFXIV_Modding_Tool/ffmt/`
   2. Note: You can safely ignore the provided `ffmt.sh` file and `cd` into the next folder.
5. Your working directory should now be the one that the `ffmt` executable lives in.
6. Confirm that the executable runs through commandline.

```
> ./ffmt

Usage: ffmt [action] {arguments}



Available actions:

  modpack import, mpi      Import a modpack, requires a .ttmp(2) to be specified

  ...

```


Your next step should be [First-time setup](userguide/quickstart/setup)

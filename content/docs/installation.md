+++
title = "Installation"
description = "How to Download and install"
weight = 1
draft = false
toc = false
bref = "A short guide to downloading and installing on Windows, Mac and Linux"
+++
## Linux Bundled release

1. Download the most recent release from the appropriate link [here](https://github.com/fosspill/FFXIV_Modding_Tool/releases). 

2. Make the file executable and run it through commandline to confirm that it works

```
> chmod +x FFMT-LINUX
> ./FFMT-LINUX
Usage: FFMT.exe [action] {arguments}

Available actions:
  modpack import, mpi      Import a modpack, requires a .ttmp(2) to be specified
  ...
```



## Universal release (Mac / Windows / Linux)

1. If Mac/Linux: [Download and install Mono](https://www.mono-project.com/docs/getting-started/install/)

2. Download and extract the universal release archive from [here](https://github.com/fosspill/FFXIV_Modding_Tool/releases).

3. Open your commandline console and browse to the extracted folder (eg: `cd Release`)

4. Confirm that the executable runs through commandline: 

#### Mac/Linux:

Run `mono FFXIV_Modding_Tool.exe` through commandline.

#### Windows:

Run `FFXIV_Modding_Tool.exe` through commandline.

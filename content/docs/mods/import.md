+++
title = "Importing modpacks"
description = "No FFXIV install is complete without a few modpacks"
weight = 10
draft = false
toc = false
bref = "Let's import our first modpack"
+++
There are two main types of modpacks: Simple and Wizard.

Simple requires no user interaction, but you can customize your import if you'd like.
Wizard <b>requires</b> user interaction.

<h3>Find the type</h3>

#### 

Firstly, figure out what kind of modpack this is:

```
> ./FFMT-LINUX mpinfo -t /path/to/modpack.ttmp2
Type: Simple
Author: 80cent
Version: 1.1
Description: N/A
Number of mods: 9001
```

<h3>Importing</h3>

Importing a full modpack
```
> ./FFMT-LINUX mpi -t /path/to/modpack.ttmp2
```
<h4>Simple Modpack Custom Import</h4>

Selectively importing mods from a simple modpack
```
> ./FFMT-LINUX mpi -t /path/to/modpack.ttmp2 --custom
> nano ~/.config/FFMT/ModPacks/modpack.cfg
> ./FFMT-LINUX mpi -t /path/to/modpack.ttmp2 --custom
```

<h4>Wizard Modpack import</h4>

Start the import. Wizard will be automatically used as long as the modpack is of type Wizard:

```
> ./FFMT-LINUX mpi -t /path/to/modpack.ttmp2
```
Follow the on-screen prompts. Example:
```
Choices:
    1 - Gryffindor
         Description
    2 - Slytherin
         Description
    3 - Ravenclaw
         Description
    4 - HuFflEpuFf
         Description
         
  Choose one or multiple (eg: 1 2 3, 0-3, *)
  > 1-3
```

- Choices are separated by spaces.
- \* selects all.
- Ranges can be combined (eg: 1-3 5-6, to skip choice 4)

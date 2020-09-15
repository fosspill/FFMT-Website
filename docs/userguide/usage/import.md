# Importing modpacks with FFMT

No FFXIV install is complete without a few modpacks

## Modpack introduction
There are two main types of modpacks: Simple and Wizard.

Simple requires no user interaction, but you can customize your import if you'd like.
Wizard **requires** user interaction.

### Find the type

Firstly, figure out what kind of modpack this is:

```
> ffmt mpinfo /path/to/modpack.ttmp2
Type: Simple
Author: 80cent
Version: 1.1
Description: N/A
Number of mods: 9001
```

### Importing

Importing a full modpack
```
> ffmt mpi /path/to/modpack.ttmp2 --all
```
#### Simple Modpack Custom Import

Selectively importing mods from a simple modpack
```
> ffmt mpi /path/to/modpack.ttmp2
Starting import...
Extracting data from modpack.ttmp2...
Would you like to use the Wizard for importing?
(Y)es, let me select the mods
(N)o, import everything

> y
Choices:
    1 - Star Trek
         Description
    2 - Star Wars
         Description         

  Choose one or multiple (eg: 1 2 3, 0-3, *)

 > 1 2
```

#### Wizard Modpack import

Start the import. Wizard will be automatically used as long as the modpack is of type Wizard:

```
> ffmt mpi /path/to/modpack.ttmp2
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

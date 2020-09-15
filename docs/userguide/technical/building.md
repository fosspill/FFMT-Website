# Building FFMT and the xivModdingFramework from Source
"I want to compile it myself", you say?

This guide is based on our `./build.sh` script, available in the repository.

## xivModdingFramework

Building the [xivModdingFramework](https://github.com/liinko/xivModdingFramework) with dotnet is usually not problematic

```dotnet build --no-incremental -c Release xivModdingFramework/xivModdingFramework/xivModdingFramework.csproj -o FFXIV_Modding_Tool/references/```

## FFMT
After the xivModdingFramework is built and available in the references folder you can build FFMT with:

```dotnet build --no-incremental -c Release FFXIV_Modding_Tool/FFXIV_Modding_Tool.csproj```

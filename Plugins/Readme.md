# Kerbal Space Program Plugin Template
This repo contains a template for the dotnet tool which allows coders to quickly create KSP plugins.

## Requirements
- Install [.Net Framework Dev Pack](https://dotnet.microsoft.com/download/dotnet-framework) (min 4.5) 
- Install Kerbal Space Program on [Steam](https://store.steampowered.com/app/220200/Kerbal_Space_Program/) or [KSP](https://www.kerbalspaceprogram.com/)

## Install Specific Template
```
dotnet new -i <template name>
```

## Templates
### Blank Template
#### Install
```
dotnet new -i Blank
```
#### Use
```
cd MyPlugin
dotnet new ksp -p "MyPlugin" -i "C:\KSP_Install"
```
The `-p` and `-i` options are optional. `-p` defaults to MyPlugin and `-i` defaults to the STEAM Windows x64 install directory


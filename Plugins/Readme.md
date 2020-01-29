# Kerbal Space Program Plugin Template
This repo contains a template for the dotnet tool which allows coders to quickly create KSP plugins.

## Install template
```
dotnet new -i template
```

## Use template
```
cd MyPlugin
dotnet new ksp -p "MyPlugin" -i "C:\KSP_Install"
```
The `-p` and `-i` options are optional. `-p` defaults to MyPlugin and `-i` defaults to the STEAM Windows x64 install directory

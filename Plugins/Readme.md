# Kerbal Space Program Plugin Template
This repo contains a template for the dotnet tool which allows coders to quickly create KSP plugins.

## Requirements
- Install Dotnet core to get the `dotnet` cli tool
  ```
  https://dotnet.microsoft.com/download
  ```
- Install .Net Framework dev-pack compatible with .Net 3.5
  ```
  https://dotnet.microsoft.com/download/dotnet-framework
  ```

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

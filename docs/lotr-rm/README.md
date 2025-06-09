Q: Which version of Unreal?

A: Inspect the properties for `.\Moria\Binaries\Win64\Moria-Win64-Shipping.exe`. The "File version" in the "Details" tab is the Unreal version.

Q: Where are the game's PAK files?

A: `.\Moria\Content\Paks`.

Use [umodel](https://www.gildor.org/en/projects/umodel) to inspect the contents of pak files.

## Install UE4SS

In the game dir, navigate to ...

`.\Moria\Binaries\Win64`

Go to  ...

https://github.com/UE4SS-RE/RE-UE4SS

... and get the latest release.

Unzip and copy into `.\Moria\Binaries\Win64`.

To debug, edit `UE4SS-settings.ini`.

```
[General]
EnableHotReloadSystem=1

[Debug]
ConsoleEnabled=1
GuiConsoleEnabled=1
GuiConsoleVisible=1
```

## Reference

- https://www.youtube.com/watch?v=ZIYQvkynng4&t=804s
- https://www.youtube.com/watch?v=TJfsX_gO4YI
- https://github.com/BestDaniel/Moria_Mods
- https://www.nexusmods.com/thelordoftheringsreturntomoria/mods/21
- https://www.nexusmods.com/thelordoftheringsreturntomoria/mods/16
- https://www.nexusmods.com/thelordoftheringsreturntomoria/mods/15
- https://www.gildor.org/en/projects/umodel#files

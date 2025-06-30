# Mod-Controller

## Create a Project

The modkit helps us set up a project per convention ...

1. Launch modkit.
2. In the upper right, find the "Conan Exiles Mod-kit" menu.
3. Select `Create a new mod ...`.
4. Name our mod folder.
5. Find the new folder in the Content Browser (under "Mods" probably).

## Add a Mod-Controller (Blueprint)

The Conan Exiles mod loader expects a special kind of Blueprint called a "Mod-Controller" ...

1. In our mod folder (in the Content Browser) ...
2. Right-click and create a new `Blueprint Class`.
3. Name it per convention `SomethingSomething_ModController` (but it could be anything; this is not how it is identified by the loader).

## Components

We can add Components to our mod directory ...

"In order to access certain functions of many blueprints, it's better to attach a component to the blueprint rather than modifying the original asset. If anyone else edits the core game asset, the mod load order will simply apply the last-one-in principle, and your functionality may/will be lost. For this reason, the mod-controller can add components to blueprints." (Modding @ conanexiles)

## Reference

- [Mod Controller Basics](https://www.conanexiles.com/wp-content/wiki/2685370865.html) @ conanexiles.

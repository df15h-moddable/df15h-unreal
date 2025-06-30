# Mod-Controller

## Why?

- The mod loader requires a mod-controller in the root directory of the mod.
- A mod-controller is a `Blueprint Class`. So, in other words, the mod loader requires a Blueprint in the root directory of the mod.
- A mod-controller can add new Components to base-game Blueprints.
- A mod-controller can merge new Data Tables with base-game Data Tables.

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

## Data Tables

"If you want to add new recipes, items, feats or work with any other table, you will need to make a new table of the same type. This new data-table will then (by the power of the mod-controller) be merged into the basegame table and give access to all of your entries." (Modding @ conanexiles)

## Reference

- [Mod Controller Basics](https://www.conanexiles.com/wp-content/wiki/2685370865.html) @ conanexiles.

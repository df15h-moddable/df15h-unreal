The Funcom kit is built from Funcom's modified version of Unreal Engine 4.15.3. [3]

The Funcom kit makes these changes to the standard Unreal IDE [3] ...

- Adds toolbar button and menu.
- R/W to anything outside of `/Content/Mods/<active mod name>/` is blocked.
- R/W to `<content>/Mods/*` is blocked, except ...
- R/W to `<content>/Mods/<active mod name>/*` is redirected to `<content>/Mods/<active mod name>/Local/*`.
- R/W to `/Content` is redirected to `<content>/Mods/<active mod name>/Content` (falls back to original path if not found in mod).
- Prevents use or export of assets licensed by Funcom from the Unreal Marketplace.

## Reference

1. [Conan Exiles Modkit](https://store.epicgames.com/en-US/p/conan-exiles--modkit) @ store.epicgames.
2. [Conan Exiles Workshop](https://steamcommunity.com/app/440900/workshop/) @ steamcommunity.
3. [Conan Exiles Modding](https://conanexiles.fandom.com/wiki/Modding) @ conanexiles.fandom.

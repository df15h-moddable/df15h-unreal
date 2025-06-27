# Unreal Editor ModKit

![](./img/unreal-=editor-01.webp)

"Using the Unreal Engine 4 Editor with our dev kit you will be able to create content almost the exact same way our own developers do.
The kit gives you access to basically all the assets of the game, from maps and blueprints to meshes and animations.
The editor itself requires some knowledge, but there are many guides available, and overall it is relatively easy to use." [6]

See the [official documentation](https://www.conanexiles.com/mods/).

The Funcom kit is built from Funcom's modified version of Unreal Engine 4.15.3. [3]

The Funcom kit is a modified version of the standard Unreal IDE [3] ...

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
4. [Modders Field Manual for Conan Exiles](https://docs.google.com/document/d/1BV9OGwnOn-1jxfTw3vX5S_taNQySpAvZ8Lb1oBTOurY/edit#) by "Dr Nash and Friends" @ docs.google.
5. [All Guides](https://www.dropbox.com/s/qp0u3bj9ork0v93/AllGuides.zip?dl=0) by Robtheswede @ dropbox.
6. [Make Your Own Mods](https://www.conanexiles.com/blog/dev-blog-13-make-your-own-mods-in-conan-exiles/) devblog Feb 2017 @ conanexiles.
7. [Modding](https://www.conanexiles.com/mods/) @ conanexiles.


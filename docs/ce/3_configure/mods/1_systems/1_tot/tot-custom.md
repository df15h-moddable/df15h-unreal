# Tot! Custom

## Features

Customization is organized into four categories ...

- Bodies
- Weapons
- Armors
- Accessories

In each category, the facilities (sliders, colors, etc) are extensive.

In addition to the player character, customizations can be applied to ...

- thralls
- Tot! Admin "puppets" (cf. Pippi "thespians")
- two types of mannequin (stick+rope, carved)

And more ...

- Add accessories "regardless of original slot".
- Save profiles/presets.
- Supports high heels.

## Quirks

Tot! Custom is feature-rich and well-implemented, but ...
it DOES NOT behave like any typical RPG customization system!

- Tot! Custom is _unlike_ the item overlay slots in most games (as implemented for Conan Exiles by Testerle and Whiskey).
- Tot! Custom is _unlike_ the vanilla transmogrifications (Thaumaturgy Illusions).

### Profiles

Tot! Custom customizations are NAMED SKINS (aka profiles).

- We DO NOT morph our character's body ...
- We do not transmogrify our weapons ...
- We do not transmogrify our armor, nor do we slot overlay items into a paper doll ...
- We do not slot overlay accessories into a paper doll ...
- To change our cusomization details on the fly, we don't unslot overlay items ...

... RATHER, we make separate NAMED SKINS (profiles) and APPLY them.

### Consequences

This system comes with some non-intuitive side-effects. Some could be called game-breaking, to various degrees.

- TC mannequins don't have item slots. They are not containers. They are simply targets for TC profiles.
- While there is a setting to require we own the gear we are customizing -- as long as a single set is in our inventory,
we can apply the profile to as many actors and mannequins as are in the vicinity.
- When the player dies, and drops all gear, the TC appearance is not removed.
Workaround: Maintain a Nude profile. Switch to it and (per settings) TC won't let you switch back until you recover your gear.
(This may be why the author created Tot! Death -- to script that.)

### Weapons

While the quirks listed above aren't showstoppers, TC's weapon customization system is something else.

- The otherwise simple feature of showing equipped weapons and tools (sheathing and unsheathing) is vastly overcomplicated.
- The intended solution is that ...
- (1) We should disable the base game setting (show/hide).
- (2) Weapons should be displayed as ACCESSORIES.
- It's a powerful system, with an extraordinary amount of control, and might be great IFF ...
- IFF we only cared about weapon display on our player character.
- The approach doesn't scale to thralls and NPCs. We'd have to create a million profiles.
- For that reason, we (1) ENABLE the base game setting (show/hide) and ignore this feature of Tot! Custom.

Q: Why so quirky?

A: A hint might lie in the doc : Accessories may be applied "regardless of original slot". The vanilla slot system might be a constraint the author wanted to work around.

## Dependencies

Requires ...

- Tot! Sudo (for API)

## Dependents

Mods dependent on Tot! Custom (for some or all functionality) ...

- Agony's Attic
- Cookie's Immersive Armors
- Cookie's Skinnery
- Eldubya's Exiled Aesthetics
- Eldubya's Exiled Armory
- Ithlinne's Wardrobe
- Juvilia & Agony's Salon
- Juvilia's Crabby Accessories
- Paen's Crabby Accessory Weapons
- Tydin's Teyahs Boutique

## Incompatible

Incompatible with ...

- Akihabara Design
- Akuba Salon
- Aquilonian Passion Body
- Fashionist
- Improved Quality of Life (IQoL)

(? Notice that the author doesn't list either "Whiskey's Acessory Wardrobe" or "Whiskey's High Heels System" as incompatible ?)

## Reference

- [Tot! Custom](https://steamcommunity.com/sharedfiles/filedetails/?id=2886779102) @ Steam Workshop.
- [Tot! Documentation](https://apiconan.totchinuko.fr/#/) @ totchinuko.fr.
- [Tot! Custom Introduction](https://www.youtube.com/watch?v=riVQcPQ-cNY) by Totchinuko @ youtube.

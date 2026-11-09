# Better Mouse and Gamepad

A [*Balatro*](https://store.steampowered.com/app/2379780/Balatro/) quality of life
mod that allows binding any key or button to a variety of quick functions,
reducing hand strain. This is possibly one of the most essential mods for any
regular *Balatro* player, allowing:

* Multiselect: hold a key to select all cards your cursor passes over,
* Deselect: deselect any selected cards,
* Sort (by suit or value): rearrange all cards in your hand,
* Play: play selected cards
* Discard: discard selected cards
* Restart: restart, keeping the current run settings
* Hold B (gamepad): hold the B button for about 0.7 seconds to close all open menus at once

https://github.com/user-attachments/assets/5e02ac8d-0474-43d4-84a5-63057609a308

## Configuration

To set up bindings, go to the Mods menu, then click 'Better Mouse and Gamepad',
then 'Config'.

In this menu, clicking on any of the features will cause the game to listen for
the next click or hold event, then bind the key to the feature.

Default configuration is as follows:

| Feature | Key |
| --- | --- |
| Multiselect | `Mouse2 (Hold)` |
| Deselect | `Mouse2 (Click)` |
| Sort by suit | `Mouse Wheel Up` |
| Sort by value | `Mouse Wheel Down` |
| Play | `Mouse5 (Click)` |
| Discard | `Mouse4 (Click)` |
| Restart | [Unbound by default] |

## Installation

Follow the
[installation instructions](https://github.com/Steamodded/smods/wiki)
for
[Steamodded](https://github.com/Steamodded/smods)
to install. This will at least include
[installing the Lovely injector](https://github.com/ethangreen-dev/lovely-injector?tab=readme-ov-file#manual-installation),
adding a `Mods` folder in your *Balatro* `%appdata%` folder, and adding
Steamodded to this folder. Once Steamodded is installed, download a release of
this repository
[here](https://github.com/uptudev/bmag/releases), and extract the source code
archive into the `Mods` folder.

Your Steamodded version should be at minimum **v1.0.0**.

## Known Issues

This mod might not be compatible with any others that override the Love2D
press/release event hooks.

Sometimes attempting to bind a key will not work for an unknown reason. If this
happens, try to bind it to another feature and try again.

## Find More Mods

You can find more mods here:

* [awesome-balatro](https://github.com/jie65535/awesome-balatro)
* [Balatro Mod Index](https://docs.google.com/spreadsheets/d/1aoJrrC7Y-dkvJwBu_U6amelYnoCrZgWqpoGRAfHN1ys)
* [discord--modding](https://discord.com/channels/1116389027176787968/1209506514763522108)
* [mod wiki](https://balatromods.miraheze.org/wiki/Main_Page)
* [nexus](https://www.nexusmods.com/games/balatro/mods)

## Contributing

Please review our [CONTIBUTING](/CONTIBUTING.md) file before attempting to contribute
in any fashion. All contributions must align with both the guidelines there and
those in the [Code of Conduct](/CODE_OF_CONDUCT.md).

## License

This project in its entirety is licensed under [the MIT/X11 license](/LICENSE).
Versions of this mod before `v2.0.0` were licensed under the GPLv3 license, but
the entire project was rewritten from scratch with the intent to re-license it under
a more suitable copyleft license.

---

<!-- other-mods:start -->
## More from SilvertongueRED

**Fit to Screen (Menu Resizer) is now on Nexus Mods:** [nexusmods.com/balatro/mods/1001](https://www.nexusmods.com/balatro/mods/1001). It stops tall pause menus and sidebars from being cut off at the top and bottom of your screen.

### See my other mods and forks of other people's mods

- [Balatro-Fit-To-Screen-Menu-Resizer-](https://github.com/SilvertongueRED/Balatro-Fit-To-Screen-Menu-Resizer-) ([Nexus Mods](https://www.nexusmods.com/balatro/mods/1001)) - stops tall pause menus and sidebars from being cut off at the top and bottom of your screen
- [Balatro-Mod-Search-and-Sort](https://github.com/SilvertongueRED/Balatro-Mod-Search-and-Sort) ([Nexus Mods](https://www.nexusmods.com/balatro/mods/984)) - search, filter and sort the Mods menu without messing up the load order
- [Balatro-Mod-Updater](https://github.com/SilvertongueRED/Balatro-Mod-Updater) ([Nexus Mods](https://www.nexusmods.com/balatro/mods/1002)) - keeps your mods, Steamodded and Lovely up to date, with backups and a rescue screen when an update breaks the game
- [Balatro-SaveRewinder-Config-Fix](https://github.com/SilvertongueRED/Balatro-SaveRewinder-Config-Fix) - Save Rewinder fork with a config fix: automatic save points and one key to rewind (a fork of [liafonx/Balatro-SaveRewinder](https://github.com/liafonx/Balatro-SaveRewinder))
- [Trance-Active-and-Updated](https://github.com/SilvertongueRED/Trance-Active-and-Updated) - colour and font manager that recolours the whole game, maintained fork (a fork of [SpectralPack/Trance](https://github.com/SpectralPack/Trance))
- [Balatro-Preview-Accuracy-Update](https://github.com/SilvertongueRED/Balatro-Preview-Accuracy-Update) - previews the score and dollars you will get from the selected cards, accuracy update (a fork of [DivvyCr/Balatro-Preview](https://github.com/DivvyCr/Balatro-Preview))
- [BalatroMods-HoldForFinalHandScore-Update](https://github.com/SilvertongueRED/BalatroMods-HoldForFinalHandScore-Update) - holds the final hand score on screen long enough to read it (a fork of [pumpncode/BalatroMods](https://github.com/pumpncode/BalatroMods), original mod by [Wiwiweb/BalatroMods](https://github.com/Wiwiweb/BalatroMods))
- [Main-Menu-Theme-Selector](https://github.com/SilvertongueRED/Main-Menu-Theme-Selector) - choose your main menu colours, background theme and title logo (a fork of [EmperorGesar/Balatro-Colour-Selector](https://github.com/EmperorGesar/Balatro-Colour-Selector))
- [Balatro-Music-Selector-Fixes-and-Features](https://github.com/SilvertongueRED/Balatro-Music-Selector-Fixes-and-Features) - pick extra soundtracks or your own music without installing all of Cardsauce (a fork of [DZAladan/Balatro-Music-Selector](https://github.com/DZAladan/Balatro-Music-Selector))
<!-- other-mods:end -->

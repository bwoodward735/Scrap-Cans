<h1 style="text-align: center;"> Scrap Cans </h1> <!-- This should be the name of your mod -->

<!-- This section contains the current version, the current downloads and the current license. Go to https://shields.io in order to update these links -->
<!-- NOTES:
    Keep the new line between the div definitions otherwise this wont work
    ![] is all you need before the round brackets. The text in the round brackets wont be displayed. If you want to change the displayed text on the left side of the button use &label=DISPLAYEDTEXT. Note that you will need to use URL escape characters
    ?style=for-the-badge this is the style for the button. This particular style seems to be the best currently available as of 2024/09/23
    Dont use blank spaces when you dont need them. The headers should handle this
 -->
<div style="margin-left: auto;
            margin-right: auto;
            width: 100%">


| Version | Downloads | License | Contributors |
| :-----: | :-------: | :-----: | :-----------: |
| ![](https://img.shields.io/github/v/release/Arkhorse/TLD-Mod-Template?sort=semver&display_name=release&style=for-the-badge&link=https%3A%2F%2Fgithub.com%2FArkhorse%2FTLD-Mod-Template%2Freleases%2Flatest) | ![](https://img.shields.io/github/downloads/Arkhorse/TLD-Mod-Template/total?style=for-the-badge) | ![](https://img.shields.io/github/license/Arkhorse/TLD-Mod-Template?style=for-the-badge) | ![](https://img.shields.io/github/contributors/Arkhorse/TLD-Mod-Template?style=for-the-badge) |

</div>

Scrap extra cans, empty lamp fuel tins, cooking pots and skillets, or build new cans at the forge.
This mod *replaces* ttr's "Recycle cans, pots and skillets" mod.

# Requirements
<!-- Yes, requirements before features.  -->
This mod requires:
- [ ] ModComponent
- [ ] ModSettings
- [ ] LocalizationUtilities
- [ ] GearSpawner
- [ ] CraftingRevisions
# Features
<!--
This should be a bullet point list of everything the mod does
-->
* Forge new cans (3 scrap = 4 cans)
* Scrap tin cans anywhere (4 cans = 3 scrap)
* Scrap lamp fuel tins anywhere (2 tins = 1 scrap; discards any Kerosene, so be careful!)
* Scrap cooking pots or skillets anywhere (4 scrap each; requires a hammer)
## Disabled Features
<!--
OPTIONAL
This should be a bullet point list of everything the mod used to do
-->
* Scrapping no longer requires use of a forge
## WIP Features
<!--
OPTIONAL
This should be a bullet point list of everything that you currently plan on creating
-->
* Scrapping pots and skillets only uses a hammer because the game does not seem to let you use a hacksaw to break them up properly. (Cast iron is hard, but *brittle*, so this will work.)  I am searching for a way to use the hacksaw as a crafting tool, so that will be coming.
# Install Instructions
<!--
This should be a bullet point list of everything the user must do in order to use the mod, including installing ML
-->
* Install MelonLoader.
* Install all dependencies listed in Requirements.
* Download the `ScrapCans.modcomponent` file and place it in your "Mods" folder.
# Localizations
<!--
This section should contain instructions on how to contribuite to the project for localization purposes
-->
As all items are vanilla items from TLD, all localizations should work.
# Credits
<!--
This should contain a list of everyone who has ever helped out with the mod, broken down into categories
-->
Thanks to everyone on the TLD modders' discord.
## Special Thanks
* ttr, for the original can recycling mod.

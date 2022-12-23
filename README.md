# Attention: Heavy WIP! Depending on your modules present you might have a hard time to get good results. I'm working through ironing out anything that comes my way.


# Sir Motte's Magnificent Darkness - Hearth Theme for Foundry VTT
![grafik](https://user-images.githubusercontent.com/82598692/206671747-330cc503-33ea-47ca-b049-1a0a63d2c85c.png)

This is my attempt at a recreation of my well received [Theme for Fantasy Grounds Unity](https://github.com/SirMotte/FGU-Theme-Hearth).
If you already want to test it and get a feel on how it looks, follow the set-up instructions below and ideally report back with findings and opinions.

## Requirements:
- Foundry VTT (Duh!)
- DnD 5E Ruleset (No support for other rulesets is planned)
- [Ernie's Modern UI](https://github.com/ernieayala/ernies-modern-layout) (Required)
- [Custom CSS Module](https://github.com/cswendrowski/FoundryVTT-Custom-CSS) (Required)
- [Tidy5ESheet](https://github.com/sdenec/tidy5e-sheet) (Recommended, must be set to Dark Ui for best results)

## Supported Modules
Others work out of the box or are not used by me. Right now I won't take requests for additional module support:

- [Action Pack](https://github.com/teroparvinen/foundry-action-pack)
- [Always HP](https://github.com/ironmonk88/always-hp)
- [Anonymous](https://github.com/reonZ/anonymous)
- [Combat Tracker Disposition](https://github.com/LebombJames/combat-tracker-disposition)
- [Damage Log](https://github.com/cs96and/FoundryVTT-damage-log)
- [Dice Tray](https://gitlab.com/asacolips-projects/foundry-mods/foundry-vtt-dice-calculator)
- [Monk's Common Display](https://github.com/ironmonk88/monks-common-display)
- [Monk's Token Bar](https://github.com/ironmonk88/monks-tokenbar)
- [Small Weather](https://github.com/LeafWulf/smallweather)

## Known Issues:
- Chat cards look still a little wild. Rework is in progress.
- Some areas of certain UI elements are hard to read or messed up. This is mostly caused by Ernie's Modern UI that will be resolved at some point. A lot needs to be done.
- [Combat Tracker Disposition](https://github.com/LebombJames/combat-tracker-disposition) - slight bugs with icons, investigating

## Installation Instructions and Set-Up

1. Install the required modules to Foundy VTT.
2. Navigate to the module settings for the Custom CSS Module and open the "Custom CSS Rules" window. Copy-Paste all entries found in the "Custom CSS Module Settings.css" and hit save. You can choose to apply the style on a global basis or as User Style. Please refere to the Custom CSS Module Documentation for further information.
3. Download the Sir_Motte_Hearth_Foundry.json from this repository.
   - Open Ernie's Modern UI Settings and open the settings menu:
   ![grafik](https://user-images.githubusercontent.com/82598692/209413448-ac9d63a4-e74f-4050-ba98-a7400adcefcc.png)
   - Navigate ti the Options Tab and Press "Import Theme"
   ![grafik](https://user-images.githubusercontent.com/82598692/209413563-291edba9-3949-4a65-bf66-0b9ab4297828.png)
   - Choose the downloaded Sir_Motte_Hearth_Foundry.json file.
4. (Only if used) Open up the Tidy5e Sheet Settings and set it to the "Alternative (dark)" color scheme. Additional Settings used need further testing in regard of UI Elements. I will update this document accordingly.

This should be it. Happy testing and bug hunting. Please report any findings to me either on Discord (Sir Motte#1305) or use the GitHub issue reporter.

Have Fun!
Sir Motte





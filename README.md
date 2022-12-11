# Attention: Heavy WIP! Turns out that I relied so much on other not mentioned modules, that anyone who wants to try this will have a hard time to get the same results...working on fixing stuff up now.


# Sir Motte's Magnificent Darkness - Hearth Theme for Foundry VTT
![grafik](https://user-images.githubusercontent.com/82598692/206671747-330cc503-33ea-47ca-b049-1a0a63d2c85c.png)

This is my attempt at a recreation of my well received [Theme for Fantasy Grounds Unity](https://github.com/SirMotte/FGU-Theme-Hearth).
If you already want to test it and get a feel on how it looks, follow the set-up instructions below and ideally report back with findings and opinions.

## Requirements:
- Foundry VTT (Duh!)
- DnD 5E Ruleset
- [Ernie's Modern UI](xxx) (Mandatory)
- [Custom CSS](xxx) (Mandatory)
- [Tidy5ESheet](https://github.com/sdenec/tidy5e-sheet) (Recommended, must be set to Dark Ui!)

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
- Some areas of certain UI elements are hard to read or messed up. This is mostly caused by Ernie's Modern UI and me not having touched these areas yet. A lot needs to be done.
- [Combat Tracker Disposition](https://github.com/LebombJames/combat-tracker-disposition) - slight bugs with icons, investigating
- [Ready Set Roll for D&D5e](https://github.com/MangoFVTT/fvtt-ready-set-roll-5e) - Currently Ernie's UI breaks the buttons on Chat cards, they still work but don't feature an icon anymore. He said he will add support in the future.
- [Token Variant Art](https://github.com/Aedif/TokenVariants) - Ernie's UI currently makes the Token HUD UI hard to use. No ETA on a fix.

## Installation Instructions and Set-Up

1. Install the required modules to Foundy VTT.
2. Navigate to the module settings for the Custom CSS Module and open the "Custom CSS Rules" window. Copy-Paste all entries found in the "Custom CSS Module Settings.css" and hit save. You can choose to apply the style on a global basis or as User Style. Please refere to the Custom CSS Module Documentation for further information.
3. Open the Ernie's Modern UI Settings and tick the following boxes. Feel free to experiment with these settings, but avoid any opacity alterations.

   ![grafik](https://user-images.githubusercontent.com/82598692/206667254-3bdc42d0-9c21-492f-be41-9eefcb3461ae.png)
   - Hit the "Settings" Button and apply the following values in the "Colors" Tab:

   ![grafik](https://user-images.githubusercontent.com/82598692/206686955-d32ebd14-2800-4f33-a5a8-6775d4742187.png)

   - Switch to the "Design" Tab and Apply the following settings. It might be necessary, in order to make the font's work, to download the Calibri Font from Google and add it to your Foundry installation. (Needs testing).

   ![grafik](https://user-images.githubusercontent.com/82598692/206669105-062adb7f-e47e-4cc3-866a-5f4d57709869.png)

   - Lastly in the "Options" Tab, check the boxes as follows and hit the "Save" Button.

   ![grafik](https://user-images.githubusercontent.com/82598692/206667745-1c8df9b4-1dcc-48c6-ad72-c246245108d1.png)

4. (Only if used) Open up the Tidy5e Sheet Settings and set it to the "Alternative (dark)" color scheme. Additional Settings used need further testing in regard of UI Elements. I will update this document accordingly.

This should be it. Happy testing and bug hunting. Please report any findings to me either on Discord (Sir Motte#1305) or use the GitHub issue reporter.

Have Fun!
Sir Motte





# Sir Motte's Magnificent Darkness - Hearth Theme for Foundry VTT
![grafik](https://user-images.githubusercontent.com/82598692/215295962-b3991143-a348-492b-ba24-25c6663d12ea.png)


This is a recreation of my well received [Theme for Fantasy Grounds Unity](https://github.com/SirMotte/FGU-Theme-Hearth).
Follow the set-up instructions below and ideally report back with findings and opinions.

## Requirements:
- Foundry VTT (Duh!)
- DnD 5E Ruleset
- [Ernie's Modern UI](https://github.com/ernieayala/ernies-modern-layout)
- [Custom CSS Module](https://github.com/cswendrowski/FoundryVTT-Custom-CSS)

## Recommended:
- [Tidy5ESheet](https://github.com/sdenec/tidy5e-sheet) (Highly Recommended, must be set to Dark Ui for best results)
- Calibri Font Installed - Instructions below.

## Installation Instructions and Set-Up

1. Install the required modules to Foundy VTT.
2. Navigate to the module settings for the Custom CSS Module and open the "Custom CSS Rules" window. Copy-Paste all entries found in the "Custom CSS Module Settings.css" and hit save. You can choose to apply the style on a global basis or as User Style. Please refere to the Custom CSS Module Documentation for further information.
3. Download the Sir_Motte_Hearth_Foundry.json from this repository.
   - Open Ernie's Modern UI Settings and open the settings menu:
   - ![grafik](https://user-images.githubusercontent.com/82598692/209413448-ac9d63a4-e74f-4050-ba98-a7400adcefcc.png)
   - Navigate to the Options Tab and Press "Import Theme".
   - ![grafik](https://user-images.githubusercontent.com/82598692/209413563-291edba9-3949-4a65-bf66-0b9ab4297828.png)
   - Choose the downloaded Sir_Motte_Hearth_Foundry.json file and import it.
4. (Only if used) Open up the Tidy5e Sheet Settings and set it to the "Alternative (dark)" color scheme. Additional Settings used need further testing in regard of UI Elements. I will update this document accordingly.
5. Install the Calibri Font for use in Foundry VTT (not mandatory but highly recommended).
   - If you're on windows, navigate to the fonts system settings and search for the Calibri Font Type.
   - ![grafik](https://user-images.githubusercontent.com/82598692/219111263-b2eb3da7-78ef-4130-91b9-271a918a6c5c.png)
   - Double Click the Font Family and select all Calibri Font types included. Ricght click and select "copy".
   - ![grafik](https://user-images.githubusercontent.com/82598692/219111688-b214a431-b5e8-4237-b053-7e0073cbc748.png)
   - Paste the files into a folder that you can easily find, ideally the Foundry VTT Data Folder.
   - ![grafik](https://user-images.githubusercontent.com/82598692/219112340-4df97917-025b-46e2-8665-3a1b25380cc1.png)   
   - Within Foundry VTT, navigate to the core settings menu and click the "Configure Additional Fonts" button.
   - ![grafik](https://user-images.githubusercontent.com/82598692/219110727-b0c3898b-0bf1-428d-befd-aaae721a4d07.png)
   - Click the Add Font Button and Create the Font entries as shown below:
   - Calibri Regular = calibri.ttf
   - Calibri Regular Italic = calibrii.ttf
   - Calibri Bold = calibrib.ttf
   - Calibri Bold Italic = calibriz.ttf
   - Calibri Light = calibril.ttf
   - Calibri Light Italic = calibrili.ttf
   - ![grafik](https://user-images.githubusercontent.com/82598692/219112725-4fa775f9-6529-4a4b-ab03-58106a02dca6.png)
   - Make sure that the Font Family Custom within Ernies's Modern UI settings is set to Calibri
   - ![grafik](https://user-images.githubusercontent.com/82598692/219114063-7663e23c-0c78-4920-9d07-8d2135c68ecb.png)
   - I don't know how to handle this on Linux or Mac, sorry. 


This should be it. Happy testing and bug hunting. Please report any findings to me either on Discord (Sir Motte#1305) or use the GitHub issue reporter.

## Currently Supported Modules
### A lot of Modules don't require dedicated support, try it out.

- [Midi QoL](https://gitlab.com/tposney/midi-qol) -> Depending on you settings you may have mixed results.
- [Action Pack](https://github.com/teroparvinen/foundry-action-pack)
- [Always HP](https://github.com/ironmonk88/always-hp)
- [Anonymous](https://github.com/reonZ/anonymous)
- [Combat Tracker Disposition](https://github.com/LebombJames/combat-tracker-disposition)
- [Damage Log](https://github.com/cs96and/FoundryVTT-damage-log)
- [Dice Tray](https://gitlab.com/asacolips-projects/foundry-mods/foundry-vtt-dice-calculator)
- [Monk's Common Display](https://github.com/ironmonk88/monks-common-display)
- [Monk's Token Bar](https://github.com/ironmonk88/monks-tokenbar)
- [Small Weather](https://github.com/LeafWulf/smallweather)
- [Deadly Encounter Benchmark](https://github.com/snshatto/deadly-encounter-benchmark)
- [DFreds Chat Pins](https://github.com/DFreds/dfreds-chat-pins)
- [Token Notes](https://wiki.theripper93.com/premium/token-notes)
- [Token Info Icons](https://github.com/jopeek/fvtt-token-info-icons)
- [Moulinette](https://github.com/SvenWerlen/moulinette-core)
- [NameForge](https://gitlab.com/ElvisPereira/nameforge)
- [Automated Animations](https://github.com/otigon/automated-jb2a-animations)


## Known Issues:
- Modules that alter UI elements can potentially cause UI issues.
- It's impossible for me to test all modules. If you come across readbility issues, contact me.
- [Module Management +](https://github.com/mouse0270/module-credits): Export Window is barely readable. Can't figure out how to fix this (<-CSS Noob)
- When opening up the Sequencer Database for JB2A Animations, the Automated Animation Effects suddenly has grey elements showing. Don't know how to fix this.


Have Fun!
Sir Motte





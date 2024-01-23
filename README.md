# FO2MapLoader

Fallout 2 executable contains unused debug code which loads a list of all available maps (you can make your own, you know) and allows you to jump between them. Essentially you end up skipping the travel world map. Simply invoke a call to 0x4829F0. Tested on Steam version (I think it is US 1.02d)

## Installation and use

- Get the latest sfall: https://github.com/sfall-team/sfall (tested on 4.3.7)
- Put gl_loadmap.int in data\scripts
- Press J in game
<img width="94" alt="image" src="https://github.com/tomakela/FO2MapLoader/assets/9822663/766b84d1-f5e3-4141-83fd-87d154d2d48b">

## Could be useful for

- Escaping a glitched save game in which leaving a map causes a crash
- Modding / testing
- Cheating :(

## To note

- Will cause crashes in some situations. E.g., during combat. This might be fixable by first ending the combat programmatically?

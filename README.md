# About
Modding utility to facilitate different languages in your Mod

# Usage
Create a folder `languages` in the folder of your mod. In there create a csv named after the display language you want to provide a translation for. `English.csv` is required, the rest are optional and will default to the English translation.

By default Rusted Moss supports:
- English: `English.csv`
- Spanish: `Español.csv`
- Portuguese: `Português.csv`
- Korean: `한국어.csv`
- Japanese: `日本語.csv`
- Simplified Chinese: `简体中文.csv`
- Traditional Chinese: `繁體中文.csv`

The csv consists of key,value pairs, e.g. `mystr,"I am translated"`

To use the translation in your code, use `global.languages.get_string(string)`

# Installation
Easiest way is to download the [Rusted Moss Mod Manager](https://github.com/Harlem512/rm-mod-manager) and install through it.

# Credits
* [Harlem512](https://github.com/Harlem512/rm-mod-manager) for making the Rusted Moss mod loader and manager
* [Rusted Moss](https://www.rustedmossgame.com/) developers for making a great game

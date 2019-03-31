# arduboy-virtualpet
A virtual-pet like game designed to run on the Arduino Leonardo based Arduboy handeld arcade game console.

## Persistent savegames
Save/Load supported thanks to the EEPROM Library, Leonardo based boards have 1kb of available storage space for storing data about the creature even when turned off.
https://www.arduino.cc/en/Reference/EEPROM

## Sprites

Used free cat sprites.

Because the Arduino OLED display only supports black and white pixels and it's only 128x64 pixels big i had to process the images before using some tools to convert them in byte arrays.

Assets and sprites used can be found in the /assets subfolder. Finally settled for a white-cat sprite with transparency used as shader mask.

Original sprites page: https://opengameart.org/content/cat-sprites

Artist: [ShepardSkin](https://twitter.com/Shepardskin)

Tool used to convert images into proper sizes/colors: *Photoshop CC 2019*

Tool used to convert sprites into byte[] animations: https://teamarg.github.io/arduboy-sprite-converter/

## Links:

Hardware: https://arduboy.com/

Basic IDE: https://www.arduino.cc/en/main/software

VSCode extension: https://marketplace.visualstudio.com/items?itemName=vsciot-vscode.vscode-arduino

Community forum: https://community.arduboy.com/
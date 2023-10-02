# Sensitivity-Converter

## Credits
This app was created as a practice project to recreate online game sensitivity converters using Python and Tkinter.
All credit goes to [Armory Gaming Gear](https://armorygaminggear.com/) and [Gaming Smart's](https://gamingsmart.com/mouse-sensitivity-converter/) online sensitivity converters for their reference.

## How to use
Simply input the game title, mouse DPI and in-game sensitivity from which you wish to convert from and the game title and mouse DPI of the game to wish to convert to. \
The newly calculated in-game sensitivity will then be available for you to copy and use in your selected game.

## How to add more games?
Simply add the name of the game and the sensitivity factor into **games.csv**.

## How to calculate sensitivity factor?
1. Calculate the eDPI of the game by multiplying the in-game sensitivity with the mouse DPI.
> eDPI = in-game sens * DPI

2. Measure the cm/360° of the above eDPI by moving your mouse across a surface and measuring the distance it takes to complete a 360° rotation.

3. Calculate the sensitivity factor with by multiplying eDPI with the calculated cm/360°.
> sensitivity factor = eDPI * cm/360°

# MS-Texture

This project is a collection of various minesweeper skins for public use.

Below is an outline of this repository by 2022-4-7.

## Parts
The minesweeper interface is divided into 4 parts: the cells, the yellow face, the frame (or border) and the counters.

|Path|File names|
|-|-|
|`cells/`|`cellx for x in 0:8`|
|`faces/`|`smileface`, `clickface`, `winface`, `lostface`, `smilefacedown`|
|`counters/`|`counterx for x in 0:9`|
|`border/`|`leftright`, `topbottom`, `yx for y in (top,bottom) and x in (left,right)`|

## Elements

Elements are miscellaneous images or basic components of other images in case you want to make your own mod. Replay cursors are in this folder.

## File types
Vector graphics: `svg` and `pdf` are supported. Scale is 10x.

## Skins
`WinmineXP` and `Arbiter` skins are supported.

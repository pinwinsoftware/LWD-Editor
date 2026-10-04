# LWD Editor

LWD Editor is a map editor for games made with Lite Engine. It is used to create and modify game maps stored in the LWD file format (Lite Engine World).

To run created levels, they must first be included in an LED file using [Lade](https://github.com/pinwinsoftware/Lade).

# Creating Maps

LWD maps have a 1:1 aspect ratio. Map sizes range from 16x16 to 128x128 tiles.

To create a new LWD map, you must select an LED file for the game you are creating the level for.

LED files contain the assets of the game, such as entities that can be placed on the map.

## Map Configurations

### Map Size

You can change the map size by clicking the left and right arrows on the map size field in the bottom-right corner.

### Player Position

The player's starting position can be set in the LEM file. 

### example:

```
map MAP01
{
      x = 3.5; // Player start x
      y = 11.5; // Player start y
      angle = 270; // Player start angle
}
```

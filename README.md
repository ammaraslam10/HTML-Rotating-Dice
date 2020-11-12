# HTML-Rotating-Dice

A rotating dice that might be used in a dice based game or for some loading screen animations maybe

Currently it works on click but the functions are generic enough to be used for any purpose

```JavaScript
function turn_cube(where)
```
Turn the cube in a specific direction (-1, 0, 1), "front" will store what number the dice will have after the rotation
```JavaScript
function dice_roll()
```
Calls "turn_cube()" 25 times, select a random direction each time
```JavaScript
function dice_click()
```
Calls "dice_roll()" on physical click

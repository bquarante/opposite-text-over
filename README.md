# Opposite Text Over

## Purpose

Switch a text to the opposite color (black or white) only on the overlapping image zone.

## Method

* Make a clone of the text div with the opposite color, and mask it with the css property 'clip'.
* Add a class to divs that needs an opposite colored text overlaping.
* Detect the overlapping div position to apply css mask on the opposite text color.
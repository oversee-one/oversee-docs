---
description: 'Type for setting colors, data type: RGB'
---

# Color

## New

Creating a new color. \
Example:

```
local something_color = Colow.new(255, 0, 0) -- green color 
```



## Getting the color

Obtaining one of the three colors (red, green, blue).\
Example:

```
local something_color = Colow.new(255, 0, 0)
local red   = something_color.red( )  -- 0
local green = something_color.green( )-- 255
local blue  = something_color.blue( ) -- 0
```



## Conversion from HSB to RGB

Function to convert from HSB to RGB\
Input: hue, saturation, brightness\
Return: Color\
Example:

```
local something_color = Colow.FromHSB(300, 97, 65) -- pink
```


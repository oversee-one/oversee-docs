---
description: Interface for drawing objects on the screen
---

# Render

### Draw Line

The function that draws the line\
Input: min, max, color, thinkness\
Example:

```lua
g_Render.AddLine(Vector2.new ( 50.0, 40.0 ), Vector2.new(100.0,200.0), Color.new( 255,255,255), 1.0); 
```

### Draw Rect

The function that draws the rect\
Input: min, max, color, thinkness, rounding, flags\
Example:

```lua
local vecMins = Vector2.new( 20.0, 40.0)
local vecMaxs = Vector2.new( 100.0, 200.0)
local RedColor = Color.new(255,0,0 )
g_Render.AddRect(vecMins, vecMaxs, RedColor, 2.0, 10.0); 
```

### Draw Filled rect

The function that draws the filled rect\
Input: min, max, color, rounding, flags\
Example:

```lua
local vecMins = Vector2.new( 20.0, 40.0)
local vecMaxs = Vector2.new( 100.0, 200.0)
local RedColor = Color.new(255,0,0 )
g_Render.AddRectFilled(vecMins, vecMaxs, RedColor, 10.0); 
```



### Draw Text

The function that draws the еуче\
Input: font, font size, pos, text, color\
Example:

```lua
local font = g_FontManager.GetFont("Test Font")
local vecPos = Vector2.new( 100.0, 200.0)
g_Render.AddRectFilled(font, 12.0, vecPos, "Something Text",RedColor); 
```

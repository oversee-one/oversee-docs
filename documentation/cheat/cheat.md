# Cheat

### Add Callback

Performing a function in a particular game function\
Input: GLOBAL_SCRIPTID, name of callback, function \
Example:

```lua
g_Cheat.AddCallBack(GLOBAL_SCRIPTID, "Draw", function() 
  -- something
end)
```

### Get Mouse Position

The function returns the mouse position\
Return: Vector2\
Example:

```lua
local vecMousePos = g_Cheat.GetMousePosition()
```


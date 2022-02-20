# Cheat Vars

### Add Callback

Performing a function in a particular game function\
Input: name of callback, function \
Example:

```lua
g_Cheat.AddCallBack("Draw", function() 
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


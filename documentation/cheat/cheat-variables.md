---
description: >-
  This section contains information about obtaining, changing, and using the
  variables of the cheat itself.
---

# Cheat Variables

### GetBool

Gets the value of a variable by name.\
Example:

```lua
local boolean = g_Cheat.GetBool("misc.auto_jump")
```

### GetInt

Gets the value of a variable by name.\
Example:

```lua
local integer = g_Cheat.GetInt("misc.fog.max_distance")
```

### GetFloat

Gets the value of a variable by name.\
Example:

```lua
local float = g_Cheat.GetFloat("misc.aspect_ratio")
```

### GetColor

Gets the value of a variable by name.\
Example:

```lua
local color = g_Cheat.GetColor("misc.something")
```



### SetBool

Sets the value of a variable by name.\
Example:

```lua
g_Cheat.GetBool("misc.auto_jump", true)
```

### SetInt

Sets the value of a variable by name.\
Example:

```lua
g_Cheat.GetInt("misc.fog.max_distance", 2500)
```

### SetFloat

Sets the value of a variable by name.\
Example:

```lua
g_Cheat.SetFloat("misc.aspect_ratio", 1.77)
```

### SetColor

Sets the value of a variable by name.\
Example:

```lua
g_Cheat.SetColor("misc.something", Color.new(0.5, 0.2, 0.0))
```

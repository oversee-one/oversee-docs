# Utils

### Pattern Scan

The function searches for an area in the module's memory according to the patter\
Input: module name, pattern\
Example:

```lua
local addr = g_Utils.PatternScan("furrys.dll", "E8 0 0 0 0")
```

### Creating Interface

The function creates an interface\
Input: module name, interface name\
Example:

```lua
local engineclient = g_Utils.CreateInterface("client.dll", "VENGINECLIENT014")
```

### Getting random int&#x20;

The function return a random int\
Input: min, max\
Example:

```lua
local random_int = g_Utils.GetRandomInt(60, 90)
```

### Getting random float

The function return a random float\
Input: min, max\
Example:

```lua
local random_float = g_Utils.GetRandomFloat(60.0, 90.0)
```



### Getting random seed

The function return a seed\
Input: seed\
Example:

```lua
local seed = g_Utils.GetRandomSeed(11)
```

### Getting unix time

The function return a unix time\
Example:

```lua
local unix = g_Utils.GetUnixTime()
```



### Is Key holded

The function return a key holded\
Input: Virtual Key \
Example:

```lua
local is_holded = g_Utils.IsKeyHold( 0x34 )
```



### Is Key toggled

The function return a key toggled\
Input: Virtual Key \
Example:

```lua
local is_toggled = g_Utils.IsKeyToggled( 0x34 )
```

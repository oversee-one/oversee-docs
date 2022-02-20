---
description: Type of angles from the source engine
---

# QAngle

## New

Creating a new angle. \
Supports int, float type\
Example:

```
local NewAngle = QAngle.new(2.0, 3.0, 0.0)
```

### Coordinates

Getting anglee coordinates\
Example:

```lua
local angSometing = QAngle.new( 6.0, 9.0, 1.0)
local pitchVariable  = angSometing.pitch -- pitchVariable = 6.0
local yawVariable    = angSometing.yaw -- yawVariable = 9.0
local rollVariable   = angSometing.roll -- rollVariable = 1.0
```



### Length

Function for obtaining angle length\
Example:

```lua
local angSomething = QAngle.new( 6.0, 9.0, 1.0)
local flLength = angSomething.Length()  --  ~ 10.862
```

### Normalize

Angle normalization function \
Returns: the length of the angle and normalizes the vector itself\
Example:\
local vecSomething = Vector.new( 6.0, 9.0)

```lua
local angSomething = Vector.new( 6.0, 9.0, 1.0)
local flLength = angSomething.Normalize() --  ~ 10.816, and normalize itself
```


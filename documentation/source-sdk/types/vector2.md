---
description: >-
  Vector2 is a directional segment in two-dimensional space that has direction
  and length.
---

# Vector2&#x20;

## New

Creating a new two-dimensional vector. \
Supports int, float type\
Example:

```
local new_2dvector = Vector2.new(2.0, 3.0)
```

### Coordinates

Getting vector coordinates\
Example:

```
local vecSomething = Vector2.new( 6.0, 9.0)
local xVariable = vecSomething.x -- xVariable = 6.0
local yVariable = vecSomething.y -- yVariable = 9.0
```



### Length

Function for obtaining vector length\
Example:

```
local vecSomething = Vector.new( 6.0, 9.0)
local fl2DLength = vecSomething.Length()  --  ~ 10.816
```


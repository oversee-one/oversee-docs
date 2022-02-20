---
description: A vector is a directional segment that has a direction and a length.
---

# Vector

## New

Creating a new Vector. \
Supports int, float type\
Example:

```
local new_vector = Vector.new(2.0, 3.0, 4.0)
```

### &#x20;Coordinates

Getting vector coordinates\
Example:

```
local vecSomething = Vector.new( 6.0, 9.0, 1.0 )
local xVariable = vecSomething.x -- xVariable = 6.0
local yVariable = vecSomething.y -- yVariable = 9.0
local zVariable = vecSomething.z -- zVariable = 1.0
```



### Length

Function for obtaining vector length\
Example:

```
local vecSomething = Vector.new( 6.0, 9.0, 1.0 )
local flLength = vecSomething.Length()  --  ~ 10.862
```



### Length2D

The function for obtaining the length of vector x and y coordinates\
Example:

```
local vecSomething = Vector.new( 6.0, 9.0, 1.0 )
local fl2DLength = vecSomething.Length2D()  --  ~ 10.816
```

### &#x20;The distance between the vectors

Function for calculating the distance between vectors\
Example:

```
local vecSomething = Vector.new( 6.0, 9.0, 1.0 )
local vecSomething2 = Vector.new( 1.0, 4.0, 3.0 )
local flVectorDistance = vecSomething.DistTo( vecSomething2 )  -- lazy to count
```

### Cross product

Function for calculating the vector product.\
Example:

```
local vecSomething = Vector.new( 6.0, 9.0, 1.0 )
local vecSomething2 = Vector.new( 1.0, 4.0, 3.0 )
local flVectorDistance = vecSomething.Cross( vecSomething2)
```



#### Scalar product

A function for calculating a scalar product.\
Example:

```
local vecSomething = Vector.new( 6.0, 9.0, 1.0 )
local vecSomething2 = Vector.new( 1.0, 4.0, 3.0 )
local flVectorDistance = vecSomething.Dot(vecSomething2)
```

#### &#x20;


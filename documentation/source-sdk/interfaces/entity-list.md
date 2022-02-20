# Entity List

### Number of entities

Returns the number of existing entities\
Input : bool inclNonNetworkable\
Example:

```
local entity_numbers = g_EntityList.NumberOfEntities( false ) -- inclNonNetworkable = false
```

### Highest Entity Index

Returns the largest entity index\
Example:

```
local highest_index = g_EntityList.NumberOfEntities()
```

### GetClientEntityFromHandle&#x20;

Returns C\_BaseEntity \
Input: unsigned long Handle\
Example:

```
local entity = g_EntityList.GetClientEntityFromHandle(something_handle)
```

### Get Local Player

Returns the local player\
Return type: C\_BasePlayer\
Example:

```
local something_player = g_EntityList.GetLocalPlayer();
```

### Get Weapon

Returns the weapon \
Input: EntIndex\
Return type: C\_BaseCombatWeapon\
Example:

```
local weapon = g_EntityList.GetWeapon( 4 ) -- 4 is ent index 
```



### Get Player From Handle

Returns the player from handle\
Return type: C\_BasePlayer\
Example:

```
local something_player = g_EntityList.GetPlayerFromHandle( something_handle);
```

### Get Weapon From Handle

Returns the weapon from handle\
Return type: C\_BaseCombatWeapon\
Example:

```
local something_weapon = g_EntityList.GetWeaponFromHandle( something_handle);
```



### Get Player from user id

Returns the player where the user id matches the function argument\
Return type: C\_BasePlayer\
Example:

```
local something_player = g_EntityList.GetPlayerFromUserId(24715681);
```


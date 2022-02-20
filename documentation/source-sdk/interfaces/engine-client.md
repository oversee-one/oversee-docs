# Engine Client

### ExecuteClientCmd

The function stuffs the command into the buffer and executes it.\
Example:

```lua
g_EngineClient.ExecuteClientCmd("say oversee better" ); 
```

### GetLevelName

Gets the full name of the map you are on\
Example:

```
local full_map_name = g_EngineClient.GetLevelName( )
```

### GetLevelNameShort

Gets the full name of the map you are on\
Example:

```
local full_map_name = g_EngineClient.GetLevelNameShort( )
```

### GetLocalPlayer

Gets the index of the local player. \
You can get a player class using EntityList\
Example:

```
local player_index = g_EngineClient.GetLocalPlayer( ) 
```

### GetNetChannel

Gets the current NetChannel\
Example:

```
local net_chan = g_EngineClient.GetNetChannel()
```

### GetScreenSize

Gets the player's current screen resolution\
Example:

```
local screen_size = g_EngineClient.GetScreenSize() -- return Vector2
```

### GetViewAngles

Returns QAngle with view angles\
Example:

```
local screen_size = g_EngineClient.GetScreenSize() -- return Vector2
```

### IsConnected

The function returns a bool whether the server is connected\
Example:

```
local is_connected = g_EngineClient.IsConnected() 
```



### IsInGame

The function returns a bool whether the player is in the game\
Example:

```
local is_ingame = g_EngineClient.IsInGame() 
```

### GetLastTimeStamp

Returns timestamp \
Data type: int\
Example:

```
local timestamp = g_EngineClient.GetLastTimestamp() 
```

### GetPlayerInfo

Returns information about the player\
Data type: PlayerInfo\
Example:

```
local playerinfo = g_EngineClient.GetPlayerInfo( 3 ) -- 3 is ent index
local is_bot = playerinfo.IsFakePlaye
```




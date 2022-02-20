# Global Vars

### GetRealTime&#x20;

Returns the current real time\
Example:

```
local real_time = g_GlobalVars.GetRealTime()
```

### GetFrameCount&#x20;

Returns the current frame count\
Example:

```
local frame_count = g_GlobalVars.GetFrameCount()
```

### GetAbsoluteFrameTime

Returns the current abs frame time\
Example:

```
local absframetime = g_GlobalVars.GetAbsoluteFrameTime()
```



### GetCurTime

Returns the current local time\
Example:

```
local curtime = g_GlobalVars.GetCurTime()
```

### GetFrameTime

Returns the current frame time \
Example:

```
local frametime = g_GlobalVars.GetFrameTime()
```

### GetMaxClients

Returns the max clients from server settings\
Example:

```
local max_clients = g_GlobalVars.GetMaxClients()
```

### GetTickCount

Returns the simulation ticks\
Example:

```
local tickcount = g_GlobalVars.GetTickCount()
```

### GetIntervalPerTick

Returns the simulation tick interval\
Example:

```
local ipt = g_GlobalVars.GetIntervalPerTick()
```



### GetSimTicksForThisFrame

Returns the simulation tick for this frame\
Example:

```
local SimTicksForThisFrame = g_GlobalVars.GetSimTicksForThisFrame()
```



### GetNetworkProtocol

Returns the current saverestore data \
Example:

```
local network_protocol = g_GlobalVars.GetNetworkProtocol()
```

### GetSaveData

Returns the current saverestore data \
Example:

```
local save_data = g_GlobalVars.GetSaveData()
```



### GetClient

Returns true if client code\
Example:

```
local client = g_GlobalVars.GetClient()
```

### GetRemoteClient

Returns true if remove client\
Example:

```
local remote_client = g_GlobalVars.GetRemoteClient()
```

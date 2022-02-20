# Fake Lags

### SetChokeAmount

This function sets how many ticks will be choked.\
Input: choke amount\
Example:

```lua
g_FakeLag.SetChokeAmount( 14 ) -- override fake lags to 14
```

### GetChokedCommands

This function returns how many ticks the fakelags choked\
Example:

```lua
local ticks_choked = g_FakeLag.GetChokedCommands() 
```

### SetPacketMode

This fuction installs a mod for fake lag\
0 - None\
1 - Send\
2 - Choke\
Example:

```lua
g_FakeLag.SetPacketMode( 1 ) -- force to send
```

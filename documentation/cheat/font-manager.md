# Font Manager

### PushFontFromFile

This function creates your font from the file\
Input: Name, FontName in windows directory, size \
Example:

```lua
g_FontManager.PushFontFromFile("Test Font","Calibri", 12)
```

### PushFontFromData

This function creates your font from the raw data\
Input: Name, RawData, size\
Example:

```lua
g_FontManager.PushFontFromFile("Test Font", rawData, 12)
```

### GetFont

This function gives you the font by name\
Input: Name\
Return: ImFont\
Example:

```lua
local font = g_FontManager.GetFont("Test Font")
```

### UpdateFonts

This function completely reinitializes all fonts, you need to call it once when you add a new font\
Example:

```lua
g_FontManager.UpdateFonts()
```


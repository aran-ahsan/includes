# includes
Include Files for PureBasic

*All files are "EnableExplicit safe" and "Multiple-include safe".*

## [JSON.pbi](JSON.pbi)
Basic JSON support (read/write/parse/modify) before PureBasic added its own JSON library in 5.30
+ Windows/Linux/Mac
+ ASCII/Unicode safe
+ Demo included
+ **PB 5.30+**: Compilation is disabled (conflicts with PB's JSON commands)
+ **PB 5.20+**: Compiles as a Module (`UseModule JSON`)
+ **Before 5.20**: Compiles as included procedures

## [Winamp.pbi](Winamp.pbi)
Gives you basic access and control of Winamp's playback status
+ Windows only
+ ASCII/Unicode safe
+ **Note**: This is for controlling Winamp from an external program, not for writing Winamp plugin DLLs

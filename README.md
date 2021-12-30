# gdscript-tmt
A port of libtmt to GDScript.
## Macros (and building)
Due to libtmt's heavy use of macros, this project uses [AnyMacro](https://github.com/xdevs23/anymacro) to implement macros in GDScript. So, before importing it into your project, navigate to a directory containing AnyMacro's source and run this command: `node js/index.js tmt.gd _tmt.gd` and rename `_tmt.gd` to `tmt.gd`. While constant and functions are perferred, macros are used when needed.

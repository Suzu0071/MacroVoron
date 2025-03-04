# MacroVoron

| Name | Description | Slicer gcode | Standalone |
| -------- | -------- | -------- | -------- |
| Cura-purge-line.cfg | Purge line taken from cura | `CURA_PURGE_LINE` | x |
| StartBland.cfg | The most common start macro | `PRINT_START EXTRUDER=Meow BED=Meow` | x |
| EndBland.cfg | The most common end macro | `PRINT_END` | x |
| SoakStart.cfg | Print start with a 10 min heatsoak | `PRINT_START EXTRUDER=Meow BED=Meow CHAMBER=Meow` | x |
| SoaktoStart.cfg | Print start that reaches a specific chamber temp to start print | `PRINT_START EXTRUDER=Meow BED=Meow HEATUP_TEMP=Meow CHAMBER=Meow` | x |

# MacroVoron
With love, from Suzuki

☆*: .｡. o(≧▽≦)o .｡.:*☆

| Name | Description | Slicer/Console gcode | Standalone |
| -------- | -------- | -------- | -------- |
| Cura-purge-line.cfg | Purge line taken from cura | `_CURA_PURGE_LINE` | ❌ |
| StartBland.cfg | The most common start macro | `_PRINT_START EXTRUDER=Meow BED=Meow` | ❌ |
| EndBland.cfg | The most common end macro | `_PRINT_END` | ❌ |
| SoakStart.cfg | Print start with a 10 min heatsoak | `_PRINT_START EXTRUDER=Meow BED=Meow CHAMBER=Meow` | ❌ |
| MaterialSoakStart.cfg | Soak or not depends on the material | `_PRINT_START EXTRUDER=Meow BED=Meow HEATUP_TEMP=Meow MATERIAL=[filament_type[initial_extruder]]` | ❌ |
| SoaktoStart.cfg | Print start that reaches a specific chamber temp to start print | `_PRINT_START EXTRUDER=Meow BED=Meow HEATUP_TEMP=Meow CHAMBER=Meow` | ❌ |
| LoadFilament.cfg | Push filament into the hotend | `LOAD_FILAMENT` | ✅ |
| UnloadFilament.cfg | Pull out the filament from the hotend | `UNLOAD_FILAMENT` | ✅ |

<img src="./Hoshimi.jpg" width=500>

  <p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/Suzu0071/MacroVoron">MacroVoron</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://github.com/Suzu0071">Suzu0071</a> is licensed under <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1" alt=""></a></p> 

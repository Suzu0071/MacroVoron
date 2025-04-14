# MacroVoron

<ins>**Don't copy paste, this is more just an example**</ins>

With love, from Suzuki

☆*: .｡. o(≧▽≦)o .｡.:*☆

*Start Macros:*
| Name | Description | Slicer/Console gcode | Standalone | Needs Chamber Sensor |
| - | - | - | - | - |
| [StartBland.cfg](./Print-Start/StartBland.cfg) | The most common start macro | `_PRINT_START EXTRUDER=Meow BED=Meow` | ❌ | ❌ |
| [SoakTimeStart.cfg](./Print-Start/SoakTimeStart.cfg) | Print start with an X min heatsoak | `_PRINT_START EXTRUDER=Meow BED=Meow SOAK_TIME=Meow CHAMBER=Meow` | ❌ | ❌ |
| [MaterialSoakStart.cfg](./Print-Start/MaterialSoakStart.cfg) | Soak or not depends on the material | `_PRINT_START EXTRUDER=Meow BED=Meow HEATUP_TEMP=Meow MATERIAL=[filament_type[initial_extruder]]` | ❌ | ✅ |
| [SoaktoStart.cfg](./Print-Start/SoaktoStart.cfg) | Print start that reaches a specific chamber temp to start print | `_PRINT_START EXTRUDER=Meow BED=Meow HEATUP_TEMP=Meow CHAMBER=Meow` | ❌ | ✅ |

*End Macros:*
| Name | Description | Slicer/Console gcode | Standalone |
| - | - | - | - |
| [EndBland.cfg](./Print-End/EndBland.cfg) | The most common end macro | `_PRINT_END` | ❌ |
| [EndSafeZ.cfg](./Print-End/EndSafeZ.cfg) | Moves the z axis by a specified "safe z" after end | `_PRINT_END` | ❌ |

*Purge Lines:*
| Name | Description | Slicer/Console gcode | Standalone | Image | 
| - | - | - | - | - |
| [Cura-purge-line.cfg](./Purge-Line/Cura-purge-line.cfg) | Purge line taken from cura | `_CURA_PURGE_LINE` | ❌ | Coming later |
| [Square.cfg](./Purge-Line/Square.cfg) | Adaptive purge in the shape of a square | `_SQUARE_PURGE` | ❌ | `./Images/Square-Purge.png` |

*Random:*
| Name | Description | Slicer/Console gcode | Standalone |
| - | - | - | - |
| [LoadFilament.cfg](./Random/LoadFilament.cfg) | Push filament into the hotend | `LOAD_FILAMENT` | ✅ |
| [UnloadFilament.cfg](./Random/UnloadFilament.cfg) | Pull out the filament from the hotend | `UNLOAD_FILAMENT` | ✅ |

*Macro add-ons:*
| Name | Description | Needs Chamber Sensor |
| - | - | - |
| [BedFan.cfg](./Add-Ons/BedFan.cfg) | Describes macro changes if using a bed fan(s) | ❌ |
| [BedFanBetter.cfg](./Add-Ons/BedFanBetter.cfg) | A better alternative to the normal BedFan.cfg | ❌ |
| [BedFanReverse.cfg](./Add-Ons/BedFanReverse.cfg) | Bed fan will turn on when it passes target temperature | ✅ |
| [MaterialZOffset.cfg](./Add-Ons/MaterialZOffset.cfg) | Sets a specific Z offset depending on material printed | ❌ |

<img src="https://raw.githubusercontent.com/Suzu0071/Helper-Repository/refs/heads/main/MacroVoron/Hoshimi.png" width=500>

  <p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/Suzu0071/MacroVoron">MacroVoron</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://github.com/Suzu0071">Suzu0071</a> is licensed under <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1" alt=""></a></p> 

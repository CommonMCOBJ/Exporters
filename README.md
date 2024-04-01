# Exporters
This is a list of exporters that implement the CommonMCOBJ spec.

| Exporter                                          | CommonMC Version | Appears in | Supported Operating Systems | Additional Notes                                                                                                                                                                            |
| ------------------------------------------------- | ---------------- | ---------- | --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Mineways](https://github.com/erich666/Mineways/) | V1               | v11.07     | Windows<sup>[1]</sup>                  | Mineways contains an additional header with much more information about the export. More of those options may be added to CommonMCOBJ in the future.                                                     |
| [cmcOBJ](https://github.com/CommonMCOBJ/cmc2obj)  | V1               | v1.0       | Any platform with JVM       | cmc2OBJ is the reference implementation of CommonMCOBJ and is intended for developers. In addition, cmc2OBJ is forked from jmc2OBJ, but will deviate as more parts are converted to Kotlin. |

[1]: Can be ran on non-Windows systems with WINE
 
## Adding Exporters 
Exporters that wish to be added to this list can be added, so long as they meet the following requirements:
- Implements CommonMCOBJ
- Source code publically availible under a open source license
- Repository updated at some point in the last year


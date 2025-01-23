# pp-0 > events
## abstract
imported and generated chronicle data

## navigation
- `e*.json` individual record

## dictionary
### json
| var | type | values | note |
|:--|:--|:--|:--|
| `id` | string | e_ | unique identifier |
| `work` | object | - | event eligibility and type |
| `data` | object | - | event details |

#### work object
| var | type | values | note |
|:--|:--|:--|:--|
| `cod` | boolean | - | will event be looked at?[^`true` if we are confident event is unique, well-sourced incident of piracy or defence-against-piracy in Hond Bay in 17th cent; `false` if we are sure event is duplicate or apocryphal or not in Hond Bay etc; `null` if unsure] |
| `cod_n` | string | - | `cod` notes |
| `pir` | boolean | - | is a piracy event? |
| `pir_n` | string | - | `pir` notes |

#### data object
| var | type | values | note |
|:--|:--|:--|:--|
| `name` | string | - | name or short description |
| `desc` | string | - | long description |
| `locn` | string | - | locations |
| `lbd` | string | - | lower bound |
| `upd` | string | - | upper bound |
| `actors` | string | - | names or agents involved |
| `lit_n` | string | - | cf pointer to published literature |
| `prim_n` | string | - | cf pointer to primary sources |
| `note` | string | - | notes |

## licence
none

## history
written 22 jan 2025 benque, cy
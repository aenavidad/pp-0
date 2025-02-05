# pp-0 > incidents
## abstract
generated chronicle data
## navigation
- `1*.json` individual record
## dictionary
### json

| var | type | values | note |
|:--|:--|:--|:--|
| `yr` | string | 1_ | year |
| `tally` | number | - | incidents tally |
| `tally_n` | string | - | `tally` notes |
| `incident0`[^ie `incident0`, `incident1`, `incident2`, and so on] | object | - | single incident |

#### incident object

| var | type | values | note |
|:--|:--|:--|:--|
| `conf` | boolean | - | is a confident incident?[^ `true` if we are sure this is a unique, well-sourced incident of piracy or defence-against-piracy in Hond Bay in the relevant 17th cent year; `false` if we are sure it isn't; `null` if unsure] |
| `conf_n` | string | - | `conf` notes |
| `pir` | boolean | - | is a piracy incident? |
| `pir_n` | string | - | `pir` notes |
| `lbd` | string | - | lower bound |
| `upd` | string | - | upper bound |
| `locn` | string | - | location |
| `desc` | string | - | description |
| `note` | string | - | notes |
| `via` | string | - | sources[^from `/events` or `/cartas`] |

## licence
none
## history
written 5 feb 2025 benque, cy
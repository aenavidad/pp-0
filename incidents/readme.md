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
| `incidents` | array | objects | incidents |
| `possible` | array | objects | incidents[^which may not be what we're looking for]

#### incident object[^in `incidents` array]

| var | type | values | note |
|:--|:--|:--|:--|
| `conf` | boolean | - | is a confident incident?[^ `true` if we are sure this is a unique, well-sourced, non-compound incident of piracy or defence-against-piracy in Hond Bay in the relevant 17th cent year; `false` if we are sure it isn't; `null` if unsure] |
| `conf_n` | string | - | `conf` notes |
| `pir` | boolean | - | is a piracy incident? |
| `pir_n` | string | - | `pir` notes |
| `lbd` | string | - | lower bound[^in `mm-dd`] |
| `upd` | string | - | upper bound[^in `mm-dd` or `yyyy-mm-dd` for multi-year incident] |
| `locn` | string | - | location |
| `desc` | string | - | description |
| `note` | string | - | notes |
| `via` | string | - | sources[^from `/events` or `/cartas`] |
| `no` | number | - | incident number[^for reference, so unique over all acts in `incidents` and `possible` arrays] |

## licence
none
## history
written 5 feb 2025 benque, cy
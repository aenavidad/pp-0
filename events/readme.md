# pp-0 > events
## abstract
imported and generated chronicle data

## navigation
- `e*.json` individual record[^likely from `historical-series-re-Belize/v-1.4/Events*.tsv` if tagged `v-1.4` or from `pre-git-hist/files/harv/1638 series*.tsv` if tagged `harv` or newly written else]

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
| `agents_sp` | string | - | Spanish agents involved |
| `agents_nsp0` | string | - | non-Spanish agents involved |
| `agents_nsp1` | string | - | non-Spanish agents involved |
| `lit_n` | string | - | cf pointer to published literature |
| `press_n` | string | - | cf pointer to press |
| `prim_n` | string | - | cf pointer to primary sources |
| `note` | string | - | notes |
| `via` | string | - | import source of record[^use to decode short citations, with full citations in `/citations` ~~for `v-1.4` in `historical-series-re-Belize/v-1.4/Sources*.tsv` and for `harv` in `pre-git-hist/files/harv/1638 sources*.tsv`~~] |

## licence
none

## history
written 22 jan 2025 benque, cy
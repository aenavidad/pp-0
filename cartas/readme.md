# pp-0 > cartas
## abstract
imported and generated calendar data
## navigation
- ~~`list.tsv` list of manuscripts calendared[^from `pre-git-hist/files/yell/data manuscripts agi 1.1-scrap*.tsv`]~~
- ~~`list.json` list of manuscripts calendared plus coding data[^from `data manuscripts agi 1.1-scrap*.tsv` and `data manuscripts agi 1.1-GTa*.tsv`]~~
- `c*.json` individual record[^from `data manuscripts agi 1.1-scrap*.tsv` and `data manuscripts agi 1.1-GTa*.tsv`, plus newly written ones]
## dictionary
### json
| var | type | values | note |
|:--|:--|:--|:--|
| `id` | string | c_ | unique identifier |
| `work` | object | - | coding intent and status[^from `cartas/list.tsv`] |
| `cat` | object | - | PARES catalogue info |
| `data` | object | - | coding output |

#### work object
| var | type | values | note |
|:--|:--|:--|:--|
| `cod` | boolean | - | will record be coded? |
| `cod_n` | string | - | `cod` notes |
| `stat` | number | - | coding status[^0 not yet started, 1 started and ongoing, 2 completed] |
| `stat_n` | string | - | `stat` notes |
#### cat object
| var | type | values | note |
|:--|:--|:--|:--|
| `url` | string | - | url |
| `docs` | number | - | document tally |
| `title` | string | - | title |
| `scope` | string | - | scope |
| `desc` | string | - | description |
| `locn` | string | - | location |
| `lbd` | string | - | lower bound |
| `upd` | string | - | upper bound |
| `ref` | string | - | call no |
#### data object
| var | type | values | note |
|:--|:--|:--|:--|
| `mil` | boolean | - | military[^`true` for `pir` or `def`] |
| `pir` | boolean | - | record has evidence of piracy incident[^even just a few words eg 'so and so attacked'] |
| `def` | boolean | - | record has evidence of defence-against-piracy ~~incident~~[^either incident (even in just a few words), or non-incident (eg re general state of defence, defence proposals, etc - but in *more* than a few words)] |
| `lit_n` | string | - | cf pointer to published literature[^only C Amaya imported, likely = ~~S 18 in `historical-series-re-Belize/v-1.4/Sources-Series S 0—1628*.tsv`~~ `citations/s18.json` ie [Cardona Amaya's 2020 *Invasiones*](https://shs.hal.science/halshs-02540842v1).] |
| `codg_n` | string | - | coding comments to coder |
| `mil_n` | string | - | notes for `mil`, `pir`, `def` |

## licence
none
## history
written 24 dec 2024 benque, cy
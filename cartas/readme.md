# pp-0 > cartas
## abstract
imported and generated calendar data
## navigation
- `list.tsv` list of manuscripts calendared[^from `pre-git-hist/files/yell/data manuscripts agi 1.1-scrap*.tsv`]
- `list.json` list of manuscripts calendared plus coding data[^from `data manuscripts agi 1.1-scrap*.tsv` and `data manuscripts agi 1.1-GTa*.tsv`]
- `c*.txt` individual record[^from `data manuscripts agi 1.1-scrap*.tsv` and `data manuscripts agi 1.1-GTa*.tsv`]
## dictionary
### tsv
| var | values | note |
|:--|:--|:--|
| `id` | c_ | unique identifier |
| `cat_url` | https_ | PARES url |
| `cod` | 0/1/^^^ | will record be coded?[^0 no, 1 yes] |
| `cod_n` | _/^^^ | `cod` value notes |
| `stat` | 0/1/2/\-^-/^^^ | coding status[^0 not yet started, 1 started and ongoing, 2 completed] |
| `stat_n` | _/^^^ | `stat` value notes |

- `^^^` is a null but applicable and retrievable value
- `-^-` is a null and either not applicable or not retreivable value

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
| `cod` | boolean | - | will record be coded |
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
#### data object
| var | type | values | note |
|:--|:--|:--|:--|
| `mil` | boolean | - | military[^`true` for `pir` or `def`] |
| `pir` | boolean | - | record has evidence of piracy incident |
| `def` | boolean | - | record has evidence of defence-against-piracy incident |
| `lit_n` | string | - | cf pointer to published literature |
| `codg_n` | string | - | coding comments to coder |
| `mil_n` | string | - | notes for `mil`, `pir`, `def` |

## licence
none
## history
written 24 dec 2024 benque, cy
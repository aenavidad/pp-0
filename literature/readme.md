# pp > literature
## abstract
extracted calendar data
## navigation
- `s*.json` individual recod[^imported from `pre-git-hist/files/harv/1638 series*.tsv` if tagged `harv`]
## dictionary
### json

| var | type | values | note |
|:--|:--|:--|:--|
| `id` | string | s_ | unique identifier[^matches `id` in `/citations` source] |
| `cite` | string | - | short citation[^matches `cite` or `old_cites` in `/citations`] |
| `note` | string | - | note |
| `via` | string | - | record source[^if imported] |
| `quotes` | array | objects | relevant quotes or extracts |

#### quote object[^in `quotes` array]

| var | type | values | note |
|:--|:--|:--|:--|
| `in` | string | - | location of quote in source |
| `quote` | string | - | quote |
| `quote_n` | string | - | `quote` notes |
| `locn` | string | - | location of incident or event or act in `quote` |
| `act` | string | - | short description of incident in `quote`[^ideally in agent-action format] |
| `att` | string | - | authors attitude towards claim in `quote`[^string of `[012][np]?` where `0` is no qualification, `1` at least some qualification, `2` uncertain or undiscernible qualification, `n` disagreement or rejection, `p` agreement or acceptance, and no letter character for uncertain or undiscernible attitude] |
| `lbd` | string | - | lower bound of incident in `quote` |
| `upd` | string | - | upper bound of incident in `quote` |
| `date` | string | - | date of incident in `quote`[^as given by author] |
| `note` | string | - | note |

## licence
none
## history
written 18 feb 2025 benque, cy
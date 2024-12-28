# log

## 23 dec 2024 onwards
- [x] emailed re**@psu.edu
- [x] emailed rod**.historiador@gmail.com
- [x] no calendar work in ``historical-series-re-Belize/work/apr-24``
- [x] none in ``/oct-23``
- [x] ``/versioning/calendar.tsv`` not filled in
- [x] check ``sheets varids.tsv`` for earliest file w/ calendar
- [x] cartas first pop up in varid 70 ie in 10-30 sep 2021
- [x] check ``pre-git-hist/events.tsv`` for sep 2021
- [x] cartas in ``files/red/rep bz fin pub 1.3_stable *.tsv`` written 7 sep 2021[^seems like a stable ``.numbers`` to ``.tsv`` export so prolly had cartas by 7 sep]
- [x] so cartas first pop up in varid 75 ie by 7 sep[^in `sheets/rep bz fin pub 1.3_stable.tsv`]
- [x] check events again for post-`v-1.4` work[^cartas next touched in `pre-git-hist/files/purp/1638 series *.tsv` on 9 jul 2022, then `purp/PARES-*.txt`, then `purp/1638 cartas *.tsv`, then `yell/data *.tsv` on 27 jul 2022 w last recorded mod on 3 aug 2022]
- [x] check work in `work/*-22`
- [x] check work in `work/*-23`
- [x] get latest data version in `txt` for `git`[^got in `tsv` and `json`]
- [x] split `list.json` for easier handling?[^yes with ``for i in `seq 0 5239`; do jq ".[$i]" list.json > "c$i.json"; done``, plus remove `cartas/list.*` to keep only object files]
- [x] fix `cod` values[^must be `true` if any `data` value is not `null` - done but not rechecked]
- [x] ~~mark `true` for null values of `cod` for cartas de Guat/Mex w/in 15 yrs of 1630[^abort at 1620 as can just navigate by `lbd` value]~~
- [x] add `ref` values to `cat` for easier navigation[^via eg `jq '.cat += {"ref" : "GUATEMALA,39,R.14,N.93"}' c0.json > tmp && mv tmp c0.json`]
- [x] coded 1638 dated records[^checked for thoroughness but not accuracy too - all such files now have non-null `cod` and data in `data` if appropriate, but pre-existing data in `data` not reviewed ie only `false cod` should have null `data`, but `true cod` may have inaccurate or incomplete pre-existing `data`]
- [x] ~~code cartas de gobernadores de Hon/Yuc first?~~
- [x] ~~coded 1639 records~~
- [x] further ensure each 1638 record is calendared w/ summary/extract, either via `cat` or added in `data`[^except records w/c seem irrelevant from `cat` eg geographically irrelevant, and non-digitised records]
- [x] code 1639 records[^fill in any null `cod`, fill in null `mil` for `true cod`, and add record summary in `data` if one in `cat` is weak (for relevant records)]
- [x] code 1640 records
- [x] code 1641 records
- [x] code 1642 records
- [x] code 1643 records
- [x] code 1644 records
- [x] code 1645 records
- [ ] code 1646 records

## prior log
* for `v-1.4`, first written by 7 sep 2021, last updated 24 oct 2021 still in belmopan, cy[^varids 75 and 11 in `work\versioning\sheets varids.tsv`]
* then worked on 9 jul 2022 to 3 aug 2022 in boston, ma[^in `purp/1638 series *.tsv` and `purp/PARES-*.txt` and `purp/1638 cartas *.tsv` and `yell/data manuscripts *.tsv`.]
* no work since then


## history
written 23 dec 2024 in benque, cy
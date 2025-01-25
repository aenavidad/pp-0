# log

## 23 dec 2024 onwards
- [x] emailed re**@psu.edu[^got reply 28 dec 2024]
- [x] emailed rod**.historiador@gmail.com[^no reply as of 22 jan 2025]
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
- [x] code 1646 records
- [x] code 1647 records
- [x] code 1648 records
- [x] code 1649 records
- [x] code 1650 records
- [x] code 1637 records
- [x] code 1636 records
- [x] code 1635 records
- [x] filed AGI formulario de alta[^got credentials 2 jan 2025]
- [x] code 1634 records
- [x] code 1633 records
- [x] code 1632 records
- [x] code 1631 records
- [x] code 1630 records
- [x] code 1651 records
- [x] code 1629 records
- [x] code 1652 records
- [x] code 1628 records
- [x] code 1653 records
- [x] code 1627 records
- [x] code 1654 records
- [x] code 1626 records
- [x] code 1655 records
- [x] code 1625 records
- [x] code 1656 records
- [x] code 1624 records
- [x] code 1657 records
- [x] code 1623 records
- [x] code 1658 records
- [x] code 1622 records
- [x] code 1621 records
- [x] code 1620 records
- [x] code 1619 records
- [x] code 1618 records
- [x] give full citation for `lit_n` short cites
- [x] get prior log for 17th cent piracy- or defence-against-piracy events in Hond Bay work
- [x] search `historical-series-re-Belize/work/versioning/events.tsv` for earliest file in `/versioning/sheets varids.tsv` with requisite events records
- [x] requisite events record first pops up in varid 212 ie in 13-14 feb 2021[^1688 hostile action only, not specifically cited but likely not assumed (given vars press sources in sheet)]
- [x] check `pre-git-hist/events.tsv` for feb 2021 and prior
- [x] requisite events record noted in `files/tran/The Baymen's experiment.rtf` written 1-4 oct 2020[^1638 Hond settlement only, but no citation and ~~possibly~~ likely assumed]
- [x] and noted in `files/tran/THIS SETTLEMENT-TURNED-COL.rtf` written 5 oct 2020[^again 1638 settlement only, ~~possibly~~ likely assumed]
- [x] and no other pre-feb 2021 records
- [x] check events again for post-`v-1.4` work[^events next touched *possibly* in `red/prelim rep bz 1.4 WORK *.tsv` on 7 nov 2021, then (sort of) in `wiki/Timeline_of_piracy_in_the_Bay_of_Honduras.xml` on 18 apr 2022 (with other wikis sort of also using events data but disregarded here in favour of only this one), then in `blue/orig data events *.tsv` on 18 may 2022, then in `purp/1638 series 1.2 Events*.tsv` on 9 jul 2022, then *possibly* in `red/rep bz fin pub 1.4 Events*.tsv` on 13 jul 2022, then in `purp/1638 series 1.3 Events*.tsv` and `purp/1638 series 1.5 Events*.tsv` on 18 jul 2022, then in `purp/1638 series 1.5 safe copy Events*.tsv` on 20 jul 2022, then in `harv/1638*.tsv` on 3 aug 2022, none further]
- [x] check for events work in `historical-series-re-Belize/work/*-22`[^null]
- [x] check in `work/*-23`[^null]
- [x] check in `work/*-24`[^null]
- [x] get latest records for eligible events in `json` to `pp-0/events`[^except for `/wiki` records or data, to be added later, and assuming no change in `red/rep bz fin pub 1.4 Events*.tsv` nor `red/prelim rep bz 1.4 WORK *.tsv`]
- [x] write `events/readme.md`
- [x] get `v-1.4` events records into one sheet, but exclude records with neither upper nor lower bound in 17th cent
- [x] further remove meteorological and biological events
- [x] add post-`v-1.4` event records starting wih latest version in `harv/1638*.tsv`
- [x] check that added records use decipherable short citations[^yes in `blue/orig data sources 1.2*.tsv` (in `harv/1638 sources*.tsv` too) for records from `harv/1638 series*.tsv`]
- [x] fix `id` values, and assign missing ones[^non-lossy odd ids > 2163 assigned ie `e2165` to `e2183`]
- [x] fix null values[^keeping `xxx` in-text null/missing value placeholder]
- [x] check for special `json` chars
- [x] get `json` strings to single `tsv`
- [x] fix character encoding issue[^Sublime Text was bugging]
- [x] figure out how to loop over[^with `for i in $(cat ids-list.txt); do jq '.[] | select (.id=="e'"$i"'")' events.json > "e$i.json"; done` for list of ids in `ids-list.txt` and array of all objects in `events.json`]
- [x] extract single-object `json` files
- [x] fill in `cod` values for all `events/e*.json` files
- [ ] check for `/events` completeness against missed post-`v-1.4` records in `/wiki`
    - [x] fix newline occurrences[^with `sed -i '' 's: /\\n :\\n :g' * `]
    - [x] did up to 1605
    - [ ] pull short citations before proceeding to fill in info gaps
- [ ] check for completeness against published lit[^eg file for `/harv` full citations]
- [ ] get all short cites in `/events` for `true` and `null` `cod` values
    - [x] for `harv` done
    - [x] for `v-1.4`
    - [ ] get into `bib` file

## prior log
### any cartas
* in `v-1.4`, first written by 7 sep 2021, last updated ~~24~~ 29 oct 2021 still in belmopan, cy[^varids 75 and 11 in `work/versioning/sheets varids.tsv`] 
* then worked on 9 jul 2022 to 3 aug 2022 in boston, ma[^in `purp/1638 series *.tsv` and `purp/PARES-*.txt` and `purp/1638 cartas *.tsv` and `yell/data manuscripts *.tsv`.]
* no work since then
### certain events[^17th cent piracy- or defence-against-piracy events in Hond Bay]
* in `v-1.4`, first written by 14 feb 2021, last updated 31 oct 2021 still in belmopan, cy[^varids 212 and 5 and 4, not counting 1638 settlement incident noted sans citation in earlier files]
* then worked on 18 apr 2022 to 3 aug 2022 in boston, ma[^ discounting (on a hunch) `red/prelim rep bz 1.4 WORK *.tsv` and counting `wiki/Timeline_of_piracy_in_the_Bay_of_Honduras.xml` (think it has original records), through prev listed files up to `harv/1638*.tsv`]
* no work since then


## history
written 23 dec 2024 in benque, cy
[Back](./README.md)

# Diary

<!-- 

Previous commits (2021 and 2022) were dry and did not explain what happened.
Now I want to have a better git history: 

git log --pretty=format:'%C(yellow)%h %Cblue%ad %Cgreen%d %Creset%s' --date=short

Example:

```
43c4aae 2022-12-06  (HEAD -> master, origin/master) 12/03 notes. Includes `move` of `Myrmecocystus Kennedyi` (84)
985ea24 2022-11-30  updating notes
43579c2 2022-11-29  updating colonies
69dd28f 2022-11-28  updating notes
f1a937f 2022-11-20  updating notes
cc57c72 2022-11-19  updating notes
217310f 2022-11-19  updating colonies numbers
```

Example for future commits:

All keys are using backticks.
  Valid keys are:
    * `move` of colony1, colony2 and colony3
    * `death` of colony1, colony2 and colony3
    * `acquisition` of colony1, colony2 and colony3
    * `sell` of colony1, colony2 and colony3
    * `preservation` of colony1, colony2 and colony3
    * `diapause` (no listed colonies)
    * `clean` of colony1, colony2 and colony3 (just for major cleaning)
    * `event` (for non-covered keys. For example when PG&E put the electricity down for 8hs)
    * `organize` (for work related to this repository; for example if I add a file, if I restructure, etc)

If a colony or colonies have been moved:
  * git `move` of `Myrmecocystus Kennedyi` (84)'
  * git commit -m '12/03 notes. Includes `move` of `Myrmecocystus Kennedyi` (84) and `Acromyrmex Versicolor`, colony (C5)'

If a colony has been moved and a queen or colony were found dead:
  * git commit -m '12/03 notes. Includes `move` of `Myrmecocystus Kennedyi` (84), `death` of `Acromyrmex Versicolor`, colony (C5)'
  * git commit -m '12/03 notes. Includes `move` of `Myrmecocystus Kennedyi` (84), `death` of `Acromyrmex Versicolor`, colony (C5) and `Aphaenogaster Occidentalis` (80)'

If a colony has been moved and a new queen or colony was acquired:
  * git commit -m '12/03 notes. Includes `move` of `Myrmecocystus Kennedyi` (84), `acquisition` of `Acromyrmex Versicolor`, colony (C5)'
  * git commit -m '12/03 notes. Includes `move` of `Myrmecocystus Kennedyi` (84), `acquisition` of `Acromyrmex Versicolor`, colony (C5) and `Aphaenogaster Occidentalis` (80)'

When colonies enter to diapause:
  * git commit -m '12/03 notes. Includes `diapause`'

Example of repo work (aka, organize):
  * git commit -m '`organize` adding diary for 2023'


Full examples:

  If a Queen/Colony has died:
    Update diary-20xx.md and commit: '02/04 notes. Includes `death` of `Camponotus Yogi` (50)'
    Update README.md and commit:     '02/04 readme. `death` of `Camponotus Yogi` (50)'


-->

## Latest diaries

* [2023](./diary-2023.md)
* [2022](./diary-2022.md)
* [2021](./diary-2021.md)
<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

[Deutsch](README.md)

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Rheinfelden only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-26 05:38 UTC, Rheinfelden: systematic collection (rheinfelden.tlex.ch): 23 addresses read; 0 added, 0 changed, 0 removed; no change; 69 not published, 0 of them with no reason. Flags: `verify-differ`.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Rheinfelden: systematic collection (rheinfelden.tlex.ch)](https://rheinfelden.tlex.ch/) | `<act>/` | daily | 2026-11-26 05:38 UTC | no change | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-26 05:37](checks/2026-11.md#ch-lexwork-rheinfelden-city-20261126t053732z) | lexwork-rheinfelden-city | 23 | 0 | 0 | 0 | 69 (0) | no change `verify-differ` | — |
| [2026-11-25 05:40](checks/2026-11.md#ch-lexwork-rheinfelden-city-20261125t054050z) | lexwork-rheinfelden-city | 37 | 0 | 0 | 0 | 69 (0) | no change `verify-differ` | — |
| [2026-11-24 12:17](checks/2026-11.md#ch-lexwork-rheinfelden-city-20261124t121734z) | lexwork-rheinfelden-city | 125 | 69 | 0 | 0 | 69 (0) | changes found | — |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.

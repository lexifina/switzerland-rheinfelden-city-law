# Rheinfelden (city): law history in git

The municipal law of the city of Rheinfelden (Stadt Rheinfelden, canton of Aargau, Switzerland) as a git history: one file per article, one commit per amending act on the day it took effect, and the amending act as the commit's author. `git blame` names the act behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law). The law of the canton of Aargau is in [lexifina/switzerland-aargau-law](https://github.com/lexifina/switzerland-aargau-law); federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in German, exactly as the city publishes it.

## What this repository holds

32 acts with 73 versions so far: the Gemeindeordnung (the city's charter) first, then the city's other enactments in force (ordinances, regulations, tariffs and decisions), in the order of the systematic collection, added in parts of about 50. Agreements, concessions, directives and repealed acts are not included.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `1-1-1/` | Gemeindeordnung (SRS 1.1-1) | 1 | one version (the oldest available), 1 January 2022 |
| `1-2-1-videouberwachungsreglement/` | Reglement über die Videoüberwachung öffentlicher Gebäude und Anlagen von Rheinfelden (SRS 1.2-1) | 4 | as enacted, then each consolidated version: 1 January 2021 to 22 June 2026 |
| `1-2-2/` | Videoüberwachungsreglement für die Regionalpolizei unteres Fricktal (SRS 1.2-2) | 1 | as enacted, 1 July 2014 |
| `1-6-1-gkr/` | Geschäfts- und Kompetenzreglement (SRS 1.6-1) | 13 | oldest version available, then each consolidated version: 6 December 2021 to 1 October 2026 |
| `1-6-2-entschadigungsreglement-gemeinderat/` | Reglement über die Entschädigung der Mitglieder des Gemeinderates (SRS 1.6-2) | 1 | as enacted, 1 January 2010 |
| `1-7-1-1-personalreglement/` | Reglement für das Personal der Einwohner- und Ortsbürgergemeinde (SRS 1.7.1-1) | 4 | oldest version available, then each consolidated version: 1 January 2021 to 1 January 2026 |
| `1-7-1-1-1-verordnung-zum-personalreglement/` | Verordnung zum Reglement für das Personal der Einwohner- und Ortsbürgergemeinde Rheinfelden (SRS 1.7.1-1.1) | 9 | oldest version available, then each consolidated version: 6 May 2021 to 1 January 2026 |
| `1-7-1-1-2-richtlinie-personalvertretung/` | Richtlinie über die Organisation und Aufgaben der Personalvertretung der Einwohner- und Ortsbürgergemeinde (SRS 1.7.1-1.2) | 2 | as enacted, then each consolidated version: 1 February 2012 to 1 August 2021 |
| `1-7-1-2-informatikreglement/` | Reglement des Gemeinderates zur Benutzung von Informatikmitteln und zur Überwachung des Vollzugs (SRS 1.7.1-2) | 2 | oldest version available, then each consolidated version: 21 October 2013 to 1 July 2024 |
| `1-7-1-3/` | Reglement über die Information der Öffentlichkeit, den Datenschutz und das Archivwesen (SRS 1.7.1-3) | 1 | as enacted, 1 July 2024 |
| `5-1-1/` | Polizeireglement der Gemeinden im Einzugsgebiet der Regionalpolizei Unteres Fricktal (SRS 5.1-1) | 5 | oldest version available, then each consolidated version: 31 May 2020 to 1 September 2026 |
| `5-1-2/` | Vertrag Regionalpolizei Unteres Fricktal (SRS 5.1-2) | 1 | as enacted, 1 January 2007 |
| `6-6-1-raumreglement/` | Reglement über die temporäre Benutzung von Räumlichkeiten der Einwohner- und Ortsbürgergemeinde Rheinfelden (SRS 6.6-1) | 2 | oldest version available, then each consolidated version: 15 November 2021 to 11 December 2023 |
| `7-1-2/` | Spezialbauvorschriften Altstadt Rheinfelden (SRS 7.1-2) | 1 | as enacted, 7 December 1993 |
| `7-1-2-1/` | Gestaltungsrichtlinien Altstadt Rheinfelden (SRS 7.1-2.1) | 1 | as enacted, 1 January 2019 |
| `7-1-3/` | Richtlinien Sanierungsbeiträge (SRS 7.1-3) | 1 | as enacted, 23 August 2004 |
| `7-1-4/` | Reglement zur Finanzierung von Erschliessungsanlagen (SRS 7.1-4) | 1 | as enacted, 1 October 2024 |
| `7-4-1-1/` | Reglement über das Multimedianetz (SRS 7.4.1-1) | 1 | as enacted, 1 January 2024 |
| `7-4-2-2/` | Reglement über Entschädigungen aufgrund der Einstellung der Gasversorgung (SRS 7.4.2-2) | 1 | as enacted, 1 August 2025 |
| `7-4-3-1/` | Wasserreglement (SRS 7.4.3-1) | 1 | as enacted, 1 October 2024 |
| `7-4-4-1/` | Reglement über die Abfallbewirtschaftung (SRS 7.4.4-1) | 1 | as enacted, 12 December 2001 |
| `7-4-5-1/` | Abwasserreglement (SRS 7.4.5-1) | 1 | as enacted, 1 October 2024 |
| `7-7-1-1/` | Reglement über die Nutzung des öffentlichen Grundes (SRS 7.7.1-1) | 4 | oldest version available, then each consolidated version: 15 March 2021 to 1 January 2026 |
| `7-7-1-2/` | Reglement über die Nutzung der Schiffsanlegestelle «Schifflände» der Stadt Rheinfelden (SRS 7.7.1-2) | 1 | as enacted, 1 October 2026 |
| `7-7-5-1-parkierungsreglement/` | Reglement über das Parkieren von Motorfahrzeugen auf öffentlichem Grund, die Erhebung von Gebühren und die Parkplatzersatzabgabepflicht (SRS 7.7.5-1) | 1 | one version (the oldest available), 1 January 2022 |
| `7-7-5-1-1/` | Vollziehungsverordnung zum Parkierungsreglement (SRS 7.7.5-1.1) | 4 | oldest version available, then each consolidated version: 1 January 2022 to 1 February 2025 |
| `8-2-1/` | Friedhof- und Bestattungsreglement (SRS 8.2-1) | 1 | as enacted, 14 January 2019 |
| `8-2-1-1/` | Verordnung zum Friedhof- und Bestattungsreglement (SRS 8.2-1.1) | 2 | as enacted, then each consolidated version: 1 January 2019 to 1 January 2026 |
| `8-6-1-kinderbetreuungs-beitragsreglement-kibe-ber/` | Reglement über kommunale Beiträge an die familienergänzende Kinderbetreuung (SRS 8.6-1) | 2 | as enacted, then each consolidated version: 1 January 2017 to 1 August 2018 |
| `8-6-1-1-kinderbetreuungs-beitragsverordnung-kibe-bev/` | Verordnung über kommunale Beiträge an die familienergänzende Kinderbetreuung (SRS 8.6-1.1) | 1 | as enacted, 1 August 2018 |
| `8-7-1/` | Richtlinien für den Fonds für Unterstützungsbedürftige (SRS 8.7-1) | 1 | one version (the oldest available), 6 April 2020 |
| `9-4-1-kurtaxenreglement/` | Reglement über die Kurtaxen (SRS 9.4-1) | 1 | one version (the oldest available), 1 January 2020 |

## Source

The SRS (systematic collection) of the city, published by the city at <https://rheinfelden.tlex.ch/>. For each act it gives every consolidated version it holds, with the day each version took effect, and a change table listing each amendment: its decision date, the day it took effect, the provision it touched and its entry in the chronological collection (CRS). Annexes the collection publishes only as separate PDF files are not included.

## Dates

- Each commit is dated at **noon, Europe/Zurich, on the day the version took effect**, as the collection gives it ("in Kraft seit / von"). The decision date of each amending act is the `Enacted:` trailer.
- An act's first commit is its oldest version in the collection. It is credited to the act as enacted only when the change table shows no amendment in force before it; otherwise it is the "oldest version available", naming the earlier amendments.
- Versions that take effect after the retrieval day are on the `zukunft` branch, never merged into `main`.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

`<act>/art-005.md` is Art. 5 (or § 5), `art-005a.md` Art. 5a; `ingress.md` holds the title, date and preamble; `gliederung.md` the section headings; `schluss.md` the closing formula and signatures. One paragraph or list item per line. Amendment markers (`*`), footnote numbers and the "Stand" date are left out.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the city's own text of that version, and every article's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the amending act, named by its entry in the chronological collection (CRS), with an e-mail address that cannot exist (`<act key>@rheinfelden.tlex.ch.invalid`). Where one version holds changes by several amending acts and the change table does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the city publishes as binding. The history starts with the oldest consolidated version the collection holds for each act, which for many acts is later than the act's enactment. Only the acts listed above are included.

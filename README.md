# Oberägeri (city): law history in git

The municipal law of the municipality of Oberägeri (Gemeinde Oberägeri, canton of Zug, Switzerland) as a git history: one file per article, one commit per amending act on the day it took effect, and the amending act as the commit's author. `git blame` names the act behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law). The law of the canton of Zug is in [lexifina/switzerland-zug-law](https://github.com/lexifina/switzerland-zug-law); federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in German, exactly as the municipality publishes it.

## What this repository holds

51 acts with 83 versions in force and one announced future version: the Gemeindeordnung (the municipality's charter) first, then the municipality's other enactments in force (ordinances, regulations, tariffs and decisions), in the order of the systematic collection, added in parts of about 50. Agreements, concessions, directives and repealed acts are not included.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `1-1-1/` | Gemeindeordnung (SRS 1.1-1) | 2 | as enacted, then each consolidated version: 1 January 2021 to 1 August 2022 |
| `1-2-1/` | Verordnung über die Benützung des Archivs (SRS 1.2-1) | 1 | as enacted, 1 August 2021 |
| `1-2-2/` | Verordnung über die Veranstaltungswerbung der Dorfeingangstafeln (SRS 1.2-2) | 1 | as enacted, 1 April 2012 |
| `1-6-1/` | Entschädigungsreglement (SRS 1.6-1) | 1 | as enacted, 1 January 2019 |
| `1-6-1-1/` | Verordnung zum Entschädigungsreglement (SRS 1.6-1.1) | 2 | as enacted, then each consolidated version: 1 January 2022 to 1 January 2025 |
| `1-6-2/` | Verordnung über die Geschäftsführung der Planungs- und Baukommission (SRS 1.6-2) | 2 | as enacted, then each consolidated version: 13 April 2015 to 1 January 2025 |
| `1-6-3/` | Verordnung über die Geschäftsführung der Schulkommission (SRS 1.6-3) | 1 | as enacted, 17 August 2015 |
| `1-6-4/` | Verordnung über die Geschäftsführung der Strategiekommission (SRS 1.6-4) | 1 | as enacted, 20 April 2020 |
| `1-6-5-vtbk/` | Verordnung über die Geschäftsführung der Tiefbaukommission (SRS 1.6-5) | 2 | as enacted, then each consolidated version: 1 January 2018 to 1 August 2025 |
| `1-6-6/` | Verordnung über die Geschäftsführung der Begleitgruppe Musikschule (SRS 1.6-6) | 1 | as enacted, 1 February 2016 |
| `1-6-7/` | Verordnung über die Geschäftsführung der Alterskommission Ägerital (SRS 1.6-7) | 1 | as enacted, 1 January 2023 |
| `1-6-8/` | Verordnung über die Geschäftsführung der Energie- und Umweltkommission (SRS 1.6-8) | 1 | as enacted, 1 January 2025 |
| `4-1-1/` | Reglement Familienergänzende Kinderbetreuung (SRS 4.1-1) | 1 | as enacted, 1 August 2020 |
| `4-1-1-1-vfekb/` | Verordnung zum Reglement Familienergänzende Kinderbetreuung (SRS 4.1-1.1) | 5 | as enacted, then each consolidated version: 1 November 2021 to 1 August 2026 |
| `4-1-2-vbseb/` | Verordnung zum Betrieb der schulergänzenden Betreuung (SRS 4.1-2) | 5 | as enacted, then each consolidated version: 1 August 2020 to 1 August 2026 |
| `4-2-1/` | Reglement Schulzahnarzt-Dienst (SRS 4.2-1) | 1 | as enacted, 1 August 2021 |
| `4-2-1-1/` | Verordnung zum Reglement Schulzahnarzt-Dienst (SRS 4.2-1.1) | 1 | as enacted, 1 August 2021 |
| `4-2-2/` | Verordnung über das Schul- und Disziplinarwesen (SRS 4.2-2) | 2 | as enacted, then each consolidated version: 1 August 2020 to 1 August 2026 |
| `4-2-3-absenzenverordnung/` | Verordnung über die Absenzen der Schülerinnen und Schüler (SRS 4.2-3) | 2 | as enacted, then each consolidated version: 1 August 2016 to 1 January 2025 |
| `4-2-4/` | Verordnung über die Schulaktivitäten (SRS 4.2-4) | 3 | as enacted, then each consolidated version: 1 August 2018 to 1 August 2026 |
| `4-2-5/` | Verordnung zum Eintritt in die Grundstufe (SRS 4.2-5) | 1 | as enacted, 1 January 2019 |
| `4-3-1/` | Musikschulreglement (SRS 4.3-1) | 1 | as enacted, 1 August 2015 |
| `4-3-1-1/` | Verordnung zum Musikschulreglement (SRS 4.3-1.1) | 1 | as enacted, 1 January 2016 |
| `4-3-1-2/` | Verordnung über das Schulgeld der Musikschule (SRS 4.3-1.2) | 1 | as enacted, 1 August 2016 |
| `4-5-1/` | Richtlinien Sportlerinnen- und Sportlerehrungen und Award-Verleihung (SRS 4.5-1) | 3 | as enacted, then each consolidated version: 18 March 2013 to 8 April 2024 |
| `5-5-1/` | Feuerwehrreglement (SRS 5.5-1) | 1 | as enacted, 1 January 1997 |
| `6-4-1-gebv/` | Gebührenverordnung (SRS 6.4-1) | 8 | as enacted, then each consolidated version: 1 January 2022 to 1 June 2026; future version effective 1 January 2027 |
| `6-5-1/` | Reglement über die Beiträge an denkmalgeschützte Objekte (SRS 6.5-1) | 1 | as enacted, 1 January 2025 |
| `6-6-1/` | Verordnung über die Benützung der Mehrzweckanlagen Maienmatt Hofmatt Alosen (SRS 6.6-1) | 1 | as enacted, 1 May 2022 |
| `6-6-2/` | Verordnung über die Benützung der Studenhütte (SRS 6.6-2) | 1 | as enacted, 14 November 2005 |
| `6-6-3-vbl/` | Verordnung über den Betrieb des Lagerhauses Bachweg 9 (SRS 6.6-3) | 1 | as enacted, 27 May 2024 |
| `7-1-1-bo/` | Bauordnung (SRS 7.1-1) | 2 | oldest version available, then each consolidated version: 30 November 2009 to 22 May 2025 |
| `7-1-2/` | Verordnung über die Delegation von Befugnissen in Baubewilligungs- und baupolizeilichen Angelegenheiten (SRS 7.1-2) | 1 | as enacted, 1 June 2008 |
| `7-3-1/` | Verordnung über die Lärmbekämpfung (SRS 7.3-1) | 1 | as enacted, 14 August 1972 |
| `7-3-2/` | Energieförderrichtlinien (SRS 7.3-2) | 2 | as enacted, then each consolidated version: 1 January 2019 to 1 January 2023 |
| `7-4-1/` | Reglement Wasserversorgung (RW) (SRS 7.4-1) | 2 | as enacted, then each consolidated version: 1 January 2016 to 1 January 2024 |
| `7-4-2/` | Konzessionsvorschriften Wasserversorgung (SRS 7.4-2) | 1 | as enacted, 31 October 1977 |
| `7-4-3-ar/` | Abwasserreglement (SRS 7.4-3) | 2 | as enacted, then each consolidated version: 1 January 2005 to 1 January 2024 |
| `7-4-3-1-var/` | Verordnung zum Abwasserreglement (SRS 7.4-3.1) | 1 | as enacted, 1 January 2024 |
| `7-4-4/` | Verordnung über die Fernwärme Quartierheizung Hofmatt (SRS 7.4-4) | 1 | as enacted, 24 January 2005 |
| `7-6-1-rstra/` | Strassenreglement (SRS 7.6-1) | 2 | as enacted, then each consolidated version: 7 December 2015 to 22 May 2025 |
| `7-7-1/` | Verordnung über die Parkplatzbewirtschaftung (SRS 7.7-1) | 1 | as enacted, 1 January 2021 |
| `7-7-2-vbog/` | Verordnung zur Benützung des öffentlichen Grundes (SRS 7.7-2) | 1 | as enacted, 1 June 2026 |
| `8-2-1/` | Friedhofreglement (SRS 8.2-1) | 2 | as enacted, then each consolidated version: 31 July 2012 to 1 October 2022 |
| `8-2-1-1/` | Verordnung zum Friedhofreglement (SRS 8.2-1.1) | 1 | as enacted, 1 October 2022 |
| `8-3-1/` | Hundehaltungs- und Hundesteuerreglement (SRS 8.3-1) | 2 | as enacted, then each consolidated version: 1 January 2017 to 1 January 2026 |
| `8-8-1/` | Vorschriften über die Wohnbauförderung (SRS 8.8-1) | 1 | as enacted, 14 December 1994 |
| `8-8-1-1/` | Wohnbauförderungsreglement (SRS 8.8-1.1) | 1 | as enacted, 14 December 1994 |
| `8-8-2/` | Verordnung über die Vermietung kommunaler Wohnungen (SRS 8.8-2) | 1 | as enacted, 1 January 2025 |
| `9-3-1/` | Verordnung über die Angelfischerei im Ägerisee (SRS 9.3-1) | 2 | as enacted, then each consolidated version: 1 July 2018 to 1 February 2023 |
| `9-4-1/` | Verordnung über die Beherbergungsabgabe (SRS 9.4-1) | 1 | as enacted, 1 January 2018 |

## Source

The SRS (systematic collection) of the municipality, published by the municipality at <https://oberaegeri.tlex.ch/>. For each act it gives every consolidated version it holds, with the day each version took effect, and a change table listing each amendment: its decision date, the day it took effect, the provision it touched and its entry in the chronological collection (CRS). Annexes the collection publishes only as separate PDF files are not included.

## Dates

- Each commit is dated at **noon, Europe/Zurich, on the day the version took effect**, as the collection gives it ("in Kraft seit / von"). The decision date of each amending act is the `Enacted:` trailer.
- An act's first commit is its oldest version in the collection. It is credited to the act as enacted only when the change table shows no amendment in force before it; otherwise it is the "oldest version available", naming the earlier amendments.
- Versions that take effect after the retrieval day are on the `zukunft` branch, never merged into `main`.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

`<act>/art-005.md` is Art. 5 (or § 5), `art-005a.md` Art. 5a; `ingress.md` holds the title, date and preamble; `gliederung.md` the section headings; `schluss.md` the closing formula and signatures. One paragraph or list item per line. Amendment markers (`*`), footnote numbers and the "Stand" date are left out.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the municipality's own text of that version, and every article's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the amending act, named by its entry in the chronological collection (CRS), with an e-mail address that cannot exist (`<act key>@oberaegeri.tlex.ch.invalid`). Where one version holds changes by several amending acts and the change table does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the municipality publishes as binding. The history starts with the oldest consolidated version the collection holds for each act, which for many acts is later than the act's enactment. Only the acts listed above are included.

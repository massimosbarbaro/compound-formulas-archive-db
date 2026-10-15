# Formule: archive of compound formulas searchable by raw material and product

*Archivio delle formule delle mescole con ricerca per materia prima e per prodotto*

**db** · 1998–2001 · version 1.0  
Author: **Massimo Sbarbaro** ([ORCID 0009-0006-8965-9013](https://orcid.org/0009-0006-8965-9013))

## Overview

Formule is the archive of the compound formulas of a plastic-film manufacturer, loaded from the formula file of the company host system. The laboratory can look up a formula and its components, find every formula that uses a given raw material (by code or by name) and every formula used for a product, and print the formulas.

I designed and programmed this application in 1998–2001. It is published here in 2026 as part of the documented record of my software work, with a permanent DOI on Zenodo.

## Main functions

- Formula sheet with its components and quantities (`FORMULE`).
- Search by formula, by raw-material code or name and by product (`SRicFor`, `SRicMP`, `SRicMPnome`, `SRicProd`).
- Printouts of single formulas and of formula lists (`Formule`, `Stampe delle Formule`).

## Data

Table `Foranart18` (formula lines: formula, component, quantity).

## Technology

Microsoft Access 2000–2003 format (.mdb), forms, reports and macros.

## Repository contents

| Path | Content |
|---|---|
| `database/` | The Access application, emptied of all data. |
| `source/` | Plain-text export (UTF-8) of forms, reports, macros, VBA modules (`SaveAsText`) and of the SQL of every query. |
| `docs/schema.md` | Tables and fields. |

## What is not included

The database is published **empty**: it has been rebuilt in a new file from the table structure and from the plain-text export of every form, report, macro and module, so no record of the original data survives. Logos, printer settings and the names of the organisations that used the application have been removed. The objects are also provided as plain text in `source/`.

## Related repositories

- [laboratory-quality-control-reports-access](https://github.com/massimosbarbaro/laboratory-quality-control-reports-access)
- [laboratory-test-requests-access](https://github.com/massimosbarbaro/laboratory-test-requests-access)
- [raw-material-incoming-analysis-access](https://github.com/massimosbarbaro/raw-material-incoming-analysis-access)

## How to cite

Use the citation metadata in [`CITATION.cff`](CITATION.cff) (GitHub: *Cite this repository*).

> Sbarbaro, Massimo. 2001. *Formule: archive of compound formulas searchable by raw material and product*. Software (db, 1998–2001), version 1.0. GitHub. https://github.com/massimosbarbaro/compound-formulas-archive-access.

## License

Released under the [MIT License](LICENSE). © 1998 Massimo Sbarbaro.

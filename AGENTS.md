# Working on assam-history-sources

Primary sources and the inscription catalogue for early Assam (Kamarupa). Part of AxomRank: see README.md for the overview and roadmap.

## Layout

- `Kamarupa-Inscriptions-Chronology.csv`: the full 53-record catalogue
- `Kamarupa-Inscriptions-350-1100.csv`: the filtered 350–1100 CE list
- `Inscriptions of Ancient Assam - Separate Texts/`: one summary per inscription
- Source PDFs with their extracted `.txt` text

## Commands

- No build. Open the CSVs in a spreadsheet or pandas

## Rules

- Use repository-relative paths in `source_url` and `summary_file`
- Keep what a source says separate from interpretation, and keep disagreements
- Coordinates often mark a nearby landmark. Keep `coordinate_precision` and `location_notes` accurate
- Before adding a PDF, check that it is public domain or permitted
- Commit as the `axomrank` account, in small reviewable commits.

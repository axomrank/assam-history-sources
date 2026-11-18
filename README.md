# Assam History Sources: primary sources and inscriptions of Kamarupa and early Assam

> Primary sources for early Assam history: the Kamarupa inscriptions catalogue (53 records), Harshacharita, Kalika Purana, Hiuen Tsang and research notes.

[Part of AxomRank](https://github.com/axomrank)

## What is inside

| File or folder | What it holds |
|---|---|
| `Kamarupa-Inscriptions-Chronology.csv` | Working catalogue of **53 inscription records**: date, findspot, coordinates with a precision note, material, king, subject, evidence status and source locator |
| `Kamarupa-Inscriptions-350-1100.csv` | Filtered list of the **38 records** assigned to 350–1100 CE (28 local/regional or seal records, 10 outside references) |
| `Inscriptions of Ancient Assam - Separate Texts/` | One summary text per inscription, plus an index and OCR notes. Includes subfolders for external, supplementary and later-context records |
| `Inscriptions-of-Ancient-Assam-M-M-Sharma-1978.*` | M. M. Sharma's edition, the main reference for the catalogue (PDF and extracted text) |
| `Harsa-Carita-…`, `Life-of-Hiuen-Tsiang-…`, `Si-Yu-Ki-…`, `Rajatarangini-…`, `Ramacaritam-…`, `Gaudavaho-…` | Outside literary sources that mention Kamarupa (PDF and text) |
| `Kalika-Purana-…`, `Yogini-Tantra-…` | Sacred texts tied to Kamarupa traditions |
| `Xuanzang-Kamarupa-Summary.txt` | Summary of Xuanzang's account of Kamarupa |
| `Audit-Notes-and-Collection-Status.txt` | What was checked, when, and what is still missing |
| `Unresolved-Inscriptions-and-Edition-Locators.txt`, `Other-Primary-Sources-to-Collect.txt` | Open research tasks |
| `Location-Column-Notes.txt`, `Kamarupa-Map-Research-Notes.txt`, `Atlas-Readme.txt` | Notes on coordinates and on the inscriptions atlas |

## How to use the catalogue

Open either CSV in a spreadsheet, or load it with pandas. Read `coordinate_precision` and `location_notes` before mapping: many coordinates mark a nearby landmark, not the exact findspot. CE dates reconstructed from regnal years are approximate. `evidence_status` says how far each record has been checked.

The catalogue is a **working research list, not a certified complete corpus**. Disagreements between sources are kept, not resolved silently.

## Roadmap: future improvements

- [ ] **Rights review:** check the copyright of every PDF, and keep only public-domain or permitted items in the public repo
- [ ] Add the standalone Inscriptions Atlas (`Inscriptions-Atlas.html`, described in `Atlas-Readme.txt`), which is not yet committed
- [ ] Add the sources still listed in `Other-Primary-Sources-to-Collect.txt`
- [ ] Add a stable citation key per source, used by the lessons and books
- [ ] Add an Ahom-period section: buranjis and Ahom copper plates

## For AI agents and contributors

Read [AGENTS.md](AGENTS.md). Distinguish what a source says from interpretation, and never present OCR text as a checked edition.

Commit as the `axomrank` account. Keep changes small and reviewable, and run the repository's checks before pushing.

## Part of AxomRank

[AxomRank](https://axomrank.pages.dev) offers free, bilingual preparation for Assam government exams. Related repositories:

- **Learn:** [axomrank.github.io](https://github.com/axomrank/axomrank.github.io) (the AxomRank learning app), [floor-test-simulator](https://github.com/axomrank/floor-test-simulator) (parliamentary majority simulator)
- **Explore Assam history:** [ahom-kingdom-history](https://github.com/axomrank/ahom-kingdom-history) (illustrated Ahom kingdom website and 41 reign lessons), [assam-history-map](https://github.com/axomrank/assam-history-map) (year-by-year historical map), [assam-history-characters](https://github.com/axomrank/assam-history-characters) (character sheets for Assam's history), [assam-visual-archive](https://github.com/axomrank/assam-visual-archive) (gallery of Assam scenes and photographs), [assam-heritage-ai-art](https://github.com/axomrank/assam-heritage-ai-art) (AI art gallery of Assamese heritage)
- **Open data:** [assam-exam-pyq](https://github.com/axomrank/assam-exam-pyq) (2,398 previous-year questions with answers), [assam-exam-syllabus](https://github.com/axomrank/assam-exam-syllabus) (syllabi for 12 recruitment boards), [assam-maps](https://github.com/axomrank/assam-maps) (map portal and GIS layers)
- **Publishing and brand:** [axomrank-blog](https://github.com/axomrank/axomrank-blog) (exam guides built from real papers), [assam-history-books](https://github.com/axomrank/assam-history-books) (13-book history of Assam), [axomrank-brand-assets](https://github.com/axomrank/axomrank-brand-assets) (brand kit and social media library)

## License and contact

No license file. Each work keeps its own copyright status. See the roadmap's rights review.

Corrections and questions: open an issue in this repository. AxomRank is run by Angsuman Das (sole proprietor).

# The Bumper Years / שנות המדבקה

An archive of 167 Israeli left-wing political bumper stickers, 1995–2005, from one activist's album — transcribed, translated, attributed where possible, dated, and annotated. Bilingual (English / Hebrew).

**Site:** https://bumperyears.github.io
**Contact:** bumperyears@duck.com

## What is here

- `index.html` — the whole site, one page.
- `data.json` — the catalogue: one record per sticker. This is the dataset; the page just displays it.
- `img/` — photographs (longest side 1200 px). `thumb/` — the same at 520 px.
- `LICENSE.md` — terms of reuse (CC BY 4.0 for catalogue text and photographs; the sticker designs belong to their issuers).

## The data

Each record in `data.json` has:

| field | meaning |
|---|---|
| `id` | catalogue number (S001–S169); permanent address is the site URL + `#S027` |
| `file` | image filename in `img/` and `thumb/` |
| `hebrew` | text as printed, lines separated by ` / ` |
| `english` | translation, with puns glossed in parentheses |
| `issuer`, `issuer_norm` | issuing organisation as read, and a normalised short name for filtering |
| `period` | one of twelve period buckets used by the site's filter |
| `year_guess`, `date_he` | proposed date, English and Hebrew |
| `confidence` | `high` / `medium` / `low` — how firm the date is |
| `fb_tag` | the collector's own tag for the item, where she gave one |
| `theme` | sub-genre (religion and state, Pride, Jerusalem, disengagement), where applicable |
| `notes`, `notes_he` | catalogue note, English and Hebrew |
| `collector_note`, `cnote_en` | the collector's own comment (Hebrew original, English translation), where there is one |
| `lean` | political lean of the sticker (nearly all `left`) |
| `w`, `h` | image dimensions |

Dates were set from the collector's tagging of the original album, from internal evidence (candidates, slogans, party names that existed only in certain years), and otherwise by educated guess marked `low`. Corrections and identifications of unattributed stickers are welcome at the address above.

## Updating the site

Replace `data.json` to change any text; add an image to `img/` and `thumb/` and a record to `data.json` to add a sticker. Nothing needs building.

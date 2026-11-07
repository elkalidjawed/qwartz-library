# Qwartz library

Effects, transitions, filters, text styles, stickers, fonts and templates for the Qwartz video
editor. Qwartz downloads them from here when you pick one in its library.

## What's in here

- `src/` - the items, one folder each, with an `item.json` (name in 12 languages, category,
  licence). Effects are small Effect Maker files (`.qfx`); bigger files are only in `dist/`.
- `dist/` - what Qwartz actually downloads: the catalog and the files, named by their SHA-256.
  Generated, don't edit by hand.

The catalog is signed. Qwartz checks the signature and the hash of every file before it uses
anything, so a copy of this repo somewhere else can't change what Qwartz accepts.

## Licences

Every item says its licence in its `item.json`:

- Fonts: SIL Open Font License 1.1 (`LICENSES/OFL-1.1.txt`), with each font's own `OFL.txt`.
- Items marked CC0-1.0 are public domain (`LICENSES/CC0-1.0.txt`).
- Items marked LicenseRef-Qwartz-Official are made for Qwartz and may be used in videos made
  with Qwartz, including commercial ones.

No music or sound effects are kept here.

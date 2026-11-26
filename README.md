# Simple Plan · Bigger Than You Think! Tour — Jakarta Lyric Book

An unofficial fan-made lyric book for the Jakarta show (27 Nov 2026). Not affiliated with or endorsed by Simple Plan.

## Files
- `index.html` — the whole book (no lyrics included).
- `lyrics.json` — **you add this yourself**. When it sits next to `index.html`, the book loads it automatically on every visit, on any device.

## Adding your lyrics
1. Open the book, go to **Backstage**, tap **Backup .json**.
2. Rename the file to `lyrics.json` and put it next to `index.html`.
3. Reload: the lyrics appear on every page. Anything you edit in the browser afterwards (Edit lyrics) stays in that browser and takes priority over the file.

## Adding pictures (posters & polaroids)
Make a `pictures/` folder next to `index.html`. Any of these files you add (`.jpg`, `.jpeg` or `.png`) appear automatically:

| File name | Where it shows |
|---|---|
| `no-pads-no-helmets-just-balls` | Poster 1 (Get Your Heart On! pages + hits medley) |
| `still-not-getting-any` | Poster 2 |
| `simple-plan` | Poster 3 |
| `get-your-heart-on` | Poster 4 |
| `taking-one-for-the-team` | Poster 5 |
| `harder-than-it-looks` | Poster 6 |
| `the-kids-in-the-crowd` | Poster 7 |
| `nothing-changes-1` … `-3` | The three polaroids on Nothing Changes |

Example: `pictures/get-your-heart-on.jpg`. A picture you add by tapping a poster in the browser takes priority on that device.

## Keep the lyrics and pictures private
Song lyrics and album artwork are copyrighted. Don't publish `lyrics.json` or the `pictures/` folder anywhere public.
- A **public** GitHub repo, or a GitHub Pages site (even one built from a private repo on a free plan), can be read by anyone.
- Host it somewhere with access control instead, e.g. Cloudflare Pages + Cloudflare Access, Netlify with password protection, or GitHub Pages with private visibility (GitHub Enterprise Cloud).
- If you do use a public repo, upload only `index.html` and `README.md`, load your lyrics on each device with **Backstage → Choose backup file**, and add pictures by tapping each poster.

## Fonts
The album fonts aren't included. The page falls back to free Google Fonts (Fredoka, Archivo Black, Bebas Neue, Anton). If you hold licences for the originals, put them in `fonts/` as `gothic.woff2`, `impacted.woff2`, `xband.woff2` and `steelfish.woff2`.

## Notes
- Syncing to a Claude account only works in the Claude-hosted version. Self-hosted, lyrics come from `lyrics.json` plus the browser's own storage.
- Backup, .txt and offline-book downloads work as normal browser downloads.

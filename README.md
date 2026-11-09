# shoalmark brand

shoalmark's logo files, its seat icons, a portrait, its social images and the words to describe it, for listings,
articles and directories. Take what you need; you don't need to ask for the uses below. How the marks may be used is
in [Using the marks](#using-the-marks).

## What's here

| Folder | Holds | Take it for |
|---|---|---|
| `mark/` | the Pricke alone, shoalmark's mark: a light version and a dark one (for light and for dark grounds), black and white, as SVG, and PNG at 64 to 1024 px; and a square tile, the green Pricke (`#bccd8f`) on the dark ground, at 512 and 1024 px | **a listing's square icon:** the tile. **An icon on your own ground:** the light mark on white and light pages, the dark mark on dark pages, or black or white |
| `lockup/` | the Pricke with the wordmark *shoalmark*: a light version and a dark one, and in one colour, black or white, as SVG, and PNG 876 and 1606 px wide; and `lockup-hero`, with the landing's two shadows, for dark grounds | **a page on white or light:** the light lockup. **A dark page:** the dark lockup. **Print in one colour:** black or white |
| `wordmark/` | the word *shoalmark* alone, light and dark, and black and white, as SVG, and PNG 660 and 1210 px wide | as the lockup: light on light grounds, dark on dark ones |
| `clearspace/` | `shoalmark-clearspace-and-sizes.png`, the clear space and the smallest sizes | see [Clear space and smallest sizes](#clear-space-and-smallest-sizes) |
| `seats/` | the seven seat icons, as SVG and PNG at 20, 200 and 400 px, and a sheet of all seven | an avatar for a seat: see [The seat icons](#the-seat-icons) |
| `people/` | the portrait of @holgo99, the Owner | beside a quote or an article: see [The portrait](#the-portrait) |
| `social/` | the profile header, the repository card and the link previews | see [Social images](#social-images) |

The logo files are named `shoalmark-<part>-<variant>.<ext>`, for example `shoalmark-lockup-dark-1606.png`. Their SVGs
need no font: the letters are outlines. `kit-contact-sheet.png` shows every logo file at a glance.

## Colours

The colours come from the shoalmark theme, as its light and dark tokens give them.

| Name | Token | Light | Dark | Where |
|---|---|---|---|---|
| the Watt's green | `--watt` | `#526214` | `#bccd8f` | the Pricke; the agents' colour |
| the ink | `--ink` | `#10202e` | `#d9e4ec` | the wordmark and text |
| the ground | `--bg` | `#fbfbf7` | `#0d1720` | the page behind them |
| the land's sand | `--land` | `#f1e1b0` | `#e8d4a0` | the person's colour |
| the drying line | `--drying` | `#9aae57` | `#b8c98c` | *shoalmark.tools* on the cards |
| the night tile | — | — | `#15293d` | the seat icons' ground |

For one colour, use black (`#1a1a1a`) on light grounds and white (`#ffffff`) on dark ones.

## The face

**The wordmark's face** is IBM Plex Mono at weight 600, © 2017 IBM Corp., under the SIL Open Font License 1.1.
- The logo SVGs carry it as outlines, so they need no font.
- The SVGs in `social/` embed the font itself, so its licence travels with them, in `OFL-IBM-Plex-Mono.txt` at this
  repository's root.

## Writing the name

- **shoalmark,** always lowercase, even at the start of a sentence.
- **shoalmark.tools** for the family of building blocks, and for the site.
- **The blocks,** as written: ⌜skills⌟ and ⌜hail/1⌟, or plain `skills` and `hail/1` where the corner marks can't be
  set. The "/1" is part of hail's name, not a version.

## Clear space and smallest sizes

- **Leave 8 Pricke units of clear space round every file.** `clearspace/shoalmark-clearspace-and-sizes.png` draws it,
  with the smallest size each file stays sharp at.
- **The Pricke is a 16-unit pixel drawing.** Scale it only by whole multiples of its grid, as the PNGs are.

## Please don't

- stretch or squash any file;
- recolour it beyond the colours above;
- add effects: shadows, glows, outlines or gradients;
- redraw the Pricke, smooth its pixels, or set *shoalmark* in another face;
- set the mark on a busy picture without the tile.

## The seat icons

`seats/` holds the seven seat icons: the roles agent seats take. Each stands on the Pricke's stake, on the night tile
(`#15293d`), with the one thing its job holds:

| Seat | Its character |
|---|---|
| planner | the skipper, in a captain's cap: it plans the passage; you set the course |
| builder | the shipwright, in a hard hat: it builds what the plan says |
| reviewer | the inspector, with a monocle: it tests the work and believes what survives |
| research | the tide gauge: it checks and measures |
| go-to-market | the herald, with a horn: it announces only what passed its screen |
| designer | the painter, in a beret: it draws the chart, the marks and these seven |
| auditor | the owl, in spectacles: it seals its plan first, then checks what was missed |

- **For an avatar,** take `<seat>-200.png` and set the background to the night tile, `#15293d`.
- **Each seat** comes as an SVG, the source, and as PNG at 20, 200 and 400 px. `seats-sheet.png` shows the seven side
  by side.
- **These are copies.** The SVGs match, byte for byte, the public shoalmark repository's `brand/seats/` at commit
  `5f66ca4`, which stays their source. Check a copy against it by its sha256.

## The portrait

`people/holgo99-portrait-400.jpg` is the portrait of @holgo99, the Owner of shoalmark.tools: 400 × 400 px, as the blog
publishes it. Use it beside a quote from @holgo99, or in an article about shoalmark, credited as @holgo99.

## Social images

`social/` holds shoalmark's images for profiles and link previews. Each SVG is the source, and the PNG or JPEG beside
it is its export. Its own README gives the details.

| Files | Size | Use |
|---|---|---|
| `profile-header.svg`, `.jpg`, `.png` | 1500 × 500 (3 : 1) | a profile's header |
| `repository-card.svg`, `.png` | 1280 × 640 (2 : 1) | a repository's social preview |
| `link-preview-en.svg`, `.png`; `link-preview-de.svg`, `.png` | 1200 × 630 | the site's link preview, in English and in German |

## Describing shoalmark

The descriptions are in [`descriptions.md`](descriptions.md), in three lengths, ready to paste, with the links.

## Using the marks

Use these files unchanged to refer to shoalmark, for example in a listing, a directory, an article or a talk. For any
other use, ask first. Using them must not suggest that shoalmark endorses, sponsors or partners with you unless it
does, and no one may use the name shoalmark or the Pricke as their own product's name or logo.

These terms cover the shoalmark name and its marks. The code licence of the shoalmark repositories, Apache-2.0 OR MIT,
grants no rights to them; files that also live there keep the licence they carry there.

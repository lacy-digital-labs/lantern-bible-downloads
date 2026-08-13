<!-- GENERATED FILE - do not edit here.

     The source is docs/downloads-readme.md.in in the lantern-bible build
     repository. `make downloads-readme` renders this file from it and
     release.yml pushes the result on every tag, so an edit made directly in
     the downloads repo is overwritten by the next release.

     Editing the template there: every double-brace placeholder is filled in
     by bsb/downloads.py from the build's own data -- profiles.PAGE_COUNTS,
     profiles.PROFILES, identity.EDITIONS and the built files in dist/. Do
     not type a page count, a file size, a filename or a count of editions
     into the prose by hand; that is exactly what went stale before. Add a
     placeholder instead. render() fails loudly on a placeholder it cannot
     fill AND on one it defines that the template never uses. -->

# The Lantern Bible — downloads

Public download mirror for **The Lantern Bible**, a free edition of the Berean
Standard Bible published as a ministry of Lacy Digital Labs, LLC.

**→ [Downloads, page counts and details](https://www.lacydigitallabs.com/lantern-bible.html)**

This repository holds no source. It exists so the files resolve for everyone —
[Releases](../../releases/latest) is the whole of it. Each release carries
three ePub editions, ten PDF editions and the cover art for all three, uploaded
automatically when the build repository tags a version.

## The editions

| Edition | What it carries |
| --- | --- |
| **Standard** | The full apparatus — footnotes, book outlines, cross-references, verse anchors, complete navigation. |
| **Reference** | The standard edition plus the topical index as a back-matter section. |
| **Reader's** | Footnotes, book outlines and the parenthesised cross-reference lists removed, for continuous reading rather than lookup. Section headings stay, set italic rather than bold; poetic indentation is kept. |

## ePub

| File | Edition | Size |
| --- | --- | --- |
| `lantern-bible.epub` | Standard | 3.18 MB |
| `lantern-bible-reference.epub` | Reference | 5.09 MB |
| `lantern-bible-reader.epub` | Reader's | 2.67 MB |

Every link is internal and every verse anchor resolves; the ePubs reflow to any
screen, so they have no fixed page count.

## PDF

The PDFs are rendered directly rather than converted from the ePub, so the
links and the collapsible bookmark tree survive — a device that converts ePub
to PDF on load discards both.

| File | Edition | Page size | Layout | Pages |
| --- | --- | --- | --- | --- |
| `lantern-compact-1col.pdf` | Standard | 105 × 140 mm | Single Column | 3,291 |
| `lantern-tablet-1col.pdf` | Standard | 148 × 210 mm | Single Column | 1,782 |
| `lantern-tablet-2col.pdf` | Standard | 148 × 210 mm | Two Column | 1,338 |
| `lantern-tablet-note.pdf` | Standard | 148 × 210 mm | Annotation Margin | 2,124 |
| `lantern-tabloid-1col.pdf` | Standard | 179 × 265 mm | Single Column | 1,305 |
| `lantern-tabloid-2col.pdf` | Standard | 179 × 265 mm | Two Column | 928 |
| `lantern-tabloid-note.pdf` | Standard | 179 × 265 mm | Annotation Margin | 1,508 |
| `lantern-tablet-2col-reference.pdf` | Reference | 148 × 210 mm | Two Column | 2,088 |
| `lantern-tabloid-2col-reference.pdf` | Reference | 179 × 265 mm | Two Column | 1,420 |
| `lantern-compact-1col-reader.pdf` | Reader's | 105 × 140 mm | Single Column | 2,711 |

Each page size is cut to the *smallest* screen in its class, so every device in
that class scales the page up rather than down and the type never renders
smaller than it was set.

The Reference Edition is offered in the two-column profiles only, and the
Reader's Edition at the compact size only — the page size each was designed
around rather than a subset of a larger matrix.

Pagination is identical on any machine that builds a given tag: the body face
is embedded rather than inherited, so the page counts above are the page counts
you get. Byte-identity is not promised across machines, though — **verify a
download by its page count and its embedded font, not by comparing its hash to
one you built yourself.**

## Cover art

Also attached, for anyone uploading the edition to a retail storefront: the
cover for each edition, in both formats, all at 1600 × 2560.

| Edition | PNG | JPEG |
| --- | --- | --- |
| Standard | `cover.png` | `lantern-bible-cover.jpg` |
| Reference | `cover-reference.png` | `lantern-bible-cover-reference.jpg` |
| Reader's | `cover-reader.png` | `lantern-bible-cover-reader.jpg` |

The PNGs are the plates embedded in the ePubs themselves. The JPEGs are the
same canvas and the same layout, re-rendered for storefronts that require that
format — a format change, not a different design.

## Getting the files

Assets are kept for the three most recent releases. Tags and release notes are
kept for all of them.

To always fetch the newest edition, link to
`https://github.com/lacy-digital-labs/lantern-bible-downloads/releases/latest/download/<filename>`
— that URL follows each new release automatically.

## Rights

The Scripture text is the Berean Standard Bible, produced in cooperation with
Bible Hub, Discovery Bible, OpenBible.com and the Berean Bible Translation
Committee, and dedicated to the public domain in April 2023. It is reproduced
without alteration.

The typographic design, formatting, navigation structure and linking apparatus
prepared for this edition are dedicated to the public domain under
[CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/). Copy,
modify and redistribute them, in whole or in part, for any purpose, without
permission and without attribution.

The book outlines and the topical index are not ours to dedicate. They are
reproduced from reference works published by Bible Hub and are used by
permission. The topical index's topics derive from Torrey's Topical Textbook,
Nave's Topical Index, the OpenBible.info Topical Bible and the BibleHub.com
Topical Bible, as credited in that work. The Reader's Edition carries neither
compilation, so its Scripture text is public domain and its entire apparatus
CC0, with nothing left to license from anyone else.

CC0 waives copyright and related rights. **It does not grant any rights in
the name "The Lantern Bible", in "Lacy Digital Labs", or in any associated
marks.** Copy and redistribute the work freely; publishing a different text
under this name would misdescribe it.

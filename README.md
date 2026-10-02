# countryballs

Countryball ("Polandball") images and small icons for countries and
territories, collected from the **[Polandball Wiki](https://polandball.miraheze.org)**
and stored here under predictable file names so they can be linked directly
(for example from seed data of a football database project).

## Naming

For a territory with slug `<slug>` (e.g. `vatican-city`):

| File | Meaning |
|---|---|
| `<slug>ball-image.png` | the main countryball picture, e.g. `vatican-cityball-image.png` |
| `<slug>ball-icon-<N>.png` | small icon variants, `N` = 1…4, e.g. `vatican-cityball-icon-2.png` |

Icons are mostly PNG, a few are animated **GIF** (`….gif`, kept as GIF so the
animation survives). Not every territory has every icon number or a main image.

Direct link pattern:

```
https://raw.githubusercontent.com/DaftRoundThing/countryballs/refs/heads/main/<file>
```

## Provenance and changes

[`SOURCES.csv`](SOURCES.csv) lists, for **every** file here, the exact URL it
was downloaded from, the Polandball Wiki article it belongs to, its original
format and what (if anything) was done to it. Authors of the individual
images are credited on the wiki's own file pages, reachable from those
articles.

Modifications relative to the originals, as required by the license:

- PNG and GIF files are **unchanged** (saved byte for byte as downloaded).
- JPEG images were converted to PNG (a format change only).
- One SVG was rasterised to PNG.

The `conversion` column of `SOURCES.csv` says which applies to which file.

## License

The Polandball Wiki states: *"Content is available under Creative Commons
Attribution-ShareAlike 4.0 International (CC BY-SA 4.0) unless otherwise
noted."* This collection is therefore distributed under the same license, see
[`LICENSE`](LICENSE) (full legal code) or
<https://creativecommons.org/licenses/by-sa/4.0/>.

"Unless otherwise noted" matters: a few images were not hosted on the wiki
itself but on Wikimedia Commons (their rows in `SOURCES.csv` have an
`upload.wikimedia.org` or `thumb.wikimedia.org` `source_url`), and those carry
whatever license is stated on their own Commons file page. If you reuse images from this
repository, check the original file page linked through `SOURCES.csv`.

This repository is not affiliated with or endorsed by the Polandball Wiki or
Miraheze.

# Artwork images

The exhibit (`Hidden Patterns.dc.html`) loads each artwork from this folder via
CSS `background-image`. Until a file is present, the card and canvas fall back
gracefully to the striped `[ artwork: … ]` placeholder — nothing breaks.

Drop in these four files (public domain), keeping the exact names:

| File              | Artwork                         | Source (public domain)                          |
|-------------------|---------------------------------|-------------------------------------------------|
| `starry-night.jpg`| The Starry Night — Van Gogh 1889| Wikimedia: *Van Gogh - Starry Night*            |
| `great-wave.jpg`  | The Great Wave — Hokusai 1831   | Wikimedia: *The Great Wave off Kanagawa*        |
| `the-scream.jpg`  | The Scream — Munch 1893         | Wikimedia: *The Scream*                         |

Recommended: landscape-ish crops, ~1400px wide, optimised JPEG.

> Note: these could not be fetched automatically — this environment's egress
> policy blocks `commons.wikimedia.org` / `upload.wikimedia.org` and the museum
> image APIs (403). Add the files locally, or upload them in chat and they'll be
> committed here.

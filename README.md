# TRAVERSE - Cover Designs

Sixteen cover designs for **TRAVERSE - A Collection of Voices, Dreams & Journeys**,
the student anthology of Cambridge International School, Dasuya (Vasal Education).

Designed by **Gurkaran**.

- **Set one - photographic:** ten covers built on real photographs, chosen from a
  library of 96, then cropped, graded and typeset by hand.
- **Set two - built with Jarvis:** the original six, drawn entirely in code. No
  photographs; every ridge, bird, ring and gradient is generated shape by shape.

All covers are also produced at full print size (A5 + 3mm bleed, 300 DPI).

## Run locally

No build step and no dependencies - it is a plain static site.

```bash
python -m http.server 8000
```

Then open <http://localhost:8000>.

## Deploy

Any static host works. For Vercel, from this folder:

```bash
vercel
```

## Layout

```
index.html        the page
css/style.css     all styles
img/              the sixteen covers
fonts/            Playfair Display 700, Jost 500
```

Photographs are from Unsplash, used under the Unsplash License
(free for commercial use, modification expected, no attribution required).

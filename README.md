# faezehkhazaee97.github.io

Personal website of Faezeh (Baran) Khazaee, machine learning for biology.

Live at https://faezehkhazaee97.github.io/

## How it is built

A single static page with no build step, served by GitHub Pages from the root of the `main` branch.

| File | What it does |
| --- | --- |
| `index.html` | The whole site: content, styles, search metadata (JSON-LD), and the Fig. 1 DNA attention animation |
| `404.html` | Page shown for broken links |
| `assets/files/Faezeh_Khazaee_CV_ComputationalBiology.pdf` | CV linked from the page |
| `assets/photo.jpg` | Portrait |
| `assets/og-image.png` | Preview image shown when the link is shared |
| `assets/favicon.svg`, `favicon.ico`, `assets/apple-touch-icon.png` | Browser and phone icons |
| `assets/fonts/` | Newsreader typeface (SIL Open Font License, see `OFL.txt`) |
| `robots.txt`, `sitemap.xml` | Tell search engines what to crawl |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Common edits

- **New paper:** copy an existing `<li>` in the Publications section of `index.html` and edit it. Also add a `ScholarlyArticle` entry to the JSON-LD block in the `<head>`.
- **Update the CV:** replace `assets/files/Faezeh_Khazaee_CV_ComputationalBiology.pdf` with a new PDF of the same name.
- **Change the photo:** replace `assets/photo.jpg` with another square image (at least 600 pixels).
- **After any edit:** update the date in `sitemap.xml` (`<lastmod>`), in the JSON-LD (`dateModified`), and in the footer.

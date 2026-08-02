# Daiju Hoshino — portfolio

Static personal site for Daiju Hoshino: biology instructor, department chair,
faculty developer, and builder working at the intersection of learning, data,
and responsible AI.

No build step and no dependencies. Open `index.html` in a browser to preview.

## Before publishing

Search `index.html` for `TODO` and replace four things:

1. **Email address.** `your-address@example.com` appears in the header, the
   speaking section, the About links, and the footer. Replace all of them.
2. **Article links.** The four cards in the Writing section currently point at
   your LinkedIn articles feed. Replace each `href` with the direct article URL.
3. **Curriculum vitae.** The About section links to
   `assets/daiju-hoshino-cv.pdf`. Add that file, or delete the link.
4. **Site address.** If you move to a custom domain, update the `canonical`,
   `og:url`, `og:image`, and `twitter:image` tags in `<head>`, and the `url`
   and `image` fields in the JSON-LD block. These must be absolute URLs or
   LinkedIn will not render a preview card.

## Files

- `index.html` — content, metadata, structured data
- `styles.css` — palette, type scale, layout, responsive rules
- `assets/hero-botanical.webp` — hero artwork (258 KB, down from 3.1 MB)
- `assets/portrait.webp` / `.jpg` — portrait, used in the hero and About
- `assets/og.jpg` — 1200×630 link-preview card
- `assets/favicon.svg` — tree mark
- `.nojekyll` — serve files directly, without Jekyll processing

## Typography

Display face is Fraunces, text face is Archivo, both loaded from Google Fonts.
Fallbacks are Georgia and Helvetica/Arial. The previous version specified
Aptos, which ships only with Microsoft 365, so most visitors never saw it.

## Publish with GitHub Pages

1. Upload every file and the `assets` folder to the root of the `main` branch.
2. Settings → Pages → Build and deployment → Deploy from a branch.
3. Choose `main` and `/ (root)`, then Save.

Published address for a repository named `Portfolio`:
`https://dhoshino44.github.io/Portfolio/`

# The Future Thread — Author Website

Landing page for **The Future Thread: Redefining Ownership, Autonomy, and Efficiency in Fashion** by Gawain "G2" Bracy II (co-authored with Diana Cañas and Mery Wayfarer).

## Live site
🔗 **https://author-site-gamma.vercel.app**

## What's here
- **`index.html`** — single-file, self-contained static site (book cover + QR code embedded as base64 data URIs, so it works offline).
- **`qr.png`** — the QR code asset (points to the IngramSpark storefront).

## Sections
- Hero with book cover + tagline
- About the book (official description)
- Author bio (Gawain "G2" Bracy II)
- Buy section — IngramSpark, Apple Books, Amazon
- **For AI Agents** — `publish.new` purchase embed (`data-slug="the-future-thread-57cc0b0c"`)
- QR "scan to buy" section
- "Coming Next" placeholder for future books

## Deployment
Hosted on **Vercel** (project: `creative-projects/author-site`). The `publish.new` AI-agent embed requires a real HTTPS origin, so the site must be served over the internet (not opened as a local `file://`).

### Deploy
```bash
vercel --prod
```

## Editing
The site is a single HTML file — edit `index.html` and redeploy. The cover and QR are embedded as base64; to swap them, replace the `data:image/...;base64,` values.

## Buy links
- IngramSpark: https://shop.ingramspark.com/b/084?params=bIQekyPdCu4nW1ZsOLQ9bknlXeSgMRv4zumOBvJJG1b
- Apple Books: https://books.apple.com/us/book/the-future-thread/id6797340322
- Amazon: https://a.co/d/0d9cxt7b

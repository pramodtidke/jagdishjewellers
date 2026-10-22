# Asset replacement guide

The current product and occasion photos are remote Unsplash demo images referenced in the HTML. They are illustrative only and must not be represented as actual Jagdish Jewellers inventory or store photographs.

Recommended replacement workflow:
1. Gather owner-approved shop exterior/interior photos, product close-ups and bridal/occasion images.
2. Export web-optimized `.webp` or `.jpg` images, ideally 1200–1800 px on the long edge.
3. Save them in `assets/images/` with descriptive names (for example `store-front.webp`, `gold-necklace-01.webp`).
4. Replace image `src` URLs in `index.html`, `about.html`, `collections.html`, `bridal.html`, and `gallery.html`; update each `alt` text to describe the actual image.
5. Keep the original SVG logo unless the owner provides an approved brand logo.
6. Test mobile crops and image loading after publishing.

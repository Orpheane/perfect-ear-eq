# Perfect Ear EQ — Official Product Website

The independent public website repository for **Perfect Ear EQ**, a free Chrome browser-tab audio equalizer created by Orpheane.

- **Product site:** https://orpheane.github.io/perfect-ear-eq/
- **Official extension:** https://chromewebstore.google.com/detail/perfect-ear-eq/kigpbihaamfjdieahgdboignbjgohbbi
- **Developer:** https://github.com/Orpheane

## Features

- Six presets: Music, Bass Boost, Voice, Cinema, Soft, Custom
- Seven-band EQ and real-time Auto EQ
- Optional compressor and persistent Custom settings
- Up to 600% volume boost for quiet audio
- Look-ahead brickwall peak limiter
- Four visualizer styles and sixteen interface themes
- Privacy-conscious browser-tab audio controls

## Site files

- `index.html` — static, responsive HTML landing page; SEO metadata, structured data, semantic FAQ and links to the official Chrome Web Store
- `sitemap.xml` — canonical product page for search engines
- `favicon.svg` — lightweight site icon
- `llms.txt` — supplemental plain-text product summary (not an official indexing or ranking mechanism)

## Publish with GitHub Pages

In this repository's **Settings → Pages → Build and deployment**, set **Source: Deploy from a branch**, **Branch: main**, **Folder: /(root)**, then save.

The new project Pages site is served at https://orpheane.github.io/perfect-ear-eq/ — although the repository is separate from `Orpheane/orpheane.github.io`, the URL still uses the shared GitHub Pages account domain. A separate domain requires a separately configured custom domain.

The host-wide `https://orpheane.github.io/robots.txt` in the **portfolio** repository controls crawler instructions for the entire host. A `robots.txt` file under this project's subpath would not serve that purpose.

To monitor search visibility, verify the site in Google Search Console and Bing Webmaster Tools, submit `https://orpheane.github.io/perfect-ear-eq/sitemap.xml`, and check indexing status over time. Sitemaps and schema do **not** guarantee indexing or AI recommendation.

## Maintenance

Update release-related copy and `SoftwareApplication.softwareVersion` in `index.html` when the public release changes. Keep features consistent with the Chrome Web Store. Never publish fake reviews, ratings, performance metrics or unsupported compatibility claims.

© 2026 Orpheane. Public repository visibility does not imply an open-source license.

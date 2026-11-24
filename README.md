# MM Apps landing page

Bilingual static HTML5 landing page for MM Auto, MM Tube and MM IPTV.

- Arabic: `/`; English: `/en/`.
- Public URL: https://moustafamagdi.github.io/MM-Apps/
- Hosting: GitHub Pages, `gh-pages` branch, root directory.
- Main download tracks the latest stable MM Auto release. Preview builds stay on the releases page.
- No visitor-side JavaScript, analytics or third-party fonts. Cairo is self-hosted under the included SIL Open Font License.

## Edit and preview

Edit `build.cjs` for content and metadata, `dist/assets/style.css` for layout. Run `node build.cjs`, then `node preview.cjs` and open http://127.0.0.1:4173. Icons in `dist/assets` are retained when the Android checkout is unavailable.

## Publish

Commit the generated `dist` files on `main`, then publish a subtree of `dist` to `gh-pages`. Do not upload `.openai` or local logs.

## Search

Both languages contain full static HTML, unique titles/descriptions, canonical URLs, reciprocal hreflang, Open Graph metadata and SoftwareApplication structured data. Sitemap: `/sitemap.xml`. Submit the sitemap in Google Search Console after ownership verification; indexing and ranking are not guaranteed.

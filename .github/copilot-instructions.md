# Website indexing

- When adding, removing, or renaming an indexable page, update `sitemap.xml` in the same change.
- List each indexable page once using its canonical HTTPS URL on `www.scanlineclassic.com`: use `/` for the home page and the `.html` path for other pages. Keep each page's canonical link consistent with the sitemap.
- Keep `robots.txt` pointing to the sitemap. Add `lastmod` only when the page's actual significant modification date is known, and update it only when the page changes significantly.

# Sanofysi website

Static website for Sanofysi Prebiotic Syrup in English, French (`/fr/`) and Swahili (`/sw/`).
No build step is needed: these files are the finished site.

## What is in here

| Path | What it is |
|---|---|
| `index.html` | Homepage |
| `sanofysi-prebiotic-syrup.html` | Product page |
| `sanofysi-journal.html` and the five article pages | Gut health guides |
| `delivery.html` | Delivery across Africa and worldwide |
| `fr/`, `sw/` | The same pages in French and Swahili |
| `assets/` | Images, icons and logos |
| `sitemap.xml`, `robots.txt`, `llms.txt` | Files for search engines and AI crawlers |
| `404.html` | Shown when a page is not found |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Put it on GitHub Pages

1. Create a new repository on GitHub.
2. Upload everything in this folder to the repository (drag the files into "Add file > Upload files", or use git).
3. In the repository, open Settings > Pages. Under "Build and deployment", choose "Deploy from a branch", pick the `main` branch and the `/ (root)` folder, then save.
4. After a minute or two the site is live at the address GitHub shows on that page.

## Before you announce the site

1. **Domain.** Search for `YOUR-DOMAIN` in `sitemap.xml` and `robots.txt` and replace it with your real address, for example `www.sanofysi.com`. If you use your own domain, add it under Settings > Pages > Custom domain.
2. **Search engines.** Add the site to Google Search Console and Bing Webmaster Tools and submit `sitemap.xml`.
3. **Checkout.** "Add to bag" is a preview only. It does not take orders or payments yet.
4. **Delivery details.** `delivery.html` says cost and time are shown at checkout. Replace that with real prices, times and courier once known.
5. **Translations.** Have a native speaker read the French and Swahili pages.

## Notes

- The `404.html` button links to `/`. If the site is served from a sub-folder (for example `username.github.io/repository/`), change that link to the sub-folder address or use a custom domain.
- All other links are relative, so the site works at any address.

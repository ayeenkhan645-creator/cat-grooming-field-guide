# Cat Grooming Field Guide — Render Static Site

A complete static HTML/CSS/JS site. 13 original 500+ word articles, 20 SEO pages, private client-side coat-care planner.

## Quick deployment (Render)
1. Create a PUBLIC GitHub repository named `cat-grooming-field-guide`.
2. Upload the contents of this ZIP to the repository. The `public/` folder must be at the repository root.
3. Open https://dashboard.render.com/ , choose New > Static Site, and connect that repository.
4. Configure:
   - Name: `cat-grooming-field-guide`
   - Branch: main
   - Build command: `echo Static website ready`
   - Publish directory: `public`
5. Deploy. The target address is `https://cat-grooming-field-guide.onrender.com` if available. For a different assigned address, replace all occurrences of the target hostname in public/*.html, public/guides/*.html, public/robots.txt and public/sitemap.xml and redeploy BEFORE GSC verification.
6. In Google Search Console add the final site URL as a URL prefix property. Download the HTML verification file and commit it to `public/`, then let Render redeploy; verify and submit `sitemap.xml`.

## Backlink record — STRICT
Exactly ONE hyperlink to www.whatismycatbreed.com exists in this entire publication.
- Source: `https://cat-grooming-field-guide.onrender.com/guides/coat-type-and-breed-labels.html`
- Anchor: `Read here`
- Target: `https://www.whatismycatbreed.com/identify-cat-breed-by-physical-features` (non-homepage educational article)
There are NO homepage links to the main site.

Two other educational web-2.0 sites are naturally cited from the homepage, plus references to veterinary organizations on the resources page.

## Important
- This is static hosting, NOT Render's web service (which sleeps on the free tier).
- Site name availability and URL have NOT been checked live.
- The journal saves entries only in the individual browser (localStorage); no server-side records or accounts.
- Inspect and test public deployment before claiming SEO readiness.

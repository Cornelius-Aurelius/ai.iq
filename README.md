# AI.IQ — GitHub Pages Site

Production-ready static site for **https://ai.iq.corneliusaurelius.com**.

## GitHub Pages deployment

1. Create a public GitHub repository (for example `ai-iq`).
2. Upload every file in this folder to the repository root.
3. In **Settings → Pages**, deploy from the `main` branch root.
4. Set **Custom domain** to `ai.iq.corneliusaurelius.com`.
5. Wait for GitHub's DNS check, then enable **Enforce HTTPS**.

The repository already contains `CNAME` with the custom domain.

## Search setup

- `robots.txt` allows crawling.
- `sitemap.xml` lists the public pages.
- Canonical URLs use the final HTTPS custom domain.
- Open Graph and X/Twitter metadata use the 1200×630 social preview.
- JSON-LD identifies the site, web application and creator without inventing ratings or reviews.
- `index.html` includes a visible, crawlable explanation of the product in addition to the interactive app.

After deployment, add the subdomain/property in Google Search Console, submit `https://ai.iq.corneliusaurelius.com/sitemap.xml`, inspect the home page URL, and request indexing.

## Data classification safeguard

AI.IQ classifies imported exports before ranking them. Audience/demographic breakdowns (for example Meta or LinkedIn job titles, seniority, industry, company size, age, gender or location) are routed to **Audience Insights** and are not treated as posts or ad creatives. Search data and descriptive/reference datasets are also excluded from the creative-winners leaderboard. Only genuine content/creative rows with measurable performance signals are eligible to be ranked as winners.

## Provenance

- **Created:** 14 September 2026
- **Creator:** [Cornelius Aurelius](https://corneliusaurelius.com/)
- **Product:** AI.IQ — Social Media Growth Intelligence

The public pages use one restrained creator attribution plus consistent author/creator structured data. This is intended to make authorship clear without keyword stuffing or artificial repetition.

## Important

Search indexing, rankings, rich results and appearance in Google AI Overviews are **not guaranteed**. This site is configured to be crawlable and eligible; Google decides whether and when to crawl, index, rank or cite a page.

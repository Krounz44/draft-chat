# Drafty Website v1

Static launch-ready website for `draftychat.com`.

## Structure
- `/` - main product website
- `/blog/` - SEO blog index
- `/privacy/` - Privacy Policy
- `/terms/` - Terms of Use
- `/404.html` - branded not-found page
- `/sitemap.xml` and `/robots.txt` - search-engine discovery

## Deployment
This package is ready for GitHub Pages at the custom domain `draftychat.com`. `CNAME` and `.nojekyll` are already included.

Upload the contents of this folder to the publishing branch/root used by the live site.

## One launch item intentionally not added
There is no App Store download button yet because the permanent App Store product URL was not supplied in the source material. Once Apple publishes the listing, add the exact URL to the primary CTA and optionally add Apple's Smart App Banner meta tag using the real App Store ID.

## SEO after deployment
1. Verify `https://draftychat.com/sitemap.xml` loads publicly.
2. Submit the sitemap in Google Search Console.
3. Request indexing for the homepage and the three initial blog articles.
4. Keep blog posts source-accurate; do not announce features that are not in the shipping app.

## Contact rule
All public website contact routes use only:

`hello@draftychat.com`

No analytics, advertising pixels, cookie trackers, contact forms, or third-party chat widgets are included in this build.

## Included brand icons
Instagram, TikTok and App Store icon SVGs are included from Font Awesome Free 6.7.2 brand icons (CC BY 4.0). They are used only to identify their respective platforms/services.

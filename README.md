# Backlink & Share Link Helper

A static, browser-based helper adapted from the original project.

## GitHub Pages setup
1. Open **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then save.
4. Wait for the Pages deployment in the **Actions** tab. The site URL will be:
   `https://mrnitin03.github.io/backlink-generator-tool/`

## Files
- `index.html` — user interface
- `styles.css`, `stealth-iframe.css` — styles
- `backlink-generator.js` — client-side logic
- `backlink-templates.json` — reviewed social-sharing destinations
- `youtube-backlink-templates.json` — reviewed sharing destinations used for video URLs
- `cors-proxies.json` — optional third-party proxy used by the ping workflow

## Important limitations and safety
- The template list was reduced from thousands of mixed/unknown destinations to common social-sharing endpoints. This avoids automatically sending your URL to a large list of unrelated sites.
- Social-sharing URLs are not the same as editorial backlinks, and they do not guarantee indexing, ranking gains, or dofollow links.
- The optional CORS proxy is a third party; do not use the tool with sensitive/private URLs.
- Review the destination before opening any generated link. Avoid repeated or unsolicited submissions. Google treats automated link creation intended to manipulate rankings as link spam.
- This is a static site: no server, database, or VPS is required.

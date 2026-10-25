# Wigbox Staff Portal

Source of the "Design Process Quick Links" page embedded on wigbox.co.il.

- `index.html`: the full page. Edit this file.
- `embed.html`: the small snippet pasted into WordPress (HTML widget). It loads `index.html` from jsDelivr. Only changes if the repo name changes.
- `legacy-wordpress-embed.txt`: the old chunked embed, kept as a backup.

## Updating the live site
1. Edit `index.html`, commit, push to `main`.
2. Open this link once to clear the CDN cache (otherwise it can take up to 12 hours):
   https://purge.jsdelivr.net/gh/Becca-Rose/wigbox-staff-portal@main/index.html
3. Refresh wigbox.co.il.

This repo is public. Never commit keys, passwords or private links.

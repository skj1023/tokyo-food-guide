# 东京食帖｜Tokyo Food Notes

A mobile-first, single-page restaurant guide based on the Tokyo food note in SiYuan.

- `index.html` is a static page with category filters, full-text search, Leaflet + OpenStreetMap, and Google Maps links.
- Verified coordinates alone are plotted; uncertain restaurant identities (including the eel shop noted as “日本橋 本根”) are not assigned guessed pins.
- Restaurant photos are linked from their source pages. Items without a verified suitable image show a transparent placeholder rather than an unrelated photo. Fuglen images are intentionally omitted because the official site prohibits reuse without permission.
- The custom domain target is `food.go.skj1023.top`; configure a DNS-only CNAME to `skj1023.github.io` in Cloudflare, then GitHub Pages can verify HTTPS.

## Sources

Individual image credits and source links are listed in the page. Map tiles © OpenStreetMap contributors; map UI uses Leaflet.

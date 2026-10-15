# Tummy Focus landing pages (production source)
Static site. Deploy target: DigitalOcean App Platform (static site, output dir `/`). Domain: tummyfocus.jjsmithonline.com (Cloudflare DNS → DO).
- `/a/` sales page · `/b/` advertorial · `/c/` Gut Check quiz (HF-style). `/` = the page JJ picks (copy it to root at go-live).
- Tracking switches on only on *.jjsmithonline.com: GTM-WT4MWLTH, Meta pixel 1614860232058835, checkout links carry utm_* + attributes[landing_page].
- Quiz → Klaviyo (company TSTCui): event `TF Gut Check Completed`; set `CONFIG.listId` once the list exists to subscribe.
Source of truth for copy/gate log: moses repo `wiki/deliverables/tummy-focus-villain-carousels-20261015/`.

# Vikku Communication — Website

Official website for **Vikku Communication**, a chip-level mobile repair shop in
Shastri Nagar, Ghaziabad (U.P.).

Static site — **no backend, no trackers**. Plain HTML, CSS and vanilla JS, matched to the
shop's electric-blue / circuit branding. Mobile-first, with click-to-call, WhatsApp
click-to-chat, a sticky mobile action bar, and a "Get Directions" map link.

## Structure
```
index.html              # single-page site
_headers                # security + cache headers (Netlify / Cloudflare Pages)
assets/css/styles.css   # blue circuit theme
assets/js/main.js       # nav, mobile menu, scroll reveal
assets/img/             # SVG logo/favicon + WhatsApp QR
```

## Run locally
```bash
node server.js   # then open http://localhost:4600
```

## Contact (shop)
- 📞 / WhatsApp: 9990581072
- 📍 MF76+F69, Razapur, Shastri Nagar, Ghaziabad, U.P. 201002

---
Static · secure (strict CSP) · free hosting (GitHub Pages).

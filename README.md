# Pixel Pirates — Website

An original children's animated pirate franchise website. Two unlikely pirates. One legendary adventure.

## Run it

Static site — no build step. Serve the folder with any static server and open `index.html`
(GitHub Pages works out of the box: Settings → Pages → deploy from branch root).

Locally: `npx serve .` or `python3 -m http.server`, then open http://localhost:8000/

> Opening the `.html` files via `file://` won't work — the pages fetch shared components (`SiteNav`, `SiteFooter`), which requires http(s).

## Pages

| File | Page |
|---|---|
| `index.html` | Entry point (redirects to Home) |
| `Pixel Pirates.dc.html` | Home — hero, characters teaser, Season 1 countdown, episodes, news, newsletter |
| `Characters.dc.html` | Pirate Red & Pirate Black profiles |
| `Fun & Games.dc.html` | Playable Treasure Memory + Treasure Hunt, badges |
| `Discover.dc.html` | Interactive world map, worlds hotspots, events timeline |
| `Shop.dc.html` | Products, filters, quick view, cart drawer, building sets |
| `Media Hub.dc.html` | Drag-and-drop media library organized by folder |
| `Pixel Pirates (standalone).html` | Self-contained offline build of the Home page |

## Structure

- `SiteNav.dc.html`, `SiteFooter.dc.html` — shared components imported by every page
- `support.js` — component runtime (do not edit)
- `image-slot.js` — drag-and-drop image slot used by the Media Hub
- `assets/` — brand artwork
- `standalone-src.html` — build source for the standalone file

© 2026 Pixel Pirates. Licensed by BBC Studios Ltd™. Original characters, artwork and stories.

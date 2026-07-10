# mhtb-assets

Static promotional assets served via GitHub Pages.

Each `ads/<placement>.json` describes one banner:
`{ "enabled": true, "image_url": "ads/<placement>.png", "target": "https://..." }`

`image_url` may be relative (resolved against the site root) or absolute.
Placements: `home_banner`, `pause_overlay`.

# Miner Merge — Gizmo remix v1.4

A React 19 mining/merge game, originally built on Gizmo.party.

- **Live:** https://xerohour.github.io/gizmo-party/
- **Gameplay:** merge pickaxes, drop them to mine blocks, earn coins, buy upgrades, open lucky blocks. Progress saves in `localStorage` (`mining-game-save`).
- **Source:** the full single-file HTML was supplied by Johnny after Gizmo.party shut down (the platform and its project pages are gone; the Wayback Machine never archived this project). No server features: haptics, text/image generation and the native tweaks panel are Gizmo-app-only and no-op on the web.
- **Assets:** all 8 media files that used to load from `content.gizmo.party` are localised under `assets/` (spritesheets, logo, font image, button background, bonus image, background music). The original Content-Security-Policy meta tag was removed because it only allowlisted `*.gizmo.party` / `runtime.gizmo.party` and would have blocked the local assets.
- **Hosting:** GitHub Pages, deploy from `main`, root. `.nojekyll` is present so Pages serves files as-is.

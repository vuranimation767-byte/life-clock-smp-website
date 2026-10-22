# Life-Clock SMP — Showcase Website

Static, client-facing showcase site for the **Life-Clock SMP** plugin (Paper 1.21.11 · Java 21), built for client **DjEoii**.

**Live:** https://vuranimation767-byte.github.io/life-clock-smp-website/

## Contents
- `index.html` — single-page showcase (mechanics, BossBar HUD states, PvP time economy, Revive Totem recipe, Revive GUI)
- `assets/style.css`
- `assets/bossbar-states.svg` — HUD color states (green / yellow / red heartbeat, PROGRESS ↔ NOTCHED_10)
- `assets/crafting-grid.svg` — 3×3 shapeless Revive Totem recipe + 5h sacrifice cost
- `assets/revive-gui.svg` — 27-slot "Select Ghost to Revive" chest GUI mock with ghost heads, tooltip, compass search

## Notes
- Pure static HTML/CSS/SVG — no JavaScript, no build step, no plugin or Java source included.
- Deploy: push to GitHub and enable Pages from `main` / root (`.nojekyll` included).

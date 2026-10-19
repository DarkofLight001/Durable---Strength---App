# Durable — Strength That Lasts

A 12-week functional strength and injury-resilience program for busy adults. No equipment required (two light dumbbells optional). Installable on phones and works offline.

## Live app

Hosted with GitHub Pages:
**https://darkoflight001.github.io/Durable---Strength---App/**

Open the link on your phone, then:
- **iPhone (Safari):** Share → *Add to Home Screen* (open it once while online so it saves itself for offline use)
- **Android (Chrome):** menu ⋮ → *Install app* / *Add to Home screen*

## What's inside

- **4 plan options** (2 or 3 full-body days, a daily 5–10 minute circuit, a 10-minute durability routine)
- **App-style plans:** swap any exercise in seconds (swipe or ‹ ›), browse alternatives by level, matched to the same movement pattern; favourites; save your own versions; adapt a plan to a target level; workout mode with rest timer and history
- **107 illustrated exercises** with animated demos and progression pathways from beginner to elite
- Weekly planner around your sport, 12-week tracker, benchmark tests, starting-point calculator
- Injury resilience, mobility, recovery and cited references

All progress and saved plans stay on the device; nothing is sent anywhere.

## Publishing with GitHub Pages

1. Create a new **public** repository and upload all files in this folder (including `.nojekyll`) to its root.
2. Go to **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, pick your main branch and **/(root)**, then **Save**.
3. Wait 1–2 minutes and open the link above.

## Files

| File | Purpose |
|------|---------|
| `index.html` | The whole app (layout, content, logic) |
| `sw.js` | Service worker for offline use |
| `manifest.webmanifest` | App name, colours and icons for installing |
| `icon-*.png` | App icons |
| `.nojekyll` | Tells GitHub Pages to serve files as-is |

## Updating the app

Replace `index.html`, then bump the cache version in `sw.js` (`durable-v1` → `durable-v2`) so installed copies pick up the change.

## Disclaimer

Educational program for healthy adults. It doesn't replace an individual medical or physiotherapy assessment.

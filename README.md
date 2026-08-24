# Benjamin Franklin Plumbing — Kickoff Priorities

Working session tool for the Benjamin Franklin Plumbing (Kansas City) kickoff call.

**Live:** https://noiceboom.github.io/bf-plumbing-kickoff/

## What it does

Five screens, in order:

1. **Services** — confirm the 20 services (and 25 sub-services) pulled off the site. Uncheck what they don't sell, toggle individual sub-services, add anything missing.
2. **Rank services** — drag to order most → least important. Tier 1 = top 5.
3. **Cities** — confirm the 34 cities, grouped MO / KS. Gold "verify" flags mark the ones that need settling on the call (Roland Park → Roeland Park, Shawnee Mission, Stanley, Lees Summit, North KC).
4. **Rank cities** — same drag-to-order. Cities that already have a real page (Kansas City, Blue Springs, Riverside) are marked.
5. **Readout** — top five and five, full order, dropped items, notes. Copy as text, download CSV, print, or copy a share link.

## State

No backend. State autosaves to `localStorage` and encodes into the URL hash, so **Copy share link** produces a URL that reproduces the exact order, drops, notes, and custom additions on any machine.

## Reordering

Drag the handle, use the ↑ / ↓ buttons, or focus a handle and press arrow keys. Works on touch.

Branding follows the [Service Scalers design guide](https://noiceboom.github.io/service-scalers-design-guide/).

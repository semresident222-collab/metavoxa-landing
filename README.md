# MetaVoxa — Landing Page

The front door to the MetaVoxa ecosystem. This repo holds **only** the navigation/landing page at `metavoxa.com` — it does not contain any of the five rooms themselves. Each room lives in its own repo, on its own subdomain.

> MetaVoxa is not a single website. It is an institutional ecosystem for surfacing what systems do not see. This page exists to point visitors to the right room.

---

## Ecosystem Map

| Room | Subdomain / URL | Repo | Status |
|------|------------------|------|--------|
| Atrium | `atrium.metavoxa.com` | `metavoxa-atrium` | Live |
| Labs | `labs.metavoxa.com` | `metavoxa-labs` | In development |
| Press | `https://substack.com/@metavoxapress` | external (Substack) | Live |
| Research | ORCID `0000-0003-4152-3863` + GitHub | external | Live |
| Founder | `marthakoroma.com` | separate repo | Live |

This landing page (`metavoxa.com`) is its own repo and deployment, separate from Atrium. Atrium previously held the root domain; it now lives at its own subdomain.

---

## What's On This Page

1. **Hero** — five-door visual (desktop: single image with positioned hotspot links; mobile: scroll-snap carousel of five separate door crops)
2. **Mission line** — "An institutional ecosystem for surfacing what systems do not see."
3. **About section** — human, conversational framing for each of the five rooms ("if you want X, go here"), plus a short "what is this page" blurb under the top-right `ABOUT` link
4. **Footer** — institutional social links (X/Twitter, LinkedIn — company page, not personal) as plain icons, no editorial copy

---

## Content Source of Truth

All copy on this page is derived from the MetaVoxa Knowledge Core (Constitution, Vocabulary, Ecosystem Map, Strategic Questions Registry, Founder Profile). If wording here and the Knowledge Core ever disagree, **the Knowledge Core wins** — this page is an output, not the source (Fortress Principle, Knowledge Core §14).

Update this page's copy only after updating the relevant Knowledge Core document first.

---

## Assets

- **Desktop hero image:** single composite image, five-door scene, ~2560×1024px. Hotspot coordinates for each door are defined in [wherever you're storing them — CSS/JS file].
- **Mobile door crops:** five separate 3:4 portrait images (~900×1200px), one per room, generated to match the desktop scene's lighting/style. Each crop bleeds ~15–20% into neighboring doors at the edges, slightly dimmed/desaturated, to read as a silhouette swipe cue.

---

## Design Language (for consistency across future MetaVoxa builds)

- **Architecture-as-metaphor** — rooms, doors, thresholds, not menus or tabs
- **Restrained navigation** — pill-shaped nav elements, minimal chrome
- **One bold signature per surface** — this page's signature is the five-door photographic scene; don't compete with it elsewhere on the page
- **Serif display type** paired with clean sans body text, consistent with marthakoroma.com and Atrium
- Each room is free to develop its own distinct mood (Labs is intentionally more "instrument/archive" coded) — the landing page should stay the quietest, most neutral surface in the ecosystem

---

*Maintained by Martha Wuya Koroma. Part of the MetaVoxa Knowledge Core ecosystem.*


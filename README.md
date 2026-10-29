# carafe Fleet Operator: the page

The public page for the carafe Fleet operator, a Kubernetes operator that runs
[Fleet](https://fleetdm.com) and, through it, keeps always-on Mac stations for AI agents (Claude Code, Codex or your own) healthy. It is one
HTML file that is also a 16-slide deck.

- **Live:** https://damaris-x.github.io/carafe-fleet-operator/
- **As a deck:** press **P** or **Present**; ← → to move, Esc to leave. Opening
  `…/#present` starts in the deck. ⌘P prints one slide per page (16:9).

This repository holds the page and its figures only, no carafe source. Everything here is
public. The internal pitch notes, with the sources for every claim on the page, are in the
carafe repository under `docs/marketing/`.

No build step: edit `index.html` or a figure in `figures/` and open a pull request (the organization
requires one for `main`). Merging it republishes the page within a minute or two.

© 2026 Cheng Cheng. All rights reserved.

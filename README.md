# Zunvio UI/UX Lab — Open Source

Original UI/UX and frontend prototypes, researched from current design patterns and built from scratch.
Published as open source under the MIT License (see `LICENSE`) on two hosts:

- **GitHub (primary):** https://github.com/zunvio/uiux-lab
- **GitLab (mirror):** https://gitlab.com/zunvio/uiux-lab — same code, mirrored for availability. Issues and contributions are handled on GitHub so discussion stays in one place.

## What's inside

| Prototype | Concept |
|---|---|
| `prototypes/01-calm-bento-saas/` | Bento feature grid with motion/glass excess removed — one accent, reading order first |
| `prototypes/02-command-dashboard/` | Dark-first bento dashboard where every tile is a working control; glass only on the command bar |
| `prototypes/03-editorial-rtl-bento/` | Cream/serif editorial trust page designed Arabic RTL-first with logical CSS properties |

Each prototype is a single self-contained `index.html` — no build step, no external scripts, fonts or trackers. Open the file in a browser to try it.

Also included: `RESEARCH_2026-10-28.md` (2026 trend scan with adopt / test / skip verdicts and sources), `DESIGN_RULES.md` (design tokens and pattern rules), `IDEAS.md` (scored concept backlog).

## How these were made — patterns, not copies

Design patterns were researched from public trend reports and pattern libraries. **All implementations in this repository are original** — no third-party code, assets, logos, text or distinctive layouts were copied. If a future addition reuses open-source work, its licence is verified at the pinned release and recorded in a licence ledger before it lands.

## Design rules honoured in every prototype

- Accessibility: visible focus, `prefers-reduced-motion` fallback, body text contrast 4.5:1 or better, mobile layout first
- No images of people — geometry, charts, UI and text only
- Performance budget: single file, under 60 KB, no external requests

## Contributing

See `CONTRIBUTING.md`. Small, focused pull requests with a before/after screenshot (UI only, no people) are welcome.

## License

MIT — see `LICENSE`. You may use, copy, modify and distribute this code with the copyright and licence notice preserved.

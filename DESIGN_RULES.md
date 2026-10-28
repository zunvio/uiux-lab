# Design Rules — UI/UX Lab v1

## Tokens (default dark set)
- bg: `#050508` / surface: `#0d0d10` / elevated: `#141418`
- text: `#f4f4f5` / muted: `#a1a1aa` (check contrast on each surface)
- accent: one per concept only (e.g. `#7c5cff` violet, `#16b8a6` teal, `#e8b33d` amber)
- radius: 20px tiles, 12px controls / border: `1px solid rgba(255,255,255,.08)`
- glass (accent only): `rgba(255,255,255,.07)` + `blur(12px)` + border above
- editorial light set: bg `#faf6ef`, ink `#1c1917`, serif display + sans body

## Pattern rules
1. Mobile + reading order first, then desktop bento spans.
2. One accent, one hero idea, one primary action per screen.
3. Motion: CSS-first, <= 300ms for micro-interactions, every animation has a `prefers-reduced-motion` off-ramp.
4. No external fonts/scripts/trackers in prototypes unless licence-verified and self-hostable for free.
5. RTL is a first-class variant, not a flip afterthought — logical CSS properties (`margin-inline-start`, `inset-inline`) from line one.
6. Performance budget per prototype: single file, < 60 KB uncompressed, no images (CSS/SVG geometry only).
7. No human figures, silhouettes, avatars or faces in any visual — geometry, charts, UI and text only.

## Invention method (research -> original)
For each concept record: pattern observed -> problem it solves for our audience -> what we change (layout, interaction, language/RTL, performance) -> why the result is not a copy. A concept with no clear "what we change" is not built.

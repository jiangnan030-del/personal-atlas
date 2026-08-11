# Design System: Computational Field Notes

## Direction
A scientific field notebook translated into a precise web portfolio. Warm paper, dark mineral ink, oxide blue annotations, and large evidence plates. The site should feel authored by a researcher who builds tools, not assembled from portfolio cards.

## Principles
1. Artifact first: real figures and repositories carry credibility.
2. One reading path: proposition, research index, selected work, trajectory, notes, contact.
3. Proximity before containers: use rules and spacing instead of cards wherever possible.
4. Evidence before adjectives: describe the problem, method, and inspectable output.
5. Quiet interaction: motion confirms action; it does not decorate the page.

## Tokens
- Canvas: #f4f2ed
- Paper: #fbfaf7
- Ink: #182126
- Muted ink: #58666c
- Rule: #ccd2d1
- Accent: #245f73
- Accent wash: #dbe9ed
- Maximum content width: 1180px
- Text measure: 68ch
- Radius: 2px for controls and 6px for media only
- Spacing scale: 4, 8, 12, 16, 24, 32, 48, 72, 104

## Typography
- Display: Noto Serif SC, Songti SC, STSong, serif. Used only for h1 and h2.
- Body/UI: Noto Sans SC, Microsoft YaHei, sans-serif.
- Data: Consolas, Liberation Mono, monospace. Used only for metadata and measurements.
- Body floor: 16px. Body line height: 1.75. Display tracking never below -0.03em.

## Components
- Masthead: compact identity, four text navigation links, one contact action.
- Research index: three ruled rows, no cards.
- Evidence plate: real image with caption and repository link.
- Project dossier: problem, method, output, tools, and action.
- Repository ledger: compact rows for secondary work.
- Timeline: ruled editorial list.
- Button: filled accent for primary action; underlined text for secondary actions.

## Responsive behavior
- Desktop uses asymmetric figure/text compositions.
- Mobile becomes one linear evidence stream in DOM order.
- Navigation remains visible and wraps; no fixed bottom bar.
- Every interactive target is at least 44px on coarse pointers.

## Anti-goals
- No identical icon-card grids.
- No nested cards, glass panels, gradient text, glows, purple gradients, fake dashboards, decorative status dots, or section eyebrows.
- No generic claims, private projects, or invented metrics.
- No repeated entrance animation on every section.

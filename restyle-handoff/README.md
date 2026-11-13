# Restyle handoff

- `RESTYLE_GUIDE.md`: how to move a page from the old styling to the new one.
- `pages/`: the four restyled views, as reference implementations.
  - `Home.vue`: homepage
  - `DesignAssets.vue`: Design Assets
  - `Tools.vue`: Tools
  - `SVGPlaceholderTextGenerator.vue`: SVG placeholder text tool
- `components/`: the restyled shared components, which appear on every page.
  - `Sidebar.vue`: side nav
  - `TopNav.vue`: top nav bar (its dropdown menus weren't restyled)
  - `DocumentationDrawer.vue`: docs drawer, including the fix that makes it follow theme changes
  - `Breadcrumbs.vue`: breadcrumb bar
- `supporting/`: what the pages import, at the same paths as in `frontend/`.
  - `src/utils/spotIllustrations.js`: the `spot()` helper
  - `src/assets/illustrations/spot/`: the Trench Coat spot illustrations the pages use

In the repo, the pages live in `frontend/src/views/` and the components in `frontend/src/components/`. The full change is PR #12 (branch `home-spot-illustrations`).

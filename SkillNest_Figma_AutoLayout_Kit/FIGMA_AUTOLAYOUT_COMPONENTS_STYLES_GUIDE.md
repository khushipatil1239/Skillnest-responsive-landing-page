# SkillNest — Figma Auto Layout, Components & Styles Setup

## Important
`SkillNest_Figma_Starter.svg` is an editable vector visual reference. Import it into Figma as a starting point. **SVG import does not create native Figma Auto Layout frames, components, or shared styles automatically**. Use the steps below to make those native Figma features.

## 1. Import the starter
1. Create a new Figma Design file and name it `SkillNest — Responsive Landing Page`.
2. Drag `SkillNest_Figma_Starter.svg` onto the canvas, or use File → Place image.
3. Keep it on a layer named `Visual reference`; lock it after sizing it to 1440 × 1180.
4. Create a new desktop frame named `Landing Page / Desktop` at 1440 px wide. Rebuild the sections with native Figma frames and text layers over the reference. Do not submit only the SVG reference as proof of Auto Layout.

## 2. Create shared colour styles
Use the Assets / Local styles area (Figma UI wording can vary):
- `Brand / Indigo` — `#4F46E5`
- `Brand / Indigo Light` — `#EEF2FF`
- `Text / Primary` — `#111827`
- `Text / Secondary` — `#475569`
- `Text / Muted` — `#64748B`
- `Surface / White` — `#FFFFFF`
- `Surface / Page` — `#F8FAFC`
- `Border / Subtle` — `#E2E8F0`
- `Accent / Green` — `#16A34A`
- `Accent / Amber` — `#D97706`

To create each style: select a native layer → Fill colour → style/library icon → create style → use the exact name above. Apply the styles to native layers.

## 3. Create shared text styles
Use Inter if available; otherwise use a visually similar sans-serif font and document that choice.
- `Heading / H1` — 56 px, ExtraBold/Bold, line height 1.15
- `Heading / H2` — 34 px, Bold/ExtraBold, line height 1.2
- `Heading / Card` — 21 px, Bold, line height 1.3
- `Body / Large` — 19 px, Regular, line height 1.55
- `Body / Default` — 15–16 px, Regular, line height 1.5
- `Label / Small` — 12–13 px, Medium/Semibold, line height 1.4
- `Button / Label` — 15–16 px, Bold, line height 1.2

Select a text layer → Text styles menu → create style. Name each style exactly as above and apply it to matching text layers.

## 4. Native Auto Layout structure
Use Shift+A to add Auto Layout to selected layers. Set resizing, spacing, padding, alignment, and radius as described.

### `Landing Page / Desktop` (vertical Auto Layout)
- Width: 1440 px; height: Hug contents if possible.
- Direction: vertical; gap: 0; padding: 0.
- Children in order: `Header`, `Hero`, `Features`, `Footer`.
- Make sections Fill container width.

### `Header` (horizontal Auto Layout)
- Width: Fill container; height: 92 px fixed.
- Padding: 24 px vertical, 96 px horizontal (for a 1440-wide frame); spacing mode: Space between; alignment: center.
- Children: `Brand group`, `Navigation group`, `Header CTA`.
- `Brand group`: logo mark + SkillNest text, horizontal Auto Layout, gap 12.
- `Navigation group`: Courses, For Teams, About; horizontal Auto Layout, gap 32.
- CTA: component `Button / Primary`, horizontal Auto Layout, padding 16 px vertical and 24 px horizontal, radius 13.

### `Hero` (horizontal Auto Layout)
- Width: Fill container; padding: 64 px top/bottom and 96 px left/right; gap: 48 px; alignment: center.
- Left column: vertical Auto Layout, width Fill container, gap 20–24 px.
- Right illustration panel: width about 535 px, height about 410 px, fixed on desktop; use nested frames with Auto Layout for dashboard rows/cards.
- Heading uses `Heading / H1`; supporting copy uses `Body / Large`.
- CTA row: horizontal Auto Layout, gap 24 px; buttons use Hug contents.
- On mobile, change Hero to vertical, horizontal padding 24 px, gap 32 px; illustration width Fill container.

### `Features` (vertical Auto Layout)
- Padding: 64 px vertical, 96 px horizontal on desktop; gap 32 px.
- Title and subtitle: vertical Auto Layout, gap 12 px.
- `Feature card row`: horizontal Auto Layout, gap 24 px; each card width Fill container.
- Each card: vertical Auto Layout, padding 26 px, gap 16 px, radius 22 px; fill white; subtle border; height Hug contents.
- On mobile, change cards to a vertical stack, gap 16 px, section horizontal padding 24 px.

### `Footer` (horizontal Auto Layout)
- Width: Fill container; padding 32 px vertical and 96 px horizontal; gap 24 px; alignment center; distribute space between.
- Brand/tagline group is vertical Auto Layout; footer links are horizontal Auto Layout.
- On mobile, switch to vertical Auto Layout and align left; use 24 px padding.

## 5. At least 3 reusable components
Make each component from native layers/frames, not just the imported SVG shapes:
1. `Button / Primary` — horizontal Auto Layout; gap 8; padding 16 × 24; fill `Brand / Indigo`; radius 13; text style `Button / Label`; white label. Create component with Ctrl/Cmd + Alt + K (or use the Create component button).
2. `Navigation / Link` — horizontal Auto Layout; padding 8 × 0; text style `Body / Default`; secondary text colour. Create component, then duplicate instances for Courses, For Teams, About.
3. `Card / Feature` — vertical Auto Layout; padding 26; gap 16; radius 22; white fill; subtle border. Children: icon tile, card heading, description. Create component and use three instances with different content.
Optional fourth: `Brand / Logo` (icon + SkillNest wordmark).

## 6. Responsive mobile frame
- Create `Landing Page / Mobile` at 390 px wide.
- Rebuild the same sections using the same styles and component instances.
- Header: logo and menu icon; hide desktop nav links; CTA may become a compact button or sit in the menu.
- Hero: vertical; heading 38–40 px; body 16 px; padding 24 px; CTA buttons stacked or wrapped.
- Feature cards: vertical stack, full width.
- Footer: vertical stack, padding 24 px.
- Check that text is not clipped and no horizontal scrolling is needed.

## 7. Final checks
- Desktop and mobile frames are named clearly.
- Auto Layout is visible on header, buttons, feature cards, and each major content section.
- Three components are visible in Assets and have at least one instance each.
- Colour and text styles appear in the local styles list and are applied.
- Brief design note: “SkillNest is for students and early-career learners who want flexible, practical online courses. Indigo communicates focus and trust; generous spacing and rounded cards make content approachable; responsive layouts keep the learning experience clear on desktop and mobile.”
- Add a page named `Components & Styles` showing the components and style swatches.
- Share the Figma file link only after checking link access. Upload this project package to GitHub separately; this kit does not upload itself.

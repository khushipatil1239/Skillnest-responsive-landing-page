# SkillNest — Responsive Product Landing Page

A polished, responsive landing page for **SkillNest**, a fictional bite-sized online learning platform. Built as an individual UI/UX and front-end student project.

## How to run
1. Download and unzip the project.
2. Open `index.html` in a browser. No build tools are required.
3. For the best experience, test desktop and mobile widths using browser developer tools.

## Target audience
Students, early-career professionals, and curious lifelong learners who want practical skills but have limited time.

## Design choices
- **Visual direction:** friendly, modern, optimistic, and editorial.
- **Color palette:** warm off-white background, deep charcoal text, violet primary actions, and soft lilac/mint/yellow feature backgrounds.
- **Typography:** Manrope for expressive headings and DM Sans for readable body text.
- **Responsive layout:** desktop two-column hero, three-column feature/course grids, and mobile single-column layouts with a collapsible navigation menu.
- **Accessibility:** semantic HTML landmarks, navigation label, responsive viewport, readable contrast, and reduced-motion support.
- **Interaction:** responsive mobile menu and hover feedback on buttons/course cards.

## Reusable components (3+)
1. **Button styles:** `.button`, `.button-primary`, `.button-dark`, `.button-light`.
2. **Feature card:** `.feature-card` with three theme variants.
3. **Course card:** `.course-card`, `.course-thumb`, `.course-info`.
4. **Brand mark:** `.brand` and `.brand-mark`.
5. **Eyebrow label:** `.eyebrow`.
6. **Navigation:** `.nav` and `.nav-links`.

## Shared styles / design tokens
CSS custom properties are defined at the top of `styles.css` in `:root`, including brand colors, typography, radius, and background/text colors. Spacing and components follow a consistent visual rhythm.

## Suggested Figma recreation
Create a 1440 px desktop frame and a 390 px mobile frame. Use Auto Layout for the navigation, hero copy/actions, feature cards, course cards, footer, and CTA. Create component variants for buttons and feature cards. Suggested shared color styles:
- Primary Violet: `#7657F6`
- Primary Hover: `#6042DF`
- Ink: `#202027`
- Warm Background: `#FAF9F6`
- Muted Text: `#6F707B`
- Lilac: `#EEE8FF`
- Mint: `#D8F5E8`
- Soft Yellow: `#FFF0B8`

## Before submission
- Personalize the project and add your own name/student details if required.
- Take screenshots at desktop and mobile sizes.
- If your instructor specifically requires a Figma file, recreate/import the design in Figma; this ZIP contains working HTML/CSS/JS, not a native `.fig` file.
- Upload the ZIP or extracted source files to your GitHub repository and submit that repository link in the class Google Sheet.

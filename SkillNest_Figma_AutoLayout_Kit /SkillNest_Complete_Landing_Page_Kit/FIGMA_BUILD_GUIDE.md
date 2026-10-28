# SkillNest — Figma Completion Guide

This kit includes a responsive website prototype and a detailed Figma build guide. **Important:** a native `.fig` file cannot be generated directly here, so complete the editable Figma design by following this guide and then submit your Figma share link alongside the GitHub repository.

## 1. Create the Figma file
Create a Figma Design file named `SkillNest — Responsive Learning Platform`.
Create these frames:
- `Desktop / 1440` — 1440 × 2200 px (extend height to fit content)
- `Mobile / 390` — 390 px wide (extend height to fit content)
- Optional `Components` page for reusable components and variants.

Use a 12-column grid on desktop: margin 80 px, gutter 24 px. On mobile use 18 px side margins.

## 2. Design tokens
Create Color Styles (or Variables) with these names and values:
- `Brand / Violet` — `#7657F6`
- `Brand / Violet Hover` — `#6042DF`
- `Text / Ink` — `#202027`
- `Text / Muted` — `#6F707B`
- `Surface / Warm` — `#FAF9F6`
- `Surface / White` — `#FFFFFF`
- `Surface / Lilac` — `#EEE8FF`
- `Surface / Mint` — `#D8F5E8`
- `Surface / Yellow` — `#FFF0B8`
- `Border / Subtle` — `#E9E7E2`

Create Text Styles:
- `Display / H1`: Manrope ExtraBold, 64 px desktop / 46 px mobile, line height 1.08
- `Display / H2`: Manrope ExtraBold, 46 px desktop / 36 px mobile, line height 1.15
- `Heading / Card`: Manrope Bold, 24 px, line height 1.2
- `Body / Regular`: DM Sans Regular, 14 px, line height 1.7
- `Body / Small`: DM Sans Regular, 11 px, line height 1.6
- `Label / Eyebrow`: DM Sans Bold, 10 px, letter spacing 1.8 px, uppercase
- `Button / Label`: DM Sans Bold, 13 px

## 3. Layout map
Create the desktop page with a vertical Auto Layout frame:
- Page background: `#FAF9F6`
- Main content max width: 1120 px, centered
- Header: 78 px height; horizontal Auto Layout, space-between, 28 px gap
- Hero: horizontal Auto Layout, 2 columns, center aligned, 40 px gap; top/bottom padding 54/64 px
- Trust strip: horizontal Auto Layout, space-between, 82 px minimum height
- Features section: vertical Auto Layout, 105 px vertical padding; heading row horizontal Auto Layout; 3 feature cards in a horizontal row with 18 px gap
- Courses section: background `#F1EFFB`; 90 px top / 100 px bottom padding; heading row and 3 course cards with 18 px gap
- Testimonial: centered vertical Auto Layout; max width 820 px; 95 px vertical padding
- CTA panel: horizontal/vertical Auto Layout; violet fill; 26 px radius; 55 px vertical and 65 px horizontal padding
- Footer: vertical Auto Layout; top row horizontal; bottom row horizontal; divider between rows

Mobile layout:
- Frame width 390 px
- 18 px left/right padding
- Header 68 px; logo left and menu icon right
- Hero stacks vertically; H1 46 px; hero illustration below copy
- Feature cards and course cards stack vertically
- CTA panel uses 25 px horizontal padding
- Footer items wrap/stack

## 4. Components to create (minimum 3; suggested 6)
Create each component with Auto Layout (Shift+A). Use hug contents where appropriate.
1. `Button / Primary` — horizontal, center aligned, padding 15 px vertical / 22 px horizontal, gap 18 px, radius 100 px, violet fill, white label and arrow.
2. `Button / Dark` — same sizing, ink fill.
3. `Button / Light` — same sizing, white fill and ink label.
4. `Feature Card` — vertical Auto Layout, padding 25 px, min height 300 px, radius 22 px; properties: title, body and icon. Make three variants: Lilac, Yellow, Mint.
5. `Course Card` — vertical Auto Layout, white fill, radius 18 px, clip content; thumbnail height 170 px; text padding 20 px.
6. `Brand Mark` — 30 × 30 px violet rounded square with white “s”, radius 10 px.
7. `Eyebrow Label` — horizontal Auto Layout, icon dot + uppercase label, gap 9 px.
8. `Navigation Item` — text component with hover/active variant if desired.

## 5. Build the desktop page section by section
1. Header: SkillNest logo, Explore, Why SkillNest, Success stories, Start learning button.
2. Hero: eyebrow “YOUR NEXT CHAPTER STARTS HERE”; headline “Small lessons. Big momentum.”; description; Explore courses button; See how it works link; social proof. Create the right-side course dashboard illustration from rounded rectangles, circles, and hills using vector shapes.
3. Trust strip: “LEARN SKILLS THAT MATTER” and Design / Technology / Business / Creativity / Personal growth.
4. Features: heading “Learning that fits your real life.” Three feature cards:
   - “Your time, your pace.” — short lessons for busy schedules.
   - “Make it. Don’t just watch.” — hands-on projects.
   - “Grow together, go further.” — feedback and community.
5. Courses: “Curiosity looks good on you.” Three cards:
   - Design thinking, made simple
   - Code your first website
   - Turn your idea into a plan
6. Testimonial quote and learner attribution.
7. Violet CTA panel “Ready to make your next move?”
8. Footer with logo, tagline, links, copyright.

## 6. Prototype and responsive checks
- Set the main CTA to scroll/navigate to the courses section (or link to courses frame).
- Make the mobile menu open/close if using interactive components.
- Check at 1440 px, 1024 px, 768 px, and 390 px.
- Ensure text is not clipped and cards stack on mobile.
- Use consistent spacing: 8, 12, 16, 18, 24, 32, 40, 56, 64 px.
- Use 22 px and 18 px corner radii for large cards and course cards.

## 7. Submission checklist
- [ ] Desktop Figma frame complete
- [ ] Mobile Figma frame complete
- [ ] Auto Layout used on header, buttons, cards, sections, footer
- [ ] At least 3 reusable components created
- [ ] Color and typography styles saved
- [ ] Figma prototype preview checked
- [ ] Figma share permission set to “Anyone with the link can view” if allowed by instructor
- [ ] Website files uploaded to GitHub
- [ ] GitHub link entered in the class Google Sheet
- [ ] Figma share link entered wherever instructor requests it

## Honest deliverable note
This folder contains a working HTML/CSS/JS website, a Figma design specification, component definitions, and a submission checklist. It does not contain a native Figma `.fig` document or a published GitHub repository because those require actions inside your Figma/GitHub accounts.

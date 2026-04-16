# Planet Systems Case Study Page

Production-ready single-page UI/UX case study built with semantic HTML5 and mobile-first CSS3.

## Files

- `index.html` - Full case-study markup and content
- `styles.css` - Design tokens, components, responsive layout, and accessibility states
- `assets/` - Image exports used in the page

## Asset Inventory

| Filename | Used In Section | Purpose / Notes |
|---|---|---|
| `Home-17d23af4-0bf3-432a-a1bc-1c6639e422d7.png` | Hero | Main hero visual of redesigned home page |
| `Image_1-2c695d4d-a359-4ade-93f8-fc5a91ed7268.png` | Key User Flows | Sitemap / information architecture map |
| `Services-d274f690-c4d9-487d-b087-b4b4d6b20bf3.png` | Wireframes & Iterations | Service card interaction exploration |
| `solutions___2-9f915c12-8f8f-43de-b323-703dc64df593.png` | Wireframes & Iterations | Solutions page early concept |
| `Support___1-e60e2fb9-7c03-4714-8564-2d40d61c2588.png` | Wireframes & Iterations | Support page concept |
| `About-c2ad5c07-8566-41fe-ac55-5432148b4414.png` | High-Fidelity Screens | About page final design |
| `Contact_us-e0f8a267-11d3-4c6d-b327-d79c81078804.png` | High-Fidelity Screens | Contact page final design |
| `Resources-fd6d6fd5-c572-4399-b5d7-18fd931e633e.png` | High-Fidelity Screens | Resources page final design |
| `Product_sub_page___1-a747b733-1035-4927-a650-5a8d57806c60.png` | High-Fidelity Screens | Product detail page final design |
| `Product_sub_page___2-de0ba752-2628-4850-b1c0-632c1621c6e9.png` | Optional swap | Alternate product detail screen |
| `career_sub_page-576b1efd-3ea3-4a8c-bcd8-be3e00d0dde6.png` | Optional swap | Career page version |
| `Events_subpage_from_about_us-fdcb9e47-6882-4d0c-91a8-62df1cc92a33.png` | Optional swap | Events page variant |
| `solutions___1-67d65e53-d29a-424c-97dd-400a70d64a00.png` | Optional swap | Alternate solutions page |

If you replace any visual, keep the same filename to avoid updating HTML references.

## Quick Edits

### Swap text

- Open `index.html`
- Update copy inside each section (`Hero`, `Problem`, `Research`, `Results`, etc.)
- Keep heading hierarchy (`h1` once, then `h2`, `h3`)

### Swap images

- Put new image into `assets/`
- Keep existing file name, or update `src` in `index.html`
- Update `alt` text to describe new visual content

### Change colors and theme

Edit variables in `styles.css` under `:root`:

- `--color-primary`
- `--color-primary-dark`
- `--color-surface`
- `--color-text`
- `--color-border`

### Change font

- Replace Google Font in `index.html` `<head>`
- Update `--font-sans` in `styles.css`

## Deployment (Static Hosting)

### Netlify
1. Create new site from Git repository
2. Build command: leave empty
3. Publish directory: `project-portfolios/planet-systems-case-study`

### Vercel
1. Import project repository
2. Framework preset: `Other`
3. Output directory: `project-portfolios/planet-systems-case-study`

### GitHub Pages
1. Push files to repository
2. Configure Pages source branch/folder
3. Set folder to `project-portfolios/planet-systems-case-study`

## Design System Snippet

- **Colors**: Primary blue for actions, soft blue surfaces for section separation, dark navy for text.
- **Typography**: Inter with clear hierarchy for case-study reading flow.
- **Spacing scale**: `--space-1` to `--space-8` for consistent rhythm.
- **Buttons**: Primary filled CTA and secondary light variant.
- **Cards**: Rounded containers with subtle border/shadow for grouped information.
- **Icons/imagery**: Imagery should support narrative progression per section.

## Accessibility Checklist

- [ ] Keyboard navigation reaches all links and CTA buttons
- [ ] Skip link appears when tabbing from top
- [ ] Visible `:focus-visible` outline is preserved
- [ ] Color contrast meets WCAG AA (verify with browser tooling)
- [ ] All informative images include meaningful `alt`
- [ ] Heading order remains logical after edits
- [ ] Decorative content is not announced by screen readers

## Performance Checklist

- [ ] Convert large PNG exports to WebP where possible
- [ ] Keep hero image optimized and correctly sized
- [ ] Use `loading="lazy"` for non-hero visuals
- [ ] Compress images before deployment (Squoosh/TinyPNG)
- [ ] Run Lighthouse checks for mobile and desktop
- [ ] Preload only critical assets

## Suggested Validation Tools

- Lighthouse (Chrome DevTools)
- WAVE accessibility checker
- Axe DevTools extension
- WebPageTest or PageSpeed Insights

## Short Critique + Improvement Suggestions

### Critique
The case study has strong visual proof and breadth of screens, but storytelling impact improves when every section ties directly to measurable outcomes and explicit design decisions.

### 5 actionable improvements
1. Add one before/after comparison block showing old vs redesigned IA and visual hierarchy.
2. Include one short usability insight quote from a stakeholder or target user.
3. Tie each major design decision to a metric or behavior change in the Results section.
4. Add a mini timeline to show discovery, design, handoff, and launch milestones.
5. Expand product page rationale by showing one deep feature decision and why it mattered.

# Landing Pack — 5 production-ready single-file templates

**Version 1.0.0**

Five landing page templates, each a single self-contained `.html` file. No build step, no dependencies, no external requests — open any file directly in a browser and it works, offline included.

| File | Template | Design language |
|---|---|---|
| `index.html` | Demo hub | Dark gallery linking all five |
| `saas.html` | SaaS product landing ("Meridian") | Clean light, indigo accent |
| `agency.html` | Studio / agency site ("Northbeam Studio") | Dark editorial, serif display type |
| `product.html` | Digital product sales page ("ShipLog") | Warm cream, conversion-focused, sticky buy bar |
| `personal.html` | Personal portfolio ("Alex Chen") | Minimal monochrome, typography-led |
| `waitlist.html` | Product waitlist ("Pulseboard") | Playful animated gradient, centered |

## What's inside each

- **SaaS landing** — sticky nav with mobile hamburger, hero with pure-CSS dashboard mockup, logo strip, 6 feature cards, 3-step how-it-works, 3-tier pricing (featured middle), testimonials, working FAQ accordion (one-open-at-a-time, keyboard accessible), final CTA, 4-column footer.
- **Agency site** — sticky nav, availability badge with pulse animation, services grid, case-study cards with CSS visuals, numbered process, package pricing, full-bleed pull-quote testimonial, contact form (styled, non-functional).
- **Product sales page** — hero with price + CTA and star rating, problem/solution split panels, 4 features with inline SVG icons, changelog-style screenshot mockup, testimonial band, pricing box with guarantee shield, `<details>`-based FAQ, **sticky buy bar** that slides in after the hero.
- **Personal portfolio** — hero with avatar placeholder, skill tags, 3 project rows with hover arrows, experience timeline, highlighted-link contact, footer.
- **Waitlist page** — animated aurora gradient background (respects `prefers-reduced-motion`), email form with validation + fake-submit success state and live counter increment, 3 glass cards.

## How to customize

1. **Colors:** every template defines its palette as CSS custom properties in `:root` at the top of its `<style>` block. Change 3–5 variables and the whole page rebrands.
2. **Names and copy:** all content is realistic fictional copy (no lorem ipsum) — find-and-replace the fictional brand ("Meridian", "Northbeam Studio", "ShipLog", "Alex Chen", "Pulseboard") with yours.
3. **Sections:** each section is a self-contained `<section>` / `<header>` / `<footer>` block; delete what you don't need, the CSS is written to survive it.
4. **Forms:** forms are styled but non-functional (demo submit only in `waitlist.html`). Point them at your form backend or remove them.

## Responsive & accessibility notes

- Designed at 375px, 768px, and 1440px breakpoints; mobile hamburger menus on templates with nav bars.
- FAQ accordions are button-driven and keyboard focusable; mobile menus use `aria-expanded`; the waitlist form uses a `role="status"` live region and labels its input.

## License

Buyers may use these templates for unlimited personal and commercial projects. Reselling or redistributing the templates themselves (as-is or modified) is not permitted.

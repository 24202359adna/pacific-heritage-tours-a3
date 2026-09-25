# Pacific Heritage Tours  
**IS229 – Web Design | Assessment 3**  
**Student:** Adriel NARIA  
**Course:** BBIT/2  
**Student ID:** 24202359  

---

## Project Description

A fully responsive multi-page website for **Pacific Heritage Tours**, a fictional tourism service offering authentic cultural and nature experiences in the Pacific region (with focus on Papua New Guinea).

This Assessment 3 submission **extends** the Assessment 2 website into a professionally styled, maintainable and responsive experience using pure HTML5 + CSS3 (no frameworks).

**Target audience:** Independent travellers, couples, families with older children, small groups, and educators seeking respectful cultural tourism.

---

## Pages

| Page | File | Purpose |
|------|------|---------|
| Home | `index.html` | Hero with background image, value cards, featured experiences |
| About | `about.html` | Story, values (card grid), partners, audience |
| Tours | `tours.html` | Detailed tour cards + indicative schedule table |
| Gallery | `gallery.html` | Responsive photo gallery (CSS Grid auto-fit) |
| Contact & Booking | `contact.html` | Full booking/enquiry form with validation & ARIA live region |

---

## Technologies & Techniques Used

- **HTML5** – full semantic structure, accessibility landmarks, ARIA
- **CSS3** – external stylesheet only, organised with CSS custom properties
- **Flexbox** – header/navigation, card internal layout, form alignment, footer
- **CSS Grid** – hero, card grids (`auto-fit` + `minmax`), gallery, footer columns
- **Media queries** – mobile-first responsive architecture
- **Flexible units** – `rem`, `%`, `fr`, `minmax()`, `clamp()`
- **Background image** + `background-blend-mode: overlay`
- **Responsive images** – `max-width: 100%`, aspect-ratio handling
- **Vanilla JavaScript** – minimal (form feedback only)
- **Git + GitHub** – version control and publication

**Not used:** Bootstrap, Tailwind, any CSS framework, downloaded themes or page builders.

---

## Design System Highlights

- Coherent Pacific-inspired colour palette (deep ocean teal + warm sunset accent)
- Modular type scale and spacing system via CSS variables
- Consistent cards, buttons, forms and focus states
- Visible `:focus-visible` outlines for keyboard users
- Sticky header + skip link
- Hero background image with gradient overlay and blend mode

---

## Responsive Behaviour

- **Mobile (< 768px)**: Single-column layouts, stacked navigation, full-width cards
- **Tablet (768px+)**: Multi-column card grids begin to appear, footer becomes 3-column
- **Desktop (1024px+)**: Enhanced hero layout, refined spacing and navigation

Structure changes at breakpoints (not merely scaled).

---

## How to View Locally

1. Clone or download this repository.
2. Open `index.html` in a modern browser, **or**
3. Use a local server (recommended):

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`

---

## Published Website

- **Live URL:** *(https://24202359adna.github.io/pacific-heritage-tours-a3/)*
- **Repository:** *(https://github.com/24202359adna/pacific-heritage-tours-a3)s*

*(Update these links after you push the Assessment 3 changes.)*

---

## Accessibility Features

- Skip-to-main-content link on every page
- Consistent navigation with `aria-current="page"`
- Logical heading hierarchy (one `<h1>` per page)
- Meaningful alt text and link text
- Properly labelled form controls + HTML5 validation
- ARIA live region for form feedback
- Visible focus states (`:focus-visible`)
- Sufficient colour contrast
- `lang="en"` on the root element

---

## Testing Evidence

- Tested in Chrome, Firefox and Edge
- Responsive testing at 375px, 768px, 1024px and 1440px viewports
- Keyboard navigation verified
- Form validation and live region tested
- Screenshots of mobile / tablet / desktop views should be included in the repository or submitted separately

---

## AI Use Declaration

- AI tools used: Grok (xAI)

- Purpose: CSS architecture suggestions, responsive layout patterns, design system structure, background image integration, code organisation and README drafting
- Student responsibility: All final design decisions, content, testing, refinements and submission remain my own work. I understand every part of the code and can explain the Flexbox, Grid, responsive techniques and background-blend-mode used.

---

## Development Notes (Assessment 3)

This site builds directly on the Assessment 2 structure and content. Major Assessment 3 additions:

- Complete visual design system (CSS variables)
- Professional typography, spacing and colour
- Meaningful Flexbox (navigation, cards, footer)
- Sophisticated CSS Grid (auto-fit card grids, gallery, hero)
- Full responsive architecture with media queries
- Hero background image with gradient overlay + `background-blend-mode`
- Polished forms, buttons, focus states and accessibility
- Organised, maintainable external CSS

---

*IS229 Web Design – Assessment 3 (2026)*

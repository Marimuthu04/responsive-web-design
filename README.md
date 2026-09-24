# Responsive Web Design - TechNova 

A responsive webpage built from scratch with semantic HTML5 and CSS3 (Grid, Flexbox, media queries, fluid images).

## Files
- `index.html` - semantic page structure
- `style.css` - styles and responsive rules
- `images/` - local SVG images (work offline)

## Methods Used
- Mobile-first CSS with `min-width` media queries at 600px, 768px and 1024px
- CSS Grid for cards and gallery; Flexbox for header and form
- Fluid images (`max-width: 100%`, `aspect-ratio`, `object-fit`)
- Relative units (`rem`) and `clamp()` for fluid typography
- CSS-only hamburger menu using a checkbox toggle

## Layout Adjustments
| Viewport | Features grid | Gallery grid | Navigation | Hero |
|---|---|---|---|---|
| Below 600px (phone) | 1 column | 1 column | Hamburger | Stacked |
| 600px+ (tablet) | 2 columns | 2 columns | Hamburger | Stacked |
| 768px+ | 2 columns | 2 columns | Horizontal | Side by side |
| 1024px+ (desktop) | 4 columns | 3 columns | Horizontal | Side by side |

## Testing
Tested using browser DevTools device mode (phone, tablet, desktop) and manual window resizing.

## Challenges and Solutions
- Mobile menu without JavaScript: solved with the checkbox toggle technique.
- Image overflow: solved with fluid image rules and `object-fit: cover`.
- Choosing breakpoints: based on where the content looks cramped, not specific devices.

## How to Run
Open `index.html` in any modern browser.

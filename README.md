# Product Card UI

A responsive, single-component product card built with pure HTML and CSS — no frameworks, no JavaScript. Designed as a hands-on exercise for practicing layout composition, hover interactions, and visual hierarchy in CSS.

## Preview

A clean e-commerce style card featuring a product image, category tag, star rating, discounted pricing, and a call-to-action button.

## Features

- **Image badge overlay** — "New" tag positioned absolutely over the product image
- **Discount pricing** — current price paired with a struck-through original price
- **Star rating display** — simple, dependency-free rating indicator
- **Hover animation** — subtle lift and shadow effect on card hover
- **Responsive-ready** — fixed-width card that adapts cleanly inside flex/grid layouts

## Tech Stack

- HTML5
- CSS3 (Flexbox, `object-fit`, `position` layering, transitions)

## Project Structure

```
product-card/
├── index.html
├── style.css
└── README.md
```

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/diro25/product-card.git
   ```
2. Open `index.html` in your browser — no build steps or dependencies required.

## Concepts Practiced

- Semantic HTML structure
- CSS positioning (`relative` / `absolute`) for badge overlays
- `object-fit: cover` for consistent image cropping
- Transitions and hover states for micro-interactions
- Typography and spacing hierarchy

## Author

**Diriba** — [GitHub @diro25](https://github.com/diro25)

## License

This project is open source and available under the [MIT License](LICENSE).

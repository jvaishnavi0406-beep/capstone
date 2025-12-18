# Fashionista — Shop 🛍️

A modern, responsive fashion e‑commerce landing page built using only HTML and CSS. It showcases a hero sale banner, product categories, a product grid, best sellers, testimonials, filters UI, and a newsletter section. [web:17][web:20]

## Features

- Hero banner highlighting a seasonal sale with a bold call-to-action button.
- Product filters sidebar for category, price range, and color options (UI only).
- Category chips/cards for Men, Women, and Accessories.
- Product grid with cards for jackets, sneakers, dresses, and handbags.
- Best Sellers section reusing the same card layout.
- Customer testimonials with profile images and quotes.
- Newsletter subscription call-to-action.
- Responsive layout using CSS Grid and Flexbox for desktop and mobile. [web:14][web:21]

## Tech Stack

- HTML5 (semantic structure, accessibility attributes like `aria-label`, `role`).
- CSS3 with custom properties (`:root` variables) for colors, radii, and shadows.
- Google Fonts: Inter and Playfair Display for clean typography. [web:13]

## Project Structure

.
├── index.html # Main page (Fashionista shop UI)
├── stylesheet.css # Styles for layout, components, and responsiveness
└── README.md # Project documentation

text

## Getting Started

1. Download or clone the project folder.
2. Make sure `index.html` and `stylesheet.css` are in the same directory.
3. Open `index.html` in your browser (double-click or use Live Server in VS Code). [web:12][web:18]
4. Adjust content (text, prices) directly in `index.html` if needed.

## Customization

- **Change images:** Replace the `src` URLs of `<img>` tags or the `background-image` in the `.hero .left` inline style with your own links or local images.
- **Change colors:** Edit the CSS variables in `stylesheet.css` under the `:root` selector (e.g. `--accent`, `--bg`, `--dark`).
- **Change fonts:** Update or replace the Google Fonts link in the `<head>` of `index.html`. 

## Limitations

- This is a **static frontend demo**: filters, cart, login, and subscribe buttons are **not wired** to any backend or JavaScript.
- No real authentication, payments, or product database. [web:21]

## License

This project is for learning and personal use. Replace external images and brand name with your own assets if you plan to publish or use commercially, and always respect image license terms from providers like Pexels or Unsplash.

# Cara Mall - E-Commerce Frontend

[![Live Site](https://img.shields.io/badge/Live%20Site-Visit%20Now-2ea44f?style=for-the-badge&logo=google-chrome&logoColor=white)](https://shivamverma30.github.io/carakart.github.io/)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

A responsive multi-page e-commerce website built with HTML, CSS, and JavaScript. This project showcases a complete storefront-style UI including a homepage, product listing, single product view, blog, about, contact, and cart pages.

## Live Demo

- https://shivamverma30.github.io/carakart.github.io/

## Overview

Cara Mall is a static frontend project designed to practice and demonstrate:

- Modern layout structuring with semantic HTML
- Responsive styling with CSS
- Basic DOM interactions using vanilla JavaScript
- Multi-page website navigation and consistent UI components

## Tech Stack

- HTML5
- CSS3
- JavaScript (Vanilla)
- Font Awesome (CDN)
- Google Fonts (Spartan)

## Key Features

- Sticky navigation header with desktop and mobile navigation behavior
- Responsive homepage hero, feature cards, banners, and product grids
- Shop page with product cards and links to single product page
- Single product page with gallery thumbnail switching
- Blog listing layout with article cards
- About page with brand story and promo video section
- Contact page with map embed and message form layout
- Cart page with product table, coupon block, and subtotal summary
- Shared newsletter and footer sections across pages

## Project Structure

```
carakart.github.io/
|- index.html
|- shop.html
|- sproduct.html
|- blog.html
|- about.html
|- contact.html
|- card.html
|- style.css
|- script.js
`- img/
   |- about/
   |- banner/
   |- blog/
   |- features/
   |- pay/
   |- people/
   `- products/
```

## Getting Started

1. Clone or download this repository.
2. Open the project folder.
3. Run any static server or open `index.html` directly in your browser.

### Option A: Open Directly

- Double-click `index.html` to launch the website.

### Option B: Use VS Code Live Server

1. Install the Live Server extension in VS Code.
2. Right-click `index.html`.
3. Select "Open with Live Server".

## Pages

- `index.html`: Home page with hero, featured products, banners, and arrivals
- `shop.html`: Product listing page
- `sproduct.html`: Single product details and image switcher
- `blog.html`: Blog/case study listing page
- `about.html`: About section, brand information, and app video
- `contact.html`: Contact details, map, and message form
- `card.html`: Cart view, coupon form, and totals section

## Customization

To customize content and branding:

- Update product text, prices, and images directly in HTML files
- Edit color palette, spacing, and responsive behavior in `style.css`
- Extend mobile menu and interaction logic in `script.js`
- Replace media under `img/` with your own assets while keeping paths consistent

## Deployment

This project is ready for static hosting platforms, including:

- GitHub Pages
- Netlify
- Vercel (static mode)

For GitHub Pages:

1. Push the project to a GitHub repository.
2. Go to repository Settings -> Pages.
3. Select the main branch and root folder.
4. Save and wait for the site URL to be published.

## Notes

- This is a frontend-only project. Cart, form submissions, authentication, and payment are currently UI-only.
- To make it production-ready, connect backend APIs and add form/cart persistence.

## Author

Created by Shivam Verma.

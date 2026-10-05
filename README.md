# EcoMart | Static E-Commerce Website Prototype

> **Academic Notice:** This project is a fictional e-commerce website developed as part of the **Introduction to Information Systems (CC4057NI / CC4058NI)** module at **Islington College** (affiliated with London Metropolitan University). It is an academic prototype created to demonstrate responsive web design, semantic HTML, CSS layout systems, and client-side JavaScript interactivity. It does not process real transactions or store live customer information.

---

## Overview

- **Author:** Om Dangol
- **Role:** Web Development Student / Coursework Project
- **Stack:** HTML5, CSS3, Vanilla JavaScript
- **Design Artifacts:** Included Wireframes (Homepage, Products, Blog, Contact, Research)
- **Deployment:** Zero dependencies; runs directly in any modern browser

---

## Features

### 1. Multi-Page Architecture
- **Home:** Hero promotion rotator, featured categories, and quick-add action triggers.
- **Products Catalog:** Dynamic product filtering by category, search bar, and grid presentation.
- **Product Detail:** Dynamic parameter-driven view showing pricing, sustainability ratings, and cart controls.
- **Shopping Cart:** Client-side cart state with quantity increment/decrement, subtotal recalculation, and simulated checkout.
- **Research & Blog:** Analysis of sustainable commerce and environmental benchmarks.
- **About Us & Team:** Member biographies, contact forms, and module deliverables.

### 2. Client-Side Interactivity
- Interactive cart drawer and persistent cart state using browser `localStorage`.
- Dynamic DOM manipulation for product sorting and filtering without page reloads.
- Client-side form input validation for feedback and inquiry submissions.
- Responsive mobile navigation toggle.

### 3. Responsive Layout & Design System
- Custom CSS styling featuring CSS Grid and Flexbox layouts.
- Adaptive typography and media queries tested across desktop, tablet, and mobile breakpoints.
- Custom wireframes documenting the layout planning phase (`Eco-mart-website/src/wireframes/`).

---

## Project Structure

```
eco-friendly-awareness-mart-website/
├── .gitignore
├── README.md
└── Eco-mart-website/
    └── src/
        ├── webwork/
        │   ├── index.html            # Main storefront homepage
        │   ├── css/
        │   │   └── style.css         # Complete site stylesheet
        │   ├── js/
        │   │   ├── cart.js           # Cart business logic
        │   │   ├── cart-page.js      # Cart table DOM renderer
        │   │   ├── data.js           # Product catalog data objects
        │   │   ├── hero-rotator.js   # Banner slider component
        │   │   └── products-page.js  # Filter & search controller
        │   ├── pages/                # Sub-pages (about, blog, cart, products)
        │   └── images/               # Product photography and banners
        └── wireframes/               # Original layout design sketches
```

---

## Quick Start

### Prerequisites
A modern web browser (Chrome, Firefox, Safari, Edge). No compilers or package managers required.

### Running Locally

```bash
# Clone the repository
git clone https://github.com/omwe77/eco-friendly-awareness-mart-website.git
cd eco-friendly-awareness-mart-website

# Option 1: Open directly in your default browser
# (On Windows):
start Eco-mart-website/src/webwork/index.html

# Option 2: Serve via Python HTTP server
python -m http.server 8000 --directory Eco-mart-website/src/webwork
# Then navigate to: http://localhost:8000
```

---

## Known Limitations

- **Backend:** Static prototype; lacks a database or payment gateway integration.
- **Authentication:** No server-side session management or user logins.

---

## License

Academic coursework project for Islington College / London Metropolitan University. Open for educational review.

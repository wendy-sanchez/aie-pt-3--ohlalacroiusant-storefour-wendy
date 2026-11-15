# Ohlala Croisant Storefour

A responsive e-commerce storefront prototype built with HTML, CSS, and JavaScript. The project explores the structure and interactions of an online store, including product browsing, category filtering, shopping cart management, and a multi-step checkout interface.

## Overview

Ohlala Croisant Storefour is a collaborative academic web development project based on a customizable online store concept.

The repository contains several storefront pages and interactive frontend components. The current catalog includes fashion-oriented sample categories, while other parts of the interface retain the original Croisant Storefour branding. The project is therefore documented as a general storefront prototype rather than a fully integrated production shop.

## Features

- **Homepage:** Main storefront layout and navigation.
- **Product catalog:** Product cards organized by category.
- **Category filtering:** Filter catalog items by category, including footwear, shirts, trousers, and accessories.
- **Shopping cart:** Add products, increase quantities, update item quantities, and remove products.
- **Cart persistence:** Store cart data in browser `localStorage`.
- **Cart summary:** Display item quantities, line totals, and subtotal.
- **Product detail page:** Dedicated product presentation with a quantity field and add-to-cart interface.
- **Multi-step checkout interface:** Three-step flow for personal information, delivery address, and card details.
- **Form validation:** Client-side validation for required checkout fields and basic card-format checks.
- **Contact page:** Contact form layout for inquiries and special requests.
- **Reusable layout components:** Shared navigation and footer elements.

## Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Page structure and content |
| CSS3 | Custom styling and responsive layouts |
| JavaScript | Shopping cart, catalog filtering, checkout interactions, and navigation |
| Tailwind CSS 4 | Utility-first styling through the browser CDN |
| Alpine.js | Lightweight declarative frontend interactions |
| Python | Local development server |
| Flask | Serves the static website during development |

## Project Structure

```text
aie-pt-3--ohlalacroiusant-storefour-wendy/
├── components/
│   └── layout-components.js
├── index.html
├── catalogo.html
├── carrito.html
├── carrito.js
├── product.html
├── product.css
├── contact.html
├── app.js
├── script.js
├── styles.css
├── server.py
├── README.md
└── README.es.md
```

## Getting Started

### Prerequisites

- Python 3
- pip
- A modern web browser

### Installation

1. Clone or download the repository.
2. Open a terminal in the project directory.
3. Install Flask:

   ```bash
   pip install flask
   ```

### Run the application

Start the local development server:

```bash
python server.py
```

Open the following address in your browser:

```text
http://localhost:3000
```

## Usage

1. Open the homepage to explore the storefront.
2. Navigate to the catalog to browse products.
3. Use the category buttons to filter the available items.
4. Add products to the shopping cart.
5. Open the cart to change quantities or remove products.
6. Review the checkout interface and move through its steps.
7. Use the contact page to explore the inquiry form.

## Project Scope and Limitations

This repository represents a frontend-oriented academic prototype. Some elements are interface demonstrations rather than complete e-commerce services.

- The shopping cart uses browser `localStorage` and does not rely on a backend database.
- The checkout validates form fields in the browser and displays a confirmation message. It does not connect to a payment gateway or process real transactions.
- The personal-information step is intentionally left as a placeholder.
- The contact form is presented as a frontend interface; no message-delivery backend is configured.
- Product and brand content is not fully consistent across all pages and should be considered sample project content.

## Team Project

This project was developed collaboratively as part of an academic web development assignment.

It provided practical experience with multi-page website structure, frontend interactions, DOM manipulation, browser storage, reusable components, and collaborative development.

---

**Project type:** Collaborative project  
**Status:** Frontend e-commerce prototype

# Brew Haven Coffee Shop Website

A responsive website for Brew Haven Coffee Shop - Freshly brewed happiness every day!

## Project Overview
Brew Haven is a 5-page static website built with HTML, CSS, and JavaScript. It showcases our coffee menu, story, and allows customers to enquire and contact us.

## Pages
1. **index.html** - Home page with welcome message and popular brews
2. **about.html** - Our story and values
3. **products.html** - Full menu (Espresso Bar, Lattes & Specials, Fresh Pastries)
4. **enquiry.html** - Enquiry form
5. **contact.html** - Location and contact details

## Features

### 1. Responsive Design
- Works on mobile, tablet, and desktop
- Grid layout: 3 columns (desktop), 2 columns (tablet), 1 column (mobile)
- Media queries at 768px and 480px

### 2. Navigation
- Highlighted current page using `aria-current="page"`
- Hover and focus states for accessibility

### 3. NEW: Live Search with Options
Added on `index.html` and `products.html`:

- **Text search:** Type e.g. "latte", "espresso", "croissant" - filters instantly
- **Dropdown filter:** All Items / Espresso Bar / Lattes / Pastries
- **Quick filter buttons:** All / Espresso Bar / Lattes / Pastries
- **Feedback message:** Shows "No items match your search" if no results
- **How it works:**
  ```javascript
    - Uses querySelector for #product-search, #search-filter, .services-card
    - Listens for input and change events
    - Filters cards by text content and data-category
    - Uses hidden attribute to hide non-matching cards

    https://github.com/projet254/WEDE-PROJECT1.git
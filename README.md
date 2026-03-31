# World Travel

A responsive, multi-page travel agency website built with HTML, CSS, JavaScript, jQuery UI, and Font Awesome. The project presents travel destinations, contact information, and a reservation overview in a clear user journey for people exploring and comparing vacation options.

## Business Problem Solved

Travel agencies need a simple digital storefront that helps customers quickly understand available destinations, compare packages, and find a way to contact or reserve a trip. This project solves that problem by combining destination discovery, package promotion, reservation information, and contact access in one lightweight website.

The site is designed for users who want to:

- Explore popular travel destinations visually.
- Compare featured travel packages by duration, location, group size, rating, and price.
- Search travel options using resort style, destination, check-in, and check-out inputs.
- View planned trips and booking statuses in a structured reservation table.
- Contact the agency or download a travel plan document.

## Technical Architecture

This is a static front-end project organized around separate pages and shared assets.

```text
Travel/
├── index.html                    # Main landing page and travel package showcase
├── style/
│   ├── style.css                 # Main page styles, layout, components, variables
│   └── responsive.css            # Responsive behavior for desktop, tablet, and mobile
├── script/
│   └── script.js                 # Sticky navbar behavior and jQuery UI datepickers
├── subPages/
│   ├── rrethNesh.html            # About page
│   ├── contactUs.html            # Contact page and contact form UI
│   ├── rezervimet.html           # Reservation table and PDF download link
│   └── subPages.css              # Shared subpage styling
├── Foto/                         # Images, logo, destination, and package assets
└── World_Travel_Planet_e_Udhetimit.pdf
```

### Architecture Highlights

- **Static multi-page structure:** Each core user flow has its own HTML page for straightforward navigation and maintainability.
- **Reusable visual language:** The main and subpage styles share layout patterns, colors, buttons, navigation, and footer structure.
- **Responsive navigation:** A checkbox-based mobile menu switches between desktop links and a compact mobile menu.
- **Light JavaScript layer:** JavaScript is used only where interactivity is needed: scroll-based navbar styling and date picker inputs.
- **External UI libraries:** jQuery UI powers date selection, while Font Awesome provides consistent icons across navigation, packages, contact details, and footer links.

## Key Features

- Responsive homepage with travel agency branding and hero search interface.
- Resort style selector, destination field, and check-in/check-out date inputs.
- Popular destination grid featuring Paris, Rome, Kyoto, Dubai, New York, and Istanbul.
- Featured package cards with images, duration, pax count, location, reviews, ratings, price, and call-to-action buttons.
- About section explaining the agency mission and travel value proposition.
- Newsletter signup UI for travel offers and updates.
- Dedicated About page with agency description and contact call-to-action.
- Dedicated Contact page with phone, email, location details, and message form layout.
- Dedicated Reservations page with tabular trip plans, booking status labels, prices, and PDF download.
- Consistent footer with social links, company links, service links, and support navigation.
- Mobile-friendly layout using media queries.

## Technologies Used

- **HTML5** for page structure and semantic content sections.
- **CSS3** for custom layout, responsive design, visual styling, buttons, cards, tables, and navigation.
- **JavaScript** for dynamic navbar behavior.
- **jQuery 3.7.1** for DOM-ready behavior.
- **jQuery UI 1.14.1** for date picker components.
- **Font Awesome 6.7.2** for icons.
- **Google Fonts** for typography.

## Challenges Solved

- **Responsive navigation:** Built a mobile menu without a heavy framework by using a checkbox toggle, icons, CSS transitions, and media queries.
- **Multi-section homepage layout:** Combined a hero search area, destination cards, travel packages, about content, newsletter signup, and footer into one cohesive page.
- **Travel package presentation:** Designed package cards that communicate important booking information quickly: duration, location, capacity, ratings, and price.
- **Reservation data readability:** Structured travel plans in a table with status badges so users can scan booking state and pricing easily.
- **Interactive date selection:** Integrated jQuery UI datepickers to make check-in and check-out inputs easier to use.

## What I Learned

- How to structure a multi-page front-end project with shared assets and consistent navigation.
- How to build responsive layouts with CSS media queries for desktop, tablet, and mobile screens.
- How to combine HTML, CSS, JavaScript, and third-party libraries in a static website.
- How to use reusable UI patterns such as cards, tables, buttons, forms, and footer sections.
- How to improve user experience with small interactions, including sticky navbar styling and date picker inputs.


## How to Run Locally

No build step is required.

1. Clone or download the repository.
2. Open `index.html` in a browser.
3. Use the navigation links to visit the About, Contact, and Reservations pages.

Because the project uses CDN links for jQuery, jQuery UI, Font Awesome, and Google Fonts, an internet connection is recommended for the full visual and interactive experience.

## Project Status

This project is a front-end prototype focused on layout, responsive design, and user experience for a travel agency website. Future improvements could include real form submission, package filtering, backend reservation storage, validation, and deployment.

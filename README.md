Myntra Clone 🚀

A responsive clone of Myntra.com, India's premier fashion e-commerce site, featuring product browsing, cart, wishlist, and search.

🏗️ Architecture

The flow of the system:

Browser (Client)

Loads static assets (HTML/CSS/JS).

Handles user interactions (search, filters, cart).

Updates UI dynamically via JavaScript DOM.

↓

Frontend Modules

Product Catalog Service (renders grids, filters).

Cart & Wishlist Manager (localStorage persistence).

Search & Navigation Handler (real-time filtering).

↓

Asset & Data Layer

Static JSON/API mocks for products (brands, prices).

CSS Grid/Flexbox for responsive layouts.

localStorage for state (cart items).

↓

JavaScript Event Bus

Dispatches events (addToCart, filterProducts).

Pub/Sub pattern for UI updates (no backend needed).

Decouples components for scalability.

↓

Responsive Renderer

Media queries for mobile/desktop views.

Pushes UI updates to browser (smooth animations).

Prepares for future API integration (fetch products).


Tech Stack
- Frontend: HTML, CSS, JavaScript (or React/Tailwind)
- Tools: GitHub, Netlify/Vercel for deployment


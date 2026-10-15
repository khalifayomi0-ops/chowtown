# ChowTown Frontend Demo

A static, frontend-only food delivery website for ChowTown. No backend, real authentication, GPS tracking, or payment gateway is connected.

## Files
- `index.html` — customer-facing website structure
- `style.css` — responsive styling
- `script.js` — mock menu, cart, checkout, demo order tracking, and admin preview interactions

## Run locally
Open `index.html` in a modern browser. For best results, serve the folder using a local static server (for example, VS Code Live Server).

## Demo functionality
- Search and category filters
- Product customisation, variants, extras, and cart
- Demo voucher `TOWN10`
- Delivery address form with an explicitly simulated location option
- Demo checkout and locally stored orders
- Demo order tracking
- Small admin preview accessible from the footer
- Local menu availability toggles and order status changes
- Local storage persistence

## Important
All order, customer, delivery, payment, and admin features are demonstrations. No real order is sent, no payment is processed, and no secure admin authentication exists. Do not use this version to accept real customer orders. Before launch, connect a backend with server-side authentication/authorization, database-backed orders and menu data, validated pricing, payment gateway verification, privacy controls, and actual delivery integrations.

## Branding
The current design uses ChowTown and a warm orange/cream/charcoal palette. Replace placeholder business details and verify product photography, food descriptions, pricing, fees, and availability before public launch.


## ChowTown brand update
The official logo is stored at `assets/chowtown-logo.png`. The interface uses deep green (`#00854A`), red (`#FF171D`), white, and charcoal; lime green is intentionally not used as a UI accent. Additional hover, floating-card, hero-motion, and reduced-motion accessibility styles are included.

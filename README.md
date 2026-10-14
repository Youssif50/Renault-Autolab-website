# Renault Autolab

A responsive multi-page website prototype for a fictional independent Renault service center. The project uses HTML5, CSS3, Bootstrap 5.3, Bootstrap Icons, and vanilla JavaScript. It makes no claim of Renault ownership, authorization, or partnership.

## Live demo

Not deployed yet. The intended GitHub Pages URL will be `https://Youssif50.github.io/renault-autolab/` once the public repository and Pages deployment are configured.

## Features

- Responsive home, service, booking, membership, shop, cart, checkout, about, and contact pages.
- Service and product search/sorting, date and form validation, and an interactive demo booking flow.
- Browser-local cart persistence, quantity updates, sample coupon, and demo checkout confirmation.
- Shared navigation and footer, accessible labels and focus states, reduced-motion support, and responsive Bootstrap layout.
- Fictional business details, sample pricing, statistics, and testimonials are identified as demonstration content.

## Technologies

HTML5, CSS3, Bootstrap 5.3, Bootstrap Icons, and vanilla JavaScript. Bootstrap, icons, Google Fonts, and remote photo URLs are CDN resources; no build tools or backend are required.

## Local preview

Open `index.html` directly in a current browser, or serve this directory using a static file server. The site is static and works without a backend. An internet connection is needed for CDN styling/icons/fonts and remote photography.

## Run locally

Open `index.html` in a modern browser, or serve this directory with a simple static server. No build step or package installation is needed. Bootstrap, Bootstrap Icons, Google Fonts, and photo fallbacks use CDN/image URLs, so an internet connection improves their appearance; the content remains laid out if those resources are unavailable.

## Pages and files

- `index.html`: home, quick booking, services overview, plans, sample products, and FAQ.
- `services.html`, `booking.html`, `memberships.html`, `shop.html`, `cart.html`, `checkout.html`, `about.html`, `contact.html`: supporting pages.
- `css/style.css`: shared design system and responsive styles.
- `js/main.js`: shared header/footer, local storage helpers, toast messages, quick booking, date limits, and back-to-top.
- `js/services.js`, `js/booking.js`, `js/memberships.js`, `js/shop.js`, `js/cart.js`: page-specific interactions and demo data.
- `images/`: favicon. Other photos are referenced by remote URLs as image fallbacks; replace them with licensed local files as needed.

## Editing the demo

Edit service names and sample starting prices in `js/services.js`; edit sample catalog items and prices in `js/shop.js`; edit plans in `js/memberships.js`. Main copy is in the relevant HTML page. Replace the remote image URLs in `js/shop.js`, `css/style.css`, and `about.html` to use local, appropriately licensed images. No image was downloaded or generated for this prototype.

## Demo behavior and limits

- Booking requests are validated and stored in browser localStorage; the booking is not sent to a workshop.
- Products, quantity changes, cart badge, sample `AUTOLAB10` coupon (10% off), and demo checkout confirmation work in the browser. No payment information is collected and no order is placed.
- Membership selection and newsletter/contact forms show demo feedback only. No subscription, enrollment, or message is sent.
- Local storage is only a convenience for this prototype, not a secure database. Clearing browser data removes the saved demo state.
- Real appointment scheduling, inventory, customer accounts, subscriptions, messaging, order processing, and payments require a secure backend and appropriate external services.
- All contact information, prices, statistics, plans, and testimonials are fictional sample content.

## Accessibility and responsive design

The site uses semantic landmarks, labels, visible focus styling, keyboard-operable Bootstrap navigation and accordions, minimum date validation, and `prefers-reduced-motion` support. Test responsive layouts in a browser at mobile, tablet, laptop, and desktop widths.

## Screenshots

No screenshots are currently included.


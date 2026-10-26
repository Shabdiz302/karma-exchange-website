# Karma Exchange website

Persian gold jewellery and accessories, 231a Nether Street, London N3 1NT.

A static site: `index.html` plus images in `img/`. No build step.

## Hosting

Deployed on Netlify from the `main` branch (publish directory: the repository root, set in `netlify.toml`).
Every push to `main` goes live automatically.

## Editing products

Products are listed in the `items` array near the top of the script in `index.html`
(code, name, Farsi name, category, price, sale price, photo).

## Online payment

`ONLINE_CHECKOUT` in `index.html` controls checkout. Until a payment provider is connected,
"Place order" gives the customer a ready-written order to send by email or WhatsApp,
and the shop replies with a secure payment link.

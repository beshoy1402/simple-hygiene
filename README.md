# Simple Hygiene

A responsive, front-end demo storefront for hygiene products. Built as a single-file website with plain HTML, CSS, and JavaScript.

## Run it

Open [index.html](./index.html) in a browser, or enable GitHub Pages:

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Choose **main** and **/(root)**, then save.
4. After GitHub Pages finishes deploying, the site will be available at:

   https://beshoy1402.github.io/simple-hygiene/

## Demo features

- Customer and worker account flows
- Product catalogue, category filters, search, cart, and demo checkout
- Customer order history and order status
- Worker order management and product inventory controls
- Responsive mobile layout and navigation
- Demo accounts and orders are stored in the current browser using localStorage

## Important demo limitations

- This is a front-end prototype. It does not connect to a production database or server.
- Passwords and demo accounts are stored locally in the browser. Do not enter real or reused passwords.
- The Google button is a visual demo only. Google OAuth is not configured.
- Checkout does not collect payment or arrange delivery.
- The worker role selector is for testing only. A real launch must enforce worker permissions on a trusted backend.
- Browser-local data does not sync between devices and can be cleared by the browser.

## Production checklist

Before accepting real customers, connect secure authentication (including Google OAuth if needed), a database, server-side role permissions, inventory/order APIs, payment processing, and delivery workflows.

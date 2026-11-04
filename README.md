# ProductHub — Product Pricing and Canvas Form Request Information System

A beginner-friendly, responsive front-end prototype built with HTML, CSS, and vanilla JavaScript.

## Features
- Dashboard with sample summary cards
- Product catalog with search, category filter, sorting, and details modal
- Compare up to four products and highlight the lowest sample price
- Canvas form request submission and demo statuses
- Shopping basket with quantity controls and order history
- Demo login and editable profile
- Responsive sidebar and mobile layout
- Browser-local demo storage using `localStorage`

## How to run in Visual Studio Code
1. Extract `product-pricing-system.zip`.
2. Open the extracted `product-pricing-system` folder in Visual Studio Code.
3. Install the **Live Server** extension (optional but convenient).
4. Right-click `index.html` and select **Open with Live Server**. You can also open `index.html` directly in your browser.
5. Use the sidebar to navigate between pages.

## Demo notes
- Login is not secure authentication. Any non-empty username/email and password will pass.
- Profile, comparison list, basket, requests, and orders are saved only in the current browser's `localStorage`.
- No payment is collected. Product images load from remote Unsplash URLs, so internet access is needed for those images.
- `Canvas form` is currently represented as a product request form. Adjust the fields and workflow to match your instructor's exact definition of a canvas form.

## Before real deployment
Use a backend (for example PHP or Node.js) and a database (for example MySQL) for secure authentication, shared product inventory, role-based access, and permanent order/request records. Never store real passwords in browser storage.

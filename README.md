# 🛒 Shopify Product Page Upsell Widget

This widget displays **related upsell products** on a Shopify product page using the product’s first collection. Customers can add related items directly to their cart without leaving the page.

Dawn theme

![Screenshot 2025-04-08 163103](https://github.com/user-attachments/assets/42062284-4ba3-4c87-9d8a-ca6618b4d34d)


## 🔧 Features

- Displays upsell products from the same collection (excluding the current product)
- Limit the number of products shown using a customizable `upsell_limit`
- Responsive **carousel** layout using Slick.js
- Handles both single-variant and multi-variant products
- AJAX-based **Add to Cart** with cart drawer refresh
- Shows a success message after adding an upsell product

## 💡 Customization

- `upsell_heading` and `upsell_limit` can be defined through theme settings
- CSS is included for styling the layout and carousel elements
- Integrates smoothly with Shopify’s cart drawer and product page layout

## 📦 Tech Stack

- **Liquid** – Shopify templating
- **JavaScript** – Vanilla + jQuery
- **Slick Carousel** – For product slide functionality
- **Shopify AJAX API** – For adding products to cart via `/cart/add.js`

## 📁 Integration

- Add this widget directly to your `product.liquid` or as a theme snippet.
- Requires Slick Carousel to be loaded in your theme assets.
- Optional: Add theme settings to control `upsell_heading` and `upsell_limit`.

---

Let me know if you'd like a `settings_schema.json` snippet or if you want to refactor this into a Shopify app block or embed snippet.

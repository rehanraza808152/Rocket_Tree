# Project Structure

```
rocket-tree/
├─ index.html               # Home page
├─ products.html            # Products listing page
├─ services.html            # Services listing page
├─ about.html               # About Us page
├─ contact.html             # Contact Us page
├─ cart.html                # Shopping cart page
├─ css/
│   └─ style.css           # Global styles
├─ js/
│   └─ main.js             # Core JavaScript (data loading, cart, WhatsApp)
├─ data/
│   ├─ products.json       # Sample product data
│   └─ services.json       # Sample service data
└─ images/
    ├─ logo.jpg            # Brand logo (replace with your own)
    ├─ hero.jpg            # Hero banner image
    └─ (product & service images)
```

**How to run**
1. Open any of the `.html` files in a browser (e.g., double‑click `index.html`).
2. All pages are linked via the navigation bar.
3. Product and service data are loaded from the JSON files; edit those files to add/remove items.
4. The shopping cart is stored in `localStorage`; it persists across page reloads.
5. Clicking *Order on WhatsApp* opens a pre‑filled WhatsApp message to `+91 8081529714`.

**Customization**
- Replace images in the `images/` folder.
- Update colors, fonts, or other styles in `css/style.css`.
- Modify product/service entries in the JSON files – see the file comments for the schema.

---
*All code is plain HTML, CSS and JavaScript – no build tools required.*

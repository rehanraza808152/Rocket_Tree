# Rocket Tree

A simple, modern, and responsive food ordering website.

## How to run
1. Open the project folder:
   ```
   cd "C:\Users\DELL\Desktop\kapil bhai\rocket-tree"
   ```
2. Open **index.html** in a browser (double‑click or `start index.html`).

## Adding your own images
Create an `images` folder inside the project (already created). Replace the placeholder files with your own high‑quality photos and keep the same filenames:
- `hero1.jpg`, `hero2.jpg` – hero section images.
- `food1.jpg`, `food2.jpg`, `food3.jpg` – food card images.

## Customising menu items
Each food card in **index.html** uses HTML `data-name` and `data-price` attributes. Edit the following sections to change name, price, description or image:
```html
<div class="food-card" data-name="Paneer Butter Masala" data-price="250">
    <img src="images/food1.jpg" alt="Paneer Butter Masala" />
    <h4>Paneer Butter Masala</h4>
    <p class="price">₹250</p>
    <p class="desc">Creamy tomato‑based gravy with soft paneer cubes.</p>
    <button class="btn whatsapp" onclick="orderWhatsApp(this)">Order on WhatsApp</button>
</div>
```

## WhatsApp ordering
The **Order on WhatsApp** button opens a pre‑filled message to:
```
https://wa.me/918081529714?text=Hello%20Rocket%20Tree!%20I%20want%20to%20order:%0AFood%20Name:%20[Food%20Name]%0APrice:%20₹[Price]%0APlease%20confirm%20my%20order.
```
The script automatically inserts the selected food name and price.

---
*Built with plain HTML, CSS and a tiny JavaScript helper – no frameworks, no server required.*

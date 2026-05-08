# Premium Product Search UI ✨

A modern and responsive product search and shopping cart app built using **HTML, CSS, and JavaScript**.  
Users can search products in real-time and manage a fully functional cart — all with zero frameworks.

---

## 🌐 Live Demo

[Click here to view](https://taseen2.github.io/Premium-Search/)

---

## 🚀 Features

- 🔍 Real-time product search
- ⚡ Dynamic filtering using JavaScript
- 🎨 Premium dark UI design
- 🏷️ Discount badge system
- 💰 Automatic discounted price calculation
- 📦 Products loaded from JSON
- 🛒 Shopping cart with add, remove & quantity controls
- ⚠️ Out-of-stock detection — blocks checkout automatically
- 📱 Responsive product grid
- ✨ Smooth animations and hover effects

---

## 📸 Preview

[![Screenshot-2026-05-08-143306.png](https://i.postimg.cc/JnxdrjsC/Screenshot-2026-05-08-143306.png)](https://postimg.cc/TLycQLjt)
[![cart.png](https://i.postimg.cc/mg33WBc0/cart.png)](https://postimg.cc/0zQKpg0f)

---

## ⚙️ How It Works

1. Products are stored inside `products.json`
2. JavaScript fetches the data using Fetch API
3. Products are dynamically rendered on the page using `map()`
4. Search input filters products instantly using `filter()`
5. Cart operations are handled using targeted array methods

---

## 🧠 Concepts Practiced

- DOM Manipulation
- Async / Await
- Fetch API
- Array Methods — `map()`, `filter()`, `some()`, `every()`, `find()`, `findIndex()`
- Template Literals
- Event Listeners
- Regular Expressions

### 🔍 Array Methods in Action

| Method | Used For |
|---|---|
| `map()` | Render every product card from JSON |
| `filter()` | Live search filtering |
| `some()` | Block checkout if any item is out of stock |
| `every()` | Enable checkout only when all items are valid |
| `find()` | Get a product by ID to open in modal |
| `findIndex()` | Remove the exact item from cart by ID |

---

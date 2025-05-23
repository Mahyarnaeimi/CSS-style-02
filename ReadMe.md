# Gradient Text Trail with HTML & CSS

This project demonstrates how to create a **smooth, multi-layered shadow trail** effect behind text using **pure HTML and CSS** (no JavaScript).

It recreates a motion blur or "echo" effect similar to that seen in dynamic graphics or stylized animations — useful for banners, headers, or creative typographic design.

---

## Features

- Trail begins as **dark gray (near black)** and gradually fades into **light gray/white**.
- The effect is made using **stacked `div` layers** with increasing **offsets** and **lightening colors**.
- Fully responsive and works in all modern browsers.
- **No JavaScript required**.

---

## Files

- `index.html` – Contains the HTML structure and embedded CSS styles.
- `README.md` – This explanation file.

---

## How It Works

### Structure

```html
<div class="trail-container">
  <div class="layer layer-8">Hello World!</div>
  <div class="layer layer-7">Hello World!</div>
  ...
  <div class="layer layer-1">Hello World!</div>
  <div class="main">Hello World!</div>
</div>

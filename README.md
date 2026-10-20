# Olive Brand Guide

### ₊⊹ About

Olive is a visual identity project for a botanical skincare brand, deeply inspired by nature and conscious beauty. The visual ecosystem combines a palette of soft, earthy colors, clean typography, and organic photographs to create a fresh, minimalist, and elegant aesthetic. This repository brings together the complete brand guidelines and examples of social media assets, demonstrating how design can convey sustainability and serenity through a cohesive visual experience.

<img width="1440" height="1926" alt="Olive-Brand-Guide" src="https://github.com/user-attachments/assets/38a83ca7-2588-4ed3-8f1b-863d99310485" />

---

### ★ Features

- **Complete Visual Identity:** Development of a visual ecosystem focused on organic minimalism and botanical aesthetics.

- **Color & Typography Systems:** Definition of an earthy color palette (with HEX codes) and standardized typography to ensure brand consistency.

- **Branding Guidelines:** Establishment of strategic keywords to align visual communication with sustainability values.

- **Social Media Templates:** Creation of ready-to-use Instagram layouts (product posts, tips, and interactions) focused on high visual engagement.

---

### ⚙️ Tech Stack

- **HTML5**
- **CSS3**
- **Google Fonts (Montserrat & Garamond)**

---

### 🖿 Project structure

```
olive-brand-guide/
├── assets/
├── index.html
└── style.css
```

---

### .ᐟ.ᐟ How It Works

- `post:not(post-dark)`: acts as an “except” condition—it selects elements that do not have the value inside the parentheses

- Image extending to the corner: `padding: 0` on the slide and the image set to `position: absolute` with `inset: 0`

- `aspect-radio: 4 / 5` with `overflow: hidden`: gives all cards the same portrait format, and large photos are cropped instead of spilling over the screen

- `z-index: 1`: for text, this ensures that “Olive” and the caption appear above the photo

- SVG icons with `stroke: currentColor`: paints the stroke with the button’s color, so to change the color, simply adjust the `color` of `.icon-btn`

- `box-shadow: 0 0 0 100vmax`: creates a solid, unfaded “shadow” that spreads in all directions with the slide’s color

- `clip-path: inset(0 -100vmax)`: clips this shadow at the top and bottom so it doesn’t overlap neighboring slides, and leaves the sides unclipped all the way to the screen edge.

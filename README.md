# BREWED — Premium 3D Coffee Website Template

A stunning, award-quality **3D coffee website template** built to pitch to specialty cafe clients. Features a scroll-driven canvas animation as the hero, a premium dark espresso design system, and 4 fully built pages.

## Pages

| File | Description |
|---|---|
| `index.html` | Homepage with 192-frame scroll animation |
| `menu.html` | "The Vault" — full product menu |
| `story.html` | Cinematic brand narrative page |
| `contact.html` | Contact form + store locations |

## Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/VivekSingh0811/CoffeeSite.git
cd CoffeeSite
```

### 2. Add the CoffeeFrames animation assets
Place your `CoffeeFrames/` folder (containing `ezgif-frame-001.jpg` → `ezgif-frame-192.jpg`) in the project root. This folder is excluded from git due to its large size (~100MB).

```
CoffeeSite/
├── index.html
├── menu.html
├── story.html
├── contact.html
├── CoffeeFrames/       ← add this folder manually
│   ├── ezgif-frame-001.jpg
│   ├── ezgif-frame-002.jpg
│   └── ... (192 frames total)
└── README.md
```

### 3. Run locally
```bash
npx serve . -p 4200
```
Then open [http://localhost:4200](http://localhost:4200)

Or simply open `index.html` directly in your browser.

## Customizing for a Client

To rebrand this template for a new cafe:

1. **Brand name** — Find & replace `BREWED` across all HTML files
2. **Gold accent color** — Change `#C9A96E` in the Tailwind config block (in each file's `<script id="tailwind-config">`)
3. **Menu items** — Edit the product cards in `menu.html`
4. **Locations** — Edit the location cards in `contact.html`
5. **Animation frames** — Replace the `CoffeeFrames/` folder with new images

## Design System

- **Background:** `#1A0F07` (espresso) / `#2C1810` (warm surface)
- **Gold accent:** `#C9A96E`
- **Fonts:** Playfair Display (headings) + Inter (body)
- **Components:** Glassmorphic cards, gold-bordered panels, scroll-driven canvas animation

## Tech Stack

- Vanilla HTML, CSS, JavaScript
- Tailwind CSS (via CDN)
- Google Fonts (Playfair Display, Inter)
- Google Material Symbols
- Canvas API for scroll-driven frame animation

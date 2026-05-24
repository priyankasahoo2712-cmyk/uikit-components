# 🎨 UIKit — CSS Component Library

A dark-themed CSS component library built with pure HTML5 and CSS3. Showcases reusable, production-ready UI components — no frameworks, no JavaScript dependencies.

---

## 🔗 Live Demo

[View Live →](https://priyankasahoo2712-cmyk.github.io/uikit-components)

---

## ✨ Components Included

| Component | Variants |
|---|---|
| **Buttons** | Solid, Outline, Ghost, Pill, Small, Large, Disabled |
| **Badges** | Colored, Dot indicator, Muted |
| **Cards** | Image card, hover effects, footer actions |
| **Alerts** | Success, Error, Warning, Info |
| **Form Inputs** | Default, Error state, Disabled, Toggle switch |
| **Avatars** | Colored initials, Avatar group with overlap |
| **Progress Bars** | Animated fill, multiple color variants |
| **Tooltips** | Hover-triggered, CSS-only |

---

## 🛠️ Built With

| Technology | Usage |
|---|---|
| HTML5 | Semantic structure |
| CSS3 | Custom properties, animations, pseudo-elements |
| Google Fonts | Space Mono + Syne |

---

## 📐 CSS Concepts Used

- **CSS Custom Properties (`--variables`)** — entire color system managed via `:root`
- **Flexbox** — component layout, alignment, wrapping
- **CSS Pseudo-elements** — tooltip arrows (`::after`), badge dots (`::before`)
- **CSS Transitions** — smooth hover and focus state changes
- **`@keyframes` animations** — progress bar fill animation on load
- **`:checked` selector** — toggle switch state without JavaScript
- **CSS specificity** — modifier classes (`.btn-sm`, `.btn-lg`, `.btn-pill`)

---

## 🎨 Design Decisions

- **Dark theme** using CSS variables makes it easy to switch to light theme by changing `:root` values only
- **Consistent spacing** using `rem` units throughout
- **Color palette** built around 4 accent colors: Yellow, Pink, Cyan, Purple
- Components are **self-contained** — each works independently without affecting others

---

## 📁 Project Structure

```
uikit-components/
│
├── index.html       # All components + CSS in one file
└── README.md        # Project documentation
```

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/priyankasahoo2712-cmyk/uikit-components.git
   ```

2. Open `index.html` in your browser — no build step needed!

---

## 🎯 What I Learned

- Building a scalable design system using CSS custom properties
- Creating reusable component classes with modifier patterns
- Writing CSS-only interactive elements (tooltips, toggles) without JavaScript
- Managing visual consistency across multiple component types
- Understanding CSS specificity and how modifier classes work

---

## 👩‍💻 Author

**Priyanka Sahoo**
Frontend Developer
📧 priyankasahoo2712@gmail.com
🔗 [GitHub](https://github.com/priyankasahoo2712-cmyk)

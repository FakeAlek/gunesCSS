# gunesCSS
<img src="https://i.ibb.co/mC9qWsBC/GunesCSS.png" width = 150 alt="logo" align="right"/>

**Version: 1.0.0-beta**

**gunesCSS** is a modular CSS library featuring utility classes, customizable components, and lightweight animations. It's ideal for rapid frontend prototyping or as a foundation for your own CSS framework.

## ✨ Features

### 🧩 Utilities
- **Colors** (`colors.css`): `--blue`, `--green-light`, `--white-smoke`
- **Spacing** (`spacing.css`): `.m10`, `.p50`, `.mx`, `px`

### 🎞️ Animations (`animations/`)
- `.fade-in`, `.fade-out`
- `.bounce`, `.bounceInf`
- `.float`

> All animations use `animation-fill-mode: forwards` and can be applied directly via class names.

### 🖱️ Button Styles (`buttons.css`)
- `.BTN3d`, `.BTNglow`, `.BTNglass`, `.BTNpulse`
- Includes hover and active effects

### 🧾 Base Elements (`main.css`)
- Consistent styling for:
  - **Text** (sizes, colors)
  - **Links**
  - **Inputs**

---

## 📦 Installation

```html
<!-- Base styles -->
<link rel="stylesheet" href="./css/main.css">

<!-- Utilities -->
<link rel="stylesheet" href="./utilities/colors.css" />
<link rel="stylesheet" href="./utilities/spacing.css" />

<!-- Components -->
<link rel="stylesheet" href="./components/button.css" />

<!-- Animations -->
<link rel="stylesheet" href="./animations/fade.css" />
<link rel="stylesheet" href="./animations/bounce.css" />
<link rel="stylesheet" href="./animations/float.css" />
```

**OR**

```css
@import url('../animations/fade.css');
@import url('../folder/data.css');

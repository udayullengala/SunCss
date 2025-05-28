# SunCSS ☀️

SunCSS is a lightweight and customizable CSS utility and component library inspired by frameworks like Bootstrap and Tailwind CSS. It provides utility classes, base styles, and common UI components to help you build modern responsive web interfaces easily.

---

## 🚀 Installation

Install via npm:

```bash
npm install suncss
```

## Usage

Import SunCSS styles in your project:

```scss
import 'suncss/dist/suncss.css';
```

## Components & Utility Classes Examples

### Buttons

```html
<button class="btn btn-primary">Primary Button</button>
<button class="btn btn-secondary">Secondary Button</button>
<button class="btn btn-success">Success Button</button>
<button class="btn btn-danger">Danger Button</button>
<button class="btn btn-warning">Warning Button</button>
<button class="btn btn-info">Info Button</button>
```

### Cards

```html
<div class="card">
  <div class="card-header">Card Header</div>
  <div class="card-body">This is some card content.</div>
  <div class="card-footer">Card Footer</div>
</div>
```

### Alerts

```html
<div class="alert alert-success">Success alert message</div>
<div class="alert alert-danger">Danger alert message</div>
<div class="alert alert-warning">Warning alert message</div>
<div class="alert alert-info">Info alert message</div>
```

### Navbar

```html
<nav class="navbar">
  <div class="navbar-brand">SunCSS</div>
  <ul class="navbar-nav">
    <li class="nav-item"><a href="#" class="nav-link">Home</a></li>
    <li class="nav-item"><a href="#" class="nav-link">About</a></li>
    <li class="nav-item"><a href="#" class="nav-link">Contact</a></li>
  </ul>
</nav>
```

### Forms

```html
<form class="form">
  <label for="email">Email</label>
  <input type="email" id="email" class="form-input" placeholder="Enter your email" />

  <label for="password">Password</label>
  <input type="password" id="password" class="form-input" placeholder="Enter your password" />

  <button type="submit" class="btn btn-primary">Submit</button>
</form>
```

### Utilities

* **Spacing:** `.m-1`, `.p-4`, `.mt-2`, `.px-3` etc.
* **Display:** `.d-block`, `.d-inline`, `.d-flex`
* **Flex:** `.flex-row`, `.flex-col`, `.justify-center`, `.items-center`
* **Grid:** `.grid`, `.grid-cols-3`
* **Border:** `.border`, `.border-primary`, `.rounded-md`
* **Shadow:** `.shadow-sm`, `.shadow-lg`
* **Background:** `.bg-primary`, `.bg-light`
* **Opacity:** `.opacity-50`
* **Misc:** `.cursor-pointer`, `.overflow-hidden`, `.visible`

## Customization

You can customize colors, fonts, breakpoints, spacing, and more by editing the SCSS variables in `src/themes/_variables.scss`.

**Enjoy building with SunCSS!**
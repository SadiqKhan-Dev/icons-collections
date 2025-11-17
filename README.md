
# 📦 SVG Icons Collection

A complete, scalable, and developer-friendly collection of **SVG icons** created for modern web and mobile interfaces.

## ✨ Features
- Lightweight and clean vector icons
- Fully scalable with no quality loss
- Dark mode and theming support using `currentColor`
- Easy to style using CSS, Tailwind, or inline attributes
- Works with HTML, React, Next.js, Vue, Svelte, Angular, Flutter, and Figma
- Well-organized folder structure for easy browsing

## 📁 Folder Structure
```
icons/
 ├── arrows/
 ├── communication/
 ├── social/
 ├── system/
 ├── media/
 ├── navigation/
 ├── files/
 └── misc/
```

## 🚀 Usage

### HTML
```html
<svg width="24" height="24" stroke="currentColor">
  <!-- SVG path here -->
</svg>
```

### React / Next.js
```jsx
import Icon from "./icons/arrows/arrow-right.svg";

function Example() {
  return <Icon className="w-6 h-6 text-blue-500" />;
}

export default Example;
```

### Styling (CSS / Tailwind)
```css
svg {
  width: 24px;
  height: 24px;
  stroke: currentColor;
}
```
```html
<svg class="text-red-600 w-6 h-6">...</svg>
```

## 🗂 Categories

| Category | Description |
|----------|-------------|
| Arrows | Directional navigation icons |
| Communication | Call, chat, email, notifications |
| Social | Popular platform logos |
| System | UI, settings, alerts, controls |
| Media | Play, pause, volume, camera |
| Files | Upload, download, folder, attachments |
| Misc | Extra utility icons |

## 🤝 Contribution Guidelines

1. Use a **24×24** artboard size  
2. Use **stroke="currentColor"** or **fill="currentColor"**  
3. Keep file names **lowercase** and **descriptive**  
4. Optimize SVG paths before committing  

## 📄 License

Released under the **MIT License**.  
Free for **commercial**, **open-source**, and **personal** use.  
Attribution is **not required**, but always appreciated.

## ⭐ Support

If you find this useful, please **star this repository** to support ongoing improvements.

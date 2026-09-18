# Creative Technology Lab - Lab 1 Submission

A modern, interactive portfolio website that meets all course requirements while showcasing advanced web design and interactivity.

## ✅ Requirements Met

### ✓ HTML Structure
- **Header with Navigation**: Contains 3 internal anchor links (About, Projects, Contact)
- **Main Content**: Three sections of semantic HTML content
- **Footer**: Copyright information
- **No `<div>` tags**: Built entirely with semantic HTML5 elements

### ✓ Three Main Sections
1. **About Section** - Introduction with hero image (`pic1.jpeg`)
2. **Projects Section** - Three project articles with descriptions
3. **Contact Section** - Call-to-action with email link

### ✓ Media & Contact Elements
- **Image**: `<img>` tag in About section with descriptive alt text
- **Email Link**: `<a href="mailto:hello@example.com">` in Contact section

### ✓ Semantic Tags Only
All HTML uses semantic tags exclusively:
```html
<header>, <nav>, <main>, <section>, <article>, <aside>, <footer>
<h1-h3>, <p>, <img>, <a>, <ul>, <li>, <small>, <strong>
```

---

## 🎨 Bonus Features (Creativity)

### Interactive Design
- ✨ **Scroll Animations** - Elements fade in as they come into view (Intersection Observer API)
- 🎯 **Interactive Cards** - Project cards lift and change color on hover
- 🔗 **Active Navigation** - Links highlight as you scroll through sections
- 📱 **Responsive Design** - Works beautifully on mobile and desktop
- 🎬 **Smooth Animations** - Staggered fade-ins, parallax effects, and gradient transitions
- ⌨️ **Keyboard Accessible** - Full keyboard navigation support
- 🎨 **Modern Aesthetics** - Professional color scheme with gradients and depth

### Technical Features
- Parallax scroll effect on hero image
- Cursor proximity detection for card effects
- Smooth scroll navigation for anchor links
- Respects `prefers-reduced-motion` for accessibility
- Mobile-first responsive design

---

## 📁 File Structure

```
Lab1/
├── lab1.html          # Main HTML file (semantic only, 0 divs!)
├── lab1.css           # Modern CSS with animations (375 lines)
├── lab1.js            # Interactive JavaScript (220 lines)
├── pic1.jpeg          # Hero image asset
└── README.md          # This file
```

---

## 🚀 How to View

1. Open `lab1.html` in any modern web browser
2. The page will load with smooth animations
3. Try hovering over project cards
4. Click navigation links for smooth scrolling
5. Scroll to see fade-in animations

---

## 🎯 Key Technical Highlights

### Semantic HTML
- No wrapper divs - uses `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`
- Proper heading hierarchy with `<h1>`, `<h2>`, `<h3>`
- Semantic elements like `<small>`, `<strong>`, `<aside>` used appropriately

### CSS Architecture
- **Animations**: 4 keyframe animations (fadeInUp, slideIn, glow, cardHover, float)
- **Gradients**: Linear and radial gradients for modern look
- **Transitions**: Smooth cubic-bezier transitions throughout
- **Mobile**: Responsive breakpoint at 700px with optimized layout

### JavaScript Interactivity
- **Intersection Observer**: Efficient scroll animation detection
- **Event Listeners**: Smooth scroll, parallax, cursor tracking
- **Accessibility**: Keyboard navigation and motion preferences
- **Performance**: No unnecessary reflows or layout thrashing

---

## 🌟 Design Philosophy

This submission goes beyond basic requirements to showcase:
- Modern web development best practices
- Accessibility and performance considerations
- User experience through smooth interactions
- Professional visual design
- Clean, maintainable code

All while strictly adhering to the constraint of **zero `<div>` tags** and only semantic HTML elements!

---

**Created**: September 17, 2026  
**UC Berkeley Frontend Lab 1**

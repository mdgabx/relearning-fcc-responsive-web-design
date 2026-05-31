# Responsive Web Design Practice Notes

## 1. Computer Basics

* Understanding computer hardware and software.
* Operating systems and file management.
* Web browsers and developer tools.
* Internet fundamentals and web technologies.

## 2. HTML Fundamentals

* Structure of an HTML document.
* Common HTML elements:

  * Headings (`<h1>` - `<h6>`)
  * Paragraphs (`<p>`)
  * Links (`<a>`)
  * Images (`<img>`)
  * Lists (`<ul>`, `<ol>`, `<li>`)
  * Forms (`<form>`, `<input>`, `<button>`)
* Semantic HTML:

  * `<header>`
  * `<nav>`
  * `<main>`
  * `<section>`
  * `<article>`
  * `<footer>`

## 3. CSS Fundamentals

* CSS syntax and selectors.
* Colors, backgrounds, and typography.
* Box Model:

  * Margin
  * Border
  * Padding
  * Content
* Positioning:

  * Static
  * Relative
  * Absolute
  * Fixed
  * Sticky

## 4. Responsive Web Design

* Mobile-first approach.
* Fluid layouts.
* Flexible images.
* Media Queries:

```css
@media (max-width: 768px) {
  .container {
    flex-direction: column;
  }
}
```

## 5. Flexbox Layout

* One-dimensional layout system.
* Important properties:

  * `display: flex`
  * `justify-content`
  * `align-items`
  * `flex-direction`
  * `flex-wrap`
  * `gap`

Example:

```css
.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
```

## 6. CSS Grid Layout

* Two-dimensional layout system.
* Important properties:

  * `display: grid`
  * `grid-template-columns`
  * `grid-template-rows`
  * `gap`
  * `grid-area`

Example:

```css
.container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
}
```

## 7. CSS Animations

### Transitions

```css
.button {
  transition: all 0.3s ease;
}

.button:hover {
  transform: scale(1.05);
}
```

### Keyframe Animations

```css
@keyframes bounce {
  0%, 100% {
    transform: translateY(0);
  }

  50% {
    transform: translateY(-10px);
  }
}

.element {
  animation: bounce 2s infinite;
}
```

## 8. Best Practices

* Use semantic HTML.
* Keep CSS organized and reusable.
* Design mobile-first.
* Test on multiple screen sizes.
* Optimize images and assets.
* Maintain accessibility standards.
* Use Flexbox and Grid appropriately depending on layout needs.

## Key Learning Goal

Build responsive, accessible, and visually appealing websites using HTML, CSS, Flexbox, Grid, and CSS animations that work across desktop, tablet, and mobile devices.

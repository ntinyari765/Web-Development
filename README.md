# Introduction to HTML and CSS

This project is a beginner-friendly introduction to **HTML** (HyperText Markup Language) and **CSS** (Cascading Style Sheets), the core technologies for building web pages.

---

## 📄 What is HTML?
HTML is the standard markup language used to create the **structure** of a webpage. It uses **elements** such as:
- Headings (`<h1>` to `<h6>`)
- Paragraphs (`<p>`)
- Links (`<a>`)
- Images (`<img>`)
- Lists (`<ul>` and `<ol>`)

## CSS Basics

### What is CSS?
CSS (Cascading Style Sheets) is used to style and format HTML elements on a webpage. It controls layout, colors, fonts, and more.

### Ways to Apply CSS
1. **Inline CSS** – Applied directly in the HTML element’s `style` attribute.
2. **Internal CSS** – Written inside a `<style>` tag in the HTML `<head>`.
3. **External CSS** – Written in a separate `.css` file and linked with `<link>`.

### CSS Syntax
A CSS rule has two main parts:
- **Selector** – Targets the HTML element.
- **Declaration Block** – Contains property-value pairs.

Example:
```html
<h1>Hello World</h1>
<p>This is my first webpage.</p>

Example:
```css
p {
  color: blue;
  font-size: 16px;
}

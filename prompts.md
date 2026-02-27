# Web Development Project – Prompt Iteration

---

## 🟢 Prompt 1 — HTML Structure

Hello ChatGPT, take the role of an advanced web development programmer from Universidad de La Sabana.  
I require you to perform the following specific actions for my web development project and explain the generated code.

Observe the following image that represents a user interface component.

To simplify the exercise:

- Generate a 400px by 300px container.
- Center it both vertically and horizontally in the viewport.
- Inside it, add the indicated elements.

### Specifications:

- Use correct semantic HTML tags such as:
  `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`.
- Use a `<main>` tag as the main container.
- Inside the main container include 8 decorative elements:
  - 4 circles
  - 4 squares
- Each figure must be represented using `<div>` elements with descriptive class names.
- Use class names such as:
  - `circle`
  - `square`
  - `top-left`
  - `top-right`
  - `bottom-left`
  - `bottom-right`
- Do not add any CSS styles yet.
- The code must be properly indented.
- Briefly explain the function of each semantic tag used.
- Follow HTML5 best practices.

---

## 🟡 Prompt 2 — Base Styles (Colors, Typography, and Box Model)

Based on the previously created HTML structure, add the base CSS styles.

### Requirements:

- Apply a basic reset using:
  `box-sizing: border-box;`
- Define a global typography using Google Fonts.
- Establish main colors (background, text, buttons).
- Apply appropriate margins and padding.
- Style buttons with a hover effect.
- Apply subtle shadows to cards if present.
- Do not use Flexbox or Grid yet for the main layout.

---

## 🔵 Prompt 3 — Layout and Refinement (Exact Positioning)

Refine the previous design so that it matches exactly the provided image.

### Requirements:

- Use `position: relative;` on the container.
- Use `position: absolute;` on each decorative figure.
- Place the elements in:
  - Top corners
  - Bottom corners
- Maintain uniform spacing from the edges.
- Ensure the correct order of shapes:

  - Top left → square + circle  
  - Top right → circle + square  
  - Bottom left → circle + square  
  - Bottom right → square + circle  

- The final result must be symmetrical and visually balanced.

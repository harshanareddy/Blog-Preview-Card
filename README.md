# Blog Preview Card

A responsive blog preview card built from a Frontend Mentor challenge. Mobile-first, accessible, and lightly animated.

## ✨ Demo
- Live: <YOUR_LINK_HERE>
- Solution: <REPO_LINK_HERE>

## 📸 Screenshot
<img width="464" height="485" alt="image" src="https://github.com/user-attachments/assets/661d4b78-4038-4f79-9487-aa17b656c405" />


## 🎯 The Challenge
Build a blog preview card and implement hover/focus states for all interactive elements on the page.

## 🧰 Built With
- Semantic HTML5
- CSS custom properties (design tokens)
- Flexbox
- Mobile-first media queries

## 📐 Responsiveness
- Base width: `width: min(92vw, 350px)` for phones (320–375px).
- Breakpoints:
  - `@media (min-width: 768px)`: larger padding/width


## ♿ Accessibility
- Visible `:focus-visible` outlines for links/buttons.
- Sufficient color contrast (dark text on light background; yellow used for accents).
- Informative `alt` text on images.
.

## 🧪 Interactions
- Title: color change on hover/focus
- Tag badge: hover cursor + focus ring
- Card: subtle lift/offset shadow on hover (reduced when `prefers-reduced-motion`)

## 🧠 What I Learned
- Centering a card both ways using `display: grid; place-items: center;` (or flex on the parent).
- Mobile-first CSS and layering desktop styles with `@media (min-width: …)`.
- Using `rem` for scalable spacing/typography; `em` for component-relative sizing.
- Managing overrides via specificity and ordering (e.g., `.container p` vs `p`).

## 🗂️ Project Structure

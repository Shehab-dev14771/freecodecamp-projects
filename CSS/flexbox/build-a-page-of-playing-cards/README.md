# 🎴 Playing Cards Display – FreeCodeCamp Project

This is a responsive web page built as part of the **FreeCodeCamp Responsive Web Design Certification** curriculum. It visually displays a set of playing cards using **HTML** and **CSS Flexbox** layout techniques.

---

## 📸 Preview

![Project Preview](https://i.postimg.cc/dQzDYpRz/Screenshot-2025-06-02-20-37-06-865.jpg)

---

## 🧾 Features & User Stories

✅ Built to meet the following user stories:

1. Display **at least three playing cards**.
2. Contains a `<main>` element with `id="playing-cards"`.
3. Inside `#playing-cards`, there are multiple `div` elements with class `card`.
4. Each `.card` contains three child `div`s with classes:
   - `.left`
   - `.middle`
   - `.right`
5. `#playing-cards` uses **Flexbox** to:
   - Center children horizontally.
   - Allow wrapping.
   - Maintain `20px` gap between cards.
6. `.card` elements use **Flexbox** to space content using `justify-content: space-between`.
7. `.left` aligns to **start** of the card.
8. `.middle` aligns to **center** of the card and stacks symbols vertically.
9. `.right` aligns to **end** of the card and is rotated 180 degrees for symmetry.
10. Clean, gradient background and responsive card layout.

---

## 🎨 Styling

- Background: `radial-gradient(circle, red, blue)`
- Cards: White with rounded corners and padding
- Flexbox used for layout of both the card container and card contents
- Cards resize and wrap on smaller screens
- Red color used for Hearts (♥) and Diamonds (♦)

---

## 🛠 Technologies

- **HTML5**
- **CSS3 (Flexbox)**

---

## 🧠 What I Learned

- Advanced **Flexbox alignment techniques**
- Centering and wrapping using Flexbox
- Semantic HTML and visual layout best practices
- Structuring a card-like component using pure CSS

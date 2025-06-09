# 💡 Ghost Landing Page – Landing Page Design

This project is a CSS-only layout for a landing page. It uses various fundamental and advanced CSS properties to style different sections of the page.

---

## 📂 CSS Properties Used

### 🧱 Global Reset

```css
body {
  margin: 0%;
  padding: 0%;
}
```
- Removes default browser spacing.

---

### 🧭 Header Styling

```css
header {
  width: 100%;
  height: 300px;
  background-color: black;
  color: white;
}
```
- Full width header with fixed height and dark background.

---

### 📌 Navigation Bar

```css
nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
ul {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
li {
  list-style: none;
  margin-right: 10px;
}
```
- Uses Flexbox to align navigation items horizontally.
- Removes list bullets from `li`.

---

### 🖼️ Header Image

```css
#header-img {
  padding-top: 50px;
  height: 40px;
  width: fit-content;
}
```
- Adds spacing above the image and sets size.

---

### 🎯 Icon Section

```css
.icon-img {
  font-size: 50px;
  color: white;
  gap: 30px;
}
#icon-things {
  gap: 30px;
}
```
- Enlarges icons and spaces them.

---

### ✉️ Subscribe Button

```css
#subscribe {
  border: 1px white solid;
  border-radius: 0.5rem;
  padding: 10px;
}
```
- White border with rounded corners and padding.

---

### 🧍 Center Text Utility

```css
.center {
  text-align: center;
}
```
- Centers content horizontally.

---

### ✒️ Header Font

```css
#header-font {
  font-weight: 100;
  position: relative;
  bottom: 20px;
  font-size: 20px;
}
```
- Thin font, moved slightly upwards.

---

### 🖼️ Section 1 – Image and Paragraph

```css
#section1 {
  display: flex;
}
#section1Img {
  height: 400px;
  width: 600px;
  padding: 30px;
}
#para1 {
  padding: 30px 0;
}
#parahead {
  color: navy;
  font-weight: 100;
  font-size: 22px;
}
#paraheading {
  position: relative;
  bottom: 20px;
  font-weight: bolder;
  font-size: 40px;
}
#para1-text {
  color: lightgray;
  font-size: 18px;
  text-align: start;
  position: relative;
  bottom: 25px;
}
```
- Flexbox layout with image and descriptive paragraph.
- Custom font styles and spacing.

---

### 📦 Small Logo Card

```css
.small-logo-card {
  display: flex;
  align-items: center;
  padding-top: 20px;
}
.small-logo-img {
  width: 40px;
  height: 40px;
}
.small-logo-card p {
  margin: 0;
  padding: 0 10px;
  font-size: 13px;
}
.small-body {
  color: lightgray;
  padding-top: 2px;
}
```
- Flex layout with icons and text, useful for feature highlights.

---

### 📑 Section 2 – Cards 

```css
#section2 {
  padding: 40px 20px;
  border-top: 1px solid lightgray;
  display: flex;
  justify-content: space-evenly;
}
.section2Box img {
  width: 300px;
  height: 200px;
  padding: 0 10px;
  border-radius: 5%;
}
.section2head {
  color: blue;
  position: relative;
  bottom: 10px;
}
.section2Box p {
  padding: 0 10px;
}
.section2heading {
  font-weight: 600;
  font-size: 20px;
  position: relative;
  bottom: 25px;
}
.section2para {
  position: relative;
  bottom: 30px;
  color: lightgray;
  width: 300px;
}
.section2lastbox {
  position: relative;
  bottom: 30px;
}
```
- Cards with headings, images, and light styling.

---

### 🎬 Section 3 – Wide Image with Description

```css
.section3Box img {
  width: 500px;
  height: 300px;
  padding: 0 10px;
  border-radius: 5%;
}
#section3 {
  padding: 40px 90px;
  border-top: 1px solid lightgray;
  display: flex;
  gap: 10px;
}
.section3para {
  position: relative;
  bottom: 30px;
  color: lightgray;
  width: 500px;
}
.section3head {
  color: blue;
  position: relative;
  bottom: 10px;
}
.section3Box p {
  padding: 0 10px;
}
```
- Big image layout with side description text and titles.

---

## ✅ Summary

| Feature        | Description |
|----------------|-------------|
| 🎨 Layout      | Flexbox-based layout |
| 🧾 Typography  | Controlled via `font-size`, `font-weight`, and `color` |
| 📷 Images      | Responsive with padding and border-radius |
| 🧭 Positioning | Relative positioning to fine-tune element location |
| 📐 Spacing     | `padding`, `margin`, and `gap` used extensively |
| 🧩 Utility     | Reusable classes like `.center` |

---

> 👨‍💻 Built using only HTML & CSS to strengthen core front-end skills.

# Flex Box Layout

A simple **HTML & CSS Flexbox layout project** created to practice and understand the basic concepts of **CSS Flexbox**, including containers, rows, columns, and nested layouts.

## 📌 Project Preview

The layout contains:

* Header
* Left sidebar
* Right content area
* Top section
* Bottom section divided into two columns
* Footer area

## 🛠️ Technologies Used

* HTML5
* CSS3
* CSS Flexbox

## 📂 Project Structure

```text
Flex-Box/
│
├── index.html
└── README.md
```

## 🎨 Layout Structure

```text
┌─────────────────────────────────────┐
│               Header                │
├──────────┬──────────────────────────┤
│          │           Top            │
│          ├──────────────────────────┤
│   Left   │     Bottom     │ Bottom  │
│ Sidebar  │       B1       │   B2    │
│          │                │         │
├──────────┴──────────────────────────┤
│               Footer                │
└─────────────────────────────────────┘
```

## 🎨 Colors Used

| Section             | Color     |
| ------------------- | --------- |
| Main Container      | `#576c8b` |
| Header              | `#576c8b` |
| Left Section        | `#FEEAAE` |
| Top Section         | `#BDE0FE` |
| Bottom Left (`B1`)  | `#C4EED7` |
| Bottom Right (`B2`) | `#FBCBCF` |
| Right Section       | `#FFFFFF` |
| Borders             | `#FFFFFF` |

## 📐 Flexbox Concepts Used

### 1. Display Flex

The main center section uses:

```css
.center {
    display: flex;
}
```

This places the left and right sections side by side.

### 2. Width Distribution

The left section occupies **20%** of the available width:

```css
.left {
    width: 20%;
}
```

The right section occupies **80%**:

```css
.right {
    width: 80%;
}
```

### 3. Nested Flexbox

The bottom section also uses Flexbox:

```css
.bottom {
    display: flex;
}
```

It contains two equal sections:

```css
.b1 {
    width: 50%;
}

.b2 {
    width: 50%;
}
```

### 4. Box Sizing

The project uses:

```css
* {
    box-sizing: border-box;
}
```

This makes width and height calculations easier by including padding and borders within the element's dimensions.

## 🚀 How to Run

1. Download or clone the project.
2. Open the project folder.
3. Open `index.html` in any modern web browser.

For example:

```text
index.html → Right Click → Open with Browser
```

## 🎯 Learning Objectives

This project helps practice:

* HTML page structure
* CSS styling
* Flexbox layout
* Width and height percentages
* Nested Flexbox
* Borders
* Background colors
* `box-sizing: border-box`

## 👨‍💻 Author

**Vikash Kumawat**

---

⭐ This project is created for learning and practicing **CSS Flexbox**.

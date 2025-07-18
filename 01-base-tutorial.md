### 1. **Introduction to CSS**

- **What is CSS?**

  - CSS stands for Cascading Style Sheets
  - Separates content (HTML) from presentation (CSS)

- **Types of CSS**

  - Inline

    ```html
    <p style="color: red;">Hello</p>
    ```

  - Internal

    ```html
    <style>
      p {
        color: red;
      }
    </style>
    ```

  - External

    ```html
    <link rel="stylesheet" href="style.css" />
    ```

- **CSS Syntax and Selectors Overview**

  ```css
  selector {
    property: value;
  }
  ```

---

### 2. **CSS Selectors (Deep Dive)**

- **Universal Selector**: `* { margin: 0; }`
- **Element Selector**: `p { color: black; }`
- **Class Selector**: `.box { border: 1px solid black; }`
- **ID Selector**: `#header { background: blue; }`
- **Group Selector**: `h1, h2, h3 { font-weight: bold; }`
- **Descendant Selector**: `div p { color: green; }`
- **Child Selector**: `ul > li { list-style: none; }`
- **Attribute Selector**:

  ```css
  input[type="text"] {
    border: 1px solid gray;
  }
  ```

---

### 3. **Colors and Units**

- **Named Colors, HEX, RGB, RGBA, HSL**

  ```css
  color: #ff0000;
  background-color: rgba(0, 0, 0, 0.5);
  ```

- **Units**

  - px, %, em, rem, vw, vh

  ```css
  font-size: 16px;
  width: 50%;
  ```

---

### 4. **Text and Fonts**

- **Font Family, Size, Weight, Style**

  ```css
  font-family: "Arial", sans-serif;
  font-size: 1.2rem;
  ```

- **Text Align, Decoration, Transform**

  ```css
  text-align: center;
  text-transform: uppercase;
  text-decoration: underline;
  ```

- **Line Height, Letter Spacing**

  ```css
  line-height: 1.5;
  letter-spacing: 0.05em;
  ```

---

### 5. **Box Model**

- **Content → Padding → Border → Margin**

  ```css
  padding: 10px;
  border: 1px solid black;
  margin: 20px;
  ```

- **box-sizing: content-box vs border-box**

  ```css
  box-sizing: border-box;
  ```

---

### 6. **Display and Visibility**

- **Display Values**:

  - block, inline, inline-block, none
  - flex, grid (later in detail)

- **Visibility** vs **display: none**
- **Example**:

  ```css
  .hidden {
    display: none;
  }
  .invisible {
    visibility: hidden;
  }
  ```

---

### 7. **Positioning and Z-Index**

- **Static, Relative, Absolute, Fixed, Sticky**

  ```css
  position: absolute;
  top: 20px;
  left: 50px;
  ```

- **z-index: stacking elements**

---

### 8. **Float and Clear**

- **float: left / right**

  ```css
  img {
    float: right;
  }
  ```

- **clear: both**

  ```css
  .clearfix::after {
    content: "";
    display: block;
    clear: both;
  }
  ```

---

### 9. **Flexbox (Modern Layouts)**

- **Container Properties**

  - display: flex
  - flex-direction: row | column
  - justify-content: space-between
  - align-items: center

- **Item Properties**

  - flex-grow, flex-shrink, flex-basis

- **Example**:

  ```css
  .container {
    display: flex;
    justify-content: space-between;
  }
  ```

---

### 10. **CSS Grid (Advanced Layouts)**

- **Grid Container**

  ```css
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 10px;
  ```

- **Grid Items**

  ```css
  grid-column: 1 / 3;
  grid-row: 2 / 4;
  ```

---

### 11. **Responsive Design**

- **Media Queries**

  ```css
  @media (max-width: 768px) {
    body {
      background: pink;
    }
  }
  ```

- **Mobile First Approach**
- **Viewport Meta Tag**

  ```html
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  ```

---

### 12. **CSS Pseudo-classes & Pseudo-elements**

- **Pseudo-classes**

  - `:hover`, `:focus`, `:nth-child()`

- **Pseudo-elements**

  - `::before`, `::after`

  ```css
  p::first-letter {
    font-size: 200%;
  }
  ```

---

### 13. **Transitions and Animations**

- **Transitions**

  ```css
  button {
    transition: background 0.3s ease;
  }
  ```

- **Keyframes Animation**

  ```css
  @keyframes slideIn {
    from {
      transform: translateX(-100%);
    }
    to {
      transform: translateX(0);
    }
  }
  .box {
    animation: slideIn 1s ease-in-out;
  }
  ```

---

### 14. **Transformations**

- **rotate, scale, skew, translate**

  ```css
  .box {
    transform: rotate(45deg);
    transform: scale(1.2);
  }
  ```

---

### 15. **CSS Variables**

- **Declaring and Using Variables**

  ```css
  :root {
    --primary-color: #3498db;
  }
  button {
    background-color: var(--primary-color);
  }
  ```

---

### 16. **CSS Functions**

- **calc()**

  ```css
  width: calc(100% - 50px);
  ```

- **clamp(), min(), max()**

  ```css
  font-size: clamp(1rem, 2vw, 2rem);
  ```

---

### 17. **Advanced Selectors**

- **:not(), \:nth-child(), \:nth-of-type()**

  ```css
  li:not(:first-child) {
    margin-left: 10px;
  }
  ```

---

### 18. **Best Practices and Optimization**

- CSS Minification
- Using shorthand properties

  ```css
  margin: 10px 15px 5px 0;
  ```

- Combining selectors
- Organizing CSS rules (reset/normalize)

---

### 19. **CSS Frameworks (Overview)**

- Bootstrap
- Tailwind CSS (utility-first)
- Material UI

---

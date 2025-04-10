24130500010-FajarDwiharjo-WCD03-Tugas3-workoutAja

# 🏋️‍♀️ WorkoutAja Landing Page

This repository contains a simple, responsive landing page built using HTML and CSS. The page is designed for a fictional fitness brand called **WorkoutAja**, promoting personalized workout plans with a modern and clean aesthetic.

## 📄 Project Structure

The project consists of the following core files:

- `index.html`: The main HTML file containing the structure of the landing page.
- `style.css`: The corresponding stylesheet responsible for layout, colors, fonts, spacing, and responsiveness.
- `images/`: A directory containing supporting images such as logo, illustrations, and icons.

## 🌐 Features

- Responsive navigation bar with logo and menu links.
- Hero section with a bold, motivational heading, supporting paragraph, and a WhatsApp-styled call-to-action button.
- Visually appealing typography using **Mulish** and **Open Sans** fonts from Google Fonts.
- Professional layout using Flexbox for alignment and spacing.
- Footer with a contact email link.
- Decorative SVG illustration positioned at the bottom of the screen.

## 📸 Preview

![Landing Page Preview](./images/preview)


## 📁 Folder Structure

```
project/
│
├── index.html
├── style.css
└── images/
    ├── logo.svg
    ├── whatsapp-icon.svg
    ├── woman.svg
    └── balls.svg
```

## 🧰 Tech Stack

- **HTML5**
- **CSS3**
- **Google Fonts** (Mulish & Open Sans)
- **Flexbox**

## 🚀 assignment source code

1. Clone the repository:
    ```bash
   git clone https://github.com/cakrawala-university/web-client-development.git
    ```

## 🚀 assignment snippet

### 🎨 Index HTML Updates

#### 🔧 1. Added `class="active"` to the Home menu item

**Before:**
```html
<li><a href="#">Home</a></li>
```

**After:**
```html
<li><a href="#" class="active">Home</a></li>
```

---

#### ✍️ 2. Modified paragraph text content in `<section class="text">`

**Before:**
```html
<p>We create <strong>exclusive and unique</strong> workouts for you. <br>
Invest in your body and get <strong>much more performance</strong><br>and quality of life.</p>
```

**After:**
```html
<p>We create <strong>exclusive and unique workouts</strong> for you. <br>
Invest in your body and<strong> get much more performance</strong><br>and quality of life.</p>
```

🔸 *Note: Moved `<strong>` tags to include more meaningful text.*

---

#### ⬆️ 3. Changed button label to uppercase and added exclamation mark

**Before:**
```html
<button alt="go to whatsapp">
  <img src="./images/whatsapp-icon.svg " alt="whatsapp icon">
  Start now
</button>
```

**After:**
```html
<button alt="go to whatsapp">
  <img src="./images/whatsapp-icon.svg " alt="whatsapp icon">
  START NOW!
</button>
```
### 🎨 CSS Style Updates

#### ✅ 1. Added list style reset to `nav ul`

**Before:**
```css
nav ul {
  display: flex;
  gap: 48px;
}
```

**After:**
```css
nav ul {
  list-style: none;
  display: flex;
  gap: 48px;
}
```

---

#### ✍️ 2. Styled `nav ul li a` with consistent typography and visual hierarchy

**Before:**
```css
nav ul li a {

}
```

**After:**
```css
nav ul li a {
  font-family: 'Mulish', sans-serif;
  font-weight: 400;
  font-size: 18px;
  line-height: 1;
  letter-spacing: 0; 
  text-decoration: none;
  opacity: 0.5;
  color: #1F1534;
}
```

---

#### 🎯 3. Improved hover state for `nav ul li a`

**Before:**
```css
nav ul li a:hover {
  
}
```

**After:**
```css
nav ul li a:hover {
  font-weight: 700;
  opacity: 1;
  color: #1f1534;
}
```

---

#### ⭐ 4. Created `.active` class to highlight active navigation item

```css
.active {
  font-weight: 700;
  opacity: 1;
}
```

---

#### 🔠 5. Styled heading (`.text h1`) and span for emphasis

**Before:**
```css
.text h1 {
  font-family: 'Mulish', sans-serif;
}

.text h1 span {
}
```

**After:**
```css
.text h1 {
  font-family: 'Mulish', sans-serif;
  font-weight: 400;
  font-size: 48px;
  line-height: 1.5;
  letter-spacing: 0; 
  text-transform: uppercase;
  color: #000000;
}

.text h1 span {
  font-weight: 700;
  color: #89C5CC;
}
```

---

#### 📝 6. Enhanced paragraph readability and color

**Before:**
```css
.text p {
  font-family: 'Open Sans', sans-serif; 
}
```

**After:**
```css
.text p {
  font-family: 'Open Sans', sans-serif; 
  font-weight: 400;
  font-size: 16px;
  line-height: 1.6;
  letter-spacing: 0; 
  color: #7D7987;
}
```

---

#### 🚀 7. Styled button with color, spacing, and rounded edges

**Before:**
```css
.text button {
  font-family: 'Open Sans', sans-serif;
  display: flex;
  gap: 8px;
}
```

**After:**
```css
.text button {
  font-family: 'Open Sans', sans-serif;
  display: flex;
  gap: 8px;
  font-weight: 500;
  font-size: 16px;
  line-height: 1;
  letter-spacing: 0; 
  align-items: center;
  line-height: 21px;
  color: #F9F9F9;
  padding: 14px 32px;
  background: #69B99D;
  border-radius: 4px;
  border: none;
}
```

---

#### 🎨 8. Added hover effect for button

**Before:**
```css
.text button:hover {
}
```

**After:**
```css
.text button:hover {
  background-color: #599882;
}
```

---

#### 📌 9. Styled `footer` and anchor link

**Before:**
```css
footer {
  font-family: 'Open Sans', sans-serif; 
}

footer a {
  color: #000;
  text-decoration: none;
  font-weight: 700;
}
```

**After:**
```css
footer {
  font-family: 'Open Sans', sans-serif; 
  font-weight: 400;
  font-size: 14px;
  line-height: 1.6;
  letter-spacing: 0; 
  text-align: center;
  color: #000;
}

footer a {
  color: #000;
  text-decoration: none;
  font-weight: 700;
}

footer a:hover {
  text-decoration: underline;
}
```

---

#### 🖼️ 10. Tweaked `#balls` element (note: color property misused)

**Before:**
```css
#balls {
  position: fixed;
  bottom: 0px;
  right: 0px;
}
```

**After:**
```css
#balls {
  position: fixed;
  bottom: 0px;
  right: 0px;
  color: linear-gradient(#89C5CC, #89C5CC); 
}
```

---

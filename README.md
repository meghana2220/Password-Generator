# 🔐 Password Generator App

A stylish, responsive, and fully functional **Password Generator** built with **HTML**, **CSS**, and **JavaScript**. This app allows users to generate secure passwords based on their preferences (length, uppercase, numbers, symbols) and provides the ability to **copy the generated password** to the clipboard with a click.

---

## 🚀 Features

- 🎛️ Adjustable password length via a range slider
- 🔠 Optional inclusion of:
  - Uppercase letters
  - Numbers
  - Symbols
- 🧠 Randomized secure password generation
- 🖱️ Click-to-copy password to clipboard
- 📱 Fully responsive for mobile devices
- 🎨 Animated, modern UI using Flexbox & CSS transitions
- 🧰 Built-in validation and event handling

---

## 🛠️ Technologies Used

| Technology     | Purpose |
|----------------|---------|
| **HTML5**      | Page structure |
| **CSS3**       | Layout, styling, media queries, custom properties |
| **JavaScript** | Logic for password generation, event handling, clipboard copy |
| **Font Awesome** | Lock icon via CDN |
| **Google Fonts** | "Poppins" for clean typography |

---

## 🧩 How It Works

### ✅ Password Generation Logic
- Uses lowercase letters by default.
- Checks the state of checkboxes to optionally include:
  - Uppercase: `"A-Z"`
  - Numbers: `"0-9"`
  - Symbols: `"!@#$%^&*()_+"`
- Password is generated using a loop based on selected length (`1–20` characters).
- Random characters are picked from the combined character set.

### ✏️ Click-to-Copy
- When the password box is clicked, JavaScript uses:
  ```js
  navigator.clipboard.writeText()
## LIVE DEMO 
https://meghana2220.github.io/Password-Generator/

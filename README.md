# Personal Profile

---

## 📌 About the Project

This is my first hands-on web project, built to practice and apply the core fundamentals of **HTML5, CSS3, and JavaScript** without using any frameworks, build tools, or templates.

The project contains two simple pages:
- **Home (`index.html`):** A basic profile page introducing services, an email subscription box, and contact information.
- **Gallery (`gallery.html`):** A simple image slider built from scratch with plain JavaScript to display project screenshots alongside a short description for each.

The primary goal of building this was practical learning: understanding page layout with Flexbox, writing custom media queries for different screen widths, handling RTL Arabic text, and practicing basic DOM manipulation in JavaScript.

---

## 🚀 Live Demo

[View Live Demo](https://mohammed-mfsa99.github.io/personal-page)

---

## 📸 Screenshots

![Desktop Screenshot](screenshots/desktop.png)


---

## ✨ Features

- Simple 2-page static website (Home & Gallery)
- Right-to-Left (RTL) Arabic text layout
- Layout structured with CSS Flexbox
- Basic responsive adjustments for mobile and tablets via media queries
- Custom image slider built with vanilla JavaScript (no slider libraries)
- Dynamic description updates based on the active slide
- Service highlights using Font Awesome icons
- Custom Arabic typography with Google Fonts

---

## 🛠️ Technologies

| Technology | Usage |
|---|---|
| **HTML5** | Semantic structure for both pages |
| **CSS3** | Flexbox layouts, basic responsiveness, and styling |
| **JavaScript** | Slider navigation and DOM manipulation |
| **Font Awesome** | Icons for services and navigation |
| **Google Fonts** | Arabic font (*El Messiri*) |

---

## 📂 Project Structure

```
personal-page/
│
├── css/
│   ├── style.css          # Main stylesheet
│   └── slider.css         # Slider styles
│
├── js/
│   └── slider.js          # Slider logic (vanilla JS)
│
├── img/
│   ├── backgron1.jpg      # Header background image
│   ├── pek1.png           # Gallery preview 1
│   ├── pek2.png           # Gallery preview 2
│   ├── pek3.png           # Gallery preview 3
│   └── pek4.png           # Gallery preview 4
│
├── index.html             # Main profile page
├── gallery.html           # Gallery / Slider page
└── README.md
```

---

## 📱 Responsive Design

Basic responsive rules applied via CSS media queries:

| Breakpoint | Applied Change |
|---|---|
| `< 1154px` | Service boxes stack vertically into a single column |
| `< 776px` | Newsletter form wraps and centers for smaller screens |
| `< 592px` | Header branding and navigation links center for mobile |

---

## 📚 What I Learned

Through building this first project, I practiced:

- Structuring multi-page static websites with HTML
- Page layout using **CSS Flexbox**
- Writing media queries from scratch without CSS frameworks
- Basic **DOM manipulation** in JavaScript (`querySelectorAll`, `addEventListener`, `classList`, `style.transform`)
- Linking UI state (changing the active description when clicking slider dots)
- Working with RTL (Right-to-Left) direction in CSS
- Organizing assets into clean directories (`css/`, `js/`, `img/`)

---

## 🔮 Future Improvements

- [ ] Add touch swipe support to the mobile slider
- [ ] Replace placeholder text with real project data
- [ ] Improve form validation for the newsletter input
- [ ] Enhance accessibility (keyboard navigation & ARIA labels)

---

## 👨‍💻 Author

**Mohammed Faez**
Frontend Web Developer

- GitHub: [mohammed-MFSA99](https://github.com/mohammed-MFSA99)
- LinkedIn: [Mohammed Faez](https://www.linkedin.com/in/mohammed-faez-alameri)

---


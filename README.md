# 🔍 Live Search

A live search bar built with pure **HTML, CSS and JavaScript**. No libraries.

**Part 4/10** of my HTML CSS JS Series 🚀

## ✨ Features
- Results filter instantly as you type
- Matching text is highlighted with a cyan glow
- Live result counter
- "No results found" state
- Press `/` to focus the search bar
- Glassmorphism dark UI with hover effects

## 🛠️ Tech Stack
- HTML5
- CSS3 (flexbox, animations, glow effects)
- Vanilla JavaScript (`filter()`, `includes()`, DOM events)

## 📂 Project Structure
```
live-search/
├── index.html
├── style.css
└── script.js
```

## ▶️ How to Run
1. Download or clone this repo
   ```bash
   git clone https://github.com/YOUR-USERNAME/live-search-html-css-js.git
   ```
2. Open `index.html` in your browser

## 💡 How It Works
1. A `data` array stores all items
2. On every keystroke, the `input` event calls `render()`
3. `filter()` keeps only the items that match the search text
4. The matching part is wrapped in `<mark>` for the glow highlight

## 👩‍💻 Author
Instagram: [@tech.by.itzwania](https://instagram.com/tech.by.itzwania)

⭐ Star this repo if you found it helpful!

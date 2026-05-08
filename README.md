A logic-based skincare routine generator that recommends AM & PM routines based on skin type and concern — built with **pure HTML, CSS, and JavaScript** (no frameworks, no AI).

**[ https://saria-codes.github.io/Skincare-routine-generator-/](#)** ← *(replace with your GitHub Pages link)*

---

## ✨ Features

- Select skin type (Oily, Dry, Combination) and primary concern (Acne, Dark Spots/PIH, Dullness)
- Generates a full AM + PM routine instantly with product names, brands, and usage tips
- Each product recommendation includes a one-line explanation of *why* it's recommended
- Copy routine to clipboard
- Fully responsive — works on mobile and desktop
- Zero dependencies — no libraries, no frameworks

## 🛠 Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Structure |
| CSS3 | Styling, responsive grid layout |
| Vanilla JavaScript | Routine logic, dynamic DOM rendering |

## 🚀 How to Run

No installation needed. Just open `index.html` in any browser — it works completely offline.

```bash
git clone https://github.com/YOUR-USERNAME/skincare-routine-generator.git
# then open index.html in your browser
```

## 📁 Project Structure

```
skincare-routine-generator/
│
└── index.html       # Single-file app — all HTML, CSS, and JS included
```

## 🧠 How It Works

All routine data is stored as a nested JavaScript object organized by:
```
skin type → concern → { am: [...steps], pm: [...steps], tip: "..." }
```
When the user selects their options, the app looks up the correct combination and dynamically renders the steps to the DOM — no page reload, no API call needed.

## 💡 What I Learned

- Building data-driven UIs with plain JavaScript (no frameworks)
- Dynamic DOM manipulation — creating and inserting elements from a JS data structure
- Responsive CSS layout using Grid and Flexbox
- Designing clean, user-friendly interfaces without UI libraries
- Structuring large JS data objects for readability and maintainability

## 🔮 Future Improvements

- [ ] Add more skin types and concerns
- [ ] Filter by ingredient preferences (fragrance-free, vegan, etc.)
- [ ] Add a budget filter (drugstore vs. premium)
- [ ] Save favorite routines with localStorage

---

> **Note:** This project was later upgraded with AI-powered generation using the Claude API.  
> See the AI version here: [GlowAI — AI Skincare Routine Generator](#) 

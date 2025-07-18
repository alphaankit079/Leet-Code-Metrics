# 📊 LeetMetric

LeetMetric is a clean and responsive web application that visualizes your LeetCode problem-solving progress using circular progress charts and statistical cards. Just enter your LeetCode username and view your submission stats categorized by difficulty — Easy, Medium, and Hard.

---

## 🔍 Features

- 🎯 Search any valid LeetCode username
- 🟢🟠🔴 Circular progress indicators for Easy, Medium, and Hard questions
- 📈 Displays total and per-difficulty submission counts
- 🌈 Modern and responsive UI
- 💡 Real-time data fetched from LeetCode GraphQL API

---

## 🛠️ Tech Stack

- **HTML5**
- **CSS3** — Flexbox, Gradients, Conic Gradients
- **JavaScript (ES6)** — DOM Manipulation, Async/Await, Fetch API
- **GraphQL API** — Fetches live LeetCode stats
- **CORS Proxy** — Uses `https://cors-anywhere.herokuapp.com/` for cross-origin requests

---

## 📂 Project Structure

```
LeetMetric/
├── index.html        # Main UI
├── index.css         # Styling and responsive layout
├── index.js          # Functionality: Fetch, validate, render data
└── README.md         # Project documentation
```

---

## 🧠 How It Works

1. The user enters their LeetCode username.
2. The app sends a GraphQL POST request to LeetCode's API via a CORS proxy.
3. The API responds with submission statistics.
4. JavaScript processes the data and:
   - Renders **circular progress charts**.
   - Creates **submission stat cards**.
   - Updates the UI in real-time.

---

## 🚀 Getting Started

### 📦 Clone the Repository

```bash
git clone https://github.com/your-username/LeetMetric.git
cd LeetMetric
```

### 🌐 Run Locally

Just open `index.html` in any modern browser.

> ⚠️ Note: This app uses a public CORS proxy (`cors-anywhere`). If it’s down or blocked, the API may not work. You can host your own proxy or look for alternatives.

---

## 🧪 Example Username

To test it out, use a real LeetCode username like:

```
john_doe_123
```

---

## 💡 Future Enhancements

- 🔐 Remove reliance on external CORS proxy
- 📱 Improve mobile responsiveness
- 🎨 Add animations for progress rings
- 🌍 Deploy to GitHub Pages or Vercel

---

## 🙌 Acknowledgements

- [LeetCode GraphQL API](https://leetcode.com/graphql)
- [CORS Anywhere](https://github.com/Rob--W/cors-anywhere)

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 👨‍💻 Author

**Ankit Kumar** – [@alphaankit079](https://github.com/alphaankit079)

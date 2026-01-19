# Website Header – Dark/Light Toggle

An elegant and responsive **Website Header with Dark/Light Mode Toggle** built using **React, Vite, and Tailwind CSS v4**.  
This project demonstrates seamless theme switching, persistent user preference using `localStorage`, and a modern hero section UI.

🔗 **Live Demo:** https://hsb-ini-14.github.io/website-header-dark-light-toggle/

---

## ✨ Features

- 🌗 Dark & Light mode toggle button  
- 💾 Remembers theme preference using `localStorage`  
- 🖥️ Respects system color scheme on first load  
- ⚡ Smooth transition animations between themes  
- 🎨 Modern hero section UI with gradients and blur effects  
- 📱 Fully responsive layout  
- 🎯 Built using Tailwind CSS v4  
- 🚀 Fast development using Vite  

---

## 🧰 Tech Stack

- **React** – UI components & state management  
- **Vite** – Fast build tool & dev server  
- **Tailwind CSS v4** – Utility-first styling  
- **Boxicons** – Icon set  
- **GitHub Pages** – Deployment  

---

## 📁 Project Structure

```
website-header-dark-light-toggle/
├── src/
│   ├── components/
│   │   └── Hero.jsx
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── public/
│   └── images/
├── vite.config.js
├── package.json
└── README.md
```

---

## 🚀 Getting Started

Follow these steps to run the project locally:

### 1. Clone the repository

```bash
git clone https://github.com/hsb-ini-14/website-header-dark-light-toggle.git
cd website-header-dark-light-toggle
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start the development server

```bash
npm run dev
```

Open your browser and visit:  
http://localhost:5173

---

## 🌍 Deployment to GitHub Pages

This project is deployed using **gh-pages**.

### Steps used:

1. Install gh-pages

```bash
npm install --save-dev gh-pages
```

2. Set base path in `vite.config.js`

```js
export default defineConfig({
  base: "/website-header-dark-light-toggle/",
});
```

3. Add scripts to `package.json`

```json
"predeploy": "npm run build",
"deploy": "gh-pages -d dist"
```

4. Deploy

```bash
npm run deploy
```

---

## ⚙️ How It Works

- The theme state is stored using React `useState`  
- On initial load:
  - Checks `localStorage` for saved theme  
  - Falls back to system preference using `prefers-color-scheme`  
- Toggles the `dark` class on the `<html>` element  
- Saves updated theme back to `localStorage`  
- Tailwind’s `dark:` utilities handle theme-based styling  
- UI transitions are handled using Tailwind transition classes  

---

## 🖼️ Preview

to be added later

---

## 🙌 Acknowledgements

- Icons by **Boxicons**  
- Styling powered by **Tailwind CSS**  
- Build tool by **Vite**  

---

## 👤 Author

**Harsh Singh Bhaduria**  
- GitHub: https://github.com/hsb-ini-14  

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub — it really helps!

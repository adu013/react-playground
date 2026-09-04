# ⚛️ React Playground

Welcome to the **React Playground**! This sandbox environment was **originally built for my own personal convenience** to quickly test ideas, experiment with components, and prototype code. However, it is fully ready for anyone else to use as an instant, lightweight React scratchpad.

It is powered by **Vite** for blazing fast performance and comes pre-configured with **ESLint** to keep code clean and consistent.

---

## 🚀 Quick Start

Get the playground running locally on your machine in less than a minute.

### 1. Clone the Repository
```bash
git clone https://github.com/adu013/react-playground && rm -rf .git
cd react-playground
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Start the Development Server
```bash
npm run dev
```
Once started, open your browser and navigate to the local server address (usually **`http://localhost:5173`**) displayed in your terminal.

---

## 🛠️ Tech Stack & Features

* **Vite**: Ultra-fast build tool with near-instant Hot Module Replacement (HMR).
* **React 19+**: Built for modern functional components and hooks.
* **ESLint**: Standard rules pre-configured (`eslint.config.js`) to catch bugs early.
* **Zero Overhead**: Skip the tedious setup and start writing code immediately.

---

## 📂 Project Structure

```text
├── public/              # Static assets
├── src/
│   ├── App.jsx          # Main entry point (write your scratchpad code here!)
│   ├── index.css        # Global styles
│   └── main.jsx         # App bootstrapping
├── .gitignore           # Gitignore file
├── index.html           # Main HTML entry point for Vite
├── eslint.config.js     # Linter configuration
├── vite.config.js       # Vite bundler configuration
├── package.json         # Project metadata and script commands
├── package-lock.json    # Locked dependency tree
└── README.md            # This guide
```

---

## 🧪 How to Use

1. Open **`src/App.jsx`**.
2. Clear out the placeholder code inside the main return statement.
3. Import your custom files or write fresh logic right inside the file.
4. Watch the preview reload instantly in your browser!

---

## 🤝 Contributing & Feedback

Since this playground is primarily built for my own convenience, please **open an issue** before submitting any major architectural changes or pull requests. This helps ensure that any proposed updates align with the goals of this personal sandbox.

If you encounter a bug or have a suggestion for a helpful utility addition, please feel free to **open a GitHub Issue** so we can discuss it!

---

## 📄 License

This project is open-source and available under the **MIT License**. Feel free to fork it, modify it, and use it for your own projects. See the

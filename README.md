# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

# 💱 Currency Converter (React + Hooks)

A simple currency converter built with **React** and **custom hooks**, that fetches real-time exchange rates using [Currency API](https://github.com/fawazahmed0/currency-api).

---

## 🚀 Features
- Convert between any two world currencies 🌍
- Real-time exchange rates via free API
- Swap functionality between `From` and `To` currencies
- Reusable **custom hook** (`useCurrencyInfo`)
- Responsive UI with **TailwindCSS**

---

## 🛠️ Technologies Used
- **React** (Functional Components + Hooks)
- **Custom Hook** for fetching currency data
- **TailwindCSS** for styling
- **Currency API** for latest exchange rates

---

## 📂 Project Structure
currency-converter/
│-- src/
│ │-- components/
│ │ └── InputBox.jsx
│ │-- hooks/
│ │ └── useCurrencyInfo.js
│ │-- App.jsx
│ │-- index.js
│-- public/
│-- package.json
│-- README.md


---

## ⚙️ Installation & Setup

1. **Clone the repo**
```bash
git clone https://github.com/<your-username>/currency-converter.git
cd currency-converter


Install dependencies

npm install


Run the app

npm run dev


The app will start at 👉 http://localhost:5173
 (if using Vite).

🔧 Usage

Enter the amount in the From currency field.

Select the From and To currencies from dropdowns.

Click Convert to get the converted amount.

Use Swap button to switch currencies instantly.

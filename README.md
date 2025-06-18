# 🎨 Background Color Changer App

A simple and visually appealing React + TailwindCSS app that allows users to change the background color of the screen with a click. Ideal for beginners learning React hooks, styling with Tailwind, and working with component-based architecture.

---

## 📌 Features

- 🎯 Instantly changes background color on button click
- ⚡ Smooth transitions using Tailwind's `duration` class
- 📱 Fully responsive and mobile-friendly layout
- 🔧 Easily extendable with new colors
- 🧠 Uses React's `useState` for color state management

---

## 🛠 Tech Stack

- **React** (with Vite)
- **Tailwind CSS**
- **JavaScript (ES6+)**
 
---

## 🚀 Getting Started

Follow these steps to run the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/Prat260104/background-color-changer.git
cd background-color-changer
```

###  2. Install Dependencies
```bash
npm install
```

###  3. Run the App Locally
```bash
npm run dev
```

###  4. Build for Production
```bash
npm run build
```
---

## 🎨 Add More Colors

To add a new color button, copy and edit an existing button in `App.jsx`:

```jsx
<button
  onClick={() => setColor("orange")}
  className="outline_none px-4 py-1 rounded-full text-white shadow-lg"
  style={{ backgroundColor: "orange" }}
>
  Orange
</button>
```
---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

- [React](https://reactjs.org)
- [Tailwind CSS](https://tailwindcss.com)
- [Vite](https://vitejs.dev)







# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh


```js
npm create vite@latest
````


```js
 cd react-context-api-theme-switcher
  npm install
  npm run dev
````

Install Tailwind CSS
Install tailwindcss and its peer dependencies, then generate your tailwind.config.js and postcss.config.js files.

```js
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
````

Configure your template paths
```js
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  darkMode: "class",
  theme: {
    extend: {},
  },
  plugins: [],
}
````

Add the Tailwind directives to your CSS
```js
@tailwind base;
@tailwind components;
@tailwind utilities;
````

Restart Server
```js
  npm run dev
````
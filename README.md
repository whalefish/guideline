# Guideline
environment: Vue 3 + Vite + TypeScript + TailwindCSS

## install Vite and TypeScript
```
npm init vite@latest projectName
cd projectName
npm i
```

## install TailwindCSS
```
npm i -D tailwindcss
npx tailwindcss init -p
```
### Set TailwindCSS
Add the paths in your `tailwind.config.js` file.
```
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./src/**/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
}
```
Add the Tailwind directives to your CSS
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

## other pulgin
```
npm i sass 
```
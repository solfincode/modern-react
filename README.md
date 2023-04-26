## Modern React Practice

1. vitejs
using vitejs to create react app using typescript

```
npm create vite@latest

#install tailwindcss
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p

```
add this in tailwindcss.config
```
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

add this in index.css
```
@tailwind base;
@tailwind components;
@tailwind utilities;

```





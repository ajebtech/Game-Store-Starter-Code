# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

<!-- Rawg Game API -->

1. https://rawg.io/apidocs
2. https://api.rawg.io/docs/

<!-- Front-End Packages -->

1. axios
   https://www.npmjs.com/package/axios
   npm i axios

2. dotenv
   https://www.npmjs.com/package/dotenv
   npm i dotenv
   import dotenv package in vite.config and define
   define: {
   "process.env.VITE_API_KEY": JSON.stringify(process.env.VITE_API_KEY),
   },
3. Tailwind
   https://tailwindcss.com/docs/installation

4. Tailwind Scrollbar
   https://www.npmjs.com/package/tailwind-scrollbar

   npm i tailwind-scrollbar

   add this plugin on tailwind.config file

   require("tailwind-scrollbar")({ nocompatible: true })

5. React Icons
   https://www.npmjs.com/package/react-icons

   npm i react-icons

6. Font used Poppins
   https://fonts.google.com/specimen/Poppins

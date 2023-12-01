# *Nike Website*

- *A dynamic landing page of nike website is developed using ReactJS, Tailwind CSS, and JavaScript to showcase my skills. The responsive design ensures that the UI looks great on various devices, making it accessible to a wide audience.*

- *Live Website : https://nike-landing-page-1.netlify.app/*

- *Tech Stack : ReactJS, Tailwind CSS, JavaScript*

# *Setting up the project*

- Create React App with Vite
  ```
  npm create vite@latest
  ```
  
- Install tailwindcss via npm, and create your tailwind.config.js file
  ```
  npm install -D tailwindcss
  npx tailwindcss init
  ```
  
- Configure your template paths
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
  
- Add the Tailwind directives to your CSS
  ```
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
  ```



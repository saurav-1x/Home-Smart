# Home-Smart

>>>> Live link: https://s-homesmart.netlify.app/


This project is a fully responsive website built using Tailwind CSS. Tailwind CSS is a utility-first CSS framework that makes it easy to create custom designs without writing any custom CSS. The website adapts seamlessly to different screen sizes, providing an optimal viewing experience on desktops, tablets, and mobile devices.

Features
Fully Responsive Design: The layout adjusts to various screen sizes, ensuring a consistent user experience across all devices.
Utility-First CSS: Utilizes Tailwind CSS for rapid and efficient styling.
Modern UI: Clean and modern user interface design.
Customizable Components: Easily customizable components for reusability.
Cross-Browser Compatibility: Works seamlessly on all major web browsers.
Technologies Used
Tailwind CSS: For styling and responsive design.
HTML5: For structuring the content. 

INSTALLATION--->>>>

->>>RUN npx tailwindcss init

->>>change the content of tailwind.config.js to  ```module.exports = {
  content: ["./*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
}```

->>>create input.css and write  ``` @tailwind base;
@tailwind components;
@tailwind utilities;```

->>>include the style.css file to html

->>>run the command ```npx tailwindcss -i input.css -o style.css --watch```

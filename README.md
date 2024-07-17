# Lms Frontend

### setup instruction

1. clone the project
... 
    git clone https://github.com/Chandus2003/Lms-front-end.git
...
2. Move in to the directory 
...
   cd lms-front-end
...

3. Instal dependency
...
   npm install
...

 4. Run the server
...  
  npm run dev
...

### How to set-up Tailvind in your project
1.  Install tailwind and Other dependency
...
   npm install -D tailwindcss postcss autoprefixer
...
2. Create the Tailwindconfing.js file
 ...
   npx tailwindcss init -p
 ...
3. Add the file and extension in the tailwind confing in the content property
 ...
   content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ]
 ...
4. Add css inside index.css file
...
   @tailwind base;
   @tailwind components;
   @tailwind utilities;
...
5. Run the server ... npm run dev ...

###   Adding neccesary  plugin and dependecy 
 ... 
 npm install @reduxjs/toolkit react-redux react-router-dom react-icons react-chartjs-2 chart.js daisyui axios react-hot-toast @tailwindcss/line-clamp
 ...
 ### Adding estlint auto import

 ...
    npm i eslint-plugin-simple-import-sort
 ...

### Setup Toster

...
   Add Toaster component in main.jsx
   <Toaster/>
...
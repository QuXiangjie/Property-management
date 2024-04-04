# Initial learning this project

## Set up
Create a folder of this project, set up the necessary library
```
cd "Web Development/ Property managment"
npm create vite@latest client
Choose React and Javascript+swc

cd client
npm I
```


Now we are going to download the taiwindcss

https://tailwindcss.com/docs/installation

https://tailwindcss.com/docs/guides/vite

when you are using vite, it is a different story

```
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init

```

/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./src/**/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
}
增加这条指令到tailwind配置文件中, tailwind.config.js


@tailwind base;
@tailwind components;
@tailwind utilities;
增加到index.css

需要添加插件ES7+ React7/Redux...
Auto Rename Tag
console Ninja
Github copilit

taiwindcss intelligence need to be set up:

"tailwindCSS.emmetCompletions": true,
"editor.inlineSuggest.enabled": true,
"editor.quickSuggestions": {
   "strings": true
},
"css.validate": false,


rfc in app.jsx
```


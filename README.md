# LMS Frontend

### Setup instruction 

1.Clone the Project
```
git clone https://github.com/MOHDAALAM786/lms-frontend.git
```

2.Move into the directory
```
cd lms-frontend
```

3.install dependencies
```
npm i
```

4.run the server
```
npm run dev
```

### Setup instruction for tailwind

[Tailwind official instruction doc](https://v3.tailwindcss.com/docs/installation)

1. Install tailwind css
```
npm install -D tailwindcss@3

```

2. Create tailwind config file 
```
 npx tailwindcss init
```

3. Add file extensions to tailwind config file  int the contents property
```
"./src/**/*.{html,js,jsx,ts,tsx}"
```

4. Add the tailwind directives at the top the `index.css` file 

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

### Adding plugins and dependencies 

```
npm install @reduxjs/toolkit react-redux react-router-dom react-icons react-chartjs-2 chart.js daisyui axios react-hot-toast @tailwindcss/line-clamp
```

### configure auto import sort eslint 
1. Install simple import sort
```
npm i -D eslint-plugin-simple-import-sort
```

2. Add rule on `.eslint.cjs`

```
 'simple-import-sort/imports':'error'
```

3. Add simple import sort plugin in `.eslint.cjs`
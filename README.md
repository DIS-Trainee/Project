# vueproject

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

### Tailwind
```
npm install -D tailwindcss postcss autoprefixer
```
### Generate Tailwind&postcss config.js
```
npx tailwindcss init -p
```
### Add path tailwind.config.js
```
ontent: [
    "./index.html",
    "./src/**/*.{vue,js,ts,jsx,tsx}",
  ],
```
### Add @tailwind directive for each of Tailwind's Style.css
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```




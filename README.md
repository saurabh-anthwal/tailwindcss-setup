# How to setup Tailwindcss
## 1. install tailwindcss
``` 
npm i -D tailwindcss
```

## 2. init tailwindcss
```
npx tailwindcss init
```

## 3. change this line in tailwindcss.config.js file
```
content: ["*"],
```

## 4. create a new css file and add these 3 line of code
```
// in main.css 

@tailwind base;
@tailwind components;
@tailwind utilities;
```
## 5. write this command
```
npx tailwindcss -i main.css -o style.css --watch
```

# Enjoy!! Happy Coding

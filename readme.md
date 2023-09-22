# Set Up Tailwind CSS
## 1. npm init -y

## 2. npm install -D tailwindcss postcss autoprefixer vite
### put script -> start: vite in package.json

### Link css file to html.
Inside css file:
@tailwind base;
@tailwind components;
@tailwind utilities;


## 4. npx tailwindcss init -p
### • In tailwind.config.js, put content = ["*"]

## 5. npm run start
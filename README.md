# Login Page
A simple login page, developed using Tailwindcss and Vitejs.

## How it looks
![picture alt](https://repository-images.githubusercontent.com/433316155/89ff4c11-283a-41a4-aa7e-f55ae5012873 "Login Page by iBishek")

## Wanna try?
* `$ git clone https://github.com/ibishek/login-page.git`
* `$ cd login-page`
* `$ npm install`
* `$ npm run tailwind-build`
* `$ npm run dev`

## I want to customize!!!
* `$ git clone https://github.com/ibishek/login-page.git`
* `$ cd login-page`
* `$ npm install`
* `$ npm run tailwind-dev`
* The main css for tailwind: `src/css/app.css`
* Builing css for development: `$ npm run tailwind-dev`
* Tailwind output: `build/app.css`

## Building for production
* Tailwindcss: `$ npm run tailwind-build`
* Minify tailwindcss: `$ npm run tailwind-build-min`
* Vite: `$ npm run build`
* In order to include minified version of tailwindcss
  - change `./build/app.css` to `./build/app.min.css` inside `main.js`
  - `$ npm run build`
* Run `$ npm run serve` to see your deloyment ready page
* Files inside the `dist` directory are deployment-ready files.

## Bug 
If you encounter any bugs please, raise an issue as soon as possible.

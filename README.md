# login-page
A Simple login page made with Tailwindcss and Vite. 

## How to customize
* `$ git clone https://github.com/ibishek/login-page.git`
* `$ npm intall`
* Prepare Tailwindcss asset for development `$ npm run tailwind-dev`
* Goto `main.js` and change `app.min.css` to `app.css`
* Start Vite Server `$ npm run dev`

## How to build for production
* Prepare Tailwindcss asset for production `$ npm run tailwind-build`
* Prepare Tailwindcss asset for production-minified version `$ npm run tailwind-build-min`
* In order to use mininfied css change `app.css` to `app.min.css` from `main.js`
* Now build for production usgin vite `$ npm run build`

After building for production using vite, now you can see a new folder created inside the root directory as dist containing index.html and all of its assets inside the assets folder.

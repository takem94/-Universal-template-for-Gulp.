# Universal template for Gulp.
This template contains all of the most famous and useful plugins. 

## What it can do
* Compile **SCSS**/**SASS** to **CSS**.
* Cleans **unused** styles and **minifying CSS**.
* It have **CSS autoprefixer** for better browsers compability. 
* Compile **Jade**/**Pug** to **HTML**.
* Make your **JavaScript** code *"es2015"*(**ES6**) and newer to *"es2011"*(**ES5**).
* Makes it possible to use **node.js modules** for the browsers.
* Makes it possible use async/await in old browsers.
* It have **[browserSync](https://browsersync.io/)** plugin. This making autoreload page, when files have changed.
* Reduces the size of pictures with formats: **jpg,jpeg,svg,gif** and **png**.
* Making **sprites** from **png** and **svg** files.
* Also contains **[Bower](https://bower.io/)** for more faster downloads and easier installation various libraries.

## Usage
*Before you begin, you need to download and install* ***[node.js](https://nodejs.org/).***

1. **[Download this template]() and unpackage in a folder.**

2. **To get started use, you need open the folder with template and initialize by this commands in console:**
 ```
 $ npm init
 $ npm install
 $ bower init
 $ bower install
 ```
3. **Then you can start use Gulp tasks by this commands:**
 * `$ gulp preload` - this task need to prepare your workflow in the ***src/*** folder.
 * `$ gulp` - default task for watching all changes in the ***src/*** folder. 
 * `$ gulp build` - this task compiling all files in the ***src/*** folder and deploy to ***dist/*** folder. Use this command, when your project is done to production.
 * `$ gulp clearcached` - just clearning all cache from memory.
 
4. **Known bugs:**
 * Don't use numbers at start in names for svg/png icon in **src/img/Sprites/SpritesSrc** directory.

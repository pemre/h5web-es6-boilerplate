# Boilerplate for HTML5 ES6 Web Apps

Yet another boilerplate for HTML5 web apps. This time using ES6 (ECMAScript 6) everywhere as well as SASS to superpower your styles and Gulp as your beloved task runner. 

This boilerplate comes with these pre-installed and ready to use features:

- Gulp with ES6 style gulpfile ([http://gulpjs.com/](http://gulpjs.com/))
- SASS ([http://sass-lang.com/](http://sass-lang.com/))
- Bourbon (ligthweight mixin library for SASS, [http://bourbon.io/](http://bourbon.io/))
- SASS-MQ (media queries in an elegant way, [https://github.com/sass-mq/sass-mq](https://github.com/sass-mq/sass-mq))
- ES6 via Babel transpiler (use all those shiny new ES6 Features now, [https://babeljs.io/](https://babeljs.io/))
- Browserify (used together with babelify for module loading the new ES6 way via import,export in your JS files)

## ES6

No reason to wait anymore, use ES6 and all its [shiny nice features](http://es6-features.org/) now! Classes, fat arrow functions, generators, promises and the new modules system can be used now using the great **Babel** transpiler that makes them available for ES5 that is supported in all modern browsers.


## Structure

All source files belong to the src folder. The page itself is served off the ```public``` folder.

Gulp tasks deploy your compiled and packed styles (one ```styles.css```) and scripts (```scripts.js```) to this public folder either uncompressed with sourcemaps as default or compressed and without sourcemaps for production (use ```--production``` argument to gulp tasks).


## Installation

You need NodeJS and npm allready installed on your system. If you need help have a look at [https://nodejs.org/](https://nodejs.org/)

All dependecies are installed as npm packages and installed using this command:

```
npm install
```

## Gulp Tasks

WIP coming soon

## Add Modules and Libraries

To add my dependencies I use npm - even for browser-only libraries, as npm is a great package manager and there is no need to use something like Bower. If your preferred library is not available as npm package or has no package.json you can use [napa](https://www.npmjs.com/package/napa) to install such packages from Git or add them manual to ```src/vendor```.

But your are free to add Bower or jspm or another JS package manager to this boilerplate. 

  

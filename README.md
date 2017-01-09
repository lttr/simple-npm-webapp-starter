Simple npm webapp starter
=========================

Starter skeleton for new simple frontend projects. Focuses on simplicity and not 
on latest tools and frameworks.

Provides fast and understandable kickoff for new web sites and apps. Contains 
tools for interactive development with HTML, CSS and JS. Additional tooling and 
structure can be added later.

In the early 2017 the `es5` is still the main supported JavaScript standard 
among web browsers. There are bazilion tools and options that are not needed for 
simple applications.

## Features

- basic task runner
- dependency manager
- live preview
- integrate external libraries
- unify multiple css and js files
- upload result via ftp

## Tools

- `npm` combined with command line tools is just enough. See [how-to-use-npm-as-a-build-tool](http://blog.keithcirkel.co.uk/how-to-use-npm-as-a-build-tool).
- `browser-sync` works seamlessly. [Command line docs](https://www.browsersync.io/docs/command-line).
- `bower`
- `clean-css`
- `dploy`

## Project structure

```
❯ tree app dist
app
├── css
│   ├── main.css
│   └── vendor
│       └── bootstrap.min.css
├── img
│   └── npm.png
├── index.html
└── js
    ├── main.js
    └── vendor
        └── bootstrap.min.js
dist
├── css
│   ├── bootstrap.min.css
│   └── main.min.css
├── img
│   └── npm.png
├── index.html
└── js
    ├── bootstrap.min.js
    └── main.min.js
```

## Quickstart

```
npm install
npm start
```

## Non features

- no es6, babel, browserify, grunt, gulp, webpack, jspm, commonjs, polymer, flux, foojs or barjs
- no frameworks
- no tests

_...however you can integrate any of these if you need._

## Sources

- [why-npm-scripts](https://css-tricks.com/why-npm-scripts/)
- [how-to-use-npm-as-a-build-tool](http://blog.keithcirkel.co.uk/how-to-use-npm-as-a-build-tool)
- [npm-scripts-example](https://github.com/keithamus/npm-scripts-example)
- [npm-build-tool](https://github.com/Caballerog/npm-build-tool)
- [web-starter-kit](https://github.com/google/web-starter-kit)
- [generator-webapp](https://github.com/yeoman/generator-webapp)
- [frontend-starter](https://github.com/kimmobrunfeldt/frontend-starter)
- [npm-build-boilerplate](https://github.com/damonbauer/npm-build-boilerplate)

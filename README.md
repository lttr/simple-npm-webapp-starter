Simple npm webapp starter
=========================

Starter skeleton for new simple frontend projects. Focuses on simplicity and not 
on latest tools and frameworks.

Provides fast and understandable kickoff for new web sites and apps. Contains 
tools for interactive development with HTML, CSS and JS. Additional tooling and 
structure can be added later.

In the early 2017 the `es5` is still the main supported JavaScript standard 
among web browsers. There are bazillion tools and options that are not needed for 
simple applications.


## Features

- live preview
- dependency manager
- basic task runner
- concats multiple css files into one
- concats multiple javascript files into one

-> _Everything on one page of configuration._


## Quickstart

Clone or download this repo. Cd into the folder.

```
npm install
```
downloads the dependencies and install tools.

```
npm start
```
builds the application, begins watching the files for changes and starts the 
local server and opens browser with the app.

## Tasks

- `clean` cleans the destination directory and recreates necessary folders
- `build` concats and copies styles, javascripts, images and html files
- `serve` starts a local server with destination directory as a root directory
- `watch` watches for changes and starts appropriate part of the build task
- `start` combines `build`, `watch` and `serve`

Run tasks with `npm run taskname`. `npm start` and `install` are default npm 
tasks, no `run` is needed.

## Tools

- `npm` combined with command line tools is your  See [sources](#sources).
- `browser-sync` for seamlessly. [Command line docs](https://www.browsersync.io/docs/command-line).
- `onchange` for detecting changes of files
- `npm-run-all` for running tasks in parallel and `shx` for multiplatform shell commands

## Project structure

```
❯ tree app/ dist/
app/
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
dist/
├── css
│   ├── app.css
│   └── vendor.min.css
├── img
│   └── npm.png
├── index.html
└── js
    ├── app.js
    └── vendor.min.js
```

## Non features

- no es6, babel, browserify, grunt, gulp, webpack, jspm, commonjs, polymer, flux, foojs or barjs
- no frameworks
- no tests

...however you can integrate any of these if you need.

## Sources

Articles:
- [why-npm-scripts](https://css-tricks.com/why-npm-scripts/)
- [how-to-use-npm-as-a-build-tool](http://blog.keithcirkel.co.uk/how-to-use-npm-as-a-build-tool)

Github repos:
- [npm-scripts-example](https://github.com/keithamus/npm-scripts-example)
- [npm-build-tool](https://github.com/Caballerog/npm-build-tool)
- [web-starter-kit](https://github.com/google/web-starter-kit)
- [generator-webapp](https://github.com/yeoman/generator-webapp)
- [frontend-starter](https://github.com/kimmobrunfeldt/frontend-starter)
- [npm-build-boilerplate](https://github.com/damonbauer/npm-build-boilerplate)

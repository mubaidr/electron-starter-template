# electron-starter-Template

[![Build status](https://ci.appveyor.com/api/projects/status/cjua6pdhjp9rqa1o?svg=true)](https://ci.appveyor.com/project/mubaidr/electron-starter-template)
[![Build Status](https://travis-ci.org/mubaidr/electron-starter-template.svg?branch=master)](https://travis-ci.org/mubaidr/electron-starter-template)

The boilerplate for electron applications.

> **Checkout [vue-electron-template](https://github.com/mubaidr/vue-electron-template) for vue.js & electron template**

## Overview

`electron-starter` takes advantage of `webpack`, `electron-builder` and so much more to provide an easy to use development and building enviroment.

### What does it offer?

- [Bulma-Pro](https://mubaidr.github.io/bulma-pro/), a theme suitable for desktop application based on [Bulma](https://bulma.io/)
- [Font-awesomse-5](https://fontawesome.com) installed
- Easily package your electron app using [electron-builder](https://github.com/electron-userland/electron-builder)
- `DEV` & `BUILD` NPM scripts using [webpack-4](https://github.com/webpack/webpack) with Hot Module Replacement enabled
- Process restarting when working in main process
- CSS/JS pre-processor support
- ES7 with [`env`](https://babeljs.io/docs/en/babel-preset-env/) by default
- ESLint configured
- Babel configured

### Screenshot

<p align="center"><img src="./screenshot.png"></p>

### Getting Started

Clone this repository, install dependencies and run using either `dev` or `build` command.

```bash
# Clone this repositoryt
git clone https://github.com/mubaidr/electron-starter-templae

# change directory to cloned path
cd electron-starter-templae

# Install dependencies
npm install

# Run in `DEV` mode
npm run dev

# Build installer for this app
npm run build

# Build directory for this app with executeable
npm run build:dir

# Lint all source files using ESLINT
npm run lint
```

### Project structure

`src` contains all the source files.

`src/main` contains electron main script.

`src/renderer` contains vue-js application.

`electron-scripts` contains dev and build scripts

#### Credits

All credits to authors of packages and tools used in the project.

# Ignite-React-01-Github-Explorer
Ignite React - 01. Github Explorer

Init a new project
```sh
yarn init -y
```

Install dependency libraries

React
```sh
yarn add react
```

React DOM
```sh
yarn add react-dom
```

[Babel.js](https://babeljs.io/): JavaScript compiler for compatibility with all browsers.

Installation as Development dependencies
```sh
yarn add @babel/core @babel/cli @babel/preset-env -D
```
See Babel help
```sh
yarn babel -h
```
Convert JavaScript file
```sh
yarn babel src/index.js --out-file dist/bundle.js
```
```sh
yarn babel src/index.jsx --out-file dist/bundle.js
```

Recognize React for Babel conversion
```sh
yarn add @babel/preset-react -D
```
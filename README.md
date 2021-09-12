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

[Webpack](https://webpack.js.org/): static module bundler for modern JavaScript applications.
Installation
```sh
yarn add webpack webpack-cli webpack-dev-server -D
```
Integration Babel with Webpack
```sh
yarn add babel-loader -D
```
Execute Webpack
```sh
yarn webpack
```
Auto 
```sh
yarn add html-webpack-plugin -D
```


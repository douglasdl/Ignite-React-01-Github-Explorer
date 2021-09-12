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

Auto refer to javascript file
```sh
yarn add html-webpack-plugin -D
```

Auto conversion after changes
```sh
yarn add webpack-dev-server -D
```
Execute Webpack Serve
```sh
yarn webpack serve
```
Create ENV variable (Mac or Linux only)
```sh
NODE_ENV=production yarn webpack
```

Create ENV variable (For any OS)
```sh
yarn add cross-env -D
```

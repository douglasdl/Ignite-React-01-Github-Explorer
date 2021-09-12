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
Integration Babel with Webpack (js, jsx)
```sh
yarn add babel-loader -D
```
Integration Babel with Webpack (css)
```sh
yarn add style-loader css-loader -D
```
Integration Babel with Webpack (SasS)
```sh
yarn add sass-loader -D
```
```sh
yarn add sass -D
```
```sh
yarn remove sass -D
```
```sh
yarn add node-sass -D
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

(SasS)[https://sass-lang.com]: Syntactically Awesome Style Sheets 

(Fast Refresh React)[https://github.com/pmmmwh/react-refresh-webpack-plugin]
Installation
```sh
yarn add -D @pmmmwh/react-refresh-webpack-plugin react-refresh
```

If have bug, remove this version
```sh
yarn remove @pmmmwh/react-refresh-webpack-plugin
```
and install this version
```sh
yarn add -D @pmmmwh/react-refresh-webpack-plugin@0.5.0-rc.5
```
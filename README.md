# simple-webpack4-starter

## Why this starter
Main goal is to enable rapid prototyping of html/css/javascript front application.

## How was built this starter
### Init blank npm project
```
npm init -y
```
### Edit ./package.json
Added build, dev and serve scripts

### Added files to project
* ./webpack.config.js
* ./src/index.js
* ./src/hello.js
* ./src/index.html

### Install webpack and needed dependencies
```
npm i -D webpack webpack-cli webpack-dev-server html-webpack-plugin style-loader css-loader
```

### Build project
```
npm run build # production mode
npm run dev # development mode
npm run serve # serve from webpack-dev-server

# simple-webpack4-starter

## Why this starter
Main goal is to enable rapid prototyping HTML/CSS/Javascript starter.

## How to use it
```
git clone https://github.com/robertocastro/simple-webpack4-starter.git
cd simple-webpack4-starter.git
npm install

npm run serve # launch dev-server on http://localhost:8080
npm run build # build production /dist folder
npm run dev # build development /dist folder
```

## How was built this starter
### Init blank npm project
```
npm init -y
```
### Edit ./package.json
Added build, dev and serve scripts

### Added files to project
* ./src/hello.js
* ./webpack.config.js
* ./src/index.js
* ./src/index.html
* ./src/images/22.jpg
* ./src/style.css


### Install webpack and needed dependencies
```
npm i -D webpack webpack-cli webpack-dev-server html-webpack-plugin copy-webpack-plugin mini-css-extract-plugin css-loader
```


# tutorial-react-without-cra
- Js transpiler since all the browser may not be up to arrow functions/class syntax ES6 type stuff.
  converts from one form of JS to another. Transpiles ES5, ES6 code to something browser understands (Babel)
  js transpiler that converts ecma script 2015 and plus code into backward compatible versions of js in current and older browser
- Js bundler - small group of files. Helps us manage dependencies, load dependencies in right order.(WebPack)
  Takes files of different files js and asset files html, css, images, js and pkgs into different smaller files, browsify, gulp.

   - npm init -y 
   - npm i react react-dom    ( create a tree Virtual DOM)
   - npm i webpack --save-dev
   - npm i webpack-cli --save-dev (watches for file changes, )
   - npm i webpack-dev-server --save-dev (start server with live reload)
   - npm i  --save-dev @babel/core  (code transpiler)
   - npm i babel-loader --save-dev (webpack uses to process different file types, ie. js code, sass loader - css.)
   - npm i @babel/preset-react --save-dev (react plugin - es2015, add supports for jsx)
   - npm i @babel/preset-env --save-dev (js bundles smaller)
   - npm i html-webpack-plugin --save-dev (simplies html, add bundles files to html)

   - webpack.config.js (entry file where webpack will create dependency graph)
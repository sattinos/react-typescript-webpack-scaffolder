![logo.png](https://github.com/sattinos/react-typescript-webpack-scaffolder/blob/master/img/logo.png?raw=true)

# react-typescript-webpack-scaffolder
react-typescript-webpack-scaffolder is a cross-platform (windows/mac/linux) node.js script that sets up React, Typescript and Webpack for a new project.


Motivation:
===========
You don't want to waste the same time in setting up Typescript, Reactjs and Webpack for every new Web project.
The process will eat time especially when modules versions conflict with each other. For example, in Webpack v4 the DevServer crashes
for any modification in the source files. The main reason for this crash is a conflict with awesome-typescript-loader module v4.
Another example, the ExtractTextWebpackPlugin is broken in Webpack v4.
The Scaffolder will take care of that, and the generated project will work with no issues.

Prerequisites:
==============
Node 9.x

Installation:
=============
npm i react-typescript-webpack-scaffolder -D

How to use:
===========
const scaffold = require('react-typescript-webpack-scaffolder');<br />
scaffold();
<br />

Currently, the scaffolder supports Webpack 4 only.
The generated project will contain the functionality:
1. Loading images of the formats (gif, png, jpeg and svg)
2. Loading css files and extract them uglified to a seperate css file.
3. Producing dev build
4. Producing production build.
5. Running in watch mode (Webpack dev server)

Once the script is finished, you can use the commands:

npm run devBuild      // to build in dev mode<br />
npm run prodBuild     // to build in production mode<br />
npm run serve         // to run webpack dev server in watch mode<br /><br />
Remember: If you want to do something twice then automate it.

Enjoy!

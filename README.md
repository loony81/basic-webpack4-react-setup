# basic-webpack-react-setup

This is a very basic already preconfigured webpack 4 development environment with all the dependencies required to start developing a web project with React and ES6. This setup already includes boostrap.min.css file as well as index.css to add custom styling. Both these files will be compiled into one resulting style.css file. But there's no support for SASS and POSTCSS compiling, just raw css.

All you have to do is just clone the repo and recreate the node_modules folder with 'npm install' command and you are good to go.

To start the webpack-dev-server run 'npm start'. For development purposes, the final bundles will be served from the memory. To create production bundles, run 'npm run build'. Webpack will output them into the 'dist' folder. And you just reference those files inside index.html:
&lt;link rel="stylesheet" type="text/css" href="dist/style.css"&gt;
<script type="text/javascript" src="dist/main.js"></script>



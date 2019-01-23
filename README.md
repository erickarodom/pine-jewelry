# Webpack 4 Boilerplate for beginners
A basic webpack 4 boilerplate for beginners to start with any JS/ES6 based project. This project uses basic html with scss. It includes working background images in scss as well as file loading in html. Uses Dev Server and Sourcemaps for easy debugging. Includes stylelinting and fixes for cleaner css. Uses Babel to convert ES6 to ES5. 
<br>
## Guide
This basic boilerplate is the final output of this comprehensive write up on Medium, plus several additions. I recommend to read this article to know the insight of how you can configure webpack from scratch.
[Webpack 3 quickstarter: Configure webpack from scratch](https://medium.com/@nirjhor123/webpack-3-quickstarter-configure-webpack-from-scratch-30a6c394038a)
<br>
1. Navigate to the appropriate parent folder of where your project will be located. This example uses a folder on the desktop called "class projects". NOTE: Start from your home directory "~".

```
$ cd path/my-projects
```

2. Clone the webpack-starter into your parent folder with the following command:

```
$ git clone https://github.com/rachy/webpack-starter.git
```
3. Change the name of webpack-starter to reflect the name of your project

4. Change your directory to the project folder. 

```
$ cd my-project
```

5. Install dependencies

```
$ npm install
```


6.  Develop locally with webpack-dev-server

```
$ npm run dev
```

## For Development version

```
$ npm run dev
```
Note: If your development browser window gets closed, you can find your project by navigating to:
[http://localhost:2000/](http://localhost:2000/)

## For Production version

```
$ npm run build
```
This is the final distribution version of your project located in the /dist folder

### To restart your project after leaving it

1. Navigate to your project folder in terminal

2. Run Dev. 

```
$ npm run dev
```

Note: it is safe to move from dev to build and build to dev. Just run [control] "c" to cancel dev processes if in the dev version.
 
## Loaders and Plugins used in this boilerplate

### Loaders
* html-loader
* sass-loader
* css-loader
* style-loader
* file-loader
* babel-loader

### Plugins
* clean-webpack-plugin
* mini-css-extract-plugin
* html-webpack-plugin
* style-lint-plugin
* optimize-css-assets-webpack-plugin
* uglify-js-plugin


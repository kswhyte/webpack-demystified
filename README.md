# Webpack Starter Kit

[Original Lesson Plan](http://frontend.turing.io/lessons/webpack-demystified.html)

### What is Webpack?

Webpack is a node feature that digs through your asset files, finds any dependencies, and spits out a single JS file that is ready for production.

What sets it apart is that it isn’t limited to only handling your JavaScript files, it thinks of everything else like a module as well. With Webpack you have access to “Loaders” which pre-process your assets (like Fonts, SASS, Images, CSS, SVGs etc) and output exactly what your browser needs to know in the smallest package possible.

It also has some really cool features like webpack-dev-server which executes Webpack whenever you refresh your browser, or a thing called hot-module-replacement which tells your project to keep an eye on any changes, automatically refreshing your browser whenever it detects action.

Big picture, Webpack finds the starter file you’ve told it to use and crawls through the tree of dependencies in the appropriate order keeping track of dependencies. It then minifies, optimizes, and loads anything it needs to make the browser happy.

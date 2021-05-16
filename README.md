# sass_base

This repository has multiple branches which each show a different way to set up SASS in a website in order to automatically convert it to CSS.

This repository is mainly intended to be used as a learning tool to understand how SASS is dependent on the environment in which it is used, i.e. there are very many ways to process it into CSS and in general, the processing is just one element in a larger process of web-bundling and task-running in order to simplify development and optimize websites.

## How to use

Switch to the appropriate branch to see the solution to process SASS into CSS.

As a learning guide, the following order is recommended:

- **with_node_sass** - The simplest solution when you only have one `main.scss` file that has to be converted to `main.css`. Uses deprecated `@import` but uses modules and is very straight-forward and pragmatic.

- **with_gulp** - This solution is very simple and should be used mostly as a way to get you up-and-running with a working version of Gulp, and see how Gulp converts SCSS to CSS, or if you merely need to convert one `.scss` file for a small website.

- **with_webpack** - 

- **with_parcel** - 

- **with_create_react_app** - 

# sass_base

This repository has multiple branches which each show a different way to set up SASS in a website in order to automatically convert it to CSS.

This repository is mainly intended to be used as a learning tool to understand how SASS is dependent on the environment in which it is used, i.e. there are very many ways to process it into CSS and in general, the processing is just one element in a larger process of web-bundling and task-running in order to simplify development and optimize websites.

## How to use

Switch to the appropriate branch to see that solution to process SASS into CSS.

As a learning guide, study the following branches in this order:

- :thumbsup: **with_node_sass** - The simplest solution when you just need to convert numerous `.scss` files into one `.css` file. It uses deprecated `@import` but has modules and so is quite extensive, straight-forward and pragmatic.

- **with_webpack** - Webpack is a JavaScript module bundler created in 2012. It is still the default website bundler although it notoriously difficult to set up and is therefore being replaced for simpler projects by Parcel. This solution is very simple and should be used mostly as a way to get you up-and-running with a working version of Website, which itself can be a challenge. Use this solution to see how Webpack converts SCSS to CSS, or if you merely need to convert one `.scss` file for a small website.

- **with_gulp** - This solution is very simple Gulp solution (although Gulp itself is not simple) and should be used mostly as a way to get you up-and-running with a working version of Gulp, and see how Gulp converts SCSS to CSS, or if you merely need to convert one `.scss` file for a small website.

- :heart: **with_parcel** - Parcel is the up-and-coming module bundler which challenges WebPack. Where Webpack is notoriously difficult to set up and configure, Parcel for the most part simply works.  This solution is up-to-date and useful in that it uses the new `@use` command to include modules which replaces the `@import` command which is now deprecated. 

- :heart: **with_create_react_app** - Using create-react-app and then making a few changes to enable SASS is probably the easiest way to use the full functionality of SASS with modules, plus you are in the rich environment of React which is definitely an advantage. 

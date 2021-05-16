# with_create_react_app

Using create-react-app and then making a few changes to enable SASS is probably the easiest way to use the full functionality of SASS with modules, plus you are in the rich environment of React which is definitely an advantage.

This solution uses the `sass` library instead of `node-sass` and so can use the `@use` commands which are recommended over the deprecated `@import` command. This solution uses two modules as an example of loading modules.

## How to use

See this howto on how to set this up manually: https://onespace.netlify.app/howtos?id=171

Or clone the repository that contains the finished solution here: 

As a learning guide, study the following branches in this order:

- :thumbsup: **with_node_sass** - The simplest solution when you just need to convert numerous `.scss` files into one `.css` file. It uses deprecated `@import` but has modules and so is quite extensive, straight-forward and pragmatic.

- **with_gulp** - This solution is very simple Gulp solution (although Gulp itself is not simple) and should be used mostly as a way to get you up-and-running with a working version of Gulp, and see how Gulp converts SCSS to CSS, or if you merely need to convert one `.scss` file for a small website.

- **with_webpack** - Webpack is a JavaScript module bundler created in 2012. It is still the default website bundler although it notoriously difficult to set up and is therefore being replaced for simpler projects by Parcel. This solution is very simple and should be used mostly as a way to get you up-and-running with a working version of Website, which itself can be a challenge. Use this solution to see how Webpack converts SCSS to CSS, or if you merely need to convert one `.scss` file for a small website.

- :heart: **with_parcel** - Parcel is the up-and-coming module bundler which challenges WebPack. Where Webpack is notoriously difficult to set up and configure, Parcel for the most part simply works.  This solution is up-to-date and useful in that it uses the new `@use` command to include modules which replaces the `@import` command which is now deprecated. 

- :heart: **with_create_react_app** - Using create-react-app and then making a few changes to enable SASS is probably the easiest way to use the full functionality of SASS with modules, plus you are in the rich environment of React which is definitely an advantage. 

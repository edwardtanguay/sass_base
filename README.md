# with_parcel

Parcel is the up-and-coming module bundler which challenges WebPack. Where Webpack is notoriously difficult to set up and configure, Parcel for the most part simply works. 

> "The cool thing with Parcel is it just figures things out."

This solution is up-to-date and useful in that it uses the new `@use` command to include modules which replaces the `@import` command which is now deprecated. Among other features, the `@use` command enables modules to have namespaces and aliases for these namespaces which is demonstrated in this solution. 


## How to use

- `npm i`
- `npm run dev` to begin watching and converting scss to css
- Important: click on the link shown by `npm run dev` in the terminal window which is a kind of Live Server
	- Live Server won't work because of a small discreption in how Parcel maps the path to the .css file
- make changes to any of the `.scss` files to see them immediately reflected in the browser

## Note

- This solution has the common modern structure where all source files are in the `src` directory and are then built to the `dist` directory with the `npm run build` command. See [this howto](https://onespace.netlify.app/howtos?id=383) that I made which shows how to easily publish this solution at Netlify (which executes the `npm run build` commands itself).

- Note that in this Parcel solution, the `index.html` file links to the `scss/main.scss` and not to `css/main.css` as the other solutions do. Parcel smartly follows this link to find out where all the .scss files it needs to watch so we don't need to tell it this.
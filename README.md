# with_node_sass

This solution automatically watches the `scss/main.scss` file and when anything changes, converts it to `css/main.css` which is read by the `index.html` file.

## How to use

- `npm i`
- `npm start`
- run Live Server on `index.html`
- make changes to `main.scss` to see them immediately reflected in the browser

## Note

- this solution uses `@import` (in the `main.scss` file) to load in other modules
- `@import` still works but is deprecated and should be replaced by `@use` (see branch: `with_parcel` for solution with `@use`)
- imported files must begin with an underscore (e.g. `_layout.scss`) so that they are not individually converted to .css
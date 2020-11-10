This is a minimal example for using parcel to configure an Elm project.

Parcel has built in support for Elm: https://parceljs.org/elm.html.
This makes use of Elm’s interop with javascript: https://guide.elm-lang.org/interop/.

Steps to run the project:

```npm start```

Steps to create this project:

1. Run `npm init -y` to create the 'package.json'.
2. Add 'index.html' and index.js' files manually. The project can then be built and started with `parcel index.html` if you have Parcel installed globally.
3. So that you don’t need Parcel installed globally, run `npm install parcel-bundler --save-dev` to install it as a local dev package and add it to the 'package.json'.
4. Add npm scripts for starting the project (`parcel index.html`) and building the project (`parcel build index.html`).
5. Run `elm init` to create the 'elm.json' file.
6. Add in Elm source code and interop with js.
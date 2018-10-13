# Elm Minify 

Minify compiled Elm modules!

[![Elm-Minify v?](https://img.shields.io/npm/v/elm-minify.svg)](https://www.npmjs.com/package/elm-minify)

![](/example.gif)

## How To Use It
The CLI is distributed through [NPM](https://www.npmjs.com/package/elm-minify):

```bash
npm i -g elm-minify
```

For example:

1. Compile your Elm module:

```bash
elm make --optimize --output=dist/main.js
```

2. Minify to `dist/main.min.js`:

```bash
elm-minify dist/main.js
```

Examples of usage and [Webpack](https://webpack.js.org/)-integration can be found in [`/examples`](https://github.com/opvasger/elm-minify/tree/master/examples).

More optimizations for Elm can be found in [the official guide](https://guide.elm-lang.org/optimization/)

## If It Isn't Working
The CLI has a number of flags to modify behavior, described here:

```bash
elm-minify --help
```

If it doesn't fit your needs or something isn't working, let me know with [a fresh issue](https://github.com/opvasger/elm-minify/issues/new)!
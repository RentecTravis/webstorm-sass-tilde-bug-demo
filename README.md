# Getting Started

## View SCSS

1. Open [`./src/index.scss`](./src/index.scss).
2. Observe that the `~` in `@import "~#style/a.scss" is underlined red.

## View `webpack.config.js`

1. Open [`webpack.config.js`](./webpack.config.js)
2. Observe that the alias `#style` is correctly mapped to the `src/style/` directory.
   `~#style` in `index.scss` should not be underlined red.

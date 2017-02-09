# standalone-react-css-transition-group

Standalone `ReactCSSTransitionGroup` implement.

Almost all code is extracted from react source code, it can be used as a `ReactCSSTransitionGroup` shim for projects based on `pract` or `inferno`.

## Install

```bash
$ npm install standalone-react-css-transition-group
```

## Usage

### Webpack config

```js
// webpack.config.js for inferno
module.exports = {
  resolve: {
    alias: {
      'react': 'inferno-compat',
      'react-dom': 'inferno-compat',
      'react-addons-css-transition-group': 'standalone-react-css-transition-group',
    },
  },
};
```

## Licence

MIT.

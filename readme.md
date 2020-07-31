# tarot-babel-config

Default Babel configuration for [Tarot](https://github.com/codynova/tarot).

This package is automatically used in the Tarot `build` process unless you have provided a custom `babelConfigPath`.

To use in your own custom configuration, install then extend this package in your babel config:

```bash
yarn add --dev tarot-babel-config
```

```jsonc
// .babelrc.json
{ "extends": "tarot-babel-config" }
```

or

```js
// babel.config.js
module.exports = {
    extends: require.resolve('tarot-babel-config'),
}
```
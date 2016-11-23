# eslint-config-nvs

This package provides a [ESLint shareable config](http://eslint.org/docs/developer-guide/shareable-configs) for the VI Company's JS coding style.

## Installation

To make use of this config, install ESLint and this package as a development dependency of your project:

```npm install eslint eslint-config-nvs --save-dev```

## Usage

Create a [`.eslintrc.*`](http://eslint.org/docs/user-guide/configuring#configuration-file-formats) config file:

### .eslintrc.js
```js
module.exports = {
  extends: 'nvs'
};
```

### .eslintrc.json
```json
{
  "extends": "nvs"
}
```

Or add the ESLint config to your `package.json`:

```json
{
  "name": "project",
  "eslintConfig": {
    "extends": "nvs"
  }
}
```

## Configuration

The default configuration supports ES2015 (ES6) code.

### Legacy code

If you need to support legacy code, you can use the [`nvs/legacy`](legacy.js) config:

```json
{
  "extends": "nvs/legacy"
}
```

## Changelog

Read the [Changelog](CHANGELOG.md)

## License

MIT © [Netvlies](http://netvlies.nl)

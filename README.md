<h1 align="center">
  <br>
  <img src="https://avatars2.githubusercontent.com/u/14073052?s=200&v=4" alt="Kinvolk" width="160">

  <img src="https://raw.githubusercontent.com/kinvolk/eslint-config/resources/eslint-logo.svg" alt="ESLint" height="160">
</h1>

# Kinvolk ESLint Config

This is a shareable ESLint config we use at [Kinvolk](https://kinvolk.io) for
our Javascript/Typescript projects.

## Installation

Install the config from NPM by using the following command:

`npm install --save-dev @kinvolk/eslint-config eslint-config-prettier`

Install also the peer dependencies NPM suggested (if they're not installed
automatically).

You can include it in your `package.json` file like the following:

```js
  "eslintConfig": {
    "extends": ["@kinvolk", "prettier", "prettier/react"]
  },
  "prettier": "@kinvolk/eslint-config/prettier-config",
```

## Development

Eslint rules should be modified in the `.eslintrc.yml` file in this repo.

### Generate index.js

The `index.js` file is generated from `.eslintrc.yml`, and can be generated using:

`make`

## License

Kinvolk's eslint-config is licensed under
[Apache 2.0](https://github.com/kinvolk/kinvolk-dev-utils/blob/master/LICENSE).

# @rdss/eslint-config

This ESLint Ruleset integrates all Javascript & Typescript related RDSS coding standard rules and can be used to run eslint on save, commit or manually.

## How to integrate this config into your project

To enable this config and ruleset in your project do the following:

1. Run `npm install --save-dev @rdss/eslint-config` to install the config as a npm dependency.
1. Create a `.eslintrc.js` in your project root.
1. Extend the created ESLint config with this config in the **extend** block: `extends: ['@rdss/eslint-config']`

A minimal example of a working `.eslintrc.js` can look like the following:

```js
/**
 * Eslint config.
 */

module.exports = {
    extends: ['@rdss/eslint-config'],
};
```

## How to run ESLint with this config

To let run ESLint with this coding standard config applied you can use several ways.
Please refer the documentation of eslint.

A common approach to check the code anyway is using `npx`:

```bash
npx eslint
```

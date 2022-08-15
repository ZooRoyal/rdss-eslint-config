# eslint-config-rdss-coding-standard

This ESLint Ruleset integrates all Javascript & Typescript related RDSS coding standard rules and can be used to run eslint on save, commit or manually.

## How to integrate this config into your project

To enable this config and ruleset in your project do the following:

1. Run `npm install --save-dev eslint-config-rdss-coding-standard` to install the config as a npm dependency.
1. Create a `.eslintrc.js` in your project root.
1. Extend the created ESLint config with this config in the **extend** block: `extends: ['rdss-coding-standard']`

A minimal example of a working `.eslintrc.js` can look like the following:

```js
/**
 * Eslint config.
 */

module.exports = {
    extends: ['rdss-coding-standard'],
};
```

## How to run ESLint with this config

### Integrate in NPM

### Integrate in VSCode

### Integrate in PHPStorm

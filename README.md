<p>
  <a href="https://www.npmjs.com/package/eslint-define-config" target="_blank">
    <img alt="NPM package" src="https://img.shields.io/npm/v/eslint-define-config.svg">
  </a>
  <a href="https://www.npmjs.com/package/eslint-define-config" target="_blank">
    <img alt="Downloads" src="https://img.shields.io/npm/dt/eslint-define-config.svg">
  </a>
  <a href="https://github.com/Shinigami92/eslint-define-config/actions/workflows/ci.yml">
    <img alt="Build Status" src="https://github.com/Shinigami92/eslint-define-config/actions/workflows/ci.yml/badge.svg?branch=main">
  </a>
  <a href="https://github.com/Shinigami92/eslint-define-config/blob/main/LICENSE">
    <img alt="License: MIT" src="https://img.shields.io/github/license/Shinigami92/eslint-define-config.svg">
  </a>
  <a href="https://prettier.io" target="_blank">
    <img alt="Code Style: Prettier" src="https://img.shields.io/badge/code_style-prettier-ff69b4.svg">
  </a>
</p>

# eslint-define-config

Provide a `defineConfig` function for `.eslintrc.js` files.

# Installation

```bash
# add eslint and eslint-define-config to project’s dev dependencies
npm install --dev eslint eslint-define-config
# or
yarn add --dev eslint eslint-define-config
```

# Usage

`.eslintrc.js`

```ts
const { defineConfig } = require('eslint-define-config');

module.exports = defineConfig({
  root: true,
  rules: {
    // rules...
  }
});
```

# Credits

- `Vite` and [Evan You](https://github.com/yyx990803) for the idea
- @antfu and her [tweet](https://twitter.com/antfu7/status/1365907188338753536)

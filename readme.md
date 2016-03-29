# eslint-config-hepsiburada

[![npm version](https://badge.fury.io/js/eslint-config-hepsiburada.svg)]
(http://badge.fury.io/js/eslint-config-hepsiburada)

This package is based on Airbnb config and provides hepsiburada's .eslintrc as an extensible shared config.

## Usage

### eslint-config-hepsiburada/legacy

Lints ES5 and below. Only requires `eslint`.

1. `npm install --save-dev eslint-config-hepsiburada eslint`
2. add `"extends": "hepsiburada/legacy"` to your .eslintrc

* We will add ES6 support later

## Improving this config

Consider adding test cases if you're making complicated rules changes, like
anything involving regexes. Perhaps in a distant future, we could use literate
programming to structure our README as test cases for our .eslintrc?

You can run tests with `npm test`. [WIP]

You can make sure this module lints with itself using `npm run lint`. [WIP]

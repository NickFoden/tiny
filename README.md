# @nickfoden/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@nickfoden/tiny.svg)](https://www.npmjs.com/package/@nickfoden/tiny)

[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@nickfoden/tiny.svg)](https://www.npmjs.com/package/@nickfoden/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @nickfoden/tiny
```

## Usage

```js
import tiny from "@nickfoden/tiny";

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```

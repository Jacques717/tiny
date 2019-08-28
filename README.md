# @jacques717/tiny

Removes all spaces from a string.

![npm](https://img.shields.io/npm/v/@jacques717/tiny)
![npm bundle size](https://img.shields.io/bundlephobia/min/tiny)

## Install

```
$ npm install @jacques717/tiny
```

## Usage

```js
const tiny = require("@jacques717/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```

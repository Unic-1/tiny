![npm (scoped)](https://img.shields.io/npm/v/@unic-1/tiny) [![install size](https://packagephobia.now.sh/badge?p=@unic-1/tiny)](https://packagephobia.now.sh/result?p=@unic-1/tiny)

# @unic-1/tiny

Removes all spaces from a string.

## Install

```
$ npm install @bamblehorse/tiny
```

## Usage

```js
const tiny = require("@bamblehorse/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```

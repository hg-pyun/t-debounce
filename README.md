# t-debounce

![npm](https://img.shields.io/npm/v/t-debounce)
![npm](https://img.shields.io/npm/dt/t-debounce)
![NPM](https://img.shields.io/npm/l/t-debounce)

The tiny debounce function.

## Installation

```shell script
$ npm install t-debounce --save
```

## How to use

```js
const debounce = require('t-debounce');
const deFunc = debounce(() => {
  console.log('exec');
}, 1000);

for (let i = 0; i < 100; i++) {
  deFunc();
}
```

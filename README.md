WDIO BrowserStack Spec Reporter
==================

> A WebdriverIO plugin to report in spec style suited for BrowserStack

*NOTE:* This plugin is forked from the [webdriverio/webdriverio](https://github.com/webdriverio/webdriverio) and extends `@wdio/spec-reporter` to report `Session IDs` for each test with a link to the BrowserStack Automate.

## Installation

```sh
$ npm install timzatko/wdio-browserstack-spec-reporter --save-dev
```

## Configuration

The following code shows the default wdio test runner configuration. Just add `'spec'` as a reporter
to the array.

```js
// wdio.conf.js
module.exports = {
  // ...
  reporters: ['dot', 'spec'],
  // ...
};
```

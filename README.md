# This repository is scheduled to be deprecated. After October 31, 2024, the contents of this repo will no longer be available on GitHub. See [developers.squarespace.com/tools](https://developers.squarespace.com/tools) for more details

Squarespace Polyfills
------------------------------

A polyfills package with the goal of standardizing polyfill implementations across Squarespace templates. [core-js](https://github.com/zloirock/core-js) implementations of static and instance methods are preferred where available.

*NOTICE: This code is licensed to you pursuant to Squarespace’s Developer Terms of Use. See license section below.*

## Usage

```sh
npm install --save @squarespace/polyfills;
```

```js
import '@squarespace/polyfills/CustomEvent';
import '@squarespace/polyfills/Element/matches';
import '@squarespace/polyfills/Element/closest';
```

### Usage Note: Bundlers

`@squarespace/polyfills` must be used with some kind of CommonJS-compatible script bundler (like Webpack, Browserify, Rollup, etc.)

## License

Portions Copyright © 2016 Squarespace, Inc. This code is licensed to you pursuant to Squarespace’s Developer Terms of Use, available at http://developers.squarespace.com/developer-terms-of-use (the “Developer Terms”). You may only use this code on websites hosted by Squarespace, and in compliance with the Developer Terms. TO THE FULLEST EXTENT PERMITTED BY LAW, SQUARESPACE PROVIDES ITS CODE TO YOU ON AN “AS IS” BASIS WITHOUT WARRANTIES OF ANY KIND, EITHER EXPRESS OR IMPLIED.

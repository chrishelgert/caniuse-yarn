# caniuse-yarn

[![npm version](https://badge.fury.io/js/%40danielbayerlein%2Fcaniuse-yarn.svg)](https://badge.fury.io/js/%40danielbayerlein%2Fcaniuse-yarn)
[![Build Status](https://travis-ci.org/danielbayerlein/caniuse-yarn.svg?branch=master)](https://travis-ci.org/danielbayerlein/caniuse-yarn)

**caniuse-yarn** checks if [Yarn](https://github.com/yarnpkg/yarn) is available.

## Installation

```bash
$ yarn add @danielbayerlein/caniuse-yarn
```

or

```bash
$ npm install @danielbayerlein/caniuse-yarn --save
```

## Usage

```javascript
const caniuseYarn = require('caniuse-yarn')();
console.log(caniuseYarn ? 'yarn' : 'npm');
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new [Pull Request](../../pull/new/master)

## Copyright

Copyright (c) 2016 Daniel Bayerlein. See [LICENSE](./LICENSE.md) for details.
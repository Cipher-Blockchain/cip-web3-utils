# cipweb3-utils

[![NPM Package][npm-image]][npm-url] [![Dependency Status][deps-image]][deps-url] [![Dev Dependency Status][deps-dev-image]][deps-dev-url]
A clone of web3-utils package named as cipweb3-utils for Cipherem chain.
This is a sub-package of [cipweb3.js][repo].

This contains useful utility functions for Dapp developers.

Please read the [documentation][docs] for more.

## Installation

### Node.js
                                                 
```bash
npm install cipweb3-utils
```

## Usage

```js
const Web3Utils = require('cipweb3-utils');
console.log(Web3Utils);
{
    sha3: function(){},
    soliditySha3: function(){},
    isAddress: function(){},
    ...
}
```

## Types

All the TypeScript typings are placed in the `types` folder.

[docs]: http://web3js.readthedocs.io/en/1.0/
[repo]: https://github.com/ethereum/web3.js
[npm-image]: https://img.shields.io/npm/v/web3-utils.svg
[npm-url]: https://npmjs.org/package/web3-utils
[deps-image]: https://david-dm.org/ethereum/web3.js/1.x/status.svg?path=packages/web3-utils
[deps-url]: https://david-dm.org/ethereum/web3.js/1.x?path=packages/web3-utils
[deps-dev-image]: https://david-dm.org/ethereum/web3.js/1.x/dev-status.svg?path=packages/web3-utils
[deps-dev-url]: https://david-dm.org/ethereum/web3.js/1.x?type=dev&path=packages/web3-utils

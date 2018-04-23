# xcxerxes-array-range [![NPM version](https://img.shields.io/npm/v/xcxerxes-array-range.svg)](https://www.npmjs.com/package/xcxerxes-array-range) [![Build Status](https://travis-ci.org/XcXerxes/xcxerxes-array-range.svg)](https://travis-ci.org/XcXerxes/xcxerxes-array-range.svg)

range array

## Example

```javascript
const range = require('xcxerxes-array-range')

console.log(range(4))
// -> [0, 1, 2, 3]

console.log(range(1, 4))
// -> [1, 2, 3]

console.log(range(4).map(item => item * item))
// -> [0, 1, 4, 9]
```

## License
Copyright © 2018 [xcxerxes](https://github.com/XcXerxes)
Released under the MIT license


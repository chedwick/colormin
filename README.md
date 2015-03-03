# colormin [![Build Status](https://travis-ci.org/ben-eb/colormin.svg?branch=master)][ci] [![NPM version](https://badge.fury.io/js/colormin.svg)][npm] [![Dependency Status](https://gemnasium.com/ben-eb/colormin.svg)][deps]

> Turn a CSS color into its smallest representation.

Install via [npm](https://npmjs.org/package/colormin):

```
npm install colormin --save
```

## Example

```js
var colormin = require('colormin');
console.log(colormin('rgba(255, 0, 0, 1)'));

// => 'red'
```

colormin works for rgb, rgba, hsl, hsla, hex & css color keywords. See more
example output in the [tests](test.js). Note that colormin does not convert
invalid CSS colors; it is not a color validator itself.

## Contributing

Pull requests are welcome. If you add functionality, then please add unit tests
to cover it.

## License

MIT © Ben Briggs

[ci]:   https://travis-ci.org/ben-eb/colormin
[deps]: https://gemnasium.com/ben-eb/colormin
[npm]:  http://badge.fury.io/js/colormin

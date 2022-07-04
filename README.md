<!--

@license Apache-2.0

Copyright (c) 2018 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->

# isFalsyArray

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Test if a value is an array-like object containing only falsy values.



<section class="usage">

## Usage

```javascript
import isFalsyArray from 'https://cdn.jsdelivr.net/gh/stdlib-js/assert-is-falsy-array@deno/mod.js';
```

#### isFalsyArray( value )

Tests if a `value` is an array-like `object` containing only falsy values.

```javascript
var bool = isFalsyArray( [ '', null, void 0, false, 0, NaN ] );
// returns true

bool = isFalsyArray( [ [], {} ] );
// returns false
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- eslint no-undef: "error" -->

```javascript
import isFalsyArray from 'https://cdn.jsdelivr.net/gh/stdlib-js/assert-is-falsy-array@deno/mod.js';

var bool = isFalsyArray( [ null, '', NaN, 0, void 0, false ] );
// returns true

bool = isFalsyArray( [ [], {}, true, 'a', 5, -5 ] );
// returns false

bool = isFalsyArray( [] );
// returns false

bool = isFalsyArray( false );
// returns false

bool = isFalsyArray( null );
// returns false
```

</section>

<!-- /.examples -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

* * *

## See Also

-   <span class="package-name">[`@stdlib/assert/is-falsy`][@stdlib/assert/is-falsy]</span><span class="delimiter">: </span><span class="description">test if a value is falsy.</span>
-   <span class="package-name">[`@stdlib/assert/is-truthy-array`][@stdlib/assert/is-truthy-array]</span><span class="delimiter">: </span><span class="description">test if a value is an array-like object containing only truthy values.</span>

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2022. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/assert-is-falsy-array.svg
[npm-url]: https://npmjs.org/package/@stdlib/assert-is-falsy-array

[test-image]: https://github.com/stdlib-js/assert-is-falsy-array/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/assert-is-falsy-array/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/assert-is-falsy-array/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/assert-is-falsy-array?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/assert-is-falsy-array.svg
[dependencies-url]: https://david-dm.org/stdlib-js/assert-is-falsy-array/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/assert-is-falsy-array/tree/deno
[umd-url]: https://github.com/stdlib-js/assert-is-falsy-array/tree/umd
[esm-url]: https://github.com/stdlib-js/assert-is-falsy-array/tree/esm
[branches-url]: https://github.com/stdlib-js/assert-is-falsy-array/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/assert-is-falsy-array/main/LICENSE

<!-- <related-links> -->

[@stdlib/assert/is-falsy]: https://github.com/stdlib-js/assert-is-falsy/tree/deno

[@stdlib/assert/is-truthy-array]: https://github.com/stdlib-js/assert-is-truthy-array/tree/deno

<!-- </related-links> -->

</section>

<!-- /.links -->

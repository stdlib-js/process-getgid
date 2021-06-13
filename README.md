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

# getgid

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] [![dependencies][dependencies-image]][dependencies-url]

> Return the numeric group identity of the calling process.

<section class="installation">

## Installation

```bash
npm install @stdlib/process-getgid
```

</section>

<section class="usage">

## Usage

```javascript
var getgid = require( '@stdlib/process-getgid' );
```

#### getgid()

Returns the numeric group identity of the calling process.

```javascript
var id = getgid();
```

</section>

<!-- /.usage -->

<section class="notes">

## Notes

-   The function **only** returns an `integer` group identity on POSIX platforms. For all other platforms (e.g., Windows, browsers, and Android), the function returns `null`. 
-   See [getgid(2)][getgid].

</section>

<section class="examples">

## Examples

<!-- eslint no-undef: "error" -->

```javascript
var getgid = require( '@stdlib/process-getgid' );

var gid = getgid();
console.log( 'gid: %d', gid );
```

</section>

<!-- /.examples -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2021. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/process-getgid.svg
[npm-url]: https://npmjs.org/package/@stdlib/process-getgid

[test-image]: https://github.com/stdlib-js/process-getgid/actions/workflows/test.yml/badge.svg
[test-url]: https://github.com/stdlib-js/process-getgid/actions/workflows/test.yml

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/process-getgid/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/process-getgid?branch=main

[dependencies-image]: https://img.shields.io/david/stdlib-js/process-getgid
[dependencies-url]: https://david-dm.org/stdlib-js/process-getgid/main

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/process-getgid/main/LICENSE

[getgid]: http://man7.org/linux/man-pages/man2/getgid.2.html

</section>

<!-- /.links -->

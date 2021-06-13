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

# Apéry's Constant

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] [![dependencies][dependencies-image]][dependencies-url]

> [Apéry's constant][apery-constant].

<section class="intro">

[Apéry's constant][apery-constant] is defined as

<!-- <equation class="equation" label="eq:apery_constant" align="center" raw="\zeta(3) = \sum_{n=1}^\infty \frac{1}{n^3} = \lim_{n\to\infty} \biggl(\frac{1}{1^3} + \frac{1}{2^3} + \cdots + \frac{1}{n^3}\biggr)" alt="Apéry's constant"> -->

<div class="equation" align="center" data-raw-text="\zeta(3) = \sum_{n=1}^\infty \frac{1}{n^3} = \lim_{n\to\infty} \biggl(\frac{1}{1^3} + \frac{1}{2^3} + \cdots + \frac{1}{n^3}\biggr)" data-equation="eq:apery_constant">
    <img src="https://cdn.rawgit.com/stdlib-js/stdlib/7e0a95722efd9c771b129597380c63dc6715508b/lib/node_modules/@stdlib/constants/float64/apery/docs/img/equation_apery_constant.svg" alt="Apéry's constant">
    <br>
</div>

<!-- </equation> -->

where `ζ(s)` is the [Riemann zeta function][@stdlib/math/base/special/riemann-zeta]

</section>

<!-- /.intro -->

<section class="installation">

## Installation

```bash
npm install @stdlib/constants-float64-apery
```

</section>

<section class="usage">

## Usage

```javascript
var APERY = require( '@stdlib/constants-float64-apery' );
```

#### APERY

[Apéry's constant][apery-constant].

```javascript
var bool = ( APERY === 1.2020569031595942 );
// returns true
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- TODO: better example -->

<!-- eslint no-undef: "error" -->

```javascript
var APERY = require( '@stdlib/constants-float64-apery' );

console.log( APERY );
// => 1.2020569031595942
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

[npm-image]: http://img.shields.io/npm/v/@stdlib/constants-float64-apery.svg
[npm-url]: https://npmjs.org/package/@stdlib/constants-float64-apery

[test-image]: https://github.com/stdlib-js/constants-float64-apery/actions/workflows/test.yml/badge.svg
[test-url]: https://github.com/stdlib-js/constants-float64-apery/actions/workflows/test.yml

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/constants-float64-apery/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/constants-float64-apery?branch=main

[dependencies-image]: https://img.shields.io/david/stdlib-js/constants-float64-apery
[dependencies-url]: https://david-dm.org/stdlib-js/constants-float64-apery/main

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/constants-float64-apery/main/LICENSE

[apery-constant]: https://en.wikipedia.org/wiki/Ap%C3%A9ry%27s_constant

[@stdlib/math/base/special/riemann-zeta]: https://github.com/stdlib-js/math-base-special-riemann-zeta

</section>

<!-- /.links -->
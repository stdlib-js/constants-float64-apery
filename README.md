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

# APERY

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> [Apéry's constant][apery-constant].

<section class="intro">

[Apéry's constant][apery-constant] is defined as

<!-- <equation class="equation" label="eq:apery_constant" align="center" raw="\zeta(3) = \sum_{n=1}^\infty \frac{1}{n^3} = \lim_{n\to\infty} \biggl(\frac{1}{1^3} + \frac{1}{2^3} + \cdots + \frac{1}{n^3}\biggr)" alt="Apéry's constant"> -->

```math
\zeta(3) = \sum_{n=1}^\infty \frac{1}{n^3} = \lim_{n\to\infty} \biggl(\frac{1}{1^3} + \frac{1}{2^3} + \cdots + \frac{1}{n^3}\biggr)
```

<!-- <div class="equation" align="center" data-raw-text="\zeta(3) = \sum_{n=1}^\infty \frac{1}{n^3} = \lim_{n\to\infty} \biggl(\frac{1}{1^3} + \frac{1}{2^3} + \cdots + \frac{1}{n^3}\biggr)" data-equation="eq:apery_constant">
    <img src="https://cdn.jsdelivr.net/gh/stdlib-js/stdlib@6e1cf583c4854b3d982f22f361f53a30c9f552dc/lib/node_modules/@stdlib/constants/float64/apery/docs/img/equation_apery_constant.svg" alt="Apéry's constant">
    <br>
</div> -->

<!-- </equation> -->

where `ζ(s)` is the [Riemann zeta function][@stdlib/math/base/special/riemann-zeta]

</section>

<!-- /.intro -->



<section class="usage">

## Usage

```javascript
import APERY from 'https://cdn.jsdelivr.net/gh/stdlib-js/constants-float64-apery@v0.0.9-deno/mod.js';
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
import APERY from 'https://cdn.jsdelivr.net/gh/stdlib-js/constants-float64-apery@v0.0.9-deno/mod.js';

console.log( APERY );
// => 1.2020569031595942
```

</section>

<!-- /.examples -->

<!-- C interface documentation. -->



<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

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

Copyright &copy; 2016-2023. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/constants-float64-apery.svg
[npm-url]: https://npmjs.org/package/@stdlib/constants-float64-apery

[test-image]: https://github.com/stdlib-js/constants-float64-apery/actions/workflows/test.yml/badge.svg?branch=v0.0.9
[test-url]: https://github.com/stdlib-js/constants-float64-apery/actions/workflows/test.yml?query=branch:v0.0.9

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/constants-float64-apery/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/constants-float64-apery?branch=v0.0.9

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/constants-float64-apery.svg
[dependencies-url]: https://david-dm.org/stdlib-js/constants-float64-apery/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/constants-float64-apery/tree/deno
[umd-url]: https://github.com/stdlib-js/constants-float64-apery/tree/umd
[esm-url]: https://github.com/stdlib-js/constants-float64-apery/tree/esm
[branches-url]: https://github.com/stdlib-js/constants-float64-apery/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/constants-float64-apery/main/LICENSE

[apery-constant]: https://en.wikipedia.org/wiki/Ap%C3%A9ry%27s_constant

[@stdlib/math/base/special/riemann-zeta]: https://github.com/stdlib-js/math-base-special-riemann-zeta/tree/deno

</section>

<!-- /.links -->

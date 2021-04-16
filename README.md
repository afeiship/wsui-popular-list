# wsui-popular-list
> Popular list for wsui.

[![version][version-image]][version-url]
[![license][license-image]][license-url]
[![size][size-image]][size-url]
[![download][download-image]][download-url]

## installation
```shell
npm i @jswork/wsui-popular-list
```

## usage
```scss
// use sass
@import '~@jswork/wsui-popular-list/dist/index.scss';

// use mixin
.test-wsui-popular-list{
  @include wsui-popular-list();
  text-align: center;
  background: #eee;
  padding: 10px 0;
  > .is-item{
    background: #f60;
    color: #fff;
  }
}
```

```html
<div class="tc test-wsui-popular-list">
  <a class="is-item" href="#">🪐</a>
  <a class="is-item" href="#">☿</a>
  <a class="is-item" href="#">♁</a>
  <a class="is-item" href="#">♃</a>
  <a class="is-item" href="#">+8</a>
</div>
```

## preview
- https://afeiship.github.io/wsui-popular-list/

## license
Code released under [the MIT license](https://github.com/afeiship/wsui-popular-list/blob/master/LICENSE.txt).

[version-image]: https://img.shields.io/npm/v/@jswork/wsui-popular-list
[version-url]: https://npmjs.org/package/@jswork/wsui-popular-list

[license-image]: https://img.shields.io/npm/l/@jswork/wsui-popular-list
[license-url]: https://github.com/afeiship/wsui-popular-list/blob/master/LICENSE.txt

[size-image]: https://img.shields.io/bundlephobia/minzip/@jswork/wsui-popular-list
[size-url]: https://github.com/afeiship/wsui-popular-list/blob/master/dist/wsui-popular-list.min.js

[download-image]: https://img.shields.io/npm/dm/@jswork/wsui-popular-list
[download-url]: https://www.npmjs.com/package/@jswork/wsui-popular-list


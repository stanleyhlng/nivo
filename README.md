<img alt="nivo" src="https://raw.githubusercontent.com/plouc/nivo/master/nivo.png" width="150" height="42" />

[![License][license-image]][license-url]
[![Travis CI][travis-image]][travis-url]
[![NPM version][npm-image]][npm-url]
[![Dependencies][gemnasium-image]][gemnasium-url]

## Layouts

### Pie

Use [d3 Pie layout](https://github.com/mbostock/d3/wiki/Pie-Layout).

#### Legends

##### PieColumnLegends

##### PieRadialLegends

##### PieSliceLegends

![PieSliceLegends](https://raw.githubusercontent.com/plouc/nivo/master/doc/nivo-pie-legend-slice.png)

### Stack

Use [d3 Stack layout](https://github.com/mbostock/d3/wiki/Stack-Layout)

## Colors

Beside highlighting data insgights, your dataviz should be pretty, right ?
**nivo** provides an easy way to deal with colors, very useful when dealing with nested components.

A lot of components have a `*Color` property, but what can we pass to it ?

- `none` will do nothing :)
- `inherit` will use color from parent context/component
- `inherit:darker(.5)` will use parent context/component color, and apply [`darker`](https://github.com/mbostock/d3/wiki/Colors#rgb_darker) function on it with an amount of `.5`
- `inherit:brighter(1)` will use parent context/component color, and apply [`brighter`](https://github.com/mbostock/d3/wiki/Colors#rgb_brighter) function on it with an amount of `1`

[license-image]: https://img.shields.io/github/license/plouc/nivo.svg?style=flat-square
[license-url]: https://github.com/plouc/nivo/blob/master/LICENSE.md
[npm-image]: https://img.shields.io/npm/v/nivo.svg?style=flat-square
[npm-url]: https://www.npmjs.com/package/nivo
[travis-image]: https://img.shields.io/travis/plouc/nivo.svg?style=flat-square
[travis-url]: https://travis-ci.org/plouc/nivo
[gemnasium-image]: https://img.shields.io/gemnasium/plouc/nivo.svg?style=flat-square
[gemnasium-url]: https://gemnasium.com/plouc/nivo
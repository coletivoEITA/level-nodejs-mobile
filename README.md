# level-nodejs-mobile

Fork of [level](https://github.com/Level/level) that is committed to support [nodejs-mobile](https://github.com/janeasystems/nodejs-mobile) because leveldown [not necessarily supports](https://github.com/Level/leveldown/issues/575) it.

## Supports

- Version 6.0.1
- Android
- iOS

## Diff

The changes made from level to level-nodejs-mobile are:

- changed dependencies: from `leveldown` to `leveldown-nodejs-mobile`

## Versioning

We will follow the convention of having the same SemVer code as the official leveldown, but with a suffix `-X` (where `X` is a number). For instance, `level-nodejs-mobile@6.0.1-3` is the `3`rd version of this library that is equivalent to `level@6.0.1`.

## License

[MIT](LICENSE.md) © 2013-present Rod Vagg and [Contributors](CONTRIBUTORS.md).

[level-badge]: https://leveljs.org/img/badge.svg

[leveldown]: https://github.com/Level/leveldown

[level-js]: https://github.com/Level/level-js

[encoding-down]: https://github.com/Level/encoding-down

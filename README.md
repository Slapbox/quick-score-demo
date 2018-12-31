# QuickScore

[![Build Status][build-badge]][build]
[![MIT License][license-badge]][license]

This is a demo of the [QuickScore](https://github.com/fwextensions/quick-score) string-scoring and fuzzy-matching library, which is based on the Quicksilver algorithm and is designed for smart auto-complete.  It lets you auto-complete against a few hundred bookmarks (title and URL) and to compare the results and speed against these string matching libraries:

* Fuse.js
* fuzzysort
* liquidmetal
* original Quicksilver algorithm

The UI is built with React, but the QuickScore library itself doesn't require it and has no dependencies.

[See the demo.](https://fwextensions.github.io/quick-score-demo)


## License

[MIT](./LICENSE) © John Dunning


[build-badge]: https://img.shields.io/travis/com/fwextensions/quick-score-demo.svg?style=flat-square&branch=dev
[build]: https://travis-ci.com/fwextensions/quick-score-demo
[license-badge]: https://img.shields.io/npm/l/quick-score-demo.svg?style=flat-square
[license]: https://github.com/fwextensions/quick-score-demo/blob/master/LICENSE

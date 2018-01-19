# spin.js [![JS.ORG](https://img.shields.io/badge/js.org-spin-ffb400.svg?style=flat-square)](http://js.org)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FEZO801%2Fspin.js.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2FEZO801%2Fspin.js?ref=badge_shield)

An animated loading spinner

 * No images, no external CSS
 * No dependencies
 * Highly configurable
 * Resolution independent
 * Uses `requestAnimationFrame()`, falling back to `setTimeout()` in IE 9
 * Works in all major browsers
 * Includes TypeScript definitions
 * MIT License


[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FEZO801%2Fspin.js.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FEZO801%2Fspin.js?ref=badge_large)

## Usage

```javascript
import {Spinner} from 'spin.js';

var target = document.getElementById('foo');
new Spinner({color:'#fff', lines: 12}).spin(target);
```

For an interactive demo and a list of all supported options please refer to the [project's homepage](http://spin.js.org).
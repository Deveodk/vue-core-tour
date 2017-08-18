# @deveodk/vue-core-tour

[![npm](https://img.shields.io/npm/v/@deveodk/vue-core-tour.svg)](https://www.npmjs.com/package/@deveodk/vue-core-tour) [![vue2](https://img.shields.io/badge/vue-2.x-brightgreen.svg)](https://vuejs.org/)

> Tour plugin for deveo core based on intro js

## Installation

```bash
npm install --save @deveodk/vue-core-tour
```
## Usage

### Bundler (Webpack, Rollup)

```js
# Example in danish
import vueCoreTour from '@deveodk/vue-core-tour'
require('@deveodk/vue-core-tour/themes/introjs-modern.css')

Vue.use(vueCoreTour, {
    scrollTo: 'tooltip',
    showStepNumbers: false,
    keyboardNavigation: true,
    nextLabel: 'Næste',
    prevLabel: 'Tilbage',
    skipLabel: 'Luk',
    doneLabel: 'Okay',
    axios: axios instance here,
    baseURL: 'API_URL HERE'
})
```

## License

[MIT](http://opensource.org/licenses/MIT)

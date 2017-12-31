# vue-pwa-mdc-template

> A PWA Vue.js project with [Material Components Web](https://github.com/material-components/material-components-web) ready to go.

## Build Setup

```bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

## Material Components Web Setup

* All component's styles (`material-components-web/dist/material-components-web.css`) are imported in `main.js`;
* All component's javascript (`material-components-web/dist/material-components-web.js`) are imported via [Webpack Provide Plugin](https://webpack.js.org/plugins/provide-plugin/) in `build/webpack.dev|prod.js`;
* Component initialization done with `mdc.autoInit()` (as described [here](https://github.com/material-components/material-components-web/blob/master/docs/getting-started.md#mdc-web-does-not-instantiate-any-components-automatically)) called in `App.vue` [mounted](https://vuejs.org/v2/api/#mounted) component life cycle.

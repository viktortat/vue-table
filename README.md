# VueTable [![CircleCI](https://circleci.com/gh/lossendae/vue-table.svg?style=shield&circle-token=2aa1824b780715141aeaed61168e185a1c1ceb67)](https://circleci.com/gh/lossendae/vue-table)

Simple table component for Vue.js 2.x with pagination and sortable columns

Documentation is available here: https://lossendae.github.io/vue-table

## Installation

```
npm install --save @lossendae/vue-table
```

Then in your component

```js 
import Vue from 'vue'
import VueTable from '@lossendae/vue-table'

// install globally...
Vue.use('vue-table', Vuetable)

// Or in your Vue component

export default {
    components: { Vuetable },
    ...
} 
```

## License

[MIT](https://github.com/lossendae/vue-table/blob/master/LICENSE)

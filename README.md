# vue-clock

> Simple clock component using Vue.js

![](screenshot.png)

## Install 

```shell
$ npm install @dangvanthanh/vue-clock --save
```

## Usage

### Vue 

#### Global

```javascript
import Vue from 'vue';
import VueClock from '@dangvanthanh/vue-clock';

Vue.use(VueClock);
```

```vue
<template>
  <div class="app">
    <vue-clock />
  </div>
</template>

<script>
import VueClock from '@dangvanthanh/vue-clock';

export default {
  components: { VueClock }
}
</script>
```

### Nuxt (or SSR)

```javascript
import Vue from 'vue';
import VueClock from '@dangvanthanh/vue-clock';
import 'vue-clock/dist/vue-clock.esm.css';

Vue.component('VueClock', VueClock);
// or
// Vue.use(VueClock);
```

### 

## License

MIT © Dang Van Thanh <dangvanthanh@dangthanh.org>

# Cute Foxes

Get the images of cute, floofy, and fluffy foxes.

I don't know why I used Vue.js, but still.

I don't get it why Vue.js v3.0.0 is more verbose than Vue.js v2.0.3.

Like see this code

```html
<!-- Vue.js Version 3  -->
<script src="https://unpkg.com/vue@3"></script>

<div id="app">{{ message }}</div>

<script>
  const { createApp } = Vue;

  createApp({
    data() {
      return {
        message: "Hello Vue!",
      };
    },
  }).mount("#app");
</script>
```

```html
<!-- Vue.js Version 2  -->
<script src="https://unpkg.com/vue@2"></script>

<div id="app">
  {{ message }}
</div

<script>
var app = new Vue({
  el: '#app',
  data: {
    message: 'Hello Vue!'
  }
})
</script>
```
As we can see the difference.

v3 is more verbose than v2.

And That is why I don't like Vue.js v3.
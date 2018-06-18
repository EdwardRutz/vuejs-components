# Vue JS Components

> Using Vue JS components

## Vue JS Notes

- See code and comments for examples
- It is good to add a prefix to component IDs to make sure they are unique, e.g. "my-component"
    `Vue.component(my-component);`
- Wrap data in a function to keep it independent and from interfering with other data objects.
```
Vue.component({
    data: function() {
        return {
        name: 'Bob'
        }
    }
});
``` 
- Render provides more flexibility than template in a Vue instance
```vuejs
new Vue({
  el: '#app',
  render: h => h(App)
})
```


## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```

For detailed explanation on how things work, consult the [docs for vue-loader](http://vuejs.github.io/vue-loader).

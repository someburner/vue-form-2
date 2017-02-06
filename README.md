# vue-form-2 (fork)

Original repo [here](https://github.com/matfish2/vue-form-2).

Removed ajax submitter code to allow custom handling of ajax/status messages.


## Installation
---
Compilation requires [babel-plugin-transform-vue-jsx](https://github.com/vuejs/babel-plugin-transform-vue-jsx).

Webpack users, use the following setup to compile the package's `jsx` files:
```js
loaders: [
    {
        test: /\.jsx?$/,
        loader: 'babel',
        exclude: /node_modules(?!\/(vue-form-2))/
    }
]
```

* [Documentation](https://matfish2.gitbooks.io/vue-form-2/content/)

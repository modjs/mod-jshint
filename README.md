mod-jshint
===

Validate javascript files with jshint


## Usage

```js
module.exports = {
    plugins: {
        "jshint": "mod-jshint"
    },
    tasks: {
        "jshint": {
            src: "./test.js"
        }
    }
};
```
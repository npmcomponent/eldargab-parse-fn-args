*This repository is a mirror of the [component](http://component.io) module [eldargab/parse-fn-args](http://github.com/eldargab/parse-fn-args). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/eldargab-parse-fn-args`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
parse-fn-args
=============

Parses function arguments.

##Usage

``` javascript
var parse = require('parse-fn-args')

function fn (a, b, c) {}

var args = parse(fn) // -> ['a', 'b', 'c']
```

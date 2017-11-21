## Compatibility
- [Kangax ES6 compatibility table](http://kangax.github.io/compat-table/es6/)


## ES Proposals / Next
- [ES proposal: optional catch binding](http://2ality.com/2017/08/optional-catch-binding.html)
- [ES proposal: Promise.try()](http://2ality.com/2017/08/promise-try.html)
- [ES proposal: class fields](http://2ality.com/2017/07/class-fields.html?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+2ality+%282ality+–+JavaScript+and+more%29)
- [ES proposal: Shared memory and atomics](http://2ality.com/2017/01/shared-array-buffer.html)
- [What Does ES2017 Bring to JavaScript?](https://appendto.com/2017/04/what-does-es2017-bring-to-javascript/)
- [Async iterators and generators](https://jakearchibald.com/2017/async-iterators-and-generators/)
- [ES proposal: arbitrary precision integers](http://2ality.com/2017/03/es-integer.html)
- [ES proposal: Shared memory and atomics](http://www.2ality.com/2017/01/shared-array-buffer.html)
- [Asyncing Feeling about JavaScript Generators](https://www.bignerdranch.com/blog/asyncing-feeling-about-javascript-generators/)
- [ES proposal: import()](http://www.2ality.com/2017/01/import-operator.html)
- [ES proposal: Rest/Spread Przoperties](http://www.2ality.com/2016/10/rest-spread-properties.html)
- [ES proposal: asynchronous iteration](http://www.2ality.com/2016/10/asynchronous-iteration.html)

### Related Libs
- [Babel: Async functions](https://babeljs.io/docs/plugins/syntax-async-functions/)


## Feature, JS version detection
- [ES Feature Tests - Kyle Simpson](https://github.com/getify/es-feature-tests)


## Modules
- [ECMAScript modules in browsers](https://jakearchibald.com/2017/es-modules-in-browsers/)


## Async/Await
- [Gotchas about async/await and Promises](https://dev.to/maxart2501/gotchas-about-asyncawait-and-promises-9di)
- [Mastering Async Await in Node.js](https://blog.risingstack.com/mastering-async-await-in-nodejs/)
- [How to write async await without try-catch blocks in Javascript](http://blog.grossman.io/how-to-write-async-await-without-try-catch-blocks-in-javascript/)
- [The 80/20 Guide to Async/Await in Node.js](http://thecodebarbarian.com/80-20-guide-to-async-await-in-node.js.html)
- [Tips for using async functions (ES2017)](http://www.2ality.com/2016/10/async-function-tips.html)
- [Async functions - making promises friendly](https://developers.google.com/web/fundamentals/getting-started/primers/async-functions)
- [ES7 async functions](https://jakearchibald.com/2014/es7-async-functions/)
- [Async Functions Proposal](https://tc39.github.io/ecmascript-asyncawait/)

### Related
- [asyncro](https://github.com/developit/asyncro)


## Decorators
- [JavaScript Decorators: What They Are and When to Use Them](https://www.sitepoint.com/javascript-decorators-what-they-are/)


## Polyfills/Shims/Transpilers

### Notes
- How to use browser implementations of new syntax instead of Babel transformation?
  - Babel should not transform syntax when browser has implemented the syntax.
  - this depends on the target browsers and their versions :(
  - core-js can be used to non syntax polifilling

- How to use browser implementations of new syntax instead of TypeScript transformation?
  - tsc can be configured to target ES6 and use ES2015+ libs or not
  - core-js can be used to non syntax polifilling

### Related Libs

- [babel-preset-env](https://github.com/babel/babel-preset-env)
- [core.js](https://github.com/zloirock/core-js)
- [regenerator](https://github.com/facebook/regenerator)
- [babel-polyfill](http://babeljs.io/docs/usage/polyfill/) [core-js][regenerator]
- [Babel.js](https://babeljs.io)


## Tricks
- [Conditionally adding entries inside Array and object literals](http://2ality.com/2017/04/conditional-literal-entries.html)
- [Require Parameters for JavaScript Functions](https://davidwalsh.name/javascript-function-parameters)


## General
- [3 Different Kinds of Prototypal Inheritance: ES6+ Edition](https://medium.com/javascript-scene/3-different-kinds-of-prototypal-inheritance-es6-edition-32d777fa16c9)
- [Object.create(null)](https://davidwalsh.name/object-create-null)
- [setTimeout VS setInterval](https://develoger.com/settimeout-vs-setinterval-cff85142555b#.kia6u6hik)
- [JavaScript Unary Operators: Simple and Useful](https://scotch.io/tutorials/javascript-unary-operators-simple-and-useful)


## Regular Expressions
- [Regular Expressions in a post-ES6 world](https://ponyfoo.com/articles/regular-expressions-post-es6)


## Arrow Function/Fat Arrow/=>
- [When 'not' to use arrow functions](https://rainsoft.io/when-not-to-use-arrow-functions-in-javascript/) [tip]


## Strings
- [4 New String Methods in ES6 that you should know](http://wesbos.com/new-es6-string-methods/)


## Arrays
- [Includes() vs indexOf() in JavaScript](https://dev.to/adroitcoder/includes-vs-indexof-in-javascript) [includes][indexOf]
- [Search JavaScript Arrays Efficiently with includes and indexOf](http://thenewcode.com/1152/Search-JavaScript-Arrays-Efficiently-with-includes-and-indexOf)


## Maps
- (What You Should Know About ES6 Maps)[https://hackernoon.com/what-you-should-know-about-es6-maps-dc66af6b9a1e#.r16zpvvq7]


## Typed Arrays
- [Exploring JavaScript: Typed Arrays](https://codingbox.io/exploring-javascript-typed-arrays-c8fd4f8bd24f#.cotf6ljbp)


## Template Strings
- [Tagged Template Literals](http://wesbos.com/tagged-template-literals/)
- [Easy Creation of HTML with JavaScript’s Template Strings](http://wesbos.com/template-strings-html/)


## Proxies
- [ES6 Features - 10 Use Cases for Proxy](http://dealwithjs.io/es6-features-10-use-cases-for-proxy/)
- [ES6 Proxies in Practice](http://www.zsoltnagy.eu/es6-proxies-in-practice/)
- [Pitfall: not all objects can be proxied transparently](http://www.2ality.com/2016/11/proxying-builtins.html)

## Promises
- [Exploring ES6: Promises](http://exploringjs.com/es6/ch_promises.html)
- [Avoid callbacks in Node.js with Bluebird promises](http://www.applandeo.com/en/avoid-callbacks-nodejs-bluebird-promises/) [node]

### Related Libs
- [bluebird](http://bluebirdjs.com/docs/getting-started.html)


## Iterators
- [Exploring ES6: Iterators](http://exploringjs.com/es6/ch_iteration.html)


## Generators
- [The Basics Of ES6 Generators](https://davidwalsh.name/es6-generators)
- [Demystifying Async Programming in Javascript](https://blog.usebutton.com/demystifying-async-programming-in-javascript-47e417566f61#.q3sxfsxsk)
- [A Practical Introduction to ES6 Generator Functions](http://thejsguy.com/2016/10/15/a-practical-introduction-to-es6-generator-functions.html)
- [Exploring ES6: Generators](http://exploringjs.com/es6/ch_generators.html)

### Related Libs
- [co](https://github.com/tj/co)

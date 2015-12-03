# NodeSchool `learnyoumongo` Solutions
Workshop: https://github.com/evanlucas/learnyoumongo

Solutions for exercises 3 through 8 are written in code that runs without transpilation.

#### Usage
```
learnyoumongo verify solution-03.js
learnyoumongo verify solution-04.js
learnyoumongo verify solution-05.js
learnyoumongo verify solution-06.js
learnyoumongo verify solution-07.js
learnyoumongo verify solution-08.js
```

## Asynchronous Solution
`solution-08-async.js` uses Bluebird to turn Mongo into an asynchronous, Promise-based API. It requires Babel to support `async`/`await` syntax.

`solution-08-async.es6` is a shim to transpile with Babel.

#### Usage
```
learnyoumongo verify solution-08-async.es6
```

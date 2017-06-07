Invocation:

```
$ npm run --silent b exponentiate.js
"use strict";

console.log(Math.sqrt(3 ** 2 + -5 ** 2));
```

The parentheses around `-5` shouldn’t be removed. Input file `exponentiate.js`:

```
console.log(Math.sqrt(3**2 + (-5)**2));
```

# Module

## `module.exports`
Use this to export a value
```
// script2.js
module.exports="123";
```
```
// script1.js
let v=require("script2.js");
console.log(v);
// 123
```

## `module.require(name)`
Require a script in the same bundle. Will be `undefined` if not running in a bundle.
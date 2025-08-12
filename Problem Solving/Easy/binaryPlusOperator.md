# Important Note: Binary + Operator in JavaScript

The binary `+` operator behaves differently when one operand is a string. It performs **string concatenation**, not numeric addition.

```js
let str = "5";
let num = 10;
let result = str + num; // result will be "510" (string)
```

Other arithmetic operators (`-`, `*`, `/`, `%`) convert strings to numbers implicitly.

Example:
```js
let str = "123";
let num = +str; // num will be 123 (number)
```

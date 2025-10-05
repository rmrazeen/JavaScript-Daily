# Sum or Product

Two numbers `a` and `b` are given. Return their sum. If both are equal, return their product.

```js
function totalProduct(a, b) {
  return a === b ? a * b : a + b;
}

// Test Cases
console.log(totalProduct(2, 0)); // 2
console.log(totalProduct(7, 7)); // 49
console.log(totalProduct(1, 2)); // 3
console.log(totalProduct(8, 6)); // 14
```
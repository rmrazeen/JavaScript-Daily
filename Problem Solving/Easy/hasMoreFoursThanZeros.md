
##  More Fours Than Zeros

Given an array `n` with integers, return `true` if it contains more `4`s than `0`s.

```js
function hasMoreFoursThanZeros(n) {
  let countFours = 0;
  let countZeros = 0;

  for (let i = 0; i < n.length; i++) {
    if (n[i] === 4) {
      countFours++;
    } else if (n[i] === 0) {
      countZeros++;
    }
  }

  return countFours > countZeros;
}

// Test Case
console.log(hasMoreFoursThanZeros([1, 2, 4, 0, 4])); // true



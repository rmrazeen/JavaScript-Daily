# Count Odd Numbers in an Array

Given an array `numbers`, return the count of odd numbers.

```js
function countOdds(numbers) {
  let oddNum = 0 ;
  for (let i = 0; i < numbers.length; i++) {
    if (numbers[i] % 2 != 0) {
      oddNum++;
    }
  }
  return oddNum;
}

// Test Cases
console.log(countOdds([1,5,2,6,5,3,9,2])); // 5
console.log(countOdds([2,6,2,5,2,8])); // 1
console.log(countOdds([1,1])); // 2
console.log(countOdds([0])); // 0
console.log(countOdds([6,3,8,2])); // 1
```
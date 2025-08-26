# Replace All 'bug' with 'flower'

Given a string `string`, replace every occurrence of the word 'bug' with 'flower'.

```js
function bugFix(string) {
  return string.replaceAll('bug', 'flower');
}

// Test Cases
console.log(bugFix('xxbugYYX')); // xxflowerYYX
console.log(bugFix('bug')); // flower
console.log(bugFix('xxbugXYYy')); // xxflowerXYYy
console.log(bugFix('bugXYYxX')); // flowerXYYxX
```
# Password Validation (Match & Length >= 20)

Given two strings `password` and `password_repeat`, check:
- They must match
- Length must be at least 20 characters

```js
function checkPassword(password, password_repeat) {
  return password === password_repeat && password.length >= 20;
}

// Test Case
console.log(checkPassword('omvdsse', 'omvdsse')); // false
```
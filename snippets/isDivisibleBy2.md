---
title: isDivisibleBy10
tags: math,beginner
---

Checks if the given number is divisble by 10.

- Use the modulo operator (%) with the value ten to check if there is a remainder after the division by ten.

```js
const isDivisibleBy10 = n => n % 10 === 0;
```

```js
isDivisibleBy10(10); // true
isDivisibleBy10(20); // true
isDivisibleBy10(25); // false
```

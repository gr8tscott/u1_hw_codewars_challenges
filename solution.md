## Return Negative

```js
function makeNegative(num) {
  return num > 0 ? -num : num
}
```

## Sum of Positive

```js
function positiveSum(arr) {
  let num = 0
  for (let i = 0; i < arr.length; i++) {
    if (arr[i] > 0) {
      num += arr[i]
    }
  }
  return num
}
```

## Function 2

```js
function square(num) {
  return num * num
}
```

## Sum Arrays

```js
function sum(numbers) {
  'use strict'
  return numbers.reduce((total, amount) => total + amount, 0)
}
```

## Reversed Strings

```js
function solution(str) {
  return str.split('').reverse().join('')
}
```

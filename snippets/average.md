### average

Returns the average of an of two or more numbers/arrays.

Use `Array.reduce()` to add each value to an accumulator, initialized with a value of `0`, divide by the `length` of the array.

```js
const average = (...arr) => [].concat(...arr).reduce((acc, val) => acc + val, 0) / arr.length;
```

```js
average([1, 2, 3]); // 2
```

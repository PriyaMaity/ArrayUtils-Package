
# 📦 @priyamaity9/arrayutils-package

A simple NPM package that provides a collection of commonly used array utility functions and more.

---

## 🚀 Installation

```
npm install @priyamaity9/arrayutils-package
```

---

## 📚 Usage

```js
const utils = require("array-utils-cw3");

console.log("Sum:", utils.sum([1, 2, 3]));                  // 6
console.log("Unique:", utils.unique([1, 2, 2, 3]));         // [1, 2, 3]
console.log("Average:", utils.average([10, 20, 30]));       // 20
console.log("Max:", utils.max([1, 4, 9]));                  // 9
console.log("Min:", utils.min([1, 4, 9]));                  // 1
console.log("isPrime(7):", utils.isPrime(7));               // true
console.log("Remove Duplicates:", utils.removeDuplicates([1,1,2,3,3])); // [1, 2, 3]
console.log("Reverse String:", utils.reverseString("hello"));           // "olleh"
console.log("isSorted:", utils.isSorted([1, 2, 3]));        // true
console.log("Range:", utils.range(1, 5));                   // [1, 2, 3, 4, 5]
```

---

## 🔧 Functions Included

| Function           | Description                                   |
|--------------------|-----------------------------------------------|
| `sum`              | Returns sum of elements in an array           |
| `unique`           | Removes duplicate entries                     |
| `average`          | Calculates the average of an array            |
| `max`              | Returns the maximum number                    |
| `min`              | Returns the minimum number                    |
| `isPrime`          | Checks if a number is prime                   |
| `removeDuplicates` | Removes repeated values                       |
| `reverseString`    | Reverses a given string                       |
| `isSorted`         | Checks if the array is sorted                 |
| `range`            | Generates a range between 2 values (inclusive)|

---

## 🧑‍💻 Author

[Priya Maity][(https://github.com/PriyaMaity/ArrayUtils-Package.git)]

---

## 📃 License

ISC

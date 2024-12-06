# JavaScript Methods

## **Array Methods**

| JavaScript Method                                                                                           | Description                                                                     | Example                                 | Example Output               |
| ----------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------- | --------------------------------------- | ---------------------------- |
| [`shift()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/shift)   | Removes the first element from an array                                         | `[1, 2, 3].shift()`                     | `Output: 1`                  |
| [`push()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/push)     | Adds one or more elements to the end of an array                                | `[1, 2, 3].push(4)`                     | `Output: [1, 2, 3, 4]`       |
| [`pop()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/pop)       | Removes the last element from an array                                          | `[1, 2, 3].pop()`                       | `Output: 3`                  |
| [`splice()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice) | Adds/removes items from an array                                                | `[1, 2, 3].splice(1, 1, 4)`             | `Output: [2]`                |
| [`sort()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/sort)     | Sorts the elements of an array mutating the original array                      | `[3, 1, 2].sort()`                      | `Output: [1, 2, 3]`          |
| [`toSorted()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/sort) | Sorts the elements of an array without mutating the original array              | `[3, 1, 2].toSorted()`                  | `Output: [1, 2, 3]`          |
| [`filter()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter) | Creates a new array with all elements that pass a test                          | `[1, 2, 3, 4].filter(x => x > 2)`       | `Output: [3, 4]`             |
| [`map()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)       | Creates a new array with the results of calling a function for each element     | `[1, 2, 3].map(x => x * 2)`             | `Output: [2, 4, 6]`          |
| [`flatMap()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)   | First applies a function to each element, then flattens the result by one level | `[1, 2, 3].flatMap(x => [x, x * 2])`    | `Output: [1, 2, 2, 4, 3, 6]` |
| [`reduce()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce) | Applies a function against an accumulator and each element                      | `[1, 2, 3].reduce((sum, x) => sum + x)` | `Output: 6`                  |
| [`some()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce)   | Tests if at least one element in the array passes the test                      | `[1, 2, 3].some(x => x > 2)	`            | `Output: true`               |
| [`every()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce)  | Tests if every element in the array passes the test                             | `[1, 2, 3].every(x => x > 0)`           | `Output: true`               |

---

## **String Methods**

| JavaScript Method                                                                                                      | Description                                        | Example                            | Example Output                          |
| ---------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------- | ---------------------------------- | --------------------------------------- |
| [`toString()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/toString)       | Converts a value to a string                       | `(123).toString()`                 | `Output: "123"`                         |
| [`toUpperCase()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/toUpperCase) | Converts a string to Uppercase                     | `"hello".toUpperCase()`            | `Output: "HELLO"`                       |
| [`toLowerCase()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/toLowerCase) | Converts a string to Lowercase                     | `"HELLO".toLowerCase()`            | `Output: "hello"`                       |
| [`concat()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/concat)           | Combines two or more strings                       | `"Hello".concat(" World!")`        | `Output: "Hello World!"`                |
| [`slice()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/slice)             | Extracts a section of a string or array            | `"JavaScript".slice(0, 4)`         | `Output: "Java"`                        |
| [`split()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/split)             | Splits a string into an array of substrings        | `"apple,banana,orange".split(",")` | `Output: ["apple", "banana", "orange"]` |
| [`includes()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/includes)       | Checks if a string contains a specified value      | `"Hello".includes("e")`            | `Output: true`                          |
| [`indexOf()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/indexOf)         | Returns the first index of a specified value       | `"JavaScript".indexOf("a")`        | `Output: 1`                             |
| [`trim()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/trim)               | Removes whitespace from both ends of a string      | `"  Hello  ".trim()`               | `Output: "Hello"`                       |
| [`padStart()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/trim)           | Pads the string from the start with another string | `"5".padStart(3, "0")`             | `Output: "005"`                         |

---

## **Number Methods**

| JavaScript Method                                                                                             | Description                                                 | Example                    | Example Output              |
| ------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------- | -------------------------- | --------------------------- |
| [`BigInt()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/BigInt)         | Creates a BigInt, a special numeric type for large Integers | `BigInt(9007199254740991)` | `Output: 9007199254740991n` |
| [`Math.floor()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/floor) | Rounds Down                                                 | `Math.floor(4.7)`          | `Output: 4`                 |
| [`Math.round()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/round) | Rounds Up & Down based on decimal                           | `Math.round(4.5)`          | `Output: 5`                 |
| [`Math.ceil()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/ceil)   | Round Up                                                    | `Math.ceil(4.3)`           | `Output: 5`                 |
| [`Math.PI`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/PI)         | Returns the value of Pi                                     | `Math.PI`                  | `Output: 3.141592653589793` |
| [`parseInt()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/parseInt)     | Converts a string to an integer                             | `parseInt("123px")`        | `Output: 123`               |
| [`parseFloat()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/parseFloat) | Converts a string to a floating-point number                | `parseFloat("3.14px")`     | `Output: 3.14`              |
| [`isFinite()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/isFinite)     | Determines whether a value is a finite number               | `isFinite(2 / 0)`          | `Output: false`             |

## **Date Methods**

| JavaScript Method                                                                                          | Description                                                               | Example                    | Example Output                  |
| ---------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------- | -------------------------- | ------------------------------- |
| [`new Date()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/BigInt)    | Creates a new Date object representing the current date and time          | `new Date()`               | `Output: current date and time` |
| [`getTime()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/floor) | Returns the time in milliseconds since the Unix Epoch                     | `new Date().getTime()`     | `Output: timestamp in ms`       |
| [`getDay()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/round)  | Returns the day of the week (0-6) from a Date object                      | `new Date().getDay()`      | `Output: day of the week (0-6)` |
| [`parse()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/round)   | Parses a date string into the number of milliseconds since the Unix Epoch | `Date.parse("2024-12-04")` | `Output: 1701676800000`         |

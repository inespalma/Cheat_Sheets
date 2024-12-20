# JavaScript Methods

## :roller_coaster: **Array Methods**

| JavaScript Method                                                                                                     | Description                                                                                      | Example                                                            | Example Output               |
| --------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------ | ---------------------------- |
| [`every()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/every)             | Tests if every element in the array passes the test                                              | `[1, 2, 3].every(x => x > 0)`                                      | `Output: true`               |
| [`filter()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)           | Creates a new array with all elements that pass a test                                           | `[1, 2, 3, 4].filter(x => x > 2)`                                  | `Output: [3, 4]`             |
| [`find()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/find)               | Returns the first element in the array that satisfies the provided testing function              | `[1, 2, 3, 4].find(x => x > 2)`                                    | `Output: 3`                  |
| [`findIndex()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/findIndex)     | Returns the index of the first element in the array that satisfies the provided testing function | `[1, 2, 3, 4].findIndex(x => x > 2)`                               | `Output: 2`                  |
| [`flatMap()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/flatMap)         | First applies a function to each element, then flattens the result by one level                  | `[1, 2, 3].flatMap(x => [x, x * 2])`                               | `Output: [1, 2, 2, 4, 3, 6]` |
| [`map()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)                 | Creates a new array with the results of calling a function for each element                      | `[1, 2, 3].map(x => x * 2)`                                        | `Output: [2, 4, 6]`          |
| [`pop()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/pop)                 | Removes the last element from an array                                                           | `[1, 2, 3].pop()`                                                  | `Output: 3`                  |
| [`push()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/push)               | Adds one or more elements to the end of an array                                                 | `[1, 2, 3].push(4)`                                                | `Output: [1, 2, 3, 4]`       |
| [`reduce()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce)           | Applies a function against an accumulator and each element                                       | `[1, 2, 3].reduce((sum, x) => sum + x)`                            | `Output: 6`                  |
| [`reduceRight()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduceRight) | Same as `reduce()`, but processes the array from right to left                                   | `[1, 2, 3].reduceRight((acc, currentValue) => acc - currentValue)` | `Output: -2`                 |
| [`shift()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/shift)             | Removes the first element from an array                                                          | `[1, 2, 3].shift()`                                                | `Output: 1`                  |
| [`slice()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/slice)             | Extracts a section of an array and returns a new array                                           | `[1, 2, 3, 4].slice(1, 3)`                                         | `Output: [2, 3]`             |
| [`sort()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/sort)               | Sorts the elements of an array mutating the original array                                       | `[3, 1, 2].sort()`                                                 | `Output: [1, 2, 3]`          |
| [`toSorted()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/sort)           | Sorts the elements of an array without mutating the original array                               | `[3, 1, 2].toSorted()`                                             | `Output: [1, 2, 3]`          |

---

## :1234: Number Methods

| JavaScript Method                                                                                             | Description                                                 | Example                    | Example Output              |
| ------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------- | -------------------------- | --------------------------- |
| [`BigInt()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/BigInt)         | Creates a BigInt, a special numeric type for large Integers | `BigInt(9007199254740991)` | `Output: 9007199254740991n` |
| [`Math.abs()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/abs)     | Returns the absolute value of a number                      | `Math.abs(-5)`             | `Output: 5`                 |
| [`Math.ceil()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/ceil)   | Round Up                                                    | `Math.ceil(4.3)`           | `Output: 5`                 |
| [`Math.floor()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/floor) | Rounds Down                                                 | `Math.floor(4.7)`          | `Output: 4`                 |
| [`Math.PI`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/PI)         | Returns the value of Pi                                     | `Math.PI`                  | `Output: 3.141592653589793` |
| [`Math.round()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/round) | Rounds Up & Down based on decimal                           | `Math.round(4.5)`          | `Output: 5`                 |
| [`parseFloat()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/parseFloat) | Converts a string to a floating-point number                | `parseFloat("3.14px")`     | `Output: 3.14`              |
| [`parseInt()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/parseInt)     | Converts a string to an integer                             | `parseInt("123px")`        | `Output: 123`               |
| [`isFinite()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/isFinite)     | Determines whether a value is a finite number               | `isFinite(2 / 0)`          | `Output: false`             |

---

## :pencil2: **String Methods**

| JavaScript Method                                                                                                      | Description                                        | Example                            | Example Output                          |
| ---------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------- | ---------------------------------- | --------------------------------------- |
| [`concat()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/concat)           | Combines two or more strings                       | `"Hello".concat(" World!")`        | `Output: "Hello World!"`                |
| [`includes()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/includes)       | Checks if a string contains a specified value      | `"Hello".includes("e")`            | `Output: true`                          |
| [`indexOf()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/indexOf)         | Returns the first index of a specified value       | `"JavaScript".indexOf("a")`        | `Output: 1`                             |
| [`padStart()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/padStart)       | Pads the string from the start with another string | `"5".padStart(3, "0")`             | `Output: "005"`                         |
| [`slice()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/slice)             | Extracts a section of a string or array            | `"JavaScript".slice(0, 4)`         | `Output: "Java"`                        |
| [`split()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/split)             | Splits a string into an array of substrings        | `"apple,banana,orange".split(",")` | `Output: ["apple", "banana", "orange"]` |
| [`toLowerCase()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/toLowerCase) | Converts a string to Lowercase                     | `"HELLO".toLowerCase()`            | `Output: "hello"`                       |
| [`toString()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/toString)       | Converts a value to a string                       | `(123).toString()`                 | `Output: "123"`                         |
| [`toUpperCase()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/toUpperCase) | Converts a string to Uppercase                     | `"hello".toUpperCase()`            | `Output: "HELLO"`                       |
| [`trim()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/trim)               | Removes whitespace from both ends of a string      | `"  Hello  ".trim()`               | `Output: "Hello"`                       |

---

## :date: **Date Methods**

| **Method**                                                                                                           | **Description**                                                           | **Example**                | **Output**                            |
| -------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------- | -------------------------- | ------------------------------------- |
| [`Date.parse()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/parse)        | Parses a date string into the number of milliseconds since the Unix Epoch | `Date.parse("2024-12-04")` | `Output: 1701676800000`               |
| [`getDate()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/getDate)         | Returns the day of the month from a Date Object                           | `new Date().getDate()`     | `Output: day of the month (1-31)`     |
| [`getDay()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/getDay)           | Returns the day of the week (0-6) from a Date object                      | `new Date().getDay()`      | `Output: day of the week (0-6)`       |
| [`getFullYear()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/getFullYear) | Returns the four-digit year (e.g., 2024) from a Date object               | `new Date().getFullYear()` | `Output: 2024`                        |
| [`getMonth()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/getMonth)       | Returns the month (0-11) from a Date object                               | `new Date().getMonth()`    | `Output: month index (0-11)`          |
| [`getTime()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/getTime)         | Returns the time in milliseconds since the Unix Epoch                     | `new Date().getTime()`     | `Output: timestamp in ms`             |
| [`new Date()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date)                | Creates a new Date object representing the current date and time          | `new Date()`               | `Output: current date and time`       |
| [`setDate()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/setDate)         | Sets the day of the month (1-31) for a Date object                        | `new Date().setDate(15)`   | `Output: new date with updated day`   |
| [`setMonth()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/setMonth)       | Sets the month (0-11) for a Date object                                   | `new Date().setMonth(5)`   | `Output: new date with updated month` |
---
## Time - Local Time Methods / UTC Time Methods

| **Date Type**       | **Description**                                                   | **Example Method**            | **Example Output**                        |
| ------------------- | ----------------------------------------------------------------- | ----------------------------- | ----------------------------------------- |
| `Local Time`        | Represents the date and time based on the user's local timezone.  | `new Date().toString()`       | `Mon Dec 09 2024 12:34:56 GMT+0000 (UTC)` |
| `UTC Time`          | Represents the date and time in Coordinated Universal Time (UTC). | `new Date().toUTCString()`    | `Mon, 09 Dec 2024 12:34:56 GMT`           |
| `ISO 8601 Format`   | Standardized date format used across systems, always in UTC.      | `new Date().toISOString()`    | `2024-12-09T12:34:56.789Z`                |
| `Locale-based Time` | Represents date and time formatted based on the user's locale.    | `new Date().toLocaleString()` | `12/9/2024, 12:34:56 PM`                  |

#### **Local Time Methods**

| **Method**          | **Description**                                                   | **Example**                    | **Output**                                |
| ------------------- | ----------------------------------------------------------------- | ------------------------------ | ----------------------------------------- |
| `toString()`        | Converts to a string in the local time zone                       | `new Date().toString()`        | `Mon Dec 09 2024 12:34:56 GMT+0000 (UTC)` |
| `toLocaleString()`  | Formats date and time according to the user's locale and timezone | `new Date().toLocaleString()`  | `12/9/2024, 12:34:56 PM`                  |
| `getHours()`        | Gets the hours in local time                                      | `new Date().getHours()`        | `12`                                      |
| `getMinutes()`      | Gets the minutes in local time                                    | `new Date().getMinutes()`      | `34`                                      |
| `getSeconds()`      | Gets the seconds in local time                                    | `new Date().getSeconds()`      | `56`                                      |
| `getMilliseconds()` | Gets the milliseconds in local time                               | `new Date().getMilliseconds()` | `789`                                     |

#### **UTC Time Methods**

| **Method**             | **Description**                       | **Example**                       | **Output**                 |
| ---------------------- | ------------------------------------- | --------------------------------- | -------------------------- |
| `toISOString()`        | Converts to ISO 8601 format, in UTC   | `new Date().toISOString()`        | `2024-12-09T12:34:56.789Z` |
| `getUTCFullYear()`     | Gets the year in UTC time             | `new Date().getUTCFullYear()`     | `2024`                     |
| `getUTCMonth()`        | Gets the month in UTC time            | `new Date().getUTCMonth()`        | `11`                       |
| `getUTCDate()`         | Gets the day of the month in UTC time | `new Date().getUTCDate()`         | `9`                        |
| `getUTCDay()`          | Gets the day of the week in UTC time  | `new Date().getUTCDay()`          | `1`                        |
| `getUTCHours()`        | Gets the hours in UTC time            | `new Date().getUTCHours()`        | `12`                       |
| `getUTCMinutes()`      | Gets the minutes in UTC time          | `new Date().getUTCMinutes()`      | `34`                       |
| `getUTCSeconds()`      | Gets the seconds in UTC time          | `new Date().getUTCSeconds()`      | `56`                       |
| `getUTCMilliseconds()` | Gets the milliseconds in UTC time     | `new Date().getUTCMilliseconds()` | `789`                      |

 

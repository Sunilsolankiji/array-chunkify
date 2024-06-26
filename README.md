﻿# array-chunkify

A utility to split an array into chunks of a specified size. Useful for pagination or batching operations.

## Installation

You can install the package using npm:

```sh
npm install array-chunkify
```

## Usage

```javascript
const chunkArray = require('array-chunkify');
```

Then, you can use the chunkArray function to split an array into chunks:

```javascript
const array = [1, 2, 3, 4, 5, 6, 7, 8, 9];
const chunked = chunkArray(array, 3);

console.log(chunked);
// Output: [[1, 2, 3], [4, 5, 6], [7, 8, 9]]
```

### API

`chunkArray(array, size)`
Splits an array into chunks of the specified size.

### Parameters
array (Array): The array to split into chunks.
size (number): The size of each chunk.

### Returns
Array[]: An array containing the chunks.

### License
This project is licensed under the MIT License - see the LICENSE file for details.

### Author
**Sunil Solanki**

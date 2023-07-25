# Next Perfect Square Code Challenge

This code challenge involves writing a JavaScript function that finds the next perfect square after the given input and returns it. A perfect square is an integer whose square root is also an integer.

## Function Signature

```js
function perfectSquare(n);
```

### Input

- The `perfectSquare` function takes a single argument `n`, which is a non-negative integer.

### Output

- The function should return the next perfect square after the input `n`.
- If the input itself is not a perfect square, the function should return `-1`.

### Examples

```js
perfectSquare(9);    // Output: 16 (3x3=9, 4x4=16)
perfectSquare(289);  // Output: 324 (17x17=289, 18x18=324)
perfectSquare(3000); // Output: -1 (square root of 3000 is 54.77)
```

### Implementation Details

The implementation of the `perfectSquare` function involves the following steps:

1. Find the square root of the input `n`.
2. Check if the square root is an integer (perfect square).
3. If the square root is an integer, increment it by 1 to find the next perfect square and return its value.
4. If the square root is not an integer, return `-1`.

### How to Use the Function

1. Copy the code from `perfectSquare.js` and paste it into your JavaScript environment or file.
2. Call the `perfectSquare` function with a non-negative integer as an argument.
3. The function will return the next perfect square or `-1` based on the input.

### Testing

You can test the function with the provided examples or write additional test cases to further validate its correctness.

```js
console.log(perfectSquare(25));   // Output: 36 (5x5=25, 6x6=36)
console.log(perfectSquare(100));  // Output: 121 (10x10=100, 11x11=121)
console.log(perfectSquare(0));    // Output: 1 (0x0=0, 1x1=1)
console.log(perfectSquare(17));   // Output: -1 (Not a perfect square)
```

Remember to handle edge cases and validate the input for non-negative integers. Enjoy the challenge!
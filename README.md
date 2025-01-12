# Type '{ x: number; y: number; }' is not assignable to type 'number'
This TypeScript code demonstrates a common type error.  The `printCoord` function expects an object with `x` and `y` properties of type number.  However, passing a number directly will lead to a type error. The solution involves correctly passing an object that matches the expected type.

## How to reproduce
1. Save the code in `bug.ts`
2. Try to compile the code using the TypeScript compiler (tsc).
# Functions

### Definition

Reusable code, a block of code that can be used to fulfill a task

### Related Terms

- **parameters**: inputs for our functions; placeholders for arguments
- **arguments**: values we pass into a function during execution
- **anonymous function**: a function with no name
- **callback**: a function passed to another as an argument/parameter
- **return**: output from our function

### Examples

```js
/**
 * Writing functions
 */

// Declaration
function myFunction(param1, param2) {
	// Placeholder names are parameters
	// Logic goes here
	return; // Returns undefined by default
}

// Expression
const myOtherFunction = function (param1, param2) {
	// We store an anonymous function in a variable
	// Logic goes here
	return; // Returns undefined by default
};

// Arrow function
const myArrowFunction = (param1, param2) => {
	// We store an anonymous function in a variable
	// Logic goes here
	return; // Returns undefined by default
};

// Callback example
const higherOrderFunction = function (otherFunction) {
	otherFunction();
};

higherOrderFunction(function () {
	console.log('Hello');
});
```

# Variables

### Definition

A container, or storage, for a value.

### Related Terms

- **const**: a variable that can't change (cannot be reassigned)
- **let**: a variable that can be modified (can be reassigned)
- **var**: can be reassigned (like `let`), global-scoped
- **block-scoped**: only accessible within a set or curly brackets / braces
- **function-scoped**: only accessible in the function it is defined in

### Examples

```js
/**
 * Writing variables
 */

// Can be reassigned, function-scoped
var myBool = true;

// Can be reassigned, block-scoped
let myNum = 12;

// Cannot be reassigned, block-scoped
const myString = 'hello';
```

# Bad Symbol (or Unexpected Symbol)
This error occurs when a symbol (token) is given to the parser that is not expected for example:
```js
var Hi)
//    ^
// Not expected
```
usually the error message will also provide you with the faulty character like:
```bash
> file (line: 1): syntax error: unexpected symbol (near ')')
```
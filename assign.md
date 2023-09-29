# Assignment Expected
This error occurs when '++', '--', +=', '-=', '*=', '/=', '%=', ':=' or '=' is expected in an expression.
***
This error can be raised when there is just a floating word in your code like:
```js
print("Hi");
var x = 10;

o // errors
```
usually the error provides you with the faulty character like:
```bash
file (line: 1): syntax error: '++', '--', +=', '-=', '*=', '/=', '%=', ':=' or '=' expected (near 'o')
```

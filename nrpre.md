# Not Resolved Predefined Value
This error is occurred when the Preprocessor does not handle a `<pre>` value either because the preprocessor was not used or an error occurred with the preprocessor.

Example:
```js
var x <pre> = math.sqrt(10000) // Should calculate on preprocess/compile time
```
if x does not calculate on preprocess time this error gets raised.
# wtfjs
js fckery

1. [increment operation](https://www.ecma-international.org/ecma-262/5.1/#sec-11.3.1)
```{javascript}
var a = '1';
a++ // gives 1
var a = '1';
a = a + 1; // gives '11' 
```

2. Check string for NaN type

```js
a = '';
console.log(a);
// output: ""

console.log(isNaN(a));
// output: false

console.log(parseInt(a));
// output: NaN
```

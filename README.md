# jsFuck-WhatsTheSum

A simple webpage created using JSFuck to calculate the sum of two numbers.


## Introduction

JSFuck-SumCalc is a unique calculator that leverages the esoteric and obfuscated programming style known as JSFuck to compute the sum of two numbers. This project demonstrates the creative and unconventional use of JavaScript for educational and experimental purposes.

---
JSFuck is an esoteric and educational programming style based on the atomic parts of JavaScript. It uses only six different characters to write and execute code.
 
## Basics
- False       =>  ```![]```
- true        =>  ```!![]```
- undefined   =>  ```[][[]]```
- NaN         =>  ```+[![]]```
- 0           =>  ```+[]```
- 1           =>  ```+!+[]```
- 2           =>  ```!+[]+!+[]```
- 10          =>  ```[+!+[]]+[+[]]```
- Array       =>  ```[]```
- Number      =>  ```+[]```
- String      =>  ```[]+[]```
- Boolean     =>  ```![]```
- Function    =>  ```[]["filter"]```
- eval        =>  ```[]["filter"]["constructor"]( CODE )()```
- window      =>  ```[]["filter"]["constructor"]("return this")()```

### What's Happening Behind the Scenes?

We've got a nifty little function that does the magic of summing up two numbers:

```javascript
function calculateSum() {
    var num1 = document.getElementById('num1').value;
    var num2 = document.getElementById('num2').value;
    var sum = parseInt(num1) + parseInt(num2);
    document.getElementById('result').innerHTML = "The sum is: " + sum;
}
```

We’ve converted this function into JSFuck, and the converted code is safely tucked away in `script.js`.
# Functions, Methods, and Objects  

**Functions** group a set of related statements together that represent a single task  
- take parameters (steps to complete task) and may return a value  

To *declare* a function:
1. Give function name 
2. Write needed statements 
```javascript 
function sayHello() {
  document.write('Hello!');
}
```
To *call* a function:
1. Only need one set of code; the function name *(e.g. ^ `sayHello()`)*  
2. Can call function as many times 
3. Can call function in doc even before declared

Functions that need more info:
```javascript 
function getArea(width, height){
  return width * height; 
}
```
The **parameters** *(^e.g. width and height^)* act as variables  

To *call* information functions:
1. The function name plus **arguments** (further values)
- *e.g.*:
```javascript
getArea(3,5)
```
To get single value from function: 
1. Utilize the *return* keyword:
```javascript 
function calculateArea(width, height) {
  var area = width * height; 
  return area;
}
var wallOne = calculate Area(3,5);
var wallTwo = calculateArea(8,5);
```
To get multiple values from function:  
1. 
```javascript 
function getSize(width, height, depth) {
  var area = width * height;
  var volume = width * height *depth;
  var sizes = [area, volume]; 
  return sizes; 
}
var areaOne = getSize(3,2,3)[0];
var volumeOne = getSize(3,2,3)[1];
```

**Function expression** when function is treated as an expression
- No name; ***anonymous function***
```javascript 
var area = function(width, height){
return width * height;
}
var size = area(3,4);
```
- Varible can be called again (similar to declaration)
*can NOT be called before its discovered and previous code can alter expression

**Varible Scope** is the location you declare a variable, which can effect where its used 
- *local variable*: within a function (can only be used within that function)  
- *global variable*: outside a function (can be used anywhere)  

# Decisions and Loops  

**Conditional statements** lets code make next step decisions

**Comparison operators** compare two operands  
  - `===`: strictly equal to 
  - `!==`: strictly not equal to 
  - `==`: is equal to 
  - `!=`: is not equal to 
  - `<`: greater than
  - `>`: less than 
  - `>=`: greater than or equal to 
  - `<=`: less than or equal to  
- *operands*: performs operation(s) to produce a result  
 
**Logical operators** combines multiple comparison operators  
- `&&`: "logical and" (tests more than one condition)
  - true && true = true 
  - true && false = false
  - false && true = false 
  - false & false = false 
- `||`: "logical or" (operator tests at least one condition)  
  - true || true = true 
  - true || false = true 
  - false || true = true 
  - false || false = false 
- `!`: "logical not" (inverts single Boolean value)  
  - !true = false 
  - !false = true  

**if statements** checks a condition (true? then run || false? don't run)
- *e.g.* 
```javascript 
if (score >= 50) { 
 congratulate();  
}
```

**if...else statements** runs differents sets of code whether the condition is true or not  
- "run one set of code if a condition is true, and another if it is false"
- *e.g.* 
```javascript
if (score >= 50) {
 congratulate(); 
 } 
 else { 
  encourage(); 
  }
```  
**Switch statements** compares a value against possible outcomes  
- *also provides a default option if none match  
- has a list of values that it goes through to evaluate to true then a break option to not keep running through the code *(also has a default it runs if none other true)*

____
# Decisions and Loops Pt.2  

"Data types can be coereced from one type to another" *(JS wants to do everything it can to not report an error)*

***All*** values = either truthy or falsy  

**Loops** checks a condition
-True? Run code block 
-False? Don't run 
- `for` loops: used when need to run specific number of times *(condition usually counter which tells it how many times to run)* 
 ```javascript 
 for (var i = 0; i < 10; i++) {
      document.write(i);
}
```
- `while` loops: used when need to run unknown number of times *(don't have to use counter and runs until false)*
```javascript 
while (i <= 10) {
  congratulate();
  }
 ``` 
- `do...while` loops: similar to while loop but will run at least once, even if false
```javascript 
do {
  congratulate(i);
 i++;
 }while(i<=10);
 }
 }
 ```

# Rules of Tails

------------

## Operators: 

### Add/Addition Operator: 

#### Example: 
`value1 + value2` -> here we are adding `value1`'s value to `value2`'s value, so if `value1` = 1, and `value2` = 2, it does `3 + 3`

---

### Subtract/Minus Operator:
#### Example: 
`value1 - value2` -> here if say `value1` = 5 and `value2` = 10, then what happens is: 5 - 10 

---

### Multiply/Times operator: 
#### Example: 
`value1 * value2` -> here if `value1` = 5 and `value2` = 5, we get 25 

---
### Division operator: 
#### Example: 
`value1 / value2` -> here if `value1` = 5 and `value2` = 5, we get 1

---

### strictly equals operator: 
*the main purpose of this addition is so that checks string und number literals can ask whether something is exactly like that `==` is loose equality, it doesn't care about casing, punctuation etc*
#### Example: 
` if ("ILoveIt" === "ILoveIt") {...}` -> it returns an implicit Boolean here, it isn't obvious but it's asking whether it's true that both strings match eachother exactly 

---
### strictly NOT equals operator: 
#### Example: 
`if ("ILoveIt" !=== "IloveIt") {...}` -> same again implicit boolean, it would return true here. 

---
### More than Operator: 
#### Example
`if (2 > 1) {...}` -> implicit boolean here, pretty self explanatory what it's asking

---
### Less Than Operator:
#### Example: 
`if (1 < 2) {...}` -> implicit boolean again, self explanatory 

---
### More than Equals Operator:
#### Example: 
`if (2 => 1) {...}` -> (a lil deviation from the C standards, it was high time that was fixed (tf is `>=` bru?), implicit boolean, self explanatory

---
### add compound operator:
#### Example: 
`x += 10` -> `x = x + 10` 

---
### subtract compound operator:
#### Example:
`x -= 10` -> `x = x - 10`

---
### Literal AND: 
#### Example:
`operation & operation` -> chaining operator, it's a way of chaining operations together in a visually distinct way

---
### Logical/Boolean AND:
#### Example:
`var result = (x > 2) && (x > 2)` -> checks if both operations are greater than 2

---
### NAND: 
#### Example:
`var result = (x > 2) !&& (x > 2)` -> checks if both operations are NOT greater than 2 

---
### Bitwise AND: 
#### Example:
```
int a = 5,
int b = 3
result = a &&& b
```
---
### Boolean/Logical OR:
#### Example: 
`if (x > 0 || y > 0) {...}` implicit boolean here, lets say `x` = 5, and `y` = 0, it would return `true` because `||` checks if one or both expressions are true otherwise it returns a `false`

---
### Bitwise OR: 
#### Example:
```
int a = 7,
int b = 4
result = a | b 
```

---
### Logical NOT:
#### Example: 
`if !(x || b) {...}` -> implicit boolean here, it only returns true if both operations are false

<u>***operator overloading is allowed***</u>

-------


## Access Semantics: 

### standard library: 

`std.interop` -> this grabs the interop function from interface `std`

---

let's say we have a class `class MyOp` and class `MyOp` has a function (static one), to access that `MyOp.MyFunction()` and lets say `MyFunction()` has some instance methods, 

`MyOp.MyFunction().MyInstanceMethod` 

---

interfaces work like classes: 

`IMyInterface.MyClass.MyStaticFunction().MyInstanceMethod` for instance, almost C++... `IMyInterface::MyClass::MyFunction::Fuckyou` 

---
Generics operate the same, 

`GMyGeneric.MyConstruct` -> in Generic's `construct` is a special type of class which means variables inside of it cannot escape encapsulation unless you access then like show at the start of line 132 

---
OBJECTS operate the same, you simply say `OMyObject[].MyFunction` -> OBJECTS do not allow for classes or interfaces 

---






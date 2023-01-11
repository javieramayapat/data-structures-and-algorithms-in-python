# Data Structures and Algoritms in Python

## Chapter 1: Objects in python

Python´s Built-In Classes: Mutable vs Inmutable

- **inmutable:**  A class is inmutable if  each  object of that class has a fixed  value upon  instantiation that  cannot  be changed.

|  Class | Description  | Inmutable?  |
| ------------ | ------------ | ------------ |
|  bool |Boolean value   | ✅  |
| int  |  Integer (arbitrary magnitude)  | ✅ |
| float  | Floating-point number  | ✅  |
| list | Mutable secuence of objects  | ❌  |
| tuple  | Inmutable sequence of  objects   |❌   |
| str  | character string  | ✅  |
|  set |  unordered set of distinct objects | ❌  |
| frozenset  | Inmutable for of set class  | ✅  |
| dict  | associative  mapping (aka dictionary)  | ❌  |

### The bool class 
This clas is use to:
- Manipulate logical boolean values like **TRUE** and **False**

📑 Interesting facst
- Did you know that the  default constructor `bool()` return `FALSE` 🕵️
- A number that is is equal to `cero` is avaluated as `FALSE`
- A number grayther  than `cero` is evaluated as `TRUE`
- Sequences and other container types, such as `strings` and `lists`, evaluate to `False` if empty and `True` if nonempty.
- An important application of this interpretation is the use of a nonboolean value as a condition in a control structure

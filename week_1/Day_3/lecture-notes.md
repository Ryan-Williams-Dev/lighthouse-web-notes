
# Lecture day 3

---

## General tips

- Hop in to Mentor queue at least once per day
- Always ask question

---

## Primative Data Types
- strings
- number
- booleans
- null
- undefined
- symbol
- bigint
> NaN is a number type
Everything else, not in this list, is an Object.
- typeof will tell you the data type
```
const firstName = "Harry";
console.log(typeof firstName);
```
To make a number a bigint, end your number in n, e.g.:
```
9474938564398563485n
```
bigints must be used with other bigints

---

## Objects

#### General

- Allows us to store multiple datatypes
  - Arrays do the same thing, are also technically objects
- Allows to conceptualise a real thing with properties
- In [ ] notation we have to pass in a string with quotations, if no quotes it will interpret it as a variable name. 
- If we know explicitly what the key will be, use dot notation object.key
- If we don't know the key name, for example looping through keys. use the [variableName] notation
- You *CANNOT* reference a key via variable name with dot notation

#### Passing Values

- **Primatives pass by value**
  - We create a copy for the function, does not affect the value in the global scope
- **Objects are passed by reference**
  - Making changes to objects in a function, makes changes to the actual object outside the function too. Mutate them
- Use pythontutor to visualise what is executing

#### Summary

Passing in primatives passes in a new copy of the data, passing in Objects passes i a reference to the same data in memory.

---

#### Methods

- Functions within/ belonging to Object
- Can pass in functionName to have it as method, or call it functionName() to give it only the return value of the function.

---

#### Keyword: this

- You can use keyword this for using same function/method in different objects

---

#### Looping Through Objects

- For-in Loop - loops through keys of object
  - Can use bracket notation object[key] in a for in loop to access the value of the current key

# TYPES, VALUES, AND VARIABLES

Answer all question!

## 3.1 Overview and Definitions

1. The kinds of values that can be represented and manipulated in a programming language are known as ?

2. When a program needs to retain a value for future use, it assigns the value to or stores the value in a ?

3. The answer to question 1 can be divided into two categories, name them.

4. List all the examples of the answers provided in question 3. 

5. There are two types in JavaScript that method cannot be invoked on, name them.

6. What is the difference between *immutable* and *mutable*. **Give code samples.** 

7. What is the difference between *undefined* and *null*?

8. Explain what you know about *Object-oriented programming*?

9. *"JavaScript differs from more static languages in that functions and classes are not just part of the language syntax: they are themselves values that can be manipulated by JavaScript programs"*. Explain.

10. What do you understand by *"JavaScript interpreter performs automatic garbage collection for memory management"*?

11. "*JavaScript constants and variable are untyped*". What do you understand by the statement?

12. What is the difference between **strict equality** and **loose equality**? 

## 3.2 Numbers

1. When a number appears directly in a JavaScript program, it is called?

2. Give examples of **integers** and **floating-point number** literals

3. List the five (5) basic arithmetic operators in JavaScript and how they work

4. How does `**` work in JavaScript?

5. The following calculations are done using the Math constructor, specify the result of the calculation
    ```javascript
        Math.pow(3, 23) // ?
        Math.round(.4) // ?
        Math.ceil(.3) // ?
        Math.floor(.9) // ?
        Math.abs(-5) // ?
        Math.max(22, 5, 78, 56, 12) // ?
        Math.min(2, 4, 1, 0) // ?
        Math.random() // ?
    ```
6. When the result of a numeric operation is larger than the largest representable number (overflow), the result is ?

7. What will be the value of this computation
    ```javascript
        let division = 17 / 0;
        console.log(division) // ?
    ```

8. What is NaN in JavaScript?

9. What do you understand by BigInt in JavaScript.

10. What is the result of this computations?
    ```javascript
        let a = 100000000n;
        let b = 203435000n;
        console.log(a + b) // ?
    ```

## 3.3 Text

1. What do you undersand by the "*length of a string*" and give code examples

2. What is the length of an empty string?

3. What are the **similarities** and **differences** of a JavaScript *string* and a JavaScript *array*?

4. How many ways can you include a string literal in your JavaScript program? Give examples

5. What are the advantages of using a backtick `(``)` over single and double quotes?

6. What will be the result of the following code
```javascript
    let word = "The sky is not the limit. Aim for the galaxy"; 
    console.log(word.length) // ?

    word.slice(1,4) // ?
    word.split(" ") // ?
    word.indexOf("g") // ?
    word.indexOf("l", 13) // ?
    word.lastIndexOf("a") // ?
    word.toUpperCase() // ?
    word.toLowerCase() // ?
    word.replace("limit", "fisayo"); // ?
    word.padStart(4, "*") // ?
    word.concat(" Even if you can make it to the sun, don't hesitate.") // ?
```

7. Refactor the code below using template literal
```javascript
let toBeRefacoted = "Computer science is an art " + "not only a science ";
```

## 3.4 Booleans

1. What are boolean values used for in programming?

2. What will be the output of the code below
```javascript
let loggedIn = false;

if(loggedIn === true) {
    console.log("Welcome");
} else {
    console.log("your password is not correct");
}
```

## 3.5 Null and Undefined

1. What is the difference between `null` and `undefined`?

## 3.6 Symbols

1. what will be the result of the code below
```javascript
    let symA = Symbol("fisayo");

    let symB = Symbol("fisayo");

    console.log(symA === symB) // ?

    // Don't just copy and paste this code and run it, 
    // take your time to understand what symbols are and 
    // understand why this code returns what it returns
```

## 3.7 Global Objects

1. What do you understand by *global object* in javascript

## 3.8 
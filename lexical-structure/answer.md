# Lexical structures answers.

1. The **lexical structure of a programming language** is the set of elementary rules that specifies how you write programs in that language.

2. **JavaScript is a text-based programming language used both on the client-side and server-side that allows you to make web pages interactive.**   ***AND*** 

    JavaScript was **invented by Brendan Eich in 1995, and became an ECMA standard in 1997.** ECMAScript is the official name of the language. ECMAScript versions have been abbreviated to ES1, ES2, ES3, ES5, and ES6. Since 2016, versions are named by year (ECMAScript 2016, 2017, 2018, 2019, 2020).

3. **What is means by case-sensitive....** It  means that language keywords, variables, function names, and any other identifiers must always be typed with a consistent capitalization of letters. **it must be written in a particular form, for example using all capital letters or all small letters, in order for the computer to recognize it.** [computing]

4. - // **SINGLE LINE COMMENT**  AND 
    - /* */ **MULTI-LINE OR BLOCK COMMENT**  are written with opening and closing tags and allow you to write comments that span across multiple lines. The opening and closing tags for block comments are: `/*` for opening a comment.
     
5. **LITERALS** represent values in JavaScript. These are fixed values—not variables—that you literally provide in your script. LIKE
    - Array lterals
    - Boolean literals
    - Floating-point literals
    - Numeric literals
    - Object literals
    - RegExp literals
    - String literals

6. **IDENTIFIER IN JAVASCRIPT** is a sequence of characters in the code that identifies a variable, function or property.
    - JavaScript identifier names should not start with any numeric values like 0-9. For example, 0xyz, and 87b are invalid names.

    - Identifier names should start with an alphabet, dollar ($), or underscore character. For example, Abc9, _abc, $pq is a valid one.

    - Excluding the first character, the rest of the name can include letters, numbers, dollar($), or underscore. But we cannot include any special characters including space (#, @, “ ”) other than underscore.

    - JavaScript Identifier names are case sensitive: for example- Abc, ABC, aBc, abc these all are the name of different variables.

    - There are some reserved keywords in JavaScript. Those are called reserved words. We cannot choose these keywords to make an identifier name. This makes the compiler confused. For example: break, let, new, boolean, etc. are not valid variable names.

7. Which of the following is true of identifiers in JavaScript.
    1. A JavaScript identifier must begin with a letter. ***TRUE***
    2. A JavaScript identifier must begin with an underscore (_). ***TRUE***
    3. A JavaScript identifier cannot begin with a dollar sign ($). ***FALSE***
    4. Digits are allowed as the first character. ***FALSE***

8.  **Reserved words in javascript**  are **word  that "looks like" a normal word, but is not allowed to be used as a normal word.**

    - break
    - continue
    - const
    - do 
    - else
    - for
    - false
    - true
    - if
    - of
    - in 
    - null
    - new
    - this 
    - var
    - let
    - with 
    - while
    - typeof
    - await
    - get
    - eval
    - set
    - async
    - return
    - import
    - try
    - function
    - instanceof
    - export
    - extends
    - default
    - delete
    - super
    - case
    - catch
    - class
    - throw
    - void
    - set

9. 
    - **UNICODE** represents the characters it supports via numbers called code points. The hexadecimal range of code points is 0x0 to 0x10FFFF (17 times 16 bits). Code units. To store or transmit code points, we encode them as code units, pieces of data with a fixed length.
    - **UNICODE NORMALIZATION.** the Unicode Consortium has defined a **process called "normalization," which produces one binary representation for any of the equivalent binary representations of a character.** Once normalized, two strings are equivalent if and only if they have identical binary representations.

10. **ABOUT THE SEMICOLON.**
    - This is all possible because JavaScript does not strictly require semicolons. When there is a place where a semicolon is needed, it adds it behind the scenes. And this is called **Automatic Semicolon Insertion.**


    ## The rules of JavaScript Automatic Semicolon Insertion.
    The JavaScript parser will automatically add a semicolon when, during the parsing of the source code, it finds these particular situations:
    1. when the next line starts with code that breaks the current one (code can spawn on multiple lines).
    2. when the next line starts with a **}**, closing the current block.
    3. when the end of the source code file is reached.
    4. when there is a **return** statement on its own line.
    5. when there is a **break** statement on its own line.
    6. when there is a **throw** statement on its own line.
    7. when there is a **continue** statement on its own line.
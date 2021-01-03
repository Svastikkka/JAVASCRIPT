# JavaScript Syntax
JavaScript syntax is the set of rules, how JavaScript programs are constructed.
In here we see some syntax rules set in javascript

<!--
1. JavaScript Values
2. JavaScript Operators
3. JavaScript Expressions
4. JavaScript Keywords
5. JavaScript Comments
6. JavaScript Identifiers
-->

1. JavaScript Values
The JavaScript syntax defines two types of values:
* Fixed values also called Literals
* Variable values also called Variables

    1.1 JavaScript Literals
    JavaScript Literals are the fixed value that cannot be changed, you do not need to specify any type of keyword to write literals. Literals are often used to initialize variables in programming, names of variables are string literals.

    A JavaScript Literal can be a numeric, string, floating-point value, a boolean value or  even an object. In simple words, any value is literal, if you write a string "Javascript 
    Tutorial" is a literal, any number like 7007 is a literal, etc.

    JavaScript supports various types of literals which are listed below:

    1. Numeric Literal :- 
        * ``` 120 // decimal literal```
        * ``` 021434 // octal literal```
        * ``` 0x4567 // hexadecimal literal```
    2. Floating-Point Literal
        * ``` 6.99689 // floating-point literal```
        * ``` -167.39894 // negative floating-point literal```

    3. Boolean Literal
        * ``` true // Boolean literal```
        * ``` false // Boolean literal```

    4. String Literal
        * ``` "Study" // String literal```
        * ``` 'tonight' // String literal```

        **Note** String literals can have some special characters too which are tabled below.

    5. Array Literal
        * An array literal is a list of zero or more expressions representing array elements that are enclosed in a square bracket([]).
        * Whenever you create an array using an array literal, it is initialized with the elements specified in the square bracket.

        **Example**

        ``` var emp = ["aman","anu","charita"];  // Array literal```

    6. Regular Expression Literal
        * Regular Expression is a pattern, used to match a character or string in some text. It is created by enclosing the regular expression string between forward slashes.
        **Example**

        ``` var myregexp = /ab+c/; // Regular Expression literal```
        ``` var myregexp = new RegExp("abc"); // Regular Expression literal```

    7. Object Literal
        * A collection of key-value pairs enclosed in curly braces({}). The key-value pair is separated by a comma.
        **Example**

        ``` var games = {cricket :11, chess :2, carom: 4}  // Object literal```


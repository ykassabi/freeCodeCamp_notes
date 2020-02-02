# JavaScript Algothms and Data Scructures Certification 
## Introduction to JavaScript

 - Comment Your JavaScript Code

    - `// This is an in-line comment.`
    - `/* This is a 
    multi-line comment */`
    >**BEST PRACTICE**  : 
As you write code, you should regularly add comments to clarify the function of parts of your code. Good commenting can help communicate the intent of your code—both for others and for your future self.

- Declare JavaScript Variables
    - Seven different data types
    
    | Variables | exemple |
    | --------  | ------- |
    | undefined |         |
    |   null    |         |
    | boolean   |   True  |
    | symbol    |         |
    | string    |  "yes"  |
    | object    | {} []   |
    | number    |    3    |
    
    - declare a variable with : `var`

- Storing Values with the Assignment Operator
  - `myVariable = 5;`
    - it s read from right to left , the value 5 (number) will be assigned (operator =) to the known variable `myVariable` , know because it s already declared.

- Initializing Variables with the Assignment Operator
    - `var a = 0;` 


- Understanding Uninitialized Variables
     > When JavaScript variables are declared, they have an initial value of undefined. If you do a mathematical operation on an undefined variable your result will be NaN which means "Not a Number". If you concatenate a string with an undefined variable, you will get a literal string of "undefined"


- Understanding Case Sensitivity in Variables

    - In JavaScript all variables and function names are case sensitive. This means that capitalization matters.
    > **BEST PRACTICE** : Write variable names in JavaScript in camelCase. In camelCase, multi-word variable names have the first word in lowercase and the first letter of each subsequent word is capitalized.
    - `var properCamelCase;`

- Add Two Numbers with JavaScript
    - **Number**  is a data type in JavaScript which represents numeric data.
    - JavaScript uses the + symbol as an addition operator when placed between two numbers.
    - ` a = 4 + 20;`

- Subtract One Number from Another with JavaScript
    - JavaScript uses the - symbol for subtraction.
    -` b = 44 - 32`
-  Multiply Two Numbers with JavaScript
    - JavaScript uses the * symbol for multiplication of two numbers.
    - `c = 4 * 3`

- Divide One Number by Another with JavaScript
    - JavaScript uses the / symbol for division.
    - `d = 4 / 2 `


- Increment a Number with JavaScript
    - `myVar = myVar + 1;` === `myVar++` === `myVar += 1`

- Decrement a Number with JavaScript
    - `i = i - 1;` === `i--`

- Create Decimal Numbers with JavaScript
    -Decimal numbers are sometimes referred to as **floating point numbers** or **floats**.

- Multiply Two Decimals with JavaScript
    - `var product = 2.0 * 1.2;`

- Divide One Decimal by Another with JavaScript
    - `var quotient = 4.4 / 2.0;`

- Finding a Remainder in JavaScript
    - The remainder operator % gives the remainder of the division of two numbers.
        - ``5 % 2 = 1 because
        Math.floor(5 / 2) = 2 (Quotient)
        2 * 2 = 4
        5 - 4 = 1 (Remainder)``
        - `17 % 2 = 1` (17 is Odd)
        - `48 % 2 = 0` (48 is Even) 
    - ⚠️ The remainder operator is sometimes incorrectly referred to as the "**modulus**" operator. It is very similar to modulus, but does not work properly with negative numbers.

- Compound Assignment With Augmented Addition `+=`
    -  it is common to use assignments `=` to modify the contents of a variable
    - `var a = 3` ...`a +=  6;` 
- Compound Assignment With Augmented Subtraction`-=`
    - `var myVar= 3` ...`myVar -= 5;`
- Compound Assignment With Augmented Multiplication `*=`
    - `var c = 10`....`c *= 10;`
- Compound Assignment With Augmented Division `/=`
    -  `var b = 13`...`b /= 3`

- Declare String Variables
    - `var myName = "your name";`
        - "your name" is called a **string literal**

- Escaping Literal Quotes in Strings `\`
    - When you are defining a string you must start and end with a single or double quote
    -In JavaScript, you can escape a quote `'` or  `"` from considering it as an end of string quote by placing a backslash `\` in front of the quote.

    - `var sampleStr = "Alan said, \"Peter is learning JavaScript\".";`


---- 20% --- 50 min

- Quoting Strings with Single Quotes
    - String values in JavaScript may be written with single or double quotes, as long as you start and end with the same type of quote
        - `var myStr = '<a href="http://www.example.com" target="_blank">Link</a>';
`
- Escape Sequences in Strings
    - Quotes are not the only characters that can be escaped inside a string. There are two reasons to use escaping characters:
        - To allow you to use characters you may not otherwise be able to type out, such as a carriage return.
        - To allow you to represent multiple quotes in a string without JavaScript misinterpreting what you mean.

        | Code | Output |
        | ---- | ------ |
        |`\'`| single quote|
        |`\"`| double quote|
        |`\\`| backslash |
        |`\n`|newline|
        |`\r`|carriage return |
        |`\t`|bat|
        |`\b`| word boudary|
        |`\f`|form feed|

- Concatenating Strings with Plus Operator `+`
    - `'My name is Alan,' + ' I concatenate.'`
- Concatenating Strings with the Plus Equals Operator `+=`
    - `+=`operator to concatenate a string onto the end of an existing string variable.
- Constructing Strings with Variables
    - `var ourStr = "Hello, our name is " + ourName + ", how are you?";`

- Appending Variables to Strings
    - ``var someAdjective = "ABCedf";
        var myStr = "Learning to code is ";
        myStr += someAdjective;``
- Find the Length of a String
    - `lastNameLength = "a name".length;`
- Use Bracket Notation to Find the First Character in a String
    - `firstName = "Charles"; firstName[0];`
- Understand String Immutability
    -  String values are immutable, which means that they cannot be altered once created.
        - For example, the following code: `var myStr = "Bob"; myStr[0] = "J";`
        - cannot change the value of myStr to "Job", because the contents of myStr cannot be altered. Note that this does not mean that myStr cannot be changed, just that the individual characters of a string literal cannot be changed. The only way to change myStr would be to assign it with a new string,
        - `var myStr = "Bob"; myStr = "Job";`

- Use Bracket Notation to Find the Nth Character in a String
    - `var secondLetterOfFirstName = firstName[1]`
- Use Bracket Notation to Find the Last Character in a String
    - `var lastLetterOfLastName = lastName[lastname.length -1];`
- Use Bracket Notation to Find the Nth-to-Last Character in a String
    - `firstName[firstName.length - 3];`

- Word Blanks
    -  `myName + " " + myVerb;`
- Store Multiple Values in one Variable using JavaScript Arrays
    - `var ourArray = ["John", 23];`

- Nest one Array within Another Array
    - `var ourArray = [["the universe", 42], ["everything", 101010]];`
- Access Array Data with Indexes
    - `var ourArray = [50,60,70]; var ourData = ourArray[0]; // equals 50`

--- 35%  --- 30 min
-  Modify Array Data With Indexes
    - `var myArray = [18,64,99]; myArray[0] = 45;`
- Access Multi-Dimensional Arrays With Indexes
    - `// Setup var myArray = [[1,2,3], [4,5,6], [7,8,9], [[10,11,12], 13, 14]];`
    - `var myData = myArray[2][1]; // => 8`

- Manipulate Arrays With `push()`
    - `var arr = [1,2,3]; arr.push(4);`

- Manipulate Arrays With `pop()`
    - `var threeArr = [1, 4, 6]; var oneDown = threeArr.pop();`
    - pop() always removes the last element of an array

- Manipulate Arrays With `shift()`
    - remove the first

- Manipulate Arrays With `unshift()`
    - Adds the element at the beginning of the array.
    - 
- Shopping List
    - subArray
- Write Reusable JavaScript with Functions
    - `function functionName() {console.log("Hello World");}`
- Passing Values to Functions with Arguments
    - `function testFun(param1, param2) {console.log(param1, param2);}`

- Global Scope and Functions
    - > scope refers to the visibility of variables. Variables which are defined outside of a function block have Global scope. This means, they can be seen everywhere in your JavaScript code.
    - > Variables which are used without the `var` keyword are automatically created in the **global scope**. This can create unintended consequences elsewhere in your code or when running a function again. You should always declare your variables with `var`.

- Local Scope and Functions
    - Variables which are declared within a function, as well as the function parameters have local scope. That means, they are only visible within that function.
    ``function myTest() {
  var loc = "foo";
  console.log(loc);}myTest(); // logs "foo" console.log(loc); // loc is not defined``
- Global vs. Local Scope in Functions
    -It is possible to have both `local` and `global` variables with the same name. When you do this, the local variable takes precedence over the `global` variable.

- Return a Value from a Function with Return
    - We can pass values into a function with arguments. You can use a return statement to send a value back out of a function.
    - ``function plusThree(num) { return num + 3; }var answer = plusThree(5); // 8``

- Understanding `Undefined` Value `returned` from a Function
    - A function can include the `return` statement but it does not have to. In the case that the function doesn't have a `return` statement, when you call it, the function processes the inner code but the returned value is `undefined`
    - ``var sum = 0;function addSum(num) {sum = sum + num;}addSum(3); // sum will be modified but returned value is undefined``
- Assignment with a Returned Value
    - everything to the right of the equal sign is resolved before the value is assigned. This means we can take the return value of a function and assign it to a variable.

- Stand in Line
    > In Computer Science a queue is an abstract Data Structure where items are kept in order. New items can be added at the back of the queue and old items are taken off from the front of the queue.
- Understanding Boolean Values
        Not Passed
- Use Conditional Logic with If Statements
        Not Passed
- Comparison with the Equality Operator
        Not Passed
- Comparison with the Strict Equality Operator
        Not Passed
- Practice comparing different values
        Not Passed
- Comparison with the Inequality Operator
        Not Passed
- Comparison with the Strict Inequality Operator
        Not Passed
- Comparison with the Greater Than Operator
        Not Passed
- Comparison with the Greater Than Or Equal To Operator
        Not Passed
- Comparison with the Less Than Operator
        Not Passed
- Comparison with the Less Than Or Equal To Operator
        Not Passed
- Comparisons with the Logical And Operator
        Not Passed
- Comparisons with the Logical Or Operator
        Not Passed
- Introducing Else Statements
        Not Passed
- Introducing Else If Statements
        Not Passed
- Logical Order in If Else Statements
        Not Passed
- Chaining If Else Statements
        Not Passed
- Golf Code
        Not Passed
- Selecting from Many Options with Switch Statements
        Not Passed
- Adding a Default Option in Switch Statements
        Not Passed
- Multiple Identical Options in Switch Statements
        Not Passed
- Replacing If Else Chains with Switch
        Not Passed
- Returning Boolean Values from Functions
        Not Passed
- Return Early Pattern for Functions
        Not Passed
- Counting Cards
        Not Passed
- Build JavaScript Objects
        Not Passed
- Accessing Object Properties with Dot Notation
        Not Passed
- Accessing Object Properties with Bracket Notation
        Not Passed
- Accessing Object Properties with Variables
        Not Passed
- Updating Object Properties
        Not Passed
- Add New Properties to a JavaScript Object
        Not Passed
- Delete Properties from a JavaScript Object
        Not Passed
- Using Objects for Lookups
        Not Passed
- Testing Objects for Properties
        Not Passed
- Manipulating Complex Objects
        Not Passed
- Accessing Nested Objects
        Not Passed
- Accessing Nested Arrays
        Not Passed
- Record Collection
        Not Passed
- Iterate with JavaScript While Loops
        Not Passed
- Iterate with JavaScript For Loops
        Not Passed
- Iterate Odd Numbers With a For Loop
        Not Passed
- Count Backwards With a For Loop
        Not Passed
- Iterate Through an Array with a For Loop
        Not Passed
- Nesting For Loops
        Not Passed
- Iterate with JavaScript Do...While Loops
        Not Passed
- Replace Loops using Recursion
        Not Passed
- Profile Lookup
        Not Passed
- Generate Random Fractions with JavaScript
        Not Passed
- Generate Random Whole Numbers with JavaScript
        Not Passed
- Generate Random Whole Numbers within a Range
        Not Passed
- Use the parseInt Function
        Not Passed
- Use the parseInt Function with a Radix
        Not Passed
- Use the Conditional (Ternary) Operator
        Not Passed
- Use Multiple Conditional (Ternary) Operators
        Not Passed
- Use Recursion to Create a Countdown
        Not Passed
- Use Recursion to Create a Range of Numbers


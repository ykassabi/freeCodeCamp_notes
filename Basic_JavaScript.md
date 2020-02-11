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
    - ``arr.push(item);
  var removed = arr.shift();
  return removed; // Change this line``

- Understanding Boolean Values
    - Booleans may only be one of two values: true or false. They are basically little on-off switches, where true is "on" and false is "off." These two states are mutually exclusive.

- Use Conditional Logic with If Statements
    - If statements are used to make decisions in code. The keyword if tells JavaScript to execute the code in the curly braces under certain conditions, defined in the parentheses. These conditions are known as Boolean conditions and they may only be true or false.
    - When the condition evaluates to true, the program executes the statement inside the curly braces. When the Boolean condition evaluates to false, the statement inside the curly braces will not execute.
    - > ``
    if (condition is true) {
      statement is executed
    }``

- Comparison with the Equality Operator
    - The most basic operator is the equality operator ==. The equality operator compares two values and returns true if they're equivalent or false if they are not. Note that equality is different from assignment (=), which assigns the value at the right of the operator to a variable in the left.
    - > ``1   ==  1  // true -- 1   ==  2 // false  -- 1   == '1'  // true  --  "3" ==  3   // true ``

- Comparison with the Strict Equality Operator
    - Strict equality (===) is the counterpart to the equality operator (==). However, unlike the equality operator, which attempts to convert both values being compared to a common type, the strict equality operator does not perform a type conversion.

- Practice comparing different values
    - If the values being compared are not of the same type, the equality operator will perform a type conversion, and then evaluate the values. However, the strict equality operator will compare both the data type and value as-is, without converting one type to the other.
    - ``3 == '3'  // returns true because JavaScript performs type conversion from string to number
        3 === '3' // returns `false` because the types are different and type conversion is not performed``

- Comparison with the Inequality Operator
    - The inequality operator `!=` is the opposite of the equality operator. It means "Not Equal" and returns `false` where equality would return `true` and vice versa. Like the equality operator, the inequality operator will convert data types of values while comparing.
    - ``1 !=  2     // true
        1 != "1"    // false
        1 != '1'    // false
        1 != true   // false
        0 != false  // false
        ``
- Comparison with the Strict Inequality Operator
    - The strict inequality operator `!==` is the logical opposite of the strict equality operator. It means "Strictly Not Equal" and returns `false` where strict equality would return true and vice versa. Strict inequality will not convert data types.

- Comparison with the Greater Than Operator
    - The greater than operator `>` compares the values of two numbers. If the number to the left is greater than the number to the right, it returns true. Otherwise, it returns false.

- Comparison with the Greater Than Or Equal To Operator
    - The greater than or equal to operator (>=) compares the values of two numbers. If the number to the left is greater than or equal to the number to the right, it returns true. Otherwise, it returns false.
    - Like the equality operator, greater than or equal to operator will convert data types while comparing.
- Comparison with the Less Than Operator
    - The less than operator `<` compares the values of two numbers. If the number to the left is less than the number to the right, it returns true. Otherwise, it returns false. Like the equality operator, less than operator converts data types while comparing.
    
- Comparison with the Less Than Or Equal To Operator
    - The less than or equal to operator `<=` compares the values of two numbers. If the number to the left is less than or equal to the number to the right, it returns true. If the number on the left is greater than the number on the right, it returns false. Like the equality operator, `less than or equal` to converts data types.

- Comparisons with the Logical And Operator
    - The logical and operator `&&` returns `true` if and only if the operands to the left and right of it are true.
    - ``  if (val <= 50  && val >= 25 ) { return "Yes";}``
- Comparisons with the Logical Or Operator
    - The logical or operator (||) returns true if either of the operands is true. Otherwise, it returns false.
    - The logical or operator is composed of two pipe symbols: (||). This can typically be found between your Backspace and Enter keys.

- Introducing Else Statements
    - > ``if (num > 10) {
        return "Bigger than 10";
        } else {
        return "10 or Less";
        }
        ``
- Introducing Else If Statements
    - ``if (num > 15) {
        return "Bigger than 15";
        } else if (num < 5) {
        return "Smaller than 5";
        } else {
        return "Between 5 and 15";
        }
        ``
- Logical Order in If Else Statements
    - the importantce of the order in if and else if statements
- Chaining If Else Statements
    - ``if (condition1) {
        statement1
        } else if (condition2) {
        statement2
        } else if (condition3) {
        statement3
        . . .
        } else {
        statementN
        }
        ``
- Golf Code
    - golf 
- Selecting from Many Options with Switch Statements
        ``switch(lowercaseLetter) {
            case "a":
                console.log("A");
                break;
            case "b":
                console.log("B");
                break;
            }``
- Adding a Default Option in Switch Statements
    ``switch (num) {
        case value1:
            statement1;
            break;
        case value2:
            statement2;
            break;
        ...
        default:
            defaultStatement;
            break;
        }
        ``

- Multiple Identical Options in Switch Statements
        > If the break statement is omitted from a switch statement's case, the following case statement(s) are executed until a break is encountered. If you have multiple inputs with the same output, you can represent them in a switch statement like this:
        ``switch(val) {
            case 1:
            case 2:
            case 3:
                result = "1, 2, or 3";
                break;
            case 4:
                result = "4 alone";
            }
            ``
- Replacing If Else Chains with Switch
        - If you have many options to choose from, a switch statement can be easier to write than many chained if/else if statements
- Returning Boolean Values from Functions
        - `` function isEqual(a,b) {
                if (a === b) {
                    return true;
                } else {
                    return false;
                }
                }``
                - better to write it as ;
        - ``function isEqual(a,b) {
                return a === b;
                }
                ``
- Return Early Pattern for Functions
        - When a return statement is reached, the execution of the current function stops and control returns to the calling location.
- Counting Cards
        Not Passed
- Build JavaScript Objects
        - ``var cat = {
                "name": "Whiskers",
                "legs": 4,
                "tails": 1,
                "enemies": ["Water", "Dogs"]
        };``

- Accessing Object Properties with Dot Notation
        - There are two ways to access the properties of an object: dot notation `.` and bracket notation `[]`, similar to an array.
        - Dot notation is what you use when you know the name of the property you're trying to access ahead of time.

- Accessing Object Properties with Bracket Notation
        - The second way to access the properties of an object is bracket notation ([]). If the property of the object you are trying to access has a space in its name, you will need to use bracket notation.
        - However, you can still use bracket notation on object properties without spaces.
        -`var drinkValue = testObj["the drink"]`

- Accessing Object Properties with Variables
        - Another use of bracket notation on objects is to access a property which is stored as the value of a variable. This can be very useful for iterating through an object's properties or when accessing a lookup table.
        - `var playerNumber = "the drink";     `
            `var player = testObj[playerNumber]; `
- Updating Object Properties
        - two way to change 
            - ``var ourDog = {
                    "name": "Camper",
                    "legs": 4,
                    "tails": 1,
                    "friends": ["everything!"]
                    };
                ``
            - `ourDog["name"] = "Happy Camper";` or 
            - `ourDog.name = "Happy Camper"; `
- Add New Properties to a JavaScript Object
        - same way as update : `myDog.bark = "woof" `
- Delete Properties from a JavaScript Object
        - `delete mydog.tails`
- Using Objects for Lookups
        - Objects can be thought of as a key/value storage, like a dictionary. If you have tabular data, you can use an object to "lookup" values rather than a `switch` statement or an `if/else` chain. This is most useful when you know that your input data is limited to a certain range.
- Testing Objects for Properties
        - Sometimes it is useful to check if the property of a given object exists or not. We can use the .`hasOwnProperty(propname)` method of objects to determine if that object has the given property name. .`hasOwnProperty()` returns `true` or `false` if the property is found or not.
        > ``var myObj = {
            top: "hat",
            bottom: "pants"
            };
            myObj.hasOwnProperty("top");    // true
            myObj.hasOwnProperty("middle"); // false``
            
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


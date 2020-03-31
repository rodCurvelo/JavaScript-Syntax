# Content
## Syntax

* Comments
    * In-line Comment
    ```JavaScript
        //This is a comment
    ```
    * Multiple lines
    ```JavaScript
        /*Multi-line
        Line 1
        Line 2
        ...*/
    ```
* Printing
    ```JavaScript
        console.log("This is a message");
    ```
* Data Types 
    ```JavaScript
        undefined,
        null,
        boolean,
        string,
        symbol,
        number,
        object
    ```
    * Undefined
        * variable with no type
    * null
        * declaring nothing 
    * boolean
        * TRUE or FALSE
    * string
        * text
    * number
        * number
    * object
        * can store a lot of variable key pairs
    * symbol
        * primitive data type that is unique

* **Set Data to a Variable** 
    * Data is like a box
        ```JavaScript
            var myName = "Oswald";
            myName = 8;
        ```
    * **3 Ways to declare a variable in JavaScript**
        ```JavaScript
            var myName = "Oswald";
            let ourName = "ourCompany";
            const pi = 3.14; 
        ```
        
        * >**var** 
            * able to use throught my whole program
        * >**let**
            * only being used within the scope where I declare that
        * >**const**
            * variable that never change 
            * I get an error if I try to change it
* **Storing Values with Assignment Operator**
    >Add Semicolon to the end of the line:
    ```JavaScript
        var a;
    ```
    >Assignment a variable:
    ```JavaScript
        var b = 2;
        b = a;
        console.log(a);
    ```
* **Initializing a Variables with Assignment Operator**
    ```JavaScript
    var a = 9;
    //var a is declaring
    // = 9 is initializing
    ``` 
* **Unintialized Variables**
    ```JavaScript
        // Initialize these three variables
        var a; 
        var b;
        var c;
        //Change these variables above, 
        //I can sum with the variables below

        // Do not change code below this line

        a = a + 1;
        b = b + 5;
        c = c + " String!";

    ```
* **Case Sensitivity in Variables**
    >The capitalization matters. JavaScript are case sensitive
    ```JavaScript
    //Declarations
    var StUdLyCapVar;
    var properCamelCase;
    var TitleCaseOver;

    //Assignments
    STUDLYCAPVAR = 10;
    PRoperCAmelCAse = "A String";
    tITLEcASEoVER = 9000;

    //THEY ARE NOT THE SAME!!!
    ```
    >Always Declare in camelCase
* **Adding Numbers**
    ```JavaScript
        var sum = 10+10;
        console.log(sum); 
    ```
* **Subtracting Numbers**
    ```JavaScript
        var difference = 45 - 33;
        console.log(difference);
    ```
* **Multiplying Numbers**
    ```JavaScript
        var product = 8 * 5;
        console.log(product);        
    ```
* **Dividing Numbers**
    ```JavaScript
        var quotient = 66 / 0;
        console.log(quotient);
    ```
* **Incrementing Numbers**
    ```JavaScript
        var myVar = 87;

        // Only change code below this line
        myVar = myVar + 1; 
        myVar++;
    ```
* **Decrementing Numbers**
    ```JavaScript
        var myVar = 12;
        myVar = MyVar - 1;
        myVar--;
    ```
* **Decimal Numbers**
    ```JavaScript
        var ourDecimal = 5.7;
        //We refer that as float
    ```
* **Multiply Decimals**
    ```JavaScript
        var item = 2.0 * 2.5;
        console.log(item);
    ```
* **Divide Decimals**
    ```JavaScript
        var item = 4.4 / 2.2;
        console.log(item);
    ```
* **Finding a Remainder**
    >Remainder of a division of two numbers
    ```JavaScript
        var remainder;
        remainder = 11 % 3;
        /* 11 divide by 3 is 9. 
        Eleven minus nine, equals 2. 
        So the remainder equals 2 */

        //Determine if the number is even or odd
    ```
* **Compound Assignment with Argument Addition**
    ```JavaScript
        var a = 1;
        a = a + 1;

        //Another way
        a += 1;
    ```
* **Compound Assignment with Argument Subtraction**
    ```JavaScript
        var a = 2;
        a = a - 1;

        //Another way
        a -= 1;
    ```
* **Compound Assignment with Argument Multiplication**
    ```JavaScript
        var a = 1;
        a = a * 1;

        //Another way
        a *= 1;
    ```
* **Compound Assignment with Argument Division**
    ```JavaScript
        var a = 42;
        a = a / 2;

        //Another way
        a /= 2;
    ```
* **Declare String Variables**
    ```JavaScript
        var firstName = "Mark";
        var lastName = "Johnson";
    ```
* **Espaping Literal Quotes in Strings**
    ```JavaScript
        var myStr = "I am a "double quoted" string inside "double quotes"";

        //Should insert  \

        myStr = "I am a \"double quoted\" string inside \"double quotes\"";

        console.log(myStr);
    ```
* **Quoting Strings with Single Quotes**
    ```JavaScript
        //JS recognizes single quote and doble quotes
        var myStr = '<a href="https://google.com">Google</a>';
    ```
* **Escape Sequences in Strings**
    ```javaScript
       /*
       CODE OUTPUT
       \'   single quote
       \"   double quote
       \\   backlash
       \n   new line
       \r   carriage return
       \t   tab
       \b   backspace
       \f   form feed
    
       */
        
    ```
* **Concatenating Strings with Plus Operator**
    > Use the + operator
    ```JavaScript
    var outStr = "I come first. " + "I come second.";
    ```
* **Concatenating Strings with Plus Equals Operator**
    ```JavaScript
    var outStr = "I come first. ";
    outStr += "I come second.";

    console.log(outStr);
    ```

* **Constructing Strings with Variables**
    ```JavaScript
    var firstName = "Mark";
    var lastName = "Johnson";

    var sentence = "Hello " + firstName + "My name is " + lastName".";

    console.log(sentence);
    ```
* **Appending Variables To Strings**
    ```JavaScript
    var anAdjective = "awesome";
    var ourStr = "course is";
    outStr += anAdjective;

    console.log(outStr);
    ```
* **Find Lenght of String**
    ```JavaScript
    var firstNameLength = 0;
    var firstName = "Ada";

    firstNameLength = firstName.length;

    console.log(firstNameLength);
    ```
* **Bracket Notation to Find First Character in String**
    ```JavaScript
    var firstLetter = "";
    var firstName = "Ada";

    firstLetter = firstName[0];

    console.log(firstLetter);
    ```
* **String Immutability**
    ```JavaScript
    var myStr = "Jello World";

    myStr [0] = "h"; // It doesn't work

    myStr = "Hello World";

    //String is immutable. I can change individual characters, only changing the entire word. 
    ```
* **Bracket Notation to Find Nth Character in String**
    ```JavaScript
    var firstName = "Ada";
    var SecondLetterOfTheFirstName = firstName[1];

    console.log(SecondLetterOfTheFirstName);
    ```
* **Bracket Notation to Find Last Character in String**
    ```JavaScript
    var firstName = "Ada";
    var lastLetterOfTheFirstName = firstName[firstName.length - 1];

    console.log(lastLetterOfTheFirstName);
    ```
    > -1 is added because the count starts with 0

* **Bracket Notation to Find Nth-to-Last Charachter in String**
    ```JavaScript
    var firstName = "Ada";
    var thirdToLastLetterOfTheFirstName = firstName[firstName.length - 3];

    console.log(thirdToLastLetterOfTheFirstName);
    ```

* **Word Blanks**
    ```JavaScript
    function wordBlanks(myNoun, myAdjective, myVerb, myAdverb) {
        var result = "";
        result += "The " + myAdjective + " " myNoun + " " +  myVerb + " " + " to the store " + myAdverb; 

        return result;
    }

    // Change the words here to test your function
    console.log(wordBlanks("dog", "big", "ran", "quickly"));

    console.log(wordBlanks("bike", "slow", "flew", "slowly"));
    ```
* **Store Multiple Values with Arrays**
    ```JavaScript
        var ourArray = ["John",23];
    ```
    >**I can add different data types in an array**
* **Nested Arrays**
    > Array inside another array
    ```JavaScript
        var myArray = [["me"],["another person"]];
    ```
* **Access Array Data with Indexes**
    ```JavaScript
        var ourArray = [50,60,70];
        var ourData  = ourArray[0]; // equals 50
    ```
    >Indexes 0,1 and 2
* **Modify Array Data With Indexes**
    >Used to modify arrays
    ```JavaScript
        var ourArray = [18, 19, 20];
        console.log(ourArray);
        ourArray[1] = 45;
        console.log(ourArray);
    ```
* **Access Multi-Dimensional Arrays With Indexes**
    ```JavaScript
        var myArray = [[1,2,3], [4,5,6], [7,8,9]];

        var myData = myArray[0][1];

        console.log(myData);
    ```
* **Manipulate Arrays with push**
    ```JavaScript
        var myArray = ["a","b", "c"];
        console.log(myArray);
        myArray.push("d","e");
        console.log(myArray);

        myArray.push(["f","g"]);
        //Adding another array

        console.log (myArray);
    ```
* **Manipulate Arrays with pop()**
    >Removing the item with the pop function
    ```JavaScript
        var myArray = [1,2,3];
        console.log(myArray);
        var myArrayDel = myArray.pop();
        console.log(myArrayDel);
    ```
* **Manipulate Arrays with Shift**
    > Similar to the pop function, but it removes the first element of an array
    ```JavaScript
        var myArray = ["a","b","c",["cat"]];
        console.log(myArray);
        var removedArr = myArray.shift();
        console.log(removedArr);
    ```
* **Manipulate Arrays with unshift()**
    ```JavaScript
    var myArray = ["a","b","c"];
    console.log(myArray);
    myArray.shift();
    console.log(myArray);
    myArray.unshift("parrot");
    console.log(myArray);
    ```
* **Shopping List**
    >Array of Arrays
    ```JavaScript
    var myList = [["Cereal", 3], ["beans", 2]];

    ```

* **Write Reusable Code With Functions**
    ```JavaScript
    function myReusable() {
        console.log("Whatsup!");
    }

    myReusable();
    ```
* **Passing Values to Functions with Arguments**
    >Variables are parameters
    ```JavaScript
    function myFuncWithArgs(a,b) {
        console.log(a - b);
    }

    myFuncWithArgs(10,5);
    ```

* **Global Scope and Functions**
    >**Global Scope** means they can be seen everywhere in JavaScript

    ```JavaScript
    //Declare your variable here
    var myGlobal = 10;
    //I can see this variable everywhere

    function fun1() {
        // Assign 5 to oopsGlobal Here
        oopsGlobal = 5;
    }

    function fun2() {
        var output = "";
        if (typeof myGlobal != "undefined") {
            output += "myGlobal: " + myGlobal;
        }
        if (typeof oopsGlobal != "undefined") {
            output += " oopsGlobal: " + oopsGlobal; 
        }
        console.log(output)
    }

    fun1();
    fun2();
    ```

* **Local Scope and Functions**
    >Only visible inside the function

    ```JavaScript
    
    functions myLocalScope() {
        var myVar = 5;
        console.log(myVar);
        // var myVar only visible inside the function
    }

    myLocalScope();

    console.log(myVar);
    ```
* **Global vs. Local Scope in Functions**
    ```JavaScript
    var outerWear = "T-shirt";
    //Global variable because is declared outside the function

    function myOutfit() {
        var outerWear = "sweater";

        return outerWear;
    }

    console.log(myOutfit());
    console.log(outWear);
    ```
* **Return a Value from a Function with Return**
    ```JavaScript
    function minusSeven(num) {
        return num - 7;
    }

    console.log(minusSeven(10));
    ```
* **Understanding Undefined Value Returned from a function**
    >If I don't use **return** the function won't return any result 
    ```JavaScript
    var sum = 0;
    // global variable 
    function addThree() {
        sum += sum + 3;
    }

    function addFive() {
        sum += + 5;
    }
    ```
* **Assignment with a Returned Value**
    ```JavaScript
    var changed = 0;

    function change(num) {
        return (num + 5) / 3;
    }

    changed = change(10);

    var processed = 0;

    function processArg(num) {
        return (num + 3) / 5;
    }

    processed = processArg(7);
    ```
# Content
## Syntax

* Comments
    * In-line Comment
    ```JavaScript
        //This is a comment
    ```
    * Multiple lines
    ```JavaScript
        /*Multi-line
        Line 1
        Line 2
        ...*/
    ```
* Printing
    ```JavaScript
        console.log("This is a message");
    ```
* Data Types 
    ```JavaScript
        undefined,
        null,
        boolean,
        string,
        symbol,
        number,
        object
    ```
    * Undefined
        * variable with no type
    * null
        * declaring nothing 
    * boolean
        * TRUE or FALSE
    * string
        * text
    * number
        * number
    * object
        * can store a lot of variable key pairs
    * symbol
        * primitive data type that is unique

* **Set Data to a Variable** 
    * Data is like a box
        ```JavaScript
            var myName = "Oswald";
            myName = 8;
        ```
    * **3 Ways to declare a variable in JavaScript**
        ```JavaScript
            var myName = "Oswald";
            let ourName = "ourCompany";
            const pi = 3.14; 
        ```
        
        * >**var** 
            * able to use throught my whole program
        * >**let**
            * only being used within the scope where I declare that
        * >**const**
            * variable that never change 
            * I get an error if I try to change it
* **Storing Values with Assignment Operator**
    >Add Semicolon to the end of the line:
    ```JavaScript
        var a;
    ```
    >Assignment a variable:
    ```JavaScript
        var b = 2;
        b = a;
        console.log(a);
    ```
* **Initializing a Variables with Assignment Operator**
    ```JavaScript
    var a = 9;
    //var a is declaring
    // = 9 is initializing
    ``` 
* **Unintialized Variables**
    ```JavaScript
        // Initialize these three variables
        var a; 
        var b;
        var c;
        //Change these variables above, 
        //I can sum with the variables below

        // Do not change code below this line

        a = a + 1;
        b = b + 5;
        c = c + " String!";

    ```
* **Case Sensitivity in Variables**
    >The capitalization matters. JavaScript are case sensitive
    ```JavaScript
    //Declarations
    var StUdLyCapVar;
    var properCamelCase;
    var TitleCaseOver;

    //Assignments
    STUDLYCAPVAR = 10;
    PRoperCAmelCAse = "A String";
    tITLEcASEoVER = 9000;

    //THEY ARE NOT THE SAME!!!
    ```
    >Always Declare in camelCase
* **Adding Numbers**
    ```JavaScript
        var sum = 10+10;
        console.log(sum); 
    ```
* **Subtracting Numbers**
    ```JavaScript
        var difference = 45 - 33;
        console.log(difference);
    ```
* **Multiplying Numbers**
    ```JavaScript
        var product = 8 * 5;
        console.log(product);        
    ```
* **Dividing Numbers**
    ```JavaScript
        var quotient = 66 / 0;
        console.log(quotient);
    ```
* **Incrementing Numbers**
    ```JavaScript
        var myVar = 87;

        // Only change code below this line
        myVar = myVar + 1; 
        myVar++;
    ```
* **Decrementing Numbers**
    ```JavaScript
        var myVar = 12;
        myVar = MyVar - 1;
        myVar--;
    ```
* **Decimal Numbers**
    ```JavaScript
        var ourDecimal = 5.7;
        //We refer that as float
    ```
* **Multiply Decimals**
    ```JavaScript
        var item = 2.0 * 2.5;
        console.log(item);
    ```
* **Divide Decimals**
    ```JavaScript
        var item = 4.4 / 2.2;
        console.log(item);
    ```
* **Finding a Remainder**
    >Remainder of a division of two numbers
    ```JavaScript
        var remainder;
        remainder = 11 % 3;
        /* 11 divide by 3 is 9. 
        Eleven minus nine, equals 2. 
        So the remainder equals 2 */

        //Determine if the number is even or odd
    ```
* **Compound Assignment with Argument Addition**
    ```JavaScript
        var a = 1;
        a = a + 1;

        //Another way
        a += 1;
    ```
* **Compound Assignment with Argument Subtraction**
    ```JavaScript
        var a = 2;
        a = a - 1;

        //Another way
        a -= 1;
    ```
* **Compound Assignment with Argument Multiplication**
    ```JavaScript
        var a = 1;
        a = a * 1;

        //Another way
        a *= 1;
    ```
* **Compound Assignment with Argument Division**
    ```JavaScript
        var a = 42;
        a = a / 2;

        //Another way
        a /= 2;
    ```
* **Declare String Variables**
    ```JavaScript
        var firstName = "Mark";
        var lastName = "Johnson";
    ```
* **Espaping Literal Quotes in Strings**
    ```JavaScript
        var myStr = "I am a "double quoted" string inside "double quotes"";

        //Should insert  \

        myStr = "I am a \"double quoted\" string inside \"double quotes\"";

        console.log(myStr);
    ```
* **Quoting Strings with Single Quotes**
    ```JavaScript
        //JS recognizes single quote and doble quotes
        var myStr = '<a href="https://google.com">Google</a>';
    ```
* **Escape Sequences in Strings**
    ```javaScript
       /*
       CODE OUTPUT
       \'   single quote
       \"   double quote
       \\   backlash
       \n   new line
       \r   carriage return
       \t   tab
       \b   backspace
       \f   form feed
    
       */
        
    ```
* **Concatenating Strings with Plus Operator**
    > Use the + operator
    ```JavaScript
    var outStr = "I come first. " + "I come second.";
    ```
* **Concatenating Strings with Plus Equals Operator**
    ```JavaScript
    var outStr = "I come first. ";
    outStr += "I come second.";

    console.log(outStr);
    ```

* **Constructing Strings with Variables**
    ```JavaScript
    var firstName = "Mark";
    var lastName = "Johnson";

    var sentence = "Hello " + firstName + "My name is " + lastName".";

    console.log(sentence);
    ```
* **Appending Variables To Strings**
    ```JavaScript
    var anAdjective = "awesome";
    var ourStr = "course is";
    outStr += anAdjective;

    console.log(outStr);
    ```
* **Find Lenght of String**
    ```JavaScript
    var firstNameLength = 0;
    var firstName = "Ada";

    firstNameLength = firstName.length;

    console.log(firstNameLength);
    ```
* **Bracket Notation to Find First Character in String**
    ```JavaScript
    var firstLetter = "";
    var firstName = "Ada";

    firstLetter = firstName[0];

    console.log(firstLetter);
    ```
* **String Immutability**
    ```JavaScript
    var myStr = "Jello World";

    myStr [0] = "h"; // It doesn't work

    myStr = "Hello World";

    //String is immutable. I can change individual characters, only changing the entire word. 
    ```
* **Bracket Notation to Find Nth Character in String**
    ```JavaScript
    var firstName = "Ada";
    var SecondLetterOfTheFirstName = firstName[1];

    console.log(SecondLetterOfTheFirstName);
    ```
* **Bracket Notation to Find Last Character in String**
    ```JavaScript
    var firstName = "Ada";
    var lastLetterOfTheFirstName = firstName[firstName.length - 1];

    console.log(lastLetterOfTheFirstName);
    ```
    > -1 is added because the count starts with 0

* **Bracket Notation to Find Nth-to-Last Charachter in String**
    ```JavaScript
    var firstName = "Ada";
    var thirdToLastLetterOfTheFirstName = firstName[firstName.length - 3];

    console.log(thirdToLastLetterOfTheFirstName);
    ```

* **Word Blanks**
    ```JavaScript
    function wordBlanks(myNoun, myAdjective, myVerb, myAdverb) {
        var result = "";
        result += "The " + myAdjective + " " myNoun + " " +  myVerb + " " + " to the store " + myAdverb; 

        return result;
    }

    // Change the words here to test your function
    console.log(wordBlanks("dog", "big", "ran", "quickly"));

    console.log(wordBlanks("bike", "slow", "flew", "slowly"));
    ```
* **Store Multiple Values with Arrays**
    ```JavaScript
        var ourArray = ["John",23];
    ```
    >**I can add different data types in an array**
* **Nested Arrays**
    > Array inside another array
    ```JavaScript
        var myArray = [["me"],["another person"]];
    ```
* **Access Array Data with Indexes**
    ```JavaScript
        var ourArray = [50,60,70];
        var ourData  = ourArray[0]; // equals 50
    ```
    >Indexes 0,1 and 2
* **Modify Array Data With Indexes**
    >Used to modify arrays
    ```JavaScript
        var ourArray = [18, 19, 20];
        console.log(ourArray);
        ourArray[1] = 45;
        console.log(ourArray);
    ```
* **Access Multi-Dimensional Arrays With Indexes**
    ```JavaScript
        var myArray = [[1,2,3], [4,5,6], [7,8,9]];

        var myData = myArray[0][1];

        console.log(myData);
    ```
* **Manipulate Arrays with push**
    ```JavaScript
        var myArray = ["a","b", "c"];
        console.log(myArray);
        myArray.push("d","e");
        console.log(myArray);

        myArray.push(["f","g"]);
        //Adding another array

        console.log (myArray);
    ```
* **Manipulate Arrays with pop()**
    >Removing the item with the pop function
    ```JavaScript
        var myArray = [1,2,3];
        console.log(myArray);
        var myArrayDel = myArray.pop();
        console.log(myArrayDel);
    ```
* **Manipulate Arrays with Shift**
    > Similar to the pop function, but it removes the first element of an array
    ```JavaScript
        var myArray = ["a","b","c",["cat"]];
        console.log(myArray);
        var removedArr = myArray.shift();
        console.log(removedArr);
    ```
* **Manipulate Arrays with unshift()**
    ```JavaScript
    var myArray = ["a","b","c"];
    console.log(myArray);
    myArray.shift();
    console.log(myArray);
    myArray.unshift("parrot");
    console.log(myArray);
    ```
* **Shopping List**
    >Array of Arrays
    ```JavaScript
    var myList = [["Cereal", 3], ["beans", 2]];

    ```

* **Write Reusable Code With Functions**
    ```JavaScript
    function myReusable() {
        console.log("Whatsup!");
    }

    myReusable();
    ```
* **Passing Values to Functions with Arguments**
    >Variables are parameters
    ```JavaScript
    function myFuncWithArgs(a,b) {
        console.log(a - b);
    }

    myFuncWithArgs(10,5);
    ```

* **Global Scope and Functions**
    >**Global Scope** means they can be seen everywhere in JavaScript

    ```JavaScript
    //Declare your variable here
    var myGlobal = 10;
    //I can see this variable everywhere

    function fun1() {
        // Assign 5 to oopsGlobal Here
        oopsGlobal = 5;
    }

    function fun2() {
        var output = "";
        if (typeof myGlobal != "undefined") {
            output += "myGlobal: " + myGlobal;
        }
        if (typeof oopsGlobal != "undefined") {
            output += " oopsGlobal: " + oopsGlobal; 
        }
        console.log(output)
    }

    fun1();
    fun2();
    ```

* **Local Scope and Functions**
    >Only visible inside the function

    ```JavaScript
    
    functions myLocalScope() {
        var myVar = 5;
        console.log(myVar);
        // var myVar only visible inside the function
    }

    myLocalScope();

    console.log(myVar);
    ```
* **Global vs. Local Scope in Functions**
    ```JavaScript
    var outerWear = "T-shirt";
    //Global variable because is declared outside the function

    function myOutfit() {
        var outerWear = "sweater";

        return outerWear;
    }

    console.log(myOutfit());
    console.log(outWear);
    ```
* **Return a Value from a Function with Return**
    ```JavaScript
    function minusSeven(num) {
        return num - 7;
    }

    console.log(minusSeven(10));
    ```
* **Understanding Undefined Value Returned from a function**
    >If I don't use **return** the function won't return any result 
    ```JavaScript
    var sum = 0;
    // global variable 
    function addThree() {
        sum += sum + 3;
    }

    function addFive() {
        sum += + 5;
    }
    ```
* **Assignment with a Returned Value**
    ```JavaScript
    var changed = 0;

    function change(num) {
        return (num + 5) / 3;
    }

    changed = change(10);

    var processed = 0;

    function processArg(num) {
        return (num + 3) / 5;
    }
    ```
* **Stand in Line**
    >Queue is an abstract data structure where items are kept in order. New items can be added and old are taken off from the front of the queue.

    >Adding line to an Array
    ```JavaScript
    function nextInLine(arr, item) {
        //Your code 
        arr.push(item);
        return arr.shift();
        //Shift removes the first item and returns that first item
    }

    var testArr = [1,2,3,4,5,6];

    //JSON.stringify is a way to change an array into a string

    console.log("Before: " JSON.stringify(testArr));

    console.log(nextInLine(testArr, 6));
    console.log("After: " + JSON.stringify(testArr));

    ```

* **Boolean Values**
    > True or False
    ```JavaScript
    function welcomeToBooleans() {
        return false;
    }
    ```

* **Use Conditional Logic with If Statements**
    ```JavaScript
    function ourTrueOrFalse(isItTrue) {
        if (isItTrue) {
            return "Yes, it's true";
        }

        return "No, it's false";
    }

    function trueOrFalse(wasThatTrue) {
        if (wasThatTrue) {
            return "Yes, that was true.";
        }
        return "No, that was false.";
    }

    console.log(trueOrFalse(true));
    ```
* **Comparison with the Equality Operator**
    > = is the assignment operator

    > == is the equality operator
    ```JavaScript
    function testEqual(val) {
        if (val == 12) { //change this line
            return "Equal";
        }
        return "Not Equal";
    }

    //Change this value to test
    testEqual(10);
    ```
* **Comparison with the Strict Equality Operator**
    >Strict equality operator checks value and data type as well. ===

    >Equality operator just check the value. ==

    ```JavaScript
    function testStrict(val) {
        if (val === 7) {
            //change this line
            return "Equal";
        }

        return "Not Equal";
    }

    // Change this value to Test
    testStrict(10);

    /*
    For example:
        3 === 3
        3 == "3"
    */

    ```
* **Practice Comparing Different Values**
    ```JavaScript
    function compareEquality(a,b) {
        if (a == b) {
            //change this line
            return "Equal";
        }

        return "Not Equal";
    }

    //Change this value to test
    console.log(compareEquality(10, "10"));
    ```

* **Comparison with the Inequality Operator**
    > **!=** represents inequality
    ```JavaScript
    function testNotEqual(val) {
        if (val != 99) { // change this line
            return "Not Equal";
        }
        return "Equal";
    }

    //Change this value to test
    console.log(testNotEqual(10));
    ```

* **Comparison with the Strict Inequality Operator**
    >String Inequality operator **!=**
    ```JavaScript
    //Setup
    function testStrictNotEqual(val) {
        //only change this line below

        if (val !== 17) {

            //Only Change Above this line

            return "Not Equal";
        }

        return "Equal";
    }

    //Change this value to test
    console.log(testStrictNotEqual(18));
    ```

* **Comparison with the Logical and Operator**
    ```JavaScript
    function testGreaterThan(val) {
        if (val > 100) { // Change this line
            return "Over 100";
        }

        if (val > 10) { 
            return "Over 10";
        }

        return "10 or Under";
    }

    // Change this line to Test
    console.log(testGreaterThan(10));
    
    ```

* **Comparison with the Greater Than Or Equal to Operator**
    > Greater than equal signal **>=**
    ```JavaScript
    function testGreaterOrEqual(val) {
        if (val >= 20) { //change this line
            return "20 or Over";
        }

        if (val >= 10) { // Change this line
            return "10 or Over";
        }

        return "Less than 10";
    }

    console.log(testGreaterOrEqual(10));
    ```

* **Comparison with the Less Than Operator**
    > Greater than equal signal **<**
    ```JavaScript
    function testGreaterOrEqual(val) {
        if (val < 20) { //change this line
            return "20 or Over";
        }

        if (val < 10) { // Change this line
            return "10 or Over";
        }

        return "Less than 10";
    }

    console.log(testGreaterOrEqual(10));
    ```

**Comparison with the Less Than or Equal Operator**
    
>Greater than equal signal **<=**

```JavaScript
    function testGreaterOrEqual(val) {
        if (val <= 20) { //change this line
            return "20 or Over";
        }

        if (val <= 10) { // Change this line
            return "10 or Over";
        }

        return "Less than 10";
    }

    console.log(testGreaterOrEqual(10)); 
```

**Comparison with the Logical and Operator**
>Greater than equal signal **&&**

```JavaScript
    function testLogicalAnd(val) {
        if (val <= 50 && val >= 25>) {
            return "Yes";
        }

        // Only change code above this line
        return "No";
    }

    console.log(testLogicalAnd(10));    
```

**Comparison with the logical OR Operator**
>Greater than equal signal **||**

```JavaScript
    function testLogicalAnd(val) {
        if (val <= 50 || val >= 25>) {
            return "Yes";
        }

        // Only change code above this line
        return "No";
    }

    console.log(testLogicalAnd(10));    
```

**Else Statement**
> If it is not true, execute the else statement
```JavaScript
    function testElse(val) {
        var result = "";
        //Only change code below this line

        if (val > 5) {
            result = "Bigger than 5";
        }else {
            result = "5 or smaller";
        }

        return result;
    }    
```

**Else If Statement**
> If it is not true, execute the else statement
```JavaScript
    if (val > 10) {
        return "Greater than 10";
    } else if (val < 5) {
        return "Smaller than 5";
    } else {
        return "Between 5 and 10";
    }
```
**Logical Order in If Else Statement**
```JavaScript
function orderMyLogic(val) {
    if (val > 10) { 
        return "Greater than 10";
    } else if (val < 5) {
        return "Smaller than 5";
    } else {
        return "Between 5 and 10";
    }

    //Check the number order
}

console.log(orderMyLogic(7));
```

**Golf Code**
```JavaScript
var names = ["Hole-in-one!", "Eagle", "Birdie", "Par", "Bogey", "Double Bogey"];

function golfScore(par, strokes) {
    if (strokes == 1) {
        return names[0];
    } else if (strokes <= par - 2) {
        return names[1];
    } else if (strokes == par - 1) {
        return names[2];
    } else if (strokes == par) {
        return names[3];
    } else if (strokes == par + 1) {
        return names[4];
    } else if (strokes == par + 2) {
        return names[3];
    }
}

console.log(golfScore(5, 4));

```

**Switch Statement**
```JavaScript
function caseInSwitch(val) {
    var answer = "";
    switch(val) {
        case 1:
            answer = "alpha";
            break;
        case 2:
            answer = "beta";
            break;
        case 3: 
            answer = "gamma";
            break;
        case 4: 
            answer = "delta";
            break;
    }

    return answer;
}

//Change this value
console.log(caseInSwitch(1));
/*
Write a switch statement which tests val and sets the answer for the following conditions:
1 - "alpha"
2 - "beta"
3 - "gamma"
4 - "delta" 
*/

```

**Default Option in Switch Statement**
> Default is similar to the Else Statement
```JavaScript
function caseInSwitch(val) {
    var answer = "";
    switch(val) {
        case 1:
            answer = "alpha";
            break;
        case 2:
            answer = "beta";
            break;
        case 3: 
            answer = "gamma";
            break;
        case 4: 
            answer = "delta";
            break;
        default:
            answer = "I don't know what is that...";
    }

    return answer;
}

//Change this value
console.log(caseInSwitch(1));

```

**Multiple Identical Options in Switch Statements**
```JavaScript
function sequentialSizes(val) {
    var answer = "";
    switch(val) {
        case 1:
        case 2:
        case 3:
            answer = "Low";
            break;
        case 4:
        case 5:
        case 6:
            answer = "Mid";
            break;
        case 7:
        case 8:
        case 9:
            answer = "High";
            break;
    }

    return answer;
}

//Change this value
console.log(sequentialSizes(1));

```

* **Returning Boolean Values from Functions**
    ```JavaScript
    function isLess() {
        // Fix this code
        if (a < b) {
            return true;
        } else {
            return false;
        }
    }

    //Instead, do this way below:

    function isLess(a,b){
        return a < b;
        // it will return true or false
    }

    // change these values to test
    console.log(isLess(10, 15));

    ```

* **Returning Early Pattern from Functions**
    ```JavaScript
    //Setup
    function abTest(a,b) {
        // Only change code below this line

        if (a < 0 || b < 0) {
            return undefined;
        }

        //Only change code above this line

        return Math.round(Math.pow(Math.sqrt(a) + Math.sqrt(b), 2));
    }

    console.log(abTest(2,2));
    ```

* **Counting Cards**
    ```JavaScript
    var count = 0;

    function cc(card) {
        switch(card) {
            case 1:
            case 2:
            case 3:
            case 4:
            case 5:
            case 6:
                count++;
                break;
            case 10:
            case "J":
            case "Q":
            case "K":
            case "A":
                count--;
                break;

        }

        var holdbet = "Hold";

        if (count > 0) {
            holdbet = "Bet";
        }

        return count + " " + holdbet;
    }

    cc(2); cc("K"); cc(10); cc('K'); cc("A");
    console.log(cc(4));

    ```

* **Build JavaScript Objects**
    ```JavaScript
    var ourDog = {
        "name": "Camper",
        "legs": 4,
        "trails": 1,
        "friends": ["everything!"]
    };

    //Only change code below this line.

    var myCat = {
        "name": "Bia",
        "legs": 4,
        "tail": 1,
        "friends": ["She has a lot of friends!"]
    };

    ```
* **Accessing Object Properties with Dot Notation**
    ```JavaScript
    var myCat = {
        "name": "Bia",
        "legs": 4,
        "tail": 1,
        "friends": ["She has a lot of friends!"]
    };

    //Only change code below this line:

    var friend1 = myCat.name;
    var friend2 = myCat.name;

    console.log(friend2);
    ```
* **Accessing Object Properties with Bracket Notation**
    ```JavaScript
    //Setup
    var testObj = {
        "an entree": "hamburguer",
        "my side": "veggies",
        "the drink": "water"
    };

    //Only change code below this line

    var entreeValue = testObj["an entree"];
    var drinkValue = testObj['the drink'];
    ```
* **Accessing Object Properties with Variables**
    ```JavaScript
    var testObj = {
        12: "Namath",
        16: "Montana",
        19: "Unitas"
    };

    //Only change code below this line;

    var playNumber = 16; 
    var player = testObj[playerNumber];

    ```

* **Delete Properties from an Object**
    >Use the **delete** keyword
    ```JavaScript
    var myCat = {
        "name": "Bia",
        "legs": 4,
        "tail": 1,
        "friends": ["She has a lot of friends!"]
    };

    delete myCat.tail;
    ```
* **Using Objects for Lookup**
    >Same functionality of a Switch Statement
    ```JavaScript

    function phoneticLookup(val) {
        var result = "";

        var lookup = {
        "alpha": "Adams",
        "bravo": "Boston",
        "charlie": "Chicago",
        "echo": "Easy",
        "foxtrot": "Frank"
        };
        result = lookup[val];
        //Only change code above this line
        return result;
    }

    console.log(phoneticLookup("charlie"));
     
    ```
* **Testing Objects For Properties**
    >**hasOwnProperty** command
    ```JavaScript
    var myObj = {
        gift: "pony",
        pet: "kitten",
        bed: "sleigh"
    };

    function checkObj(checkProp) {
        // Your code here
        if (myObj.hasOwnProperty(checkProp)) {
            return myObj[checkProp];
        } else {
            return "Not Found";
        }
    }

    //Test your code by modifying these values
    console.log(checkObj("gift"));
    ```
* **Manipulating Complex Objects**
    ```JavaScript
    var myMusic = [
        {
            "artist": "Ademir Galeno",
            "title": "Campus Bar",
            "release_year": "2016",
            "formats": [
                "CD",
                "8T",
                "LP"
            ],
            "gold": true
        }
        // Add record here
        {
            "artist": "Ze Maguinho",
            "title": "Vamo fazer bebe",
            "release_year": "2018",
            "formats": [
                "CD",
                "8T",
                "LP",
                "Youtube video"
            ],
            "gold": true
        }
    ];
    ```
* **Accessing Nested Objects**
    ```JavaScript
    //Setup
    var myStorage = {
        "car": {
            "inside": {
                "glove box": "maps",
                "passenger seat": "crumbs"
            },
            "outside": {
                "trunk": "jack"
            }
        }
    };

    var gloveBoxContents = myStorage.car.inside["glove box"]; //Change this line

    console.log(gloveBoxContents)
    ```
* **Accessing Nested Arrays**
    ```JavaScript
    var myPlants = [
        {
            type: "flowers",
            list: [
                "rose",
                "tulip",
                "dandelion"
            ]
        },
        {
            type: "trees",
            list: [
                "fir",
                "pine",
                "birch"
            ]
        }
    ];

    // Only change code below this line

    var secondTree = "myPlants[1].list[1]";
    ```
* **Record Collection**
    ```JavaScript
    var collection = {
        "2548": {
            "album": "Slippery When Wet",
            "artist": "Bon Jovi",
            "tracks": [
                "Let It Rock",
                "You Give Love a Bad Name"
            ]
        },
        "2468": {
            "album": "1999",
            "artist": "Prince",
            "tracks": [
                "1999",
                "Little Red Corvette"
            ]
        },
        "1245": {
            "artist": "Prince",
            "tracks": []
        },
        "5439": {
            "artist": "ABBA Gold"
        }
    };

    //Keep a copy of the collection for tests
    var collectionCopy = JSON.parse(JSON.stringify(collection));  

    console.log(collectionCopy);

    //Only change code below this line
    function updateRecords(id, prop, value) {
        if (value === "") {
            delete collection[id][prop];
        } else if (prop === "tracks") {
            collection[id][prop] = collection[id][prop] || [];
            collection[id][prop].push(value);
        } else {
            collection[id][prop] = value;
        }

        return collection;
    }

    //Alter values below to test your code
    console.log(updateRecords(5439, "artist", "ABBA"));
    ```
* **Iterate with While Loops**
    ```JavaScript
    var myArray = [];

    var i = 0;
    while(i < 5) {
        myArray.push(i);
        i++;
    }

    console.log(myArray);
    ```
* **Iterate with For Loops**
    ```JavaScript
    var ourArray = [];

    for (var i = 0; i < 5; i++) {
        ourArray.push(i);
    }

    console.log(ourArray);
    ```
* **Iterate Odd numbers with a For Loop**
    ```JavaScript
    var ourArray = [];

    for(var i = 0; i < 10; i += 2) {
        ourArray.push(i);
    }

    console.log(ourArray);

    //Setup
    var myArray = [];

    // Only change code below this line
    //Odd Numbers
    for(var i = 1; i < 10; i += 2) {
        myArray.push(i);
    }

    console.log(myArray);
    ```
* **Count Backwards with a For Loop**
    ```JavaScript
    var ourArray = [];

    for(var i = 10; i > 0; i -= 2) {
        ourArray.push(i);
    }

    console.log(ourArray);
    ```
* **Iterate Through an Array with a For Loop**
    ```JavaScript
    var ourArr = [9, 10, 11, 12];
    var ourTotal = 0;

    for(var i = 0; i < ourArr.length; i++) {
        ourTotal += ourArr[i];
    } 

    console.log(ourTotal);

    //Setup
    var myArr = [2,3,4,5,6];
    ```
* **Nesting For Loops**
    ```JavaScript
    function multiplyAll(arr) {
        var product = 1;

        for (var i=0; i < arr.length; i++) {
            for(var j=0; j < arr[i].length; j++) {
                product *= arr[i],[j];
            }            
        }

        return product;
    }

    var product = multiplyAll([[1,2],[3,4],[5,6,7]]);

    console.log(product);
    ```
* **Iterate with Do... While Loops**
    ```JavaScript
    var myArray = [];
    var i = 10;

    // Only change code below this line.

    do {
        myArray.push(i);
        i++;
    }  while (i < 5);

    console.log(i, myArray);
    ```
* **Profile Lookup**
    ```JavaScript
    var contacts = [
        {
            "firstName": "Akira",
            "lastName": "Laine",
            "number": "1233546",
            "likes": ["Pizza", "Coding"]
        },
        {
            "firstName": "Joe",
            "lastName": "Limberg",
            "number": "123896",
            "likes": ["Cake", "Coding"]
        },
        {
            "firstName": "Mark",
            "lastName": "Twin",
            "number": "897546",
            "likes": ["Candy", "Coding"]
        }
    ]

    //finding for name and property
    function lookUpProfile(name, prop) {
        for (var i = 0; i < contacts.length; i++) {
            if(contacts[i].firstName === name) {
                return contacts[i][prop] || "No such Property";
            }
        }
        return "No such contact";
    }

    var data = lookUpProfile("Akira", "likes");

    console.log(data);
    ```
* **Generate Random Fractions**
    ```JavaScript
    function randomFraction() {
    
        return Math.random();
    }

    console.log(randomFraction());
    ```
* **Generate Random Whole Numbers**
    ```JavaScript
    var randomNumberBetween0and19 = Math.floor(Math.random() * 20);

    function randomWholeNum() {
        return Math.random();
    }    

    console.log(randomWholeNum());
    ```
* **Generate Random Whole Numbers within a Range**
    ```JavaScript
    function ourRandomRange(ourMin, ourMax) {
        return Math.floor(Math.random() * (ourMax - ourMin + 1)) + ourMin;
    }

    ourRandomRange(1,9);

    // Only change code below this line

    function randomRange(myMin, myMax) {
        return Math.floor(Math.random() * (myMax - myMin + 1)) + myMin;
    }

    var myRandom = randomRange(5,15);

    console.log(myRandom);
    ```
* **Use the parseInt Function**
    ```JavaScript
    function convertToInteger(str) {
        return parseInt(str);
    }

    convertToInteger("56");
    ```
* **Use the parseInt Function with a Radix**
    ```JavaScript
    function convertToInteger(str) {
        return parseInt(str, 2)
    }

    convertToInteger("10011");
    ```
* **Use the Conditional (Ternary) Operator**
    ```JavaScript
    // condition ? statement-if-true : statement-if-false;
    function checkEqual(a, b) {
        /*
        if(a === b) {
            return true;
        } else {
            return false;
        }
        */
        return a === b ? true : false;

        return a === b;
    }

    checkEqual(1,2); 
    ```
* **Use Multiple Conditional (Ternary) Operators**
    ```JavaScript
    function checkSign(num) {
        return num > 0 ? "positive" : num < 0 ? "negative" : "zero"
    }

    console.log(checkSign());
    ```
* **Differences Between the var and let Keywords**
    > **let** does not allow declaration twice
    ```JavaScript
        //Change for let and you will get an error message.
        var carName = "Bia";
        var quote;

        var catName = "Franklin";

        function catTalk() {
            "use strict";

            catName = "Oliver";
            quote = catName + " says Meow!";
        }

        catTalk1();

        let carName = "Bia";
        let quote;

        let catName = "Franklin";

        function catTalk1() {
            "use strict";

            catName = "Oliver";
            quote = catName + " says Meow!";
        }

        catTalk1();
    ```
* **Compare Scopes of the var and let Keywords**
    ```JavaScript
    function checkScope() {
        "use strict";
            var i = "function scope";
            if (true) {
                i = "block scope";
                console.log("Block scope i is ", i);
            }
            console.log("Function scope is: ", i);
            return i;
    }

    checkScope();
    ```
* **Declare a Read-Only Variable with the const keyword**
    ```javaScript
    function printManyTimes(str) {
        "use strict";

        // If a declare variable below as const, I won't be able to declare again
        var sentence = str + " is cool!";
        //const SENTENCE = str + "is cool!";

        setence = str + " is amazing!";

        for(var i = 0; i < str.length; i+=2) {
            console.log(sentence);
        }
    }

    printManyTimes("freeCodeCamp");
    ```
* **Mutate an Array Declared with const**
    ```JavaScript
    const s = [5,7,2];
    function editInPlace() {
        "use strict";

        //s = [2, 5, 7];
        s[0] = 2;
        s[1] = 5;
        s[3] = 7;
    }

    editInPlace();
    
    console.log(s);
    ```
* **Prevent Object Mutation**
    > Use **Object.freeze();**
    ```JavaScript
    function freezeObj(MATH_CONSTANTS) {
        "use strict";
        const MATH_CONSTANTS = {
            PI: 3.14
        };

        Object.freeze(MATH_CONSTANTS);

        try {
            MATH_CONSTANTS.PI = 99;
        } catch( ex ) {
            console.log(ex);
        }
        return MATH_CONSTANTS.PI;
    }

    const PI = freezeObj();

    console.log(PI);
    ```
* **Use Arrow Functions to Write Concise Anonymous Functions**
    ```javaScript
    //Anonymous Function. Function doesn't have a name, only the variable
    //I can convert an anonymous function to an arrow function
    var magic = function() {
        return new Date();
    };

    //The first function is the same as below (arrow function):
    // => signal represents return
    var magic = () => new Date();
    };
    ```
* **Write Arrow Functions with Parameters**
    ```javaScript
    var myConcat = (arr1, arr2) => arr1.concat(arr2);

    console.log(myConcat([1,2], [3,4,5]));
    ```
* **Write Higher Order Arrow Functions**
    ```javaScript
    const realNumberArray = [4, 5.6, -9.8, 3.14, 42, 6, 8.34, -2];

    const squareList = (arr) => {
        const squaredIntegers = arr.filter(num => Number.isInteger(num) && num > 0).map(x => x * x);
        return squaredIntegers;
    };

    const squaredIntegers = squareList(realNumberArray);

    console.log(squaredIntegers);
    ```
* **Write Higher Order Arrow Functions**
    ```javaScript
    const increment = (function(){
        return function increment(number, value = 1) {
            return number + value;
        };
    }); ();
    console.log(increment(5, 2));
    console.log(increment(5));
    ```
* **Use the Rest Operators with Function Parameters**
    ```javaScript
    const sum (function() {
        return function sum(x, y, z) {
            const args = [ x, y, z];
            return args.reduce((a, b) => a + b, 0);
        };
    });();
    console.log(sum(1,2,3));
    console.log(increment(5));
    ```
* **Use the Rest Operators with Function Parameters**
    > Rest Operator is **...**
    ```javaScript
    const sum (function() {
        return function sum(...args) {
            // I don't need this anymore const args = [ x, y, z];
            return args.reduce((a, b) => a + b, 0);
        };
    });();
    console.log(sum(1,2,3));
    ```
* **Use the Spread Operator to Evaluate Arrays In-Place**
    ```javaScript
    const arr1 = ['JAN', 'FEB', 'MAR', 'APR',]'MAY'];

    let arr2;
    (function() {
        arr2 = [...arr1]; //change this line
        arr1[0] = 'potato'
    })();

    console.log(arr2);

    ```
* **Use Destructuring Assignment to Assign Variables from Objects**
    > { x : a, y : b, z : c } = voxel
    ```javaScript
    var voxel = {x: 3.6m y:7.4, z:6.54};

    var x = voxel.x; // x = 3.6
    var y = voxel.y; // y = 7.4
    var z = voxel.z; // z = 6.54

    const { x : a, y : b, z : c } = voxel; // a = 3.6, b = 7.4, c = 6.54

    const AVG_TEMPERATURES = {
        today: 77.5,
        tomorrow: 79
    };

    function getTempOfTmrw(avgTemperatures) {
        "use strict";
        //Change code below this line
        //const tempOfTomorrow = undefined; // change this line

        const { tomorrow : tempOfTomorrow } = avgTemperatures;
        // get the tomorrow field and assign it to tempTomorrow variable

        return tempOfTomorrow;
    }

    console.log(getTempOfTmrw(AVG_TEMPERATURES)); //should be 79

    ```
* **Destructuring Assignment with Nested Objects**
    ```javaScript
    const LOCAL_FORECAST = {
        today: { min: 72, max: 83 },
        tomorrow: { min: 73.3, max: 84.6 }
    };

    function getMaxOfTmrw(forecast) {
        "use strict";

        const { tomorrow : {max: maxOfTomorrow }} = forecast;

        return maxOfTomorrow;
    }

    console.log(getMaxOfTmrw(LOCAL_FORECAST));

    ```
* **Use Destructuring Assignment to Assign Variables from Arrays**
    ```javaScript
    const [z, x, , y] = [1,2,3,4,5,6];
    console.log(z, x, y);

    let a = 8, b = 6;
    (() => {
        "use strict";
        [a, b] = [b, a]
    });();
    // console.log(a);
    // console.log(b);

    ```
* **Use Destructuring Assignment with the Rest Operator**
    ```javaScript
    const source = [1,2,3,4,5,6,7,8,9,10];
    function removeFirstTwo(list) {

        const [ a, b, ...arr] = list;
        const [ , , ...arr] = list;

        return arr;
    }

    const arr = removeFirstTwo(source);
    console.log(arr);
    console.log(source);
    ```
* **Use Destructuring Assignment to Pass an Object as a Function's Parameters**
    ```javaScript
    const stats = {
        max: 56.78,
        standard_deviation: 4.34,
        median: 34.54,
        mode: 23.87,
        min: -0.75,
        average: 35.85
    };

    const half = (function() {
        //max, min (max)
        return function half(max, min) {
            return (max + min) / 2.0;
        };
    }) ();

    console.log(stats);
    console.log(half(stats));

    ```
* **Create Strings using Template Literals**
    ```javaScript
    const person = {
        name: "Zodiac Hasbro",
        age: 56
    };

    //Template literal with multi-line and string interpolation
    const greeting = `Hello, my name is ${person.name}! I am ${person.age} years old.`;

    console.log(greeting);

    const result = {
        success: ["max-length", "no-amd", "prefer-arrow-functions"],
        failure: ["no-var", "var-on-top", "linebreak"],
        skipped: ["id-blacklist", "no-dup-keys"]
    };

    function makeList(arr) {
        const resultDisplayArray = [];
        for (let i = 0; i < arr.length; i++) {
            resultDisplayArray.push(`<li class="text-warning">${arr[i]}</li>`)
        }

        return resultDisplayArray;
    }

    /**

    makeList(result.failure) should return:
    [`<li class="test-warning">no-var]</li>`,
      <li class="test-warning">var-on-top</li>`,
      <li class="text-warning">linebreak</li>` ]
    **/

    const resultDisplayArray = makeList(result.failure);

    console.log(resultDisplayArray)

    ```
* **Write Concise Object Literal Declarations Using Simple Fields**
    ```javaScript
    /*const createPerson = (name, age, gender) => {
        return {
            name: name,
            age: age, 
            gender: gender
        };
    };
    */

    //Beter aproach
    const createPerson = (name, age, gender) => ({ name, age, gender });

    console.log(createPerson("Zodiac Hasbro", 56, "male"));
    ```
* **Write Concise Declarative Functions**
    ```javaScript
    // the long way to put a function within an object
    /*const bicycle = {
        gear: 2,
        setGear: function(newGear) {
            "use strict";
            this.gear = newGear;
        }
    };
    */

    //Simple way:
    const bicycle = {
        gear: 2,
        setGear (newGear) {
            "use strict";
            this.gear = newGear;
        }
    };

    bycicle.setGear(3);
    console.log(bicycle.gear);
    ```
* **Use class Syntax to Define a Constructor Function**
    ```javaScript
    /*
    var SpaceShuttle = function(targetPlanet){
        this.targetPlanet = targetPlanet;
    }

    var zeus = new SpaceShuttle('Jupiter');

    console.log(zeus.targetPlanet)

    */

    //Using class
    class SpaceShuttle{
        constructor(targetPlanet) {
            this.targetPlanet = targetPlanet;
        }
    }

    var zeus = new SpaceShuttle('Jupiter');

    console.log(zeus.targetPlanet)


    /*
    
    function makeAClass() {
        return Vegetable;
    }

    const Vegetable = makeClass();
    const carrot = new Vegetable('carrot');
    console.log(carrot.name);
    
    */

    // Class way:

    function makeAClass() {
        class Vegetable {
            constructor(name){
                this.name = name;
            }
        }

        return Vegetable;
    }

    const Vegetable = makeClass();
    const carrot = new Vegetable('carrot');
    console.log(carrot.name);

    ```
* **Use getters and Setters to Control Access to an Object**
    ```javaScript
    class Book {
        constructor(author) {
            this._author = author;
        }

        // getter 
        get writer() {
            return this._author;
        }

        // setter 
        set writer(updatedAuthor){
            this._author = updatedAuthor;
        }
    }

    function makeClass() {

        class Thermostat {
            constructor(temp) {
                // Underscore _ means private variable
                this._temp = 5/9 * (temp - 32);
            }
            get temperature() {
                return this._temp;
            }

            set temperature(updatedTemp) {
                this._temp = updatedTemp;
            }
        }

        return Thermostat;
    }

    const Thermostat = makeClass();
    const thermos = new Thermostat(76);
    let temp = thermos.temperature;
    thermos.temperature = 26;
    temp = thermos.temperature;
    console.log(temp);
    ```
* **Understand the Difference Between import and require**
    ```javaScript
    
    //Creating file CapitalizeStrings a part
    export const capitalizeString = str => str.toUpperCase()

    //...

    import { capitalizeString } from "./path"

    const cap = capitalizeString("hello");

    console.log(cap);

    ```
* **Use Export to Reuse a Code Block**
    ```javaScript
    const capitalizeString = (string) => {
        return  string.charAt(0).toUpperCase() + string.slice(1);
    }

    // exporting the function and the 2 variables
    export { capitalizeString };

    export const foo = "bar";
    export const bar = "foo";
    ```
* **Use * to Import Everything from a file**
    ```javaScript

    import * as capitalizeStrings from "./path";

    ```
* **Create an Export Fallback with export default**
    >Export default
    ```javaScript
    export default function subtract(x,y) {return x - y;}
    ```
* **Import Default Export**
    ```javaScript
    import subtract from "math_functions";

    subtract(7,4);
    ```
---
## Data Structure

* **Stacks**
    ```javaScript
    var letters = []; //this is my stack

    var word = "happyCoding";

    var rword = "";

    //put letters of word into stack
    for (var i = 0; i < word.length; i++) {
        letters.push(word[i]);
    }

    //pop off the stack in reverse order
    for (var i = 0; i < word.length; i++) {
        rword += letters.pop();
    }

    if (rword === word) {
        console.log(word + " is a palindrome.");
    } else {
        console.log(word + " is not a palindrome.");
    }

    // Creates a stack 
    var Stack = function() {
        this.count = 0;
        this.storage = {};

        //Adds a value onto the end of the stack
        this.push = function(value) {
            this.storage[this.count] = value;
            this.count++;
        }

        //Removes and returns the value at the end of the stack
        this.pop = function() {
            if (this.count === 0) {
                return undefined;
            }

            this.count--;
            var result = this.storage[this.count];
            delete this.storage[this.count];
            return result;
        }

        this.size = function() {
            return this.count;
        }

        // Returns the value at the end of the Stack
        this.peek = function() {
            return this.storage[this.count-1];

        }
    }

    var myStack = new Stack();

    myStack.push(1);
    myStack.push(2);
    console.log(myStack.peek());
    console.log(myStack.pop());
    console.log(myStack.peek());
    myStack.push("niceCatCalendar");
    console.log(myStack.size());
    console.log(myStack.peek());
    console.log(myStack.pop());
    console.log(myStack.peek());

    ```
* **Sets**
    ```javaScript

        function mySet() {
        // the var collection will hold the set
        var collection = [];
        // this method will check for the presence of an element and return true or false
        this.has = function(element) {
            return (collection.indexOf(element) !== -1);
        };
        // this method will return all the values in the set
        this.values = function() {
            return collection;
        };
        // this method will add an element to the set
        this.add = function(element) {
            if(!this.has(element)){
                collection.push(element);
                return true;
            }
            return false;
        };
        // this method will remove an element from a set
        this.remove = function(element) {
            if(this.has(element)){
                index = collection.indexOf(element);
                collection.splice(index,1);
                return true;
            }
            return false;
        };
        // this method will return the size of the collection
        this.size = function() {
            return collection.length;
        };
        // this method will return the union of two sets
        this.union = function(otherSet) {
            var unionSet = new mySet();
            var firstSet = this.values();
            var secondSet = otherSet.values();
            firstSet.forEach(function(e){
                unionSet.add(e);
            });
            secondSet.forEach(function(e){
                unionSet.add(e);
            });
            return unionSet;
        };
        // this method will return the intersection of two sets as a new set
        this.intersection = function(otherSet) {
            var intersectionSet = new mySet();
            var firstSet = this.values();
            firstSet.forEach(function(e){
                if(otherSet.has(e)){
                    intersectionSet.add(e);
                }
            });
            return intersectionSet;
        };
        // this method will return the difference of two sets as a new set
        this.difference = function(otherSet) {
            var differenceSet = new mySet();
            var firstSet = this.values();
            firstSet.forEach(function(e){
                if(!otherSet.has(e)){
                    differenceSet.add(e);
                }
            });
            return differenceSet;
        };
        // this method will test if the set is a subset of a different set
        this.subset = function(otherSet) {
            var firstSet = this.values();
            return firstSet.every(function(value) {
            return otherSet.has(value);
            });
        };
    }
    var setA = new mySet();  
    var setB = new mySet();  
    setA.add("a");  
    setB.add("b");  
    setB.add("c");  
    setB.add("a");  
    setB.add("d");  
    console.log(setA.subset(setB));
    console.log(setA.intersection(setB).values());
    console.log(setB.difference(setA).values());

    var setC = new Set();  
    var setD = new Set();  
    setC.add("a");  
    setD.add("b");  
    setD.add("c");  
    setD.add("a");  
    setD.add("d");  
    console.log(setD.values())
    setD.delete("a");
    console.log(setD.has("a"));
    console.log(setD.add("d"));     
    ```
* **Queues**
    ```javaScript
    
    function Queue() {
        collection = [];
        this.print = function() {
            console.log(collection);
        };
        this.enqueue = function(element) {
            collection.push(element);
        };
        this.dequeue = function() {
            return collection.shift();
        };
        this.front = function() {
            return collection.shift();
        }
        this.size = function() {
            return collection.length;
        };
        this.isEmpty = function() {
            return (collection.length === 0);
        };
    }

    var q  = new Queue();
    q.enqueue('a');
    q.enqueue('a');
    q.enqueue('a');
    q.print();
    q.dequeue();
    console.log(q.front());
    q.print();

    function priorityQueue () {
        var collection = [];
        this.printCollection = function() {
            (console.log(collection));
        };
        this.enqueue = function(element){
            if(this.isEmpty()){
                collection.push(element);
            } else {
                var added = false;
                for (var i=0; i<collection.length; i++){
                    if(element[1] < collection[i][i]){
                        //checking priorities
                        collection.splice(i,0,element);
                        added = true;
                        break;
                    }
                }
                if (!added){
                    collection.push(element);
                }
            }
        };
        this.dequeue = function() {
            var value = collection.shift();
            return value[0];
        };
        this.front = function(){
            return collection[0];
        };
        this.size = function() {
            return collection.length;
        };
        this.isEmpty = function() {
            return (collection.length === 0);
        };
    }

    var pq = new priorityQueue(); 
    pq.enqueue(['Beau Carnes', 2]); 
    pq.enqueue(['Quincy Larson', 3]);
    pq.enqueue(['Ewa Mitulska-Wójcik', 1])
    pq.enqueue(['Briana Swift', 2])
    pq.printCollection();
    pq.dequeue();
    console.log(pq.front());
    pq.printCollection();

    ```
    * **Binary Search Tree**
        ```javaScript
        class Node {
        constructor(data, left = null, right = null) {
            this.data = data;
            this.left = left;
            this.right = right;
        }
        }

        class BST {
        constructor() {
            this.root = null;
        }
        add(data) {
            const node = this.root;
            if (node === null) {
            this.root = new Node(data);
            return;
            } else {
            const searchTree = function(node) {
                if (data < node.data) {
                if (node.left === null) {
                    node.left = new Node(data);
                    return;
                } else if (node.left !== null) {
                    return searchTree(node.left);
                }
                } else if (data > node.data) {
                if (node.right === null) {
                    node.right = new Node(data);
                    return;
                } else if (node.right !== null) {
                    return searchTree(node.right);
                }
                } else {
                return null;
                }
            };
            return searchTree(node);
            }
        }
        findMin() {
            let current = this.root;
            while (current.left !== null) {
            current = current.left;
            }
            return current.data;
        }
        findMax() {
            let current = this.root;
            while (current.right !== null) {
            current = current.right;
            }
            return current.data;
        }
        find(data) {
            let current = this.root;
            while (current.data !== data) {
            if (data < current.data) {
                current = current.left;
            } else {
                current = current.right;
            }
            if (current === null) {
                return null;
            }
            }
            return current;
        }
        isPresent(data) {
            let current = this.root;
            while (current) {
            if (data === current.data) {
                return true;
            }
            if (data < current.data) {
                current = current.left;
            } else {
                current = current.right;
            }
            }
            return false;
        }
        remove(data) {
            const removeNode = function(node, data) {
            if (node == null) {
                return null;
            }
            if (data == node.data) {
                // node has no children 
                if (node.left == null && node.right == null) {
                return null;
                }
                // node has no left child 
                if (node.left == null) {
                return node.right;
                }
                // node has no right child 
                if (node.right == null) {
                return node.left;
                }
                // node has two children 
                var tempNode = node.right;
                while (tempNode.left !== null) {
                tempNode = tempNode.left;
                }
                node.data = tempNode.data;
                node.right = removeNode(node.right, tempNode.data);
                return node;
            } else if (data < node.data) {
                node.left = removeNode(node.left, data);
                return node;
            } else {
                node.right = removeNode(node.right, data);
                return node;
            }
            }
            this.root = removeNode(this.root, data);
        }
        isBalanced() {
            return (this.findMinHeight() >= this.findMaxHeight() - 1)
        }
        findMinHeight(node = this.root) {
            if (node == null) {
                return -1;
            };
            let left = this.findMinHeight(node.left);
            let right = this.findMinHeight(node.right);
            if (left < right) {
                return left + 1;
            } else {
                return right + 1;
            };
        }
        findMaxHeight(node = this.root) {
            if (node == null) {
                return -1;
            };
            let left = this.findMaxHeight(node.left);
            let right = this.findMaxHeight(node.right);
            if (left > right) {
                return left + 1;
            } else {
                return right + 1;
            };
        }
        inOrder() {
            if (this.root == null) {
            return null;
            } else {
            var result = new Array();
            function traverseInOrder(node) {       
                node.left && traverseInOrder(node.left);
                result.push(node.data);
                node.right && traverseInOrder(node.right);
            }
            traverseInOrder(this.root);
            return result;
            };
        }
        preOrder() {
            if (this.root == null) {
            return null;
            } else {
            var result = new Array();
            function traversePreOrder(node) {
                result.push(node.data);
                node.left && traversePreOrder(node.left);
                node.right && traversePreOrder(node.right);
            };
            traversePreOrder(this.root);
            return result;
            };
        }
        postOrder() {
            if (this.root == null) {
            return null;
            } else {
            var result = new Array();
            function traversePostOrder(node) {
                node.left && traversePostOrder(node.left);
                node.right && traversePostOrder(node.right);
                result.push(node.data);
            };
            traversePostOrder(this.root);
            return result;
            }
        }

        levelOrder() {
            let result = [];
            let Q = []; 
            if (this.root != null) {
                Q.push(this.root);
                while(Q.length > 0) {
                    let node = Q.shift();
                    result.push(node.data);
                    if (node.left != null) {
                        Q.push(node.left);
                    };
                    if (node.right != null) {
                        Q.push(node.right);
                    };
                };
                return result;
            } else {
                return null;
            };
        };
        }



        const bst = new BST();

        bst.add(9);
        bst.add(4);
        bst.add(17);
        bst.add(3);
        bst.add(6);
        bst.add(22);
        bst.add(5);
        bst.add(7);
        bst.add(20);

        console.log(bst.findMinHeight());
        console.log(bst.findMaxHeight());
        console.log(bst.isBalanced());
        bst.add(10);
        console.log(bst.findMinHeight());
        console.log(bst.findMaxHeight());
        console.log(bst.isBalanced());
        console.log('inOrder: ' + bst.inOrder());
        console.log('preOrder: ' + bst.preOrder());
        console.log('postOrder: ' + bst.postOrder());

        console.log('levelOrder: ' + bst.levelOrder());

    ```

* **Bynary Search Tree Traversal & Height**

    ![Binary tree diagram](https://markdown-here.com/img/icon256.png)

    ```javaScript
        class Node {
            constructor(data, left = null, right = null) {
            this.data = data;
            this.left = left;
            this.right = right;
            }
        }

        class BST {
            constructor() {
            this.root = null;
            }
            add(data) {
            const node = this.root;
            if (node === null) {
                this.root = new Node(data);
                return;
            } else {
                const searchTree = function(node) {
                if (data < node.data) {
                    if (node.left === null) {
                    node.left = new Node(data);
                    return;
                    } else if (node.left !== null) {
                    return searchTree(node.left);
                    }
                } else if (data > node.data) {
                    if (node.right === null) {
                    node.right = new Node(data);
                    return;
                    } else if (node.right !== null) {
                    return searchTree(node.right);
                    }
                } else {
                    return null;
                }
                };
                return searchTree(node);
            }
            }
            findMin() {
            let current = this.root;
            while (current.left !== null) {
                current = current.left;
            }
            return current.data;
            }
            findMax() {
            let current = this.root;
            while (current.right !== null) {
                current = current.right;
            }
            return current.data;
            }
            find(data) {
            let current = this.root;
            while (current.data !== data) {
                if (data < current.data) {
                current = current.left;
                } else {
                current = current.right;
                }
                if (current === null) {
                return null;
                }
            }
            return current;
            }
            isPresent(data) {
            let current = this.root;
            while (current) {
                if (data === current.data) {
                return true;
                }
                if (data < current.data) {
                current = current.left;
                } else {
                current = current.right;
                }
            }
            return false;
            }
            remove(data) {
            const removeNode = function(node, data) {
                if (node == null) {
                return null;
                }
                if (data == node.data) {
                // node has no children 
                if (node.left == null && node.right == null) {
                    return null;
                }
                // node has no left child 
                if (node.left == null) {
                    return node.right;
                }
                // node has no right child 
                if (node.right == null) {
                    return node.left;
                }
                // node has two children 
                var tempNode = node.right;
                while (tempNode.left !== null) {
                    tempNode = tempNode.left;
                }
                node.data = tempNode.data;
                node.right = removeNode(node.right, tempNode.data);
                return node;
                } else if (data < node.data) {
                node.left = removeNode(node.left, data);
                return node;
                } else {
                node.right = removeNode(node.right, data);
                return node;
                }
            }
            this.root = removeNode(this.root, data);
            }
            isBalanced() {
            return (this.findMinHeight() >= this.findMaxHeight() - 1)
            }
            findMinHeight(node = this.root) {
                if (node == null) {
                    return -1;
                };
                let left = this.findMinHeight(node.left);
                let right = this.findMinHeight(node.right);
                if (left < right) {
                    return left + 1;
                } else {
                    return right + 1;
                };
            }
            findMaxHeight(node = this.root) {
                if (node == null) {
                    return -1;
                };
                let left = this.findMaxHeight(node.left);
                let right = this.findMaxHeight(node.right);
                if (left > right) {
                    return left + 1;
                } else {
                    return right + 1;
                };
            }
            inOrder() {
            if (this.root == null) {
                return null;
            } else {
                var result = new Array();
                function traverseInOrder(node) {       
                node.left && traverseInOrder(node.left);
                result.push(node.data);
                node.right && traverseInOrder(node.right);
                }
                traverseInOrder(this.root);
                return result;
            };
            }
            preOrder() {
            if (this.root == null) {
                return null;
            } else {
                var result = new Array();
                function traversePreOrder(node) {
                result.push(node.data);
                node.left && traversePreOrder(node.left);
                node.right && traversePreOrder(node.right);
                };
                traversePreOrder(this.root);
                return result;
            };
            }
            postOrder() {
            if (this.root == null) {
                return null;
            } else {
                var result = new Array();
                function traversePostOrder(node) {
                node.left && traversePostOrder(node.left);
                node.right && traversePostOrder(node.right);
                result.push(node.data);
                };
                traversePostOrder(this.root);
                return result;
            }
            }

            levelOrder() {
                let result = [];
                let Q = []; 
                if (this.root != null) {
                    Q.push(this.root);
                    while(Q.length > 0) {
                        let node = Q.shift();
                        result.push(node.data);
                        if (node.left != null) {
                            Q.push(node.left);
                        };
                        if (node.right != null) {
                            Q.push(node.right);
                        };
                    };
                    return result;
                } else {
                    return null;
                };
            };
        }



        const bst = new BST();

        bst.add(9);
        bst.add(4);
        bst.add(17);
        bst.add(3);
        bst.add(6);
        bst.add(22);
        bst.add(5);
        bst.add(7);
        bst.add(20);

        console.log(bst.findMinHeight());
        console.log(bst.findMaxHeight());
        console.log(bst.isBalanced());
        bst.add(10);
        console.log(bst.findMinHeight());
        console.log(bst.findMaxHeight());
        console.log(bst.isBalanced());
        console.log('inOrder: ' + bst.inOrder());
        console.log('preOrder: ' + bst.preOrder());
        console.log('postOrder: ' + bst.postOrder());

        console.log('levelOrder: ' + bst.levelOrder());
    ```
* **Hash Table**
    ```javaScript

    var hash = (string, max) => {
    var hash = 0;
    for (var i = 0; i < string.length; i++) {
        hash += string.charCodeAt(i);
    }
    return hash % max;
    };

    let HashTable = function() {

    let storage = [];
    const storageLimit = 14;
    
    this.print = function() {
        console.log(storage)
    }

    this.add = function(key, value) {
        var index = hash(key, storageLimit);
        if (storage[index] === undefined) {
        storage[index] = [
            [key, value]
        ];
        } else {
        var inserted = false;
        for (var i = 0; i < storage[index].length; i++) {
            if (storage[index][i][0] === key) {
            storage[index][i][1] = value;
            inserted = true;
            }
        }
        if (inserted === false) {
            storage[index].push([key, value]);
        }
        }
    };

    this.remove = function(key) {
        var index = hash(key, storageLimit);
        if (storage[index].length === 1 && storage[index][0][0] === key) {
        delete storage[index];
        } else {
        for (var i = 0; i < storage[index].length; i++) {
            if (storage[index][i][0] === key) {
            delete storage[index][i];
            }
        }
        }
    };

    this.lookup = function(key) {
        var index = hash(key, storageLimit);
        if (storage[index] === undefined) {
        return undefined;
        } else {
        for (var i = 0; i < storage[index].length; i++) {
            if (storage[index][i][0] === key) {
            return storage[index][i][1];
            }
        }
        }
    };

    };

    console.log(hash('quincy', 10))

    let ht = new HashTable();
    ht.add('beau', 'person');
    ht.add('fido', 'dog');
    ht.add('rex', 'dinosour');
    ht.add('tux', 'penguin')
    console.log(ht.lookup('tux'))
    ht.print();
    ```

* **Linked List**
    ```javaScript
    function LinkedList() { 
    var length = 0; 
    var head = null; 

    var Node = function(element){
        this.element = element; 
        this.next = null; 
    }; 

    this.size = function(){
        return length;
    };

    this.head = function(){
        return head;
    };

    this.add = function(element){
        var node = new Node(element);
        if(head === null){
            head = node;
        } else {
            var currentNode = head;

            while(currentNode.next){
                currentNode  = currentNode.next;
            }

            currentNode.next = node;
        }

        length++;
    }; 

    this.remove = function(element){
        var currentNode = head;
        var previousNode;
        if(currentNode.element === element){
            head = currentNode.next;
        } else {
            while(currentNode.element !== element) {
                previousNode = currentNode;
                currentNode = currentNode.next;
            }

            previousNode.next = currentNode.next;
        }

        length --;
    };
    
    this.isEmpty = function() {
        return length === 0;
    };

    this.indexOf = function(element) {
        var currentNode = head;
        var index = -1;

        while(currentNode){
            index++;
            if(currentNode.element === element){
                return index;
            }
            currentNode = currentNode.next;
        }

        return -1;
    };

    this.elementAt = function(index) {
        var currentNode = head;
        var count = 0;
        while (count < index){
            count ++;
            currentNode = currentNode.next
        }
        return currentNode.element;
    };
    
    
    this.addAt = function(index, element){
        var node = new Node(element);

        var currentNode = head;
        var previousNode;
        var currentIndex = 0;

        if(index > length){
            return false;
        }

        if(index === 0){
            node.next = currentNode;
            head = node;
        } else {
            while(currentIndex < index){
                currentIndex++;
                previousNode = currentNode;
                currentNode = currentNode.next;
            }
            node.next = currentNode;
            previousNode.next = node;
        }
        length++;
    }
    
    this.removeAt = function(index) {
        var currentNode = head;
        var previousNode;
        var currentIndex = 0;
        if (index < 0 || index >= length){
            return null
        }
        if(index === 0){
            head = currentNode.next;
        } else {
            while(currentIndex < index) {
                currentIndex ++;
                previousNode = currentNode;
                currentNode = currentNode.next;
            }
            previousNode.next = currentNode.next
        }
        length--;
        return currentNode.element;
    }

    } 

    var conga = new LinkedList();
    conga.add('Kitten');
    conga.add('Puppy');
    conga.add('Dog');
    conga.add('Cat');
    conga.add('Fish');
    console.log(conga.size());
    console.log(conga.removeAt(3));
    console.log(conga.elementAt(3));
    console.log(conga.indexOf('Puppy'));
    console.log(conga.size());
    ```
* **Trie**
    ```javaScript
        let Node = function() {
        this.keys = new Map();
        this.end = false;
        this.setEnd = function() {
            this.end = true;
        };
        this.isEnd = function() {
            return this.end;
        };
    };

    let Trie = function() {

        this.root = new Node();

        this.add = function(input, node = this.root) {
            if (input.length == 0) {
                node.setEnd();
                return;
            } else if (!node.keys.has(input[0])) {
                node.keys.set(input[0], new Node());
                return this.add(input.substr(1), node.keys.get(input[0]));
            } else {
                return this.add(input.substr(1), node.keys.get(input[0]));
            };
        };

        this.isWord = function(word) {
            let node = this.root;
            while (word.length > 1) {
                if (!node.keys.has(word[0])) {
                    return false;
                } else {
                    node = node.keys.get(word[0]);
                    word = word.substr(1);
                };
            };
            return (node.keys.has(word) && node.keys.get(word).isEnd()) ? 
        true : false;
        };

        this.print = function() {
            let words = new Array();
            let search = function(node, string) {
                if (node.keys.size != 0) {
                    for (let letter of node.keys.keys()) {
                        search(node.keys.get(letter), string.concat(letter));
                    };
                    if (node.isEnd()) {
                        words.push(string);
                    };
                } else {
                    string.length > 0 ? words.push(string) : undefined;
                    return;
                };
            };
            search(this.root, new String());
            return words.length > 0 ? words : mo;
        };

    };

    myTrie = new Trie()
    myTrie.add('ball'); 
    myTrie.add('bat'); 
    myTrie.add('doll'); 
    myTrie.add('dork'); 
    myTrie.add('do'); 
    myTrie.add('dorm')
    myTrie.add('send')
    myTrie.add('sense')
    console.log(myTrie.isWord('doll'))
    console.log(myTrie.isWord('dor'))
    console.log(myTrie.isWord('dorf'))
    console.log(myTrie.print())
    ```
* **Heap (max and min)**
    ```javaScript
        // left child: i * 2
        // right child: i * 2 + 1
        // parent: i / 2

        let MinHeap = function() {
            
            let heap = [null];
            
            this.insert = function(num) {
                heap.push(num);
                if (heap.length > 2) {
                    let idx = heap.length - 1;
                    while (heap[idx] < heap[Math.floor(idx/2)]) {
                        if (idx >= 1) {
                            [heap[Math.floor(idx/2)], heap[idx]] = [heap[idx], heap[Math.floor(idx/2)]];
                            if (Math.floor(idx/2) > 1) {
                                idx = Math.floor(idx/2);
                            } else {
                                break;
                            };
                        };
                    };
                };
            };
            
            this.remove = function() {
                let smallest = heap[1];
                if (heap.length > 2) {
                    heap[1] = heap[heap.length - 1];
                    heap.splice(heap.length - 1);
                    if (heap.length == 3) {
                        if (heap[1] > heap[2]) {
                            [heap[1], heap[2]] = [heap[2], heap[1]];
                        };
                        return smallest;
                    };
                    let i = 1;
                    let left = 2 * i;
                    let right = 2 * i + 1;
                    while (heap[i] >= heap[left] || heap[i] >= heap[right]) {
                        if (heap[left] < heap[right]) {
                            [heap[i], heap[left]] = [heap[left], heap[i]];
                            i = 2 * i
                        } else {
                            [heap[i], heap[right]] = [heap[right], heap[i]];
                            i = 2 * i + 1;
                        };
                        left = 2 * i;
                        right = 2 * i + 1;
                        if (heap[left] == undefined || heap[right] == undefined) {
                            break;
                        };
                    };
                } else if (heap.length == 2) {
                    heap.splice(1, 1);
                } else {
                    return null;
                };
                return smallest;
            };
        
            this.sort = function() {
                let result = new Array();
                while (heap.length > 1) {
                    result.push(this.remove());
                };
                return result;
            };

        };

        let MaxHeap = function() {
            
            let heap = [null];
            
            this.print = () => heap;

            this.insert = function(num) {
                heap.push(num);
                if (heap.length > 2) {
                    let idx = heap.length - 1;
                    while (heap[idx] > heap[Math.floor(idx/2)]) {
                        if (idx >= 1) {
                            [heap[Math.floor(idx/2)], heap[idx]] = [heap[idx], heap[Math.floor(idx/2)]];
                            if (Math.floor(idx/2) > 1) {
                                idx = Math.floor(idx/2);
                            } else {
                                break;
                            };
                        };
                    };
                };
            };
            
            this.remove = function() {
                let smallest = heap[1];
                if (heap.length > 2) {
                    heap[1] = heap[heap.length - 1];
                    heap.splice(heap.length - 1);
                    if (heap.length == 3) {
                        if (heap[1] < heap[2]) {
                            [heap[1], heap[2]] = [heap[2], heap[1]];
                        };
                        return smallest;
                    };
                    let i = 1;
                    let left = 2 * i;
                    let right = 2 * i + 1;
                    while (heap[i] <= heap[left] || heap[i] <= heap[right]) {
                        if (heap[left] > heap[right]) {
                            [heap[i], heap[left]] = [heap[left], heap[i]];
                            i = 2 * i
                        } else {
                            [heap[i], heap[right]] = [heap[right], heap[i]];
                            i = 2 * i + 1;
                        };
                        left = 2 * i;
                        right = 2 * i + 1;
                        if (heap[left] == undefined || heap[right] == undefined) {
                            break;
                        };
                    };
                } else if (heap.length == 2) {
                    heap.splice(1, 1);
                } else {
                    return null;
                };
                return smallest;
            };

        };
    ```
* **Graphs breadth-first search**
    ```javaScript
        function bfs(graph, root) {
        var nodesLen = {};
        
        for (var i = 0; i < graph.length; i++) {
            nodesLen[i] = Infinity;
        }
        nodesLen[root] = 0; 
        
        var queue = [root]; 
        var current; 

        while (queue.length != 0) {
            current = queue.shift();
            
            var curConnected = graph[current];
            var neighborIdx = []; 
            var idx = curConnected.indexOf(1); 
            while (idx != -1) {
            neighborIdx.push(idx); 
            idx = curConnected.indexOf(1, idx + 1); 
            }
            
            for (var j = 0; j < neighborIdx.length; j++) {
            if (nodesLen[neighborIdx[j]] == Infinity) {
                nodesLen[neighborIdx[j]] = nodesLen[current] + 1;
                queue.push(neighborIdx[j]); 
            }
            }
        }
        return nodesLen;
    };
    ```
---
## Main JS Functions

| Function  | Description                                                                                  |
|-----------|----------------------------------------------------------------------------------------------|
| forEach() | (filter will returns an array - meaning you do not need a separate variable for an array)    |
| map()     | creates an array by calling a specific function on each element present in the parent array. |
| sort()    | Takes two params                                                                             |
| reduce()  | Reduces the array to a single value - from LEFT to RIGHT                                     |

---



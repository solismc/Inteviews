# General Knowledge Questions:

Please write your answers in the code blocks.

**NOTICE:** Some (but not all) questions may be easier to answer with code or pseudocode. As an example, all of these are an acceptable answer to the question "How do you iterate a variable in PHP?"

```
$number++;
```

```
num = num + 1
```

```
variable "num" now equals "num" + 1
```

-----------------------------------------------------------------------

## Section: PHP

1. How do you get information from a form that is submitted using the "get" method?

```
[Put Your Answer Here]



```

2. What is the correct way to create a function in PHP?

```
<?php

function bookAuthor ()
{
    echo "Paulo Coelho"
}
```

3. Name a method to output an array?

```
Using return

function getName ()
{
    return "Manuel Solis";
}

$myName = getName

```

4. Which operator is used to check if two values are equal and of same data type?

```
The "Not Identical" operator (!==)

varDump (3 !== "3")

```

5. Which superglobal variable holds information about headers, paths, and script locations?

```
[Put Your Answer Here]
```

6. Explain how `static function` works in PHP class methods.

```
In PHP, any method declared as static will be accessible without having to create an object or having to instantiate it. Static functions are associated with a class and not the object. ANy shared logic across multiple instances should be put inside a static method.
```


7. What is the commonly used library for database connections?

```
PDO (PHP Data Objects). MySQLi is another one.
```

8. What is the commonly used library for making requests?

```
[Put Your Answer Here]
```

9. What is PHP function strlen?

```
It's a function that returns the length of a string. It takes one parameter of type string and returns a value of integer with the length of the string.
```


## Section: SQL

For the below questions, assume you are using this table (named `Persons`):

| Id | FirstName | LastName  |
|----|-----------|-----------|
| 1  | Peter     | Jackson   |
| 2  | Adam      | Savage    |
| 3  | Linus     | Sebastian |
| 4  | Brent     | Spiner    |
| 5  | Doom      | Guy       |

1. How would you select just the first record and only the column `FirstName`?

```
SELECT FirstName FROM Persons WHERE id = '1';
```

2. How would you select all the records where the `FirstName` is "Peter" and the `LastName` is "Jackson"?

```
SELECT * FROM Persons WHERE FirstName = 'Peter', LastName = 'Jackson';
```

3. How would you select all the records where the `LastName` starts with an "s"?

```
SELECT * FROM Persons WHERE LastName = 'S*';
```

4. How would you select all the records where the `FirstName` is alphabetically between "Brent" and "Linus"?

```
[Put Your Answer Here]
```

5. How would you insert the name "David Tennant"?

```
INSERT INTO Persons (FirstName, LastName) VALUES ('David', 'Tennant'); 
```

6. How would you change all the records where the `FirstName` is equal to "Peter" into "Samuel"?

```
UPDATE Persons SET FirstName = 'Samuel' WHERE FirstName = 'Peter';
```

7. How would you delete the records where the `LastName` is "Sebastian"?

```
DELETE FROM Persons WHERE LastName = 'Sebastian';
```

8. How would you get the number of records in the `Persons` table?

```
[Put Your Answer Here]
```

9. Give an example of how would you join 2 related tables together?

```
SELECT FirstName FROM Persons INNER JOIN Employees ON Persons.FirstName = Employees.FirstName;

In this particular case, because it is ann INNER JOIN, it would merge the records that are present in both the Persons table AND the Employee table.

Another option would be to use OUTER JOIN - LEFT or RIGHT.
```


## Section: Vanilla Javascript

1. How do you create a function in JavaScript?

```
function myFunction (p1, p2){
    return p1 + p2;
}
```

2. How do you call a function named "myFunction"?

```
var myFunction = function (a, b){
    return a * b;
}
console.log (myFunction);

```

4. How to write an IF statement for executing some code if "i" is NOT equal to 5?

```
if (5 !== 5) {
    console.log('Yes');
}
```

5. How does a WHILE loop start?

```
We need to set an initial value or 'starting point'. For example:

let count = 1;
while count < 5)[
    console.log (count);
count++ //this will add 1 to count until it reaches 4    
]
```

6. How does a FOR loop start?

```
for (let 1=0; 1 < 3; i++){
    console.log (i);
}
```

7. How do you round the number 7.25, to the nearest integer?

```
Using Math.round method
Math.round (7.25)
This will be rounded down to 7
```

8. What will the following code return: Boolean(10 > 9) true

## Section: jQuery

1. Can jQuery animate() method can be used to animate ANY CSS property?

```
No, not ANY. It needs to be a numeric CSS property. 
```

2. Which jQuery method is used to hide selected elements?

```
hide() method
```

3. Which jQuery method is used to perform an asynchronous HTTP request?

```
ajax() method
```

4. Look at the following selector: $("div p"). What does it select?

```
It will select all <p> elements that are a direct child of the <div> element
```


## Section: React

1. What is JSX?

```
It is a syntax similar to HTML or XML that React uses and extends ECMAScript so that HTLM code and be incorporated into Javascript/ React code.
It is a syntax extension to Javascript.
 
It makes it easier to add HTML into Javascript. Until JSX came along, this was not possible. It made life simpler for developers.
It prevents injection attacks. By default, React DOM converts everything to a string before rendering on the page. This prevents things from being injected that are not explicitly written in the application.
```

2. What triggers a render cycle?

```
The componentDidMount Method
```

3. What is a React Hook?

```
It is a new feature in React 16.8. It allows the developer to use state and other React features without writing a class.
It allows the developer split one component into smaller functions based on the pieces of code that are specifically related to that function rather than forcing a split based on lifecycle methods.
```

4. Which method in a React Component should you override to stop the component from updating?

```
componentDidUpdate()
```

5. Which method in a React Component is called after the component is rendered for the first time?

```
[Put Your Answer Here]
```

6. What happens when you call setState() inside render() method?

```
It can lead to an infinite loop, therefore it should be avoided. The render function should not be used to modify state. 
```


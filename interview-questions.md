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
[Put Your Answer Here]
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
[Put Your Answer Here]
```

3. How would you select all the records where the `LastName` starts with an "s"?

```
[Put Your Answer Here]
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
[Put Your Answer Here]
```


## Section: Vanilla Javascript

1. How do you create a function in JavaScript?

```
[Put Your Answer Here]
```

2. How do you call a function named "myFunction"?

```
[Put Your Answer Here]
```

4. How to write an IF statement for executing some code if "i" is NOT equal to 5?

```
[Put Your Answer Here]
```

5. How does a WHILE loop start?

```
[Put Your Answer Here]
```

6. How does a FOR loop start?

```
[Put Your Answer Here]
```

7. How do you round the number 7.25, to the nearest integer?

```
[Put Your Answer Here]
```

8. What will the following code return: Boolean(10 > 9)

## Section: jQuery

1. Can jQuery animate() method can be used to animate ANY CSS property?

```
[Put Your Answer Here]
```

2. Which jQuery method is used to hide selected elements?

```
[Put Your Answer Here]
```

3. Which jQuery method is used to perform an asynchronous HTTP request?

```
[Put Your Answer Here]
```

4. Look at the following selector: $("div p"). What does it select?

```
[Put Your Answer Here]
```


## Section: React

1. What is JSX?

```
[Put Your Answer Here]
```

2. What triggers a render cycle?

```
[Put Your Answer Here]
```

3. What is a React Hook?

```
[Put Your Answer Here]
```

4. Which method in a React Component should you override to stop the component from updating?

```
[Put Your Answer Here]
```

5. Which method in a React Component is called after the component is rendered for the first time?

```
[Put Your Answer Here]
```

6. What happens when you call setState() inside render() method?

```
[Put Your Answer Here]
```


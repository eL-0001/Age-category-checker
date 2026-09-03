# Age Category Checker

A simple C# console application that checks a person's age and determines which age category they belong to.

This is a beginner C# practice project created to help develop familiarity with basic programming concepts such as user input, number conversion, conditions, loops, string interpolation, and input validation.

## What It Does

The program:

* Asks the user to enter their name.
* Asks the user to enter their age.
* Checks whether the age is a valid number.
* Checks that the age is not negative.
* Determines the person's age category.
* Displays the person's name together with their age category.
* Stops after a valid age category has been determined.

The program uses `if`, `else if`, and `else` statements to determine the appropriate category.

The current age categories are:

| Age   | Category |
| ----- | -------- |
| 0–12  | Child    |
| 13–17 | Teenager |
| 18–64 | Adult    |
| 65+   | Senior   |

## Example

```text
Age Category Checker

Enter Name: Alex

Enter your age: 16

Alex is a Teenager
```

Another example:

```text
Age Category Checker

Enter Name: Sam

Enter your age: 72

Sam is a Senior
```

If invalid input is entered:

```text
Enter your age: hello

Please input valid age in numbers
```

If a negative age is entered:

```text
Enter your age: -5

Age cannot be negative. Try again
```

The program then allows the user to enter the information again.

## C# Concepts Practiced

This project provides practice with:

* `Console.WriteLine()` and `Console.Write()`
* `Console.ReadLine()`
* Variables
* `string`
* `int`
* `int.TryParse()`
* String interpolation
* `if`, `else if`, and `else`
* `while` loops
* `continue`
* Basic input validation
* Basic error handling

## How It Works

The program first asks the user for their name and age.

The age entered by the user is converted into an integer using `int.TryParse()`. If the input is not a valid number, the program displays an error message and asks for the age again.

The program also checks whether the age is negative. If it is, an error message is displayed and the user is asked to try again.

Once a valid age is entered, the program compares the age against the different categories and displays the appropriate result.

## Future Improvements

Possible improvements for a future version include:

* Improve the input validation and user instructions.
* Make the program handle empty names.
* Allow the user to check multiple people without restarting the program.
* Improve the overall user interface of the console application.
* Experiment with different or additional age categories.
* Separate some of the program's functionality into methods.
* Add automated tests.

## Author

**eL-0001 (also Bokang Malgas)**

This project was created as part of my early C# learning and practice.

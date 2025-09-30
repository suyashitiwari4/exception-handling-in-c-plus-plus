# exception-handling 

# PROGRAM 1

Aim

To write a C++ program that performs division of two numbers and uses exception handling to handle the division by zero error gracefully.

Theory

In programming, dividing a number by zero is undefined and causes a runtime error. Exception handling is a mechanism to handle such errors during program execution without abruptly terminating the program. In C++, try block contains the code that may throw an exception. If an exception occurs, the control passes to the catch block, where the error is handled. In this program, if the denominator (n2) is zero, an exception is thrown. The catch block catches this exception and prints an appropriate error message, preventing the program from crashing.

Algorithm

1.Start.

2.Prompt the user to enter two floating-point numbers, n1 and n2.

3.Read the input values.

4.Use a try block:

5.Check if n2 is zero.

6.If yes, throw n2 as an exception.

7.Else, perform division n1/n2 and store in ans.

8.Display the result.

9.Use a catch block to catch the exception of type float:

10.Display error message indicating division by zero.

11.End.

# PROGRAM 2

Aim

To write a C++ program that takes a person's age as input and uses exception handling to check if the person is underage (less than 18). If underage, an exception is thrown and handled to display an error message.

Theory

Age verification is a common validation step where the system checks if a person meets a minimum age requirement (e.g., 18 years). In C++, exceptions provide a way to handle errors or unexpected conditions gracefully. Here, the program throws an integer exception if the age is less than 18, indicating that the user is underage. The thrown exception is caught in the catch block where an appropriate error message is displayed. If the age is valid (18 or more), the program outputs an approval message.

Algorithm

1.Start.

2.Prompt the user to enter the age.

3.Read the input value into n1.

4.Use a try block:

5.If n1 < 18, throw n1 as an exception.

6.Else, print the age and approval message.

7.Use a catch block to catch the exception of type int:

8.Print the error message indicating underage with the thrown value.

9.End.

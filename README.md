# Java-Lab-002

## Variables, Types and Operators

Be able to explain what variables are. Understand variable types, allowed names, and valid values.
Know how to create and use string, integer, floating-point, and boolean variables.

### Part 1 - PricelessScript.java - [MasterCard YouTube Ad](https://www.youtube.com/watch?v=Q_6stXKGuHo)

The lab template contains a program that prints the following:
```
2 tickets: $28.00
2 hotdogs, 2 popcorn, 2 sodas: $18.00
1 autographed baseball $45.00
real conversation with 11 year old son: priceless
true
```

Ignore the code that you don't fully recognize and concentrate on changing the variables to alter the MasterCard *Priceless* script to say:
```
3 tickets: $42.00
3 hotdogs, 3 popcorn, 3 sodas: $27.00
2 autographed baseball $90.00
watching the Giants win: priceless
false
```

### Part 2 - Interpretation
Take note of the various variables and their data types. Write a brief summary in this section of the README.md file listing the:
* Variable name
* Its data type
* and example values you can assign them.

scriptTemplateLine1 - String - "character", "4", "%s"

people - integer - 4, 5, 10

ticketPrice - float - 2.7f, 19.42f, 99.9f

itemPrice - double - 6.2, 3.7, 10.12

trueOrFalse - boolean - true, false

formatter - NumberFormat - NumberFormat.getCurrencyInstance()


Next give TWO example variable names and TWO example variable assignments that are *WRONG* and explain why.
* Hint: your IDE can help you discover these!

int smallNumber = 0.01 - This is an incorrect variable assingment because integers cannot have fractional values.

String notWords = 3 - This is an incorrect variable assignment because while you can have numbers in strings, you need to have double quotes around them to make it a string.

### Part 3 - Bonus: Play around with Java String Format Specifiers.

Pick several of the Java format specifiers below and define variables of the correct type utilize *sout* and *String.format* to view the resulting formats.

![Format Specifiers](JavaStringFormatSpecifiers.png)

### Part 4 - Submission
* Commit your working code
* Push it to your Remote/origin branch (i.e. GitHub)
* Then issue a Pull request to the instructor branch
    * Make sure to save the Pull request URL and submit it for the lab.
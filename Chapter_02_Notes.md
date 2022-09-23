## Zybooks
Chapter 2 Notes:
* Variable: A named item used to hold a value
  * Variable Declaration: Creates a space in memory with name and type
* Assignment: Storing value in variable
* Expression: A number, variable, or a calculation
* Integer Literal: An integer appearing in an exoression not as a variable
* Floating-point Literal: A number with a fractional part (I.e. 1.0, 0.0, or 374.984)
* Identifier: "Name" of a variable/function
  * Reserved Word/Keyword: A word that is part of the language --> can't be an Identifier
  * All Keywords in c++: http://en.cppreference.com/w/cpp/keyword
* Camel Case: All words start with capital apart from the first
* Unary: Operator that only has one value being affected/inputted (- and !)
* Compound Operator: Shorthand way to update variable (I.e. "+=")
* Incremental Development: The process of writing, compiling, and testing a small amount of code before writing more
 * Step-by-Step analysis of the code to ensure quality
* Dividing by 0.0 results in "inf" or -inf"
 * Dividing 0.0 by 0.0 --> "0.0 / 0.0" results in "NaN" or Not a Number
* **Constant**: a variable that cannot bechanged within assignment statements. Identified with keyword ```const```
* **Function**: a list of statements executed by invoking the function's name 
 * **function call**: functionName(params)
  * sqrt(x)
  * pow(x,y)
  * fabs(x) *absolute value for floating point values* 
  * abs(x) *absolute value for int values*
  * Link to more [Built-in Math Functions](https://cplusplus.com/reference/cmath/?kw=cmath)
 randNum
 **Integer division** ( / ) --> however, when floating point values are present, floating point division is applied
 **Modulo** (%) --> Only reserved for integer division
 
 **Type Conversion**: a conversion of one data type to another
 **Implicit Conversion**: compiler automatically performs several common conversions between integer and double types
 
**type cast**: explicity converts a value of one type to another type
**static_cast**: converts the expression's value to the indicated type
```
int myIntVar = 2;
(static_cast<double>(myIntVar));
```
 

## Lecture 9/21/2022
* Important KeyWords:
 * M_PI ==> pi
 * fixed ==> fixes the number of spaces after decimal point that a double can have
 * setprecision(int n) ==> number will be capped by n decimal places
* 

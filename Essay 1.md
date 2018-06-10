# Comparison of C and C++
#### Tanya Schulz, CSCI 5828: Spring 2018

## Overview
This essays provides a brief analysis of the similarities and differences between C and C++. Before the two languages are compared, their individual histories are reviewed to further provide context. Multiple examples are provided to compare the languages directly.

## Introduction and Background
C was born in 1972 and was primarily utilized in developing the Unix operating system, as most of the Unix system was written in C during that time. C was ideal for operating system development because it uses a simple set of keywords, has what people describe as a "clean style", and is overall a straightforward compiler. In 1979, development of C++ began, and it was based on C began. The first stable release was in 1985. In sum, C++ was developed to improve and advance C so that writing programs was easier. The major development was the addition of object oriented programming, which significantly changed the functionality of C overall. Because C++ is a superset of C, any C program is also a legitimate C++ program. C++ is the C language and much more, as it was derived from C. <br>

Because C++ was derived from C, it shares many properties with C but contains many improvements.The remainder of this essay details this fact via exploring the similarities and differences.

## Comparison between C and C++
The main difference between the languages is the C++ is object oriented while C is a procedural language. The following list further details more differences between the two: <br>

* C++ emphasizes objects and not the steps and C emphasizes the procedure and steps. In other words, C++ has higher abstraction. C is formulated step by step. <br>
* C++ utilizes Boolean, String, user-defined, and built-in data types. C only supports primitive and built-in data types. <br>
* C++ has an inline function and C does not. <br>
* The data is more secure in C++ because it is hidden and cannot be accessed by external functions. However, the data is not secure in C. <br>
* Inheritance is possible in C but not C++. <br>
* C++ has namespaces to utilize elements of the C++ library <br>
* Functions must be declared in C++ before use, unlike C <br>

The primary similarity between C and C++ is that they share the same basic syntax. For example, "main()" and "auto()" are two examples of shared syntax.

## Examples
The first example exhibits similarities and differences between the two languages in terms of syntax via basic "Hello World" programs. <br>

\#include <stdio.h> <br>
`int main()` <br>
`{` <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`printf("Hello, World!");` <br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`return 0;` <br>
`}` <br>

"Hello World" program in C++: <br>
`\#include <iostream>`  <br>
`int main()` <br>
`{ `<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`std::cout << "Hello World";`<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `return 0;`<br>
`}` <br>

The similarities between the two programs are: <br>
1. The use of "int main()"  to indicate the main function <br>
2. "return 0;" to stop the function <br>
3. Brackets, { }, are indicate the beginning and end of the function main <br>
4. Both languages use ";" at the end of lines to indicate the end of a statement <br>  

The differences are: <br>
1. In C, "#include <stdio.h>" is a command that compiles the input and output file. <br>
2. In C++, "\#include <iostream>" is used to declare the input and output library. <br>
3. "printf()" is used in C to display the text <br>
4. "std" is an example of a namespace used in C++ <br>
5. "cout" is used as an output in C++ that is declared in isostream using the std namespace. <br>

The next example demonstrates how the two languages implement functions in different manners. The first set of code is valid in C, but not in C++, because the function isn't declared before use. The second set of code illustrates how C++ must declare the function to achieve the same result. However, it is important to note that in C, "return o;" must be used to stop the function, but this is already built into C++, and thus is not necessary. <br>

In C: <br>
`#include <stdio.h>` <br>
`int main()` <br>
`{`
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    `foo();` <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    `return 0;` <br>
`}` <br>

`int foo()` <br>
`{` <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    `printf( "Hello world" );` <br>
`}` <br>

In C++: <br>
`\#include <iostream>` <br>

`int main()` <br>
`{` <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`std::cout << "Hello World!";` <br>
`}` <br>

The last example describes how structures are declared in both languages, and declaring an integer is used to show this. In C++, the structure keyword must be indicated before the structure type to declare it. On the other hand, the structure keyword must be included when declaring the structure instance. <br>

In C, an integer is declared as follows: <br>
`int variable [= value];` <br>

In C++, the same result is achieved as follows: <br>
`int variable` <br>
`{` <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`int x;` <br>
`};` <br>

`variable value;` <br>


## References
1. https://www.invensis.net/blog/it/25-key-differencesbetween-c-plus-plus/ <br>
2. https://www.cs.fsu.edu/~myers/c++/notes/cdiff.html <br>
3. https://en.wikipedia.org/wiki/C_(programming_language) <br>
4. https://en.wikipedia.org/wiki/C%2B%2B <br>
5. https://www.geeksforgeeks.org/c-language-set-1-introduction/ <br>
6. http://durofy.com/10-major-differences-between-c-and-c/ <br>
7. https://mathbits.com/MathBits/CompSci/Introduction/history.htm <br>
8. https://www.cprogramming.com/tutorial/c-vs-c++.html <br>

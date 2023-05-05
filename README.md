Download Link: https://assignmentchef.com/product/solved-csf211-data-structures-and-algorithms-assignment-0
<br>
Allow language: <strong>C</strong>

<h1>General Tips</h1>

<ul>

 <li>Try to use functions as much as possible in your code. Functions increase reusability and the pass-by-value feature provides a significant help sometimes. Modularizing your code also helps you to debug efficiently.</li>

 <li>Use scanf to read characters/strings from STDIN. Avoid using getchar, getc or gets. Try to read up about character suppression in scanf as it will be very helpful in some of the problems.</li>

 <li>Use printf instead of putc, putchar or puts to print character/string output on STDOUT. Indent your code appropriately and use proper variable names. These increase readability and writability of the code. Also, Use comments wherever necessary.</li>

 <li>Use a proper IDEs like Sublime Text or VSCode as they help to run and test your code on multiple test-cases easily. You can install Windows Subsystem Linux (WSL) or MinGW 7.3.0, if you are Windows user to compile and run your programs. Alternatively, you can run and test your codes on <a href="https://www.onlinegdb.com/">Online GDB</a><a href="https://www.onlinegdb.com/">.</a> If you are using WSL or Linux to run your programs, make sure that the gcc version is gcc 5.4.1 c99.</li>

</ul>

1

<h1>A: Big Sum</h1>

Depending on the platform, the largest integer data type in C will allow you to store numbers that are tens of digits long. In this question, you will write a program that will enable you to add non-negative integers that are at most a thousand digits long. To this end, create two strings that can be used to store upto 1000 digit positive integers in base 10; Each digit will be a character in the usual positional number system. Obtain these numbers as input from the user and assume that the first number is greater than or equal to the second and that the numbers are non-negative. Your program should compute their sum, store it in a string without padding zeros to the left and print it. <em>Note: You need to write the entire program in the </em><em>main() function without having to write separate functions. Further, you are not allowed to use any header file other than </em><em>stdio.h</em>

<h2>Input</h2>

The first line of input contains the integer A (0 ≤ A ≤ 10<sup>1000</sup>) represented as a string. The second line of input contains the integer B (A ≤ B ≤ 10<sup>1000</sup>) represented as a string.

<h2>Output</h2>

Print a single string, representing the sum of the two integers provided to you, without zeros padded to the left.

input 78977 98173

output 177150

input 123 1

output 124

input 68730457693724357452985234523765 11974275824875928729875504587907

output 80704733518600286182860739111672

2
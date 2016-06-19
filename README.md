# Offset Sum
Problem Prompt:   You are given a string of letters on a first line of input.
The first two characters are the number of letters that your program should examine (a number from 01 to 30). 
Your program should print out all the different lowercase letters in this string as well as an offset count as described below.

Goin from left to right from the first occurence of a character, if the character is repeaated after k more characters, k should be added to the count. If a character is not repeated. the count is 0.

All characters should be in lowercase, and ignore any non-lowercase characters (such as digits, uppercaseletters, and symbols).Include error checking for the number of characters and print ERROR if there is failure.

# Sample Input #1
06ababab

# Sample Output #1
a 6
b 6

# Sample Input #2
12hello there world

# Sample Output #2
h 7
e 16
l 1
o 0
t 0
r 0

# Sample Input #3
70hello there world

# Sample Output #3
ERROR

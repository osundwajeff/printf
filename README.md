# 0x11. C-printf
A remake of the printf function by [Penny Ng'etuny](https://github.com/Peinah) and Jeff Osundwa for ALX-Holberton Software Engineering project.
## Requirements

- Allowed editors: vi, vim, emacs
- All your files will be compiled on Ubuntu 20.04 LTS using 'gcc', using the options '-Wall -Werror -Wextra -pedantic -std=gnu89'
- All your files should end with a new line
- A README.md file, at the root of the folder of the project is mandatory
- Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
- You are not allowed to use global variables
- No more than 5 functions per file
- In the following examples, the main.c files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own main.c files at compilation. Our main.c files might be different from the one shown in the examples
- The prototypes of all your functions should be included in your header file called main.h
- Don’t forget to push your header file
- All your header files should be include guarded
- Note that we will not provide the _putchar function for this project

 ---
 ## Example
```
#include "main.h"
_printf("The %s won the Finals %d times", "Warriors", 6);
$ The Warriors won the Finals 6 times
``` 
---

### Task 0: 
A function that produces output according to a format.
Returns: the number of characters printed (excluding the null byte used to end output to strings)
write output to stdout, the standard output stream
format is a character string. The format string is composed of zero or more directives.

### Task 1:
It handles the conversion specifiers d and i.

File man_3_printf: Contains a manpage for the printf function.

### Task 3:
Handling of  the following custom conversion specifiers:
b: the unsigned int argument is converted to binary

### Task 4:
Handles the following conversion specifiers: u,o,x,X.
You don’t have to handle the flag characters
You don’t have to handle field width
You don’t have to handle precision
You don’t have to handle the length modifiers

### Task 5:
To use a local buffer of 1024 chars in order to call write as little as possible.

### Task 6:
Handle the following conversion specifier: p.
You don’t have to handle the flag characters
You don’t have to handle field width
You don’t have to handle precision
You don’t have to handle the length modifiers

### Task 7:
Handling  the following custom conversion specifier:
S : prints the string.
Non printable characters (0 < ASCII value < 32 or >= 127) are printed this way: \x, followed by the ASCII code value in hexadecimal (upper case - always 2 characters)

### Task 8:
Handle the following flag characters for non-custom conversion specifiers:
+
space
#

### Task 9:
Handle the following length modifiers for non-custom conversion specifiers:
l
h
Conversion specifiers to handle: d, i, u, o, x, X

### Task 10:
Handle the field width for non-custom conversion specifiers.

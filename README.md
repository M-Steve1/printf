# 0x10. C - printf

## Description
This team project is part of the first year curriculum of Holberton School.
_printf replicates the C standard library printf() function.

What you should learn from this project:

* How to use git in a team setting
* Applying variadic functions to a big project
* The complexities of printf
* Managing a lot of files and finding a good workflow

---

## Prototype
```int _printf(const char *format, ...);```

## Usage
* Prints a string to the standard output, according to a given format
* All files were created and compiled on Ubuntu 14.04.4 LTS using GCC 4.8.4 with the command ```gcc -Wall -Werror -Wextra -pedantic *.c```
* Returns the number of characters in the output string on success, -1 otherwise
* Call it this way: ```_printf("format string", arguments...)``` where ```format string``` can contain conversion specifiers and flags,
along with regular characters

## Examples

* ```_printf("Hello, Stephen and Lanre\n")``` *prints "Hello, Stephen and Lanre followed by a new line."*
* ```_printf("%s", "Hello")``` *prints "Hello"*
* ```_printf("This is a number: %d", 1024)``` *prints "This is a number: 1024"*

---

### Authors
* **Modebe Stephen** - [modebestephen2@gmail.com](https://github.com/M-Steve1)
* **Awe Olanrewaju** - [lanreawe7@gmail.com](https://github.com/Lanre-Awe)

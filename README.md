#Simple Shell_

## Description
Project scope to create simple UNIX command interpreter.
Shell opens files, creates files and modifies files.  

## How to used it
- Compiling the program: 
```sh
gcc -Wall -Werror -Wextra -pedantic *.c -o hsh
```
- Use the program with:
```sh
./shs
```
## file in:
- Interactive mode
- Non-interactie mode
___
___

## Project Requirements

1. All your files will be compiled on Ubuntu 20.04 LTS using gcc
2. All your files should end with a new line
3. A README.md file, at the root of the folder of the project is mandatory
4. Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
5. Your shell should not have any memory leaks
6. No more than 5 functions per file
7. Use system calls only when you need to

___
___

## Functions Shell

| FUNTION | WHAT DOES |
| ------ | ------|
| *_getenv | get a environ variable |
| *get_command | This function read the input line |
| **tk_cm | get token of the string |
| *_path_dir | values path |
| execution | create fork. |

___
___

## Functions Error

| FUNCTION | WHAT DOES |
| ------ | ------|
| error_input | Funtion for error in line comand |

___
___

# Output

- Example of error with sh: 
```sh
$ echo "qwerty" | /bin/sh
/bin/sh: 1: qwerty: not found
$ echo "qwerty" | /bin/../bin/sh
/bin/../bin/sh: 1: qwerty: not found
$
```
- Same error with your program hsh:
```sh
$ echo "qwerty" | ./hsh
./hsh: 1: qwerty: not found
$ echo "qwerty" | ./././hsh
./././hsh: 1: qwerty: not found
$
```
___
___

# Authors
- Kimberley Mubiru
- Maobe Maeba
___
___


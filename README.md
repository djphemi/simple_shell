# 0x16.C Simple Shell :ledger:


This project was built by Femi and Lade.

# Table of Contents
1. [Authors](#Authors)
2. [How To Use](#How-To-Use)
3. .[explanation](#Explanation)

# Authors
![header](https://capsule-render.vercel.app/api?type=rect&color=gradient&height=1)

# How To Use

## How to compile

### Requirements

- All your files will be compiled on Ubuntu 20.04.2 LTS
- Your C programs and functions will be compiled with gcc 9.3.0
- Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
- No more than 5 functions per file

### Flags to compile
```shell
$ gcc -Wall -Werror -Wextra -pedantic *.c
```
## Explanation


## Non interactive

pass the commands in the stdin but no prints the prompt.

```shell
$ echo "ls" | ./hsh
```
## interactive

the program is execute and the prompt is print, and wait for the user.
```shell
$ ./hsh
($)
```

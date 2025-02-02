---
tags:
  - softwaredd
  - flashcards
---

# Code Execution

[google classroom link](https://docs.google.com/presentation/d/1pfuyVXSHoOIv913PNJ6H7WufqFIkzfSIHmdtwVroCNA/edit#slide=id.p1)
## Interpretation

What are the features of the interpretation method of code execution?
?
- Program will run till it encounters the first error
- Program is converted to machine code instruction by instruction and executed before moving on to the next instruction
- Slower to execute
- Easier to identify cause of bugs. (errors are shown one by one)


## Compilation 

What are the features of the Compilation method of code execution?
?
- The entire file is converted to machine code before being executed.
- Any and all errors are shown together.
- Program will not begin executing with errors.
- Faster to execute


## Incremental Compilation

What is incremental compilation?
?
Same as normal compilation except it involves only recompiling the necessary sections of the code. This makes it much faster for big projects.

# Translation To Object Code

What are the steps done by the computer to translate code into object code?
?
- Lexical Analysis
- Syntactical Analysis
- Code generation

___

What is done during the Lexical Analysis stage of code translation?
?
1. Source code is read 1 character at a time
2. Each word is checked to ensure it is a valid part of the programming language
3. Documentation elements such as blank space and comments are removed
4. Each identified element is given a token

What is a lexeme?
?
A string of characters

What are the two types of tokens assigned during the code translation stage of lexical analysis?
?
- Elements defined by the programming language  eg. reserved words like IF or WHILE and special characters of constants like +, - or 3.14159
- Tokens to represent programmer defined elements such as variables or procedures

What errors are identified during the Lexical Analysis stage of code translation?
?
- Undeclared identifiers
- Incorrectly named identifiers or subroutines
- Incorrect constant syntax 

___

What does the Syntactical Analysis stage of code translation do?
?
It arranges the tokens assigned by the Lexical Analysis stage into an order than will be understood by the computer.

What errors are identified during the Syntactical Analysis stage of code translation?
?
Type related error (caused by incompatible data types). eg. trying to divide a string by an integer.

___

What happens at the code generation stage of the code translation process?
?
The previously assigned tokens are converted are converted into their respective machine code in






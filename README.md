# Legol Compiler - Phase 4

## A simple C program that simulates building and stacking Legol Building Blocks.

-   [ ] I am a huge Lego fan so I decided that I want to create a simple compiler based on this. A basic Legol-building-block language and output instructions. A single Legol command will be read from the user and then processes it. Then it will print what it is doing. Lastly the program will end.
-   [ ] Phase 4 of this project now feels like a real parser that understands command structure

## What phase 4 does?

-   [ ] This program will now have:
    -   [ ] A recursive descent parser that properly handles commands
    -   [ ] Separate parsing functions for each command type
    -   [ ] Better organized code structure
    -   [ ] Clearer error messages
    -   [ ] Still maintains all previous features: symbol table & interactive loop

## How to Use

-   [ ] Run the program
-   [ ] Type one of these commands:
    -   [ ] `BUILD` `<color>` `<size>` (Example: `BUILD pink large`)
    -   [ ] `STACK` `<color>` `<size>` (Example: `STACK mint medium`)
    -   [ ] `END` (to stop the program)
-   [ ] The program now better understands the structure of each command
-   [ ] See immediate results and the growling symbol table after each command

## Example

```
-> Welcome to the Legol Mini Compiler!
You can uae these commands:
BUILD <color> <size> -> to build a single Legol Building block
STACK <color1> <color2> -> to stack one Legol Building block on another
END -> to quit the program

Please enter Legol command:
BUILD
Please enter a Legol color and size:
white large

WORD TYPES:
BUILD = command (token1 = 1)
white = color (token2 = 2)
large = size (token3 = 3)

RESULT: You built a white Legol Building block of size large!

SYMBOL TABLE:
Word Type Description
BUILD  | Command | Command to build a Legol Block
white  | Color   | Color of the Legol Block
large  | Size    | Size of the Legol Block

Please enter a Legol command:
END

RESULT: All done! Bye bye!
```

## What You'll Learn: Phase 4

-   [ ] This version shows:
    -   [ ] How parsers break down commands into components
    -   [ ] There is a recursive parser technique
    -   [ ] Better code organization with separate parsing functions
    -   [ ] How compilers understand command structure

## Enjoying it's Growth

-   [ ] This program is now feels like a real language processor because:
    -   [ ] It properly handles different command formats
    -   [ ] The code is better organized and easier to extend
    -   [ ] It's laying the foundation for more complex language features
    -   [ ] Still maintains all the interactive features

-   [ ] Encompass:
    -   [ ] C Programming Language
-   [ ] C → This language is best to use when writing a compiler, it is fast, and close to how computers actually work.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

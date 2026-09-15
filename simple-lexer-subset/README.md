# Assignment 2: Implementing Subset Construction Algorithm

## Problem Description

Your task is to complete the lexer implementation. As in the previous assignment, the lexer should recognize the following regular expression:

- `IF | ID | INT`
    - `IF` is defined as `'if'`
    - `ID` is defined as `[A-Za-z_] [A-Za-z0-9_]*`
    - `INT` is defined as `0 | [1-9] [0-9]*`

However, unlike the previous assignment where you directly hard-coded the DFA, in this assignment you need to implement the subset construction algorithm to convert an NFA to a DFA.

### Tasks

1. Complete the `convertNfaToDfa` method in [src/main/java/simplelexersubset/SimpleLexer.java](src/main/java/simplelexersubset/SimpleLexer.java). 
2. To test your solution, run JUnit tests in [src/test/java/simplelexersubset/SimpleLexerTest.java](src/test/java/simplelexersubset/SimpleLexerTest.java). You can execute them by typing the following command from the repository root:


```sh
sbt simpleLexerSubset/test
```

## What to Submit

1. A zip file of your completed project. Regarding how to create the zip file, follow [this instruction](https://www.gitkraken.com/learn/git/github-download#how-to-download-a-github-repository).

### How to Submit

Submit the following two files via BlackBoard.

1. A zip file of your completed project

### Submission Deadline

**Due: September 17, 2026; 3:00pm KST**

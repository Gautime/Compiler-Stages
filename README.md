# Compiler-Stages
This is a personal project to implement and learn about the stages of a C compiler. I have implemented the first two stages of compiler which are Lexical analysis and Syntax analysis.  

## Lexical Analyser
Lexical analyser is the first step in compilers. The function of this program is to convert the imput code into sequence of tokens. There are many tokens in a C program and each token is either a keyword, an identifier, a constant, a string literal, or a symbol.

## Syntax Analyser

It is sometimes called as parser. It constructs the parse tree. It takes all the tokens one by one and uses Context Free Grammar to construct the parse tree.
The rules of programming can be entirely represented in some few productions. Using these productions we can represent what the program actually is. The input has to be checked whether it is in the desired format or not.
The parse tree is also called the derivation tree.Parse trees are generally constructed to check for ambiguity in the given grammar. There are certain rules associated with the derivation tree.

* Any identifier is an expression.
* Any number can be called an expression.
* Performing any operations in the given expression will always result in an expression. For example,the sum of two expressions is also an expression.
* The parse tree can be compressed to form a syntax tree.

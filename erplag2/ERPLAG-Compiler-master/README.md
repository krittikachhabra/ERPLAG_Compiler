# ERPLAG-Compiler

ERPLAG is a language inspired from C, but is a simplified version of it.

We have implemented a compiler for this language in a pipelined manner with its various stages being:
  * Lexer
  * Parser
  * AST generation
  * Typechecking & Semantic checking
  * Code Generation (NASM 64-bit compatible assembly)

This project was a part of the course Compiler Construction at BITS Pilani, under Dr. Vandana Aggarwal.

**Authors**
 * [Akanksha Dara](https://github.com/akankshadara)
 * [Divakar Verma](https://github.com/vdivakar)
 
**Usage**
```{r, engine='bash', count_lines}
To compile: make
To execute: ./compiler testcase.txt code.asm
```

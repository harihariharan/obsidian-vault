1. It is a compiler and a toolkit for building compilers, which are programs that convert the instructions into a form that can be read and executed by the computer.
2. It is a collection of modular and reusable compilers and toolchain technologies.

How different it is from GCC?
1. Both are compilers.
2. GCC - Supports a no. of programming languages, while LLVM - isn't a compiler for any given language whereas it is framework to generate object code from any kind of source code.
3. LLVM - licensed more liberally, while GCC - more restrictions for reuse.
How does it works?
1. Front-end - clang for turning a source code into an interim format then it turns interim format to final machine code.
Lexical Analysis — Converts program text into words and tokens (everything apart from words, such as spaces and semicolons).  
‍
Parsing — Groups the words and tokens from the lexical analysis into a form that makes sense.  
Semantic Analyser — Identifies the types and logics of the programs.  
‍
Optimization — Cleans the code for better run-time performance and addresses memory-related issues.  
‍
Code Generation — Turns code into a binary file that is executable.
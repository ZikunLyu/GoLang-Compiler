# GoLang-Compiler

This is a compiler implementation for a subset of the Go language, GoLite.   

There are 7 main stages of a compiler:   
Scanner, Parser, Weeder, AST, Symbol Table, Typechecker and Code Generator.   

GoLite adopts most of Go's syntax but on a smaller pool of base types and build-in functions.   
Most noticeably, GoLite only supports the ASCII charset, unlike Go which is UTF-8 encoded. Also, GoLite disallows slice/array/struct literals.   
Nevertheless, GoLite supports all of Go's operators, control-flow structures and the type declaration feature. 

The flex/bison model in C as our primary tool for the implementation. 
The implementation language is C and the target language is Java.
This compiler convert GoLang to Java code.

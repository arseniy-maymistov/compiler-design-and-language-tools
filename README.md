# Compiler Construction and YARA Rule Parsing

Compiler coursework using Flex/Bison: expression parsing, a C-like language translator for x86-64, ELF code generation, and a YARA grammar parser.

## Overview

The reports describe a two-stage lexical/syntax analyzer, a translator from a C-like language to NASM assembly, and a minimal compiler that emits x86-64 machine code and an ELF executable. A separate coursework project implements a YARA-rule recognizer with lexical, syntax, and partial semantic checks.

## Topics and Features

- Lexical and syntax analysis using Flex and Bison
- AST construction and symbol-table handling
- Translation of arithmetic/logical expressions and control flow to x86-64 assembly
- Machine-code emission, backpatching, and ELF generation, as described in the report
- YARA grammar parsing and checks for string-variable use
- Make-based build and test workflow, as described in the reports

## Technologies

C/C++ (verify per implementation), Flex, Bison, NASM, x86-64, ELF, Make

## Project Context

This is an educational portfolio project based on university coursework. The README summarizes what is supported by the accompanying coursework reports; it does not imply that every listed topic is implemented in a production-ready system.

## Build and Reproducibility

Build and run instructions, dependencies, test commands, and sample inputs should be added after the original implementation files have been recovered and verified. Do not publish a project as runnable until those steps have been tested from a clean checkout.

## Notes

The reports include implementation listings, but standalone source files were not present in the archive. Extract and test the source, preserve licensing/attribution, and include examples of accepted and rejected input.

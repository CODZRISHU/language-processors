Introduction
This repository is a comprehensive resource for understanding and implementing key components of language processors. Each module is implemented with detailed explanations and code examples to help students and professionals alike.

Components Overview
Pass1 and Pass2
Pass1 and Pass2 are critical stages in the assembly process:

Pass1: Scans the source code, constructs the symbol table, and resolves labels and addresses.
Pass2: Uses the output from Pass1 to generate the final machine code or object code.
DFA (Deterministic Finite Automaton)
DFA is a finite state machine used for lexical analysis, which:

Recognizes patterns in the input string.
Checks if a string belongs to a specific language defined by a regular expression.
SR Parser (Shift-Reduce Parser)
Shift-Reduce Parser is a bottom-up parsing technique used to:

Parse the input string by shifting symbols onto a stack and reducing them using grammar rules.
Construct a syntax tree for the input string.
Lexical Analyzer
The Lexical Analyzer:

Tokenizes the source code into meaningful symbols (tokens).
Identifies keywords, operators, identifiers, and literals.
Removes whitespace and comments from the source code.

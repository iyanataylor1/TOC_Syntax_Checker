# TOC_Syntax_Checker

## Syntax Checker for a Simple Programming Language

In a group of 3-4 students design and implement a syntax checker for a small, well-defined 
programming language using Context-Free Grammars (CFGs) and parsing techniques. The goal is to 
demonstrate your group’s ability to: 
 Construct grammars 
 Analyse ambiguity 
 Apply grammar transformations 
 Implement a working parser 
 Validate input programs 
 Produce derivations or parse trees 

This project mirrors real-world tasks performed in compiler design, interpreters, IDEs, and markup 
validators. 

Each group must choose one of the following language domains: 
1. Arithmetic Expressions with Precedence 
2. Conditional Statements (if–then–else) 
3. HTML-like Nested Tags 
4. Simple Assignment Statements
   
Your syntax checker must determine whether an input program/document written in your chosen 
language is syntactically valid. 

### Use of Libraries and Tools: 
Students may use standard programming libraries for data structures, string 
manipulation, and input/output. However, automatic parser generators or grammar
processing tools (e.g., ANTLR, YACC, Bison) are not permitted, as the objective of 
this assignment is to demonstrate an understanding of grammar design, parsing 
logic, and theoretical principles. 
Any external libraries used must be clearly documented and justified in the report.

### Core Theoretical Requirements
Your submission must demonstrate mastery of the following Theory of Computation concepts: 
1. Context-Free Grammar Design 
 Define terminals and non-terminals 
 Provide a complete set of production rules 
 Explain the structure and rationale of your grammar 
2. Ambiguity Analysis 
 Identify whether your grammar is ambiguous 
 Provide examples illustrating ambiguity (if present) 
 Discuss how ambiguity a ects parsing 
3. Parsing - Implement one of the following: 
 Top-down parser (e.g., recursive descent) 
 Bottom-up parser (e.g., shift-reduce, CYK, etc.) 
Your parser must: 
 Accept syntactically valid inputs 
 Reject invalid inputs 
 Produce parse trees or leftmost/rightmost derivations 
 Provide meaningful syntax error messages 
4. Grammar Normalization 
 Convert your grammar to Chomsky Normal Form (CNF) 
 Show each transformation step 
 Explain why CNF is useful in parsing

### Functional Requirements
Your syntax checker must: 
 Read an input program/document 
 Validate it using your grammar 
 Generate a parse tree or derivation sequence 
 Detect and report syntax errors 
 Demonstrate correctness using test cases

# COMPILER-DESIGN-BASICS-TASK-03

NAME : Siva A

COMPANY : CODTECH IT SOLUTIONS

INTERN ID : CT08RJU

DOMAIN : C PROGRAMMING

DURATION : FEBRUARY 5th, 2025 to MARCH 5th, 2025 (4 WEEKS)

MENTOR : NEELA SANTHOSH

OVERVIEW OF THIS PROGRAM:

KEY COMPONENTS:

Token Classification:

The program classifies tokens into several categories:

Keywords: Reserved words in the programming language (e.g., int, float, if, else, while, return, for).

Operators: Symbols that represent operations (e.g., +, -, *, /, =, ==, <, >, <=, >=, !=).

Identifiers: Names given to variables, functions, etc., which must start with a letter or underscore and can contain alphanumeric characters and underscores.

Numbers: Numeric literals (e.g., integers and floating-point numbers).

Unknown Tokens: Any other characters that do not fit into the above categories.

Functions:

is_keyword: Checks if a token is a keyword by comparing it against a predefined list of keywords.

is_operator: Checks if a token is an operator by comparing it against a predefined list of operators.

is_identifier: Validates if a token is a valid identifier based on naming rules.

classify_token: Classifies a token and prints its type.

lexical_analyzer: Reads characters from an input file, builds tokens, and classifies them. It handles whitespace and single-character operators.

File Handling:

The program opens a specified input file (e.g., sample_input.txt), reads its contents character by character, and processes the tokens found within.
Main Function:

The main function orchestrates the program by opening the input file, invoking the lexical analysis function, and closing the file afterward.

OUTPUT:

Token: int | Type: Keyword

Token: x | Type: Identifier

Token: = | Type: Operator


Token: 10 | Type: Number

Token: ; | Type: Unknown

Token: float | Type: Keyword

Token: y | Type: Identifier

Token: = | Type: Operator

Token: 3.14 | Type: Number

Token: ; | Type: Unknown

Token: if | Type: Keyword

Token: ( | Type: Unknown

Token: x | Type: Identifier

Token: > | Type: Operator

Token: y | Type: Identifier

Token: ) | Type: Unknown

Token: { | Type: Unknown

Token: return | Type: Keyword

Token: x | Type: Identifier

Token: + | Type: Operator

Token: y | Type: Identifier

Token: ; | Type: Unknown

Token: } | Type: Unknown



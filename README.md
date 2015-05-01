# Arithmetic-Parsing
parses and evaluates arithmetic expressions

  - An abstract-syntax tree (AST) for the expression is created from parsing the input.
  - The AST used in evaluation so the input is not directly evaluated in the language
  - The expression will be a string or list of symbols like "(1+3)*7".
  - The four symbols + - * / are supported as binary operators with conventional precedence rules.
  - Precedence-control parentheses are also be supported.

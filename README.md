# Lexical-Analyzer-for-Ceng-

Project Definition: The Program should accept a source file called
code.Ceng and produce a text file named as code.lex that contains all the
tokens of the code.lex listed one after the other.

Example:

if code.Ceng contains:

var:=var_1+18;(*additonn*)

var_1++; (*increment*)

code.lex would be:

Identifier(var)

Operator(:=)

Identifier(var_1)

Operator(+)

IntConst(18)

EndOfLine

Identifier(var_1)

Operator(++)

EndOfLine

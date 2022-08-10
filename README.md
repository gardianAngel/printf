C - printf
Write a function that produces output according to format.
c : converts input into a character
s : converts input into a string

Handle the following conversion specifiers:
d : converts input into a base 10 integer
i : converts input into an integer

Create a man page for your function

Handle the following conversion specifiers:
b : the unsigned int argument is converted to binary
Handle the following conversion specifiers:
u : converts the input into an unsigned integer
o : converts the input into an octal number
x : converts the input into a hexadecimal number
X : converts the input into a hexadecimal number with capital letters

Use a local buffer of 1024 chars in order to call write as little as possible.

Handle the following custom conversion specifier:
S : prints the string.
Non printable characters (0 < ASCII value < 32 or >= 127) are printed this way: \x,
followed by the ASCII code value in hexadecimal (upper case - always 2 characters)

Handle the following conversion specifier:
p : int input is converted to a pointer address

Handle the following flag characters for non-custom conversion specifiers:
+ : adds a + in front of signed positive numbers and a - in front of signed negative numbers
space : same as +, but adds a space (is overwritten by +)
# : adds a 0 in front of octal conversions that don't begin with one, 
and a 0x or 0X for x or X conversions
Handle the following length modifiers for non-custom conversion specifiers:
l : converts d, i, u, o, x, X conversions in short signed or unsigned ints
h : converts d, i, u, o, x, X conversions in long signed or unsigned ints

Handle the field width for non-custom conversion specifiers.

Handle the precision for non-custom conversion specifiers.

Handle the 0 flag character for non-custom conversion specifiers.

Handle the - flag character for non-custom conversion specifiers.

Handle the following custom conversion specifier:
r : prints the reversed string

Handle the following custom conversion specifier:
R : prints the rot13'ed string

All the above options work well together.


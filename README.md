# Style-Guide
Avoid complex flow constructs, such as goto and recursion.
All loops must have fixed bounds. This prevents runaway code.
Avoid heap memory allocation after initialization.
Restrict functions to a single printed page.
Use a minimum of two runtime assertions per function.
Restrict the scope of data to the smallest possible.
Check the return value of all non-void functions, or cast to void to indicate the return value is useless.
Use the preprocessor only for header files and simple macros.
Limit pointer use to a single dereference, and do not use function pointers.
Compile with all possible warnings active; all warnings should then be addressed before release of the software.

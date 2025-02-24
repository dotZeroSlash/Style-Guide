# Style-Guide
Avoid complex flow constructs, such as goto and recursion. <br>
All loops must have fixed bounds. This prevents runaway code. <br>
Avoid heap memory allocation after initialization. <br>
Restrict functions to a single printed page. <br>
Use a minimum of two runtime assertions per function. <br>
Restrict the scope of data to the smallest possible. <br>
Check the return value of all non-void functions, or cast to void to indicate the return value is useless. <br>
Use the preprocessor only for header files and simple macros. <br>
Limit pointer use to a single dereference, and do not use function pointers. <br>
Compile with all possible warnings active; all warnings should then be addressed before release of the software.

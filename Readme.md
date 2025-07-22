# Data Types in C++
# Pratyush Saha
# PRN-24070123078
In C++, data types are used to define what kind of data a variable can hold (numbers, characters, decimals, etc.).

They can be grouped into 4 main categories:

1. Basic (Fundamental) Data Types
These are the core types used for most variables:

Data Type	Size (Typical)	Usage / Function
int	4 bytes	Stores whole numbers (e.g., 10, -5)
float	4 bytes	Stores decimal numbers (single precision) (e.g., 3.14)
double	8 bytes	Stores decimal numbers (double precision, more accurate)
char	1 byte	Stores a single character (e.g., 'A')
bool	1 byte	Stores true or false (logical values)
void	-	Represents "no value", used in functions that don’t return anything

2. Derived Data Types
These are built using fundamental types:

Type	Function
Array	Stores multiple elements of the same type in a sequence. Example: int arr[5];
Pointer	Stores the memory address of another variable. Example: int *ptr = &x;
Reference	An alias for another variable. Example: int &ref = x;
Function	A block of code that can be called multiple times with inputs (parameters) and outputs (return value).

3. User-Defined Data Types
Created by the programmer to model complex data:

Type	Function
Class	Defines objects with attributes (data) and methods (functions). Basis of OOP.
Structure (struct)	Groups different data types into one unit (simpler than a class).
Enumeration (enum)	Defines a set of named constants. Example: enum Color { Red, Green, Blue };
Typedef / using	Creates a new name (alias) for an existing data type.

4. Abstract / Special Data Types
Used for advanced programming:

Type	Function
Function Pointers	Point to functions, allowing dynamic function calls.
nullptr	Represents a null pointer (no valid memory address).
Templates (Generic Types)	Allows writing functions/classes independent of data type (e.g., template <typename T>).

# Pointers

# Aim
To study about pointers and understand its usage in C++.

# Tools
Visual Studio Code

# Theory
Pointers in C++ are variables that store memory addresses as their values. They enable direct memory manipulation and are fundamental for various C++ features, including dynamic memory allocation and data structures. •int* ptr; declares a pointer to an integer. •ptr = &x; stores the address of variable x in the pointer ptr. •*ptr is called the dereference operator. It gives us access to the value stored at the memory address ptr is pointing to.

The size of pointer in a system is equal for every pointer no matter what type of data it is pointing to. It does not depend on the type, but on operating system and CPU architecture. The size of pointers in C++ is

8 bytes for a 64-bit System 4 bytes for a 32-bit System The logic is simple: pointers store the addresses of the memory and in a computer, the maximum width of a memory address is determined by the CPU architecture.
# Algorithms
### Incrementing Data Types Using Pointers
Initialization
Declare and initialize variables of the following data types:

int a

float f

double d

char c

bool b

Pointer Assignment
For each variable, declare a pointer of the corresponding type and assign it the memory address of that variable.

int *aptr = &a;

float *fptr = &f;

double *dptr = &d;

char *cptr = &c;

bool *bptr = &b;

Process and Display
For each pointer (aptr, fptr, dptr, cptr, bptr):

a. Print Initial Address: Display the current memory address stored in the pointer.

b. Increment Pointer: Increment the pointer (pointer++). This advances the pointer's value by the size of the data type it points to (e.g., sizeof(int), sizeof(float), etc.).

c. Print New Address: Display the new memory address now stored in the pointer to show the result of the increment.

End
### Revering An Array
Start.

Initialize an integer array with elements {10, 20, 30, 40, 50}.

Create a pointer and point it to the last element of the array (arr + 4).

Print "Reversed array is:". using ---For i from 4 down to 0:

Print the value pointed to by the pointer.

Decrement the pointer to move to the previous element.

End.

### Finding Difference Of Array Elements
Start.

Initialize an integer array A with {10, 20, 30, 40, 50}.

Create pointer ap1 pointing to the 3rd element (A[2]).

Create pointer ap2 pointing to the 5th element (A[4]).

Calculate diff = *ap2 - *ap1.

Display "Difference is:" followed by diff.

End.

### Reading/Printing A String
Start.

Declare a character array str of size 20.

Prompt the user to enter a string and store it in str.

Initialize a pointer ptr to point to str.

Print "String is:".

While the character pointed to by ptr is not '\0' (null terminator):

Print the character pointed to by ptr.

Increment ptr to move to the next character.

End.
# Uses Of Pointers
Pointers are a useful concept in C++ that allow direct access to memory addresses, providing greater control over memory and data manipulation. Below are some primary uses of pointers in C++:

•Dynamic Memory Allocation: Pointers allow memory to be allocated dynamically at runtime using operators like new and delete. This enables the creation of objects or arrays whose sizes are determined during execution.

•Implementing Data Structures: Pointers are used to implementing complex data structures such as linked lists, trees, and graphs, where elements are dynamically allocated and linked together. Pass Arguments by Pointer: Pass the argument with their address and make changes in their value using pointer. So that the values get changed into the original argument.
# Conclusion:
This experiment hellped in understanding the concept and importance of pointers.

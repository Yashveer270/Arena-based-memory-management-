# Arena-based-memory-management-
Arena-based memory management is a type of memory management in which each allocated object is assigned to a region. A region, also called an arena, is a collection of allocated objects that can be efficiently deallocated all at once. It is used for compaction and serialization of complex data structures and objects, or for managing memory in safety-critical and /or fault tolerant systems.  An arena is just a large, contiguous piece of memory that you allocate once and then use to manage memory manually by handing out parts of that memory. In this you get full control over how the memory allocation works. The single library call for the initial allocation is the only thing out of your control.  Arenas can be used to allocate memory blocks of a fixed size. It can also be used for a particular task and once that task is over, it can be freed and we don’t need to worry about individual deallocations. The arena consists of the unused memory and the heap. The heap is where all user-allocated memory is located. The heap grows up from a lower memory address to a higher memory address. 
// ALGORITHM
1 Define the size of the required ram of the system.

2 Define a pointer to the struct NODE of the Nature struct.

3 create a function to check whether the memory is pointing to a null reference or not if so, the return a statement stating that it is false.

4 Create a function allocate with the Following parameters: pointer to arena, size Of

the memory required and memory to be Transferred.

5 In the function allocate if the offset is less that the required memory then

Move the pointer to a new location as the previous memory is full and the move the offset to the start of the new location.

6 return the ptr

7 repeat the steps 5 and 6 till the required memory is reached.

8 create a main function to declare the above-mentioned functions.

9 in the main function input the size if the memory to taken as input and create an array with the same of return type float

10 create another pointer named nptr to store the address of the specified memory location.

11 If the memory handling and usage of the specific memory is done then put a function “free” to free the used memory for further future use.

12 Exit from the loops.

13 End

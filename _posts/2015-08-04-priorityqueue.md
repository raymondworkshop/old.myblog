
###

#### Stack: FILO (first in, last out) [1]
   * Stored in computer RAM
   * stack grows and shrinks as functions push and pop local variables;
   Variables are allocated and freed automatically .
   
   * CPU manage the memory, reading from and writing to stack variables is very fast

#### Heap [1]
   * Stored in computer RAM
   * heap variables are essentially global in scope.
   * Heap memory is slightly slower to be read from and written to, 
   because one has to use pointers to access memory on the heap.
   
   * If we need variables like arrays and structs that can change size dynamically,
   then we will likely need to allocate them on the heap.
   
#### queue : FIFO

#### stack : FILO (first in, last out) 

#### Priority Queue
   * The case: a collection in which items can be added at any time, but the only item that can be removed is the one with the **highest priority**.
   We collect a set of items, then process the one with the largest key, **then perhaps collect more items**, then process the one with the current largest key.
   
   * The implementations
     - unordered array/linked-list: 
	   + To insert: push in the stack. 成(1)
	   + To remove the max: exchange the MAX with the item at the end, and then delete that one. 成(n)
	   
	 - ordered array/linked-list:
	   + for insert to move larger entries on the right position,thus keeping the keys in the order array. 成(n)
	   + The MAX is always at the end. 成(1)
	   
	 -  heap [2]
	   + 

####
[1]: http://gribblelab.org/CBootcamp/7_Memory_Stack_vs_Heap.html "stack and heap"
[2]: http://cs.lmu.edu/~ray/notes/pqueues/ "priority queue"
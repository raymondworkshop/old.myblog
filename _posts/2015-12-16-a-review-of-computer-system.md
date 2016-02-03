---
layout: post
title: "A review of Computer System"
date: 2015-12-16
comments: true
categories: [technology, system, summary]
---

####Optimizing Program Performance [ch5]  
 * **trade-off between how easy a program is to implement and maintain, and how fast it runs**
   - Select an appropriate set of algorithms and data structures
   - make the compiler optimize the code effectively

 * The limitations of optimizing compilers -
   - reducing excessive function calls
   - eliminating unneeded memory references - introduce temp variables to hold intermediate rsults

 * program profiling

 * Amdahl's Law
   - The performance gain depends both on **xhow much we improve this part**
   and **how large a fraction** of the overall time this part originally required

#### The Memory Hierarchy [ch6]
 * Storage Technologies - **trade-off between price and performance (access times)**
   - Static Random-Access memory(SRAM) - stable - cache memory
   - Dynamic RAM - sensitive to any disturbance - main memory
   - Solid state dist (SSD)
   - rotating disk

 * DRAM and disk access times are much larger than CPU CYCLE TIMES
   - So systems bridge the gaps by organizing memory as a hierarchy of storage devices
   -  **locality - try to bridge the processor-memory gap**
     + temporal locality - locate same data objects multiple time

     + spatial locality - nearby memory location

 * programs with good locality access most of their data from fast cache memories
   - Exploiting SRAM-based cache memories
     + programs that fetch data primarily from cache memories can run much faster than ones that fetch data primarily
       from memory
   - temporal locality -  using a data object as often as possible once it has been read from memory
   - spatial locality - by reading data objects sequentially, with stride 1, in the order they are stored in memory


#### Linking [ch7] - enable separate compilation (just only recompile one source and relink )
 * Linking - concatenates blocks together, and decides on **run-time locations** for the concatenated blocks
   - symbol resolution step -  symbol table in .symtab
     + associate each global symbol (functions and global variables) reference with a **unique** symbol definition

   - relocation - associate **a memory location with each symbol** definition, and then make them point to the memory
   location
     + meger all sections of the same type into a new aggregate section
     + relocate symbol references so that they point to the correct run-time addresses

 * linking with static libraries
   - related functions can be compiled into separate object modules and then packaged in a single static library file;
   At link time, the linker will **copy only the object modules**(symbol resolution) that are referenced by the program.

   - advantages
     + need to maintain and update the static libraries periodically
     + At run time, the code of the functions like I/O functions is duplicated in the text segment of each running process

 * dynamic linking with shared libraries
   - a single copy of the .text section of a shared libray in memory can be **shared** by different running
   - the basic idea is to **link the relocation and symbol table info** when the executable file is created, and then
     complete the linking process (**code and data** ) dynamically when the program is loaded

#### Exceptional Control Flow (ECF) [ch8]
 * control flow (a sequence of control transfer) of the processor
   - control transfer - from the address ak to ak+1

 * Exception - a change in the processor's state (event) triggers an abrupt control tansfer (an exception)
   - **an abrupt change in the control flow** in response to some change in the processor's state
   - **The change in processor's state** is known as an event

   - interrupt handling - occurs as a result of events in I/O device
   - traps handling - a procedure-like interface between user programs and the kernel known as a system call
   - fault handling - result from error conditions
   - abort handling

 * process -
   - an independent logical control flow
   - a private address space

   - concurrent flows - a logical flow whose execution overlaps in time with another
   - signals  
   - [TODO]

#### Virtual Memory [ch9]

#### Network programming

#### concurrent programming

#### reference
 * [Computer Systems: A Programmer's Perspective, 2/E](http://csapp.cs.cmu.edu/public/code.html)
 * [Introduction to Caches](http://www.cs.umd.edu/class/sum2003/cmsc311/Notes/Memory/introCache.html)

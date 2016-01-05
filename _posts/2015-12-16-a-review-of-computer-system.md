---
layout: post
title: "A review of Computer System"
date: 2015-12-16
comments: true
categories: [technology, system, note]
---

####Optimizing Program Performance [ch5]
 * trade-off between how easy a program is to implement and maintain, and how fast it runs
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
 * Storage Technologies - trade-off between price and performance (access times)
   - Static Random-Access memory(SRAM) - stable - cache memory
   - Dynamic RAM - sensitive to any disturbance - main memory
   - Solid state dist (SSD)
   - rotating disk

 * DRAM and disk access times are much larger than CPU CYCLE TIMES
   - So systems bridge the gaps by organizing memory as a hierarchy of storage devices
   -  locality - try to bridge the processor-memory gap
     + temporal locality - locate same data objects multiple time
    
     + spatial locality - nearby memory location
     
 * programs with good locality access most of their data from fast cache memories
   - Exploiting SRAM-based cache memories
     + programs that fetch data primarily from cache memories can run much faster than ones that fetch data primarily
       from memory
   - temporal locality -  using a data object as often as possible once it has been read from memory
   - spatial locality - by reading data objects sequentially, with stride 1, in the order they are stored in memory


#### 

reference

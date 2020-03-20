---
layout: post
title: "[updating] Notes on the Softwre Architecutres"
date: 2019-10-04
comments: true
categories: [home, notes, learning]
abstract: "[updating] Notes on the Softwre Architecutres"
---

### Notes on construction of software system at scale 
  - Software engineering creates **practical, cost-effective solutions** to develop software systems in the service of mankind.  

  - Software Engineeers are less likely to design data structures and algorithms from scratch and **more likely to build systems from library and framework components**.  

  -  

#### lessons
 * building on one another's successes
 


#### Concepts of design for complex systems - From programs to systems
  - algorithms & Data structures -> reuse of libraries, frameworks 
  - Functions with inputs and outpurs -> Asynchronous and reactive designs 
  - sequential and local computation -> Parallel and distributed computation 
  - Full functional specifications -> partial, composable, targeted models 

#### Software engineering 
  - **Costs and time constraints matter, not just capability**  
  
#### Software degisn - good design follows a process  
  * **Interface-based design** - API  defines expectations for clients  
    - Contracts - agreement between provider and users  
      + **Interface specifies expectations** 
        - design for **change and reuse**  
        - functionality, correctness, performance expectations  
    - **Information hiding** -> modularity  
        - spearates **API** from implementation  

    - objects **provide diff implementations** for the same specification  
    - client **only cares about interface**, not about the implementation  
    -  
    - doc  
      + **what the method does**, no not doc implementation details 
      + 
    - **test-driven** development   
      + write tests before you write the code  
      +  write **test based on the specification**    

  * design (sub)systems
    - design for robustness and change  

  * design for large-scale reuse  
  
  * think before coding 

#### Java
  * Static Analysis 
    - Compiler ensures **types** are correct 
  * Proofs (Formal verification) 
    - **mathematically prove code** matches its specification 
  *  Testing 
  *  
  *  Write tests based on the **specification**  
    - Think about testing when writing code 

    - Test-driven development -> Writing tests before you write the code 

#### concurrent and distributed software 


#### reference
* [The Architecture of Open Source Applications](http://www.aosabook.org/en/index.html)


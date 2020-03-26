---
layout: post
title: "[updating] Notes on the Softwre Architecutres"
date: 2019-10-04
comments: true
categories: [notes, learning]
abstract: "[updating] Notes on the Softwre Architecutres"
---


### Notes on construction of software system at scale 
  - Software engineering creates **practical, cost-effective solutions** to develop software systems in the service of mankind.  
  - Software Engineeers are less likely to design data structures and algorithms from scratch and **more likely to build systems from library and framework components**.  

  -  

#### lessons
 * Static checking    
   - **the types of all variables** are known at compile time, therefor deduce the types of all expressions 
   - primarily **type checking for safety** from bugs  

 * language choose  
   - safety, clarity, abstraction, engineering instincts     


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
* **[Sp2016-6.005: Software Construction](http://web.mit.edu/6.031/www/sp19/)**  
* **[CMU-Principles of Software Construction](https://www.cs.cmu.edu/~charlie/courses/17-214/2019-fall/index.html#schedule)**
* [The Architecture of Open Source Applications](http://www.aosabook.org/en/index.html)

* **[CMU-17-313-Foundations of Software Engineering](http://www.cs.cmu.edu/~ckaestne/15313/2018/index.html#schedule)**
* **[Introduction to Software Product Management](https://www.coursera.org/learn/introduction-to-software-product-management/home/welcome)**
* 
* **[CS110: Principles of Computer Systems](http://web.stanford.edu/class/archive/cs/cs110/cs110.1202/templates/calendar)**
* **[Computer Systems - A programmer's Perspective](http://www.cs.cmu.edu/~213/schedule.html)** 
*  
* [Internet-scale Distributed Systems](https://www.cs.tufts.edu/comp/117/) 
* 
* [Solution-software construction](https://github.com/claytonm/6005)
* [Software Design and Architecture Specialization](https://www.coursera.org/specializations/software-design-architecture?siteID=9IqCvd3EEQc-8H1WIaytP2nbUrO9_Kx7hQ&utm_content=10&utm_medium=partners&utm_source=linkshare&utm_campaign=9IqCvd3EEQc)
* [MIT-6.033 Spring 2018-principles of computer system design](hhttp://web.mit.edu/6.033/www/index.shtml)
* <del>[Advanced Operating Systems on Udacity](https://www.udacity.com/wiki/ud189)</del>
* <del>[Software Architecture and Design] (https://www.udacity.com/wiki/saad/schedule)</del>
* <del>[Software Development Process](https://www.udacity.com/courses/ud805) </del> 
* <del>[Software Architecture and Design](https://www.udacity.com/wiki/saad/schedule)</del> 


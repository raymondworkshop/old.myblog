---
layout: post
title: "Notes on the Software Architect"
date: 2020-02-11
comments: true
categories: [home, notes, learning]
abstract: "Notes on how to do users' Requirements and the Software Architecture"
---

#### 500L


#### ch4 Empathize with Stakeholders  - product manager  

*  Talk to the Right People  - who 
   - create a stakeholder Map -  a network diagram  

*  Discover the Business Goals - why they care  
   - **who wants it and what they want**
   - Record Business Goal Statements  
     + subject + measurable outcome + Context (the need)  
     + "(stakeholder) Mayor wanna (goal) reduce procurement costs by 30%, (context) to avoid making budget cuts to education or other essential services in an election year."  

#### ch5 - Architecturally Significant Requirements (ASR)
*  **planning** -  
   - **problem definition**  from a user's point of view  
     + **a clear statement of the problem** that the sytem is supposed to solve   
     + understanding what you want to build  
   - **requirements prerequisite** ensure that the user drives the system's functionality   
     + **how to specify requirements well**   
     + the requirements checklist   

   - **system Architecture**   
     + determine the conceptual integrity of the system  
     + a architecture first needs **an overview** that describes the system in broadterm 
     + the architecture should **define the major buildign blocks** in a program 
     +  the communication rules for each buildign block should be well defined  


*  Define the **what**, the requirements from architecture  

*  Capture Constraints as Simple Statements  
   - like "Must build a browser-based web application, the context is to descreases concerns about software delivery and maintenance."  

*  Capture Quality Attributes as Scenarios  
   - Quality Attributes Scenarios describe **how the system is expected to operate within a certain environmental context**    
   - a quality attribute scenario **communicates the intent of the requirement** so anyone can understand it  
     + like "performace - A user sees research results within 5 seconds when the system is at an average load of 2 searchs per second."    
     + "Availability - A user's searches for open RFPs and receives a list of RFPs 99% of the time on average over the course of the year."  

   - precise and measurable 


*  Influential Functional Requirements  



#### **Design in Construction**   

#### ch6 - choose an Architecture  

* architects **choose structures to promote quality attributes** in the system  

* accept the constraints  

* **explore Patterns** to promote desired Quality Attributes  

*  find the functional requirements and ensure the architecture can achieve them 
  - **assign specific functional responsibilities to each element** 

#### ch7 - how to explore design concepts  

* collect published patterns catalogs  

* design exploration - how  
  - **survey** the existing ones 
  - **give a presentation** of the available ones 
  - share a brief demo 
  - **recommend** a technology that seemed reasonable 

* decision  
  - "how do the proposed solutions influence our **top-quality attributes**?"  


#### ch8 - how to create models  

* pick an appropriate pattern as meta-model 
  - meta-model defines the concepts and the rules of how the concepts are applied 


* **add new concepts** to the meta-model 
  - start the process by **asking a question**   
     + like "which components cost us the most if they are unavailable"  

  -  Name it  
     + the name describe the element's **responsibility but also its purpose** 
     + understanding **what it does and why it exists**      


* Organize code to make patterns obvious 
  - pair with diff teammates   
  - it would be wise to **explore our architecture options in a collaborative workshop**  
    + not everyone agrees with or understands the current architecture  



#### ch9 - how to make design decisions   

* plan and facilitate an architecture design studio  



#### ch10 - how to visualize design ideas  


#### reference  
* [500lines](https://github.com/muyun/500lines)
* [code complete] 
* [from programmer to architect]  

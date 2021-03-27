---
layout: post
title: "Logic Gate"
date: 2015-10-07
comments: true
categories: [notes,algorithms]
abstract: "XOR"
---
> <small>What is XOR? </small>

####  exclusive or (XOR)  [1] , [2] 
  * used in cryptography because it let's us **'flip' the bits** using a mask in a reversable operations

  * p1 (+) p2 (+) ... (+) pn is true if the number of variables with the value true (1) is odd, because the XOR is associative

  * XOR is the same as addition modulo 2
    - p1 (+) p2 (+) ... (+) pn == ( p1 + p2 + ... + pn) % 2 - dividing mod 2 is one way to determine if a number is even or odd
    - Only the variables that have value 1 contribute to the sum, that determines how many variables have value 1

  * doing parity check
    - kind of checksum: use the XOR to check whether there is the flip


[1]: http://stackoverflow.com/questions/14526584/what-does-the-xor-operator-do  
[2]: http://www.cs.umd.edu/class/sum2003/cmsc311/Notes/BitOp/xor.html

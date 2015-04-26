---
layout: post  
title: "One-time is good, Two-time is bad"  
category: crypto
tagline: "Let's break two-time pad"
tags : [ont-time pad]
---
{% include JB/setup %}

Let's break two-time pad!

## Contents
+ [Intro](#part0)
+ [Attack](#partI)

----------------------------------

## Intro
<p id="part0"></p>

Below is the problem sets about this attack.
[Stanford](https://class.coursera.org/crypto-014/quiz/feedback?submission_id=23073) and
[Maryland](https://class.coursera.org/cryptography-002/wiki/Assignment_2)

Here is the solution[Stanford](https://github.com/gzc/Coursera-Course/tree/master/Stanford-Crypto1/week1) then
[Maryland](https://github.com/gzc/Coursera-Course/tree/master/Maryland-Cryptography/Programming_Assignment_2)

### Main points
if the same key used twice, then the result of (c1 Xor c2) will reveal a lot information about the original messages.

For example, the space is very crucial. ' ' ^ 'a' = 'A' and ' ' ^ 'A' = 'a'. When ' '  Xor with a letter then it will 
produce corresponding letter. So it is the very start to break two-time pad.

----------------------------------


## Attack
<p id="part0"></p>

Once we know the drawbacks behind it, we could easily break it.

Everything is covered in my code above.

----------------------------------
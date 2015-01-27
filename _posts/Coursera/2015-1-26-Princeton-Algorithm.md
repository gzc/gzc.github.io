---
layout: post  
title: "Coursera Princeton Algorithm"  
category: algorithm
tagline: "algorithm"
tags : [Coursera, algorithm]
---
{% include JB/setup %}

写这个文章纯粹是帮助自己做个笔记，记录自己每周学到叻什么 ^_^ ~~~~
[课程地址](https://class.coursera.org/algs4partI-007/lecture).

## Contents
+ [Week1](#partI)

----------------------------------

## Week1
<p id="partI"></p>

### Week1讲了什么?

Week1主要是介绍了Union-Find算法. 包括
- Quick Find : Find的时间是Constant,但做union时候要把全部一组的都得更新一遍
- Quick Union : 很像树，只需要更新root
- Weighted Quick Union : 小的树挂到大的树，实现中没用height而是用size
- Path Compression : 防止height过高
总之非常有用！

### 编程练习
是一个关于渗透的习题，模拟水从最高流到最下。
我一开始速度不够，那就要改进isFull和percolate使得constant call times.
那么只要记录每个union是否包含第一排或者最后一排就可以了，所以我多开了两个数组～～
[我的作业](https://github.com/gzc/Coursera-Course/tree/master/Princeton-Algorithm/homework1).


----------------------------------



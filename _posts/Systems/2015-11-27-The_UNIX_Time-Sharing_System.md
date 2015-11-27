---
layout: post  
title: "The UNIX Time-Sharing System"  
category: Systems
tagline: "UNIX is promoting Time-Sharing"
tags : [UNIX, Time-Sharing, Systems]
---
{% include JB/setup %}

Bugs in 802.11b WEP and let's break it!

## Contents
+ [OVERVIEW](#part0)
+ [File System](#partI)
+ [Process](#partII)
+ [Shell](#partIII)

----------------------------------

## OVERVIEW
<p id="part0"></p>

In their paper, they discussed about about a simple, multi-user, and interactive operating system called Unix for the computer PDP-11/40 and 45.

- File System.
- Process.
- Shell.

----------------------------------

## File System
<p id="partI"></p>

In unix there are three types of files, these are ordinary, directory, and special files. 

- An ordinary file contains information as strings separated by a new line. 
- A directory imposes a structure of the set of ordinary files. It lets the user to organize the ordinary files into a tree form. The tree structure was imposed by defining a root directory, where all searches start. Every directory has a parent directory and all directories is rooted at the root directory. One major contribution of this paper is on allowing  links which are not allowed in existing larger operating systems. Instead of the actual directory, links are pointers to a directory. What happens to a directory happens to all links that are pointed in that directory. 
- The third type of file is called special files. These files are associated with I/O devices that are supported by UNIX, examples of which are mountable devices such as external memory drives. Treating I/O devices as files, according to the paper has threefold advantage.
- Removable File Systems ： no link may exist between one file system hierarchy and another.
- File Protection : i.e. control scheme used by UNIX. Where capability to read, write, or execute is controlled by a 7 bit information about the file.

You should know

1. how inode works
2. what is a superblock
3. how descriptor works

----------------------------------

## Process
<p id="partII"></p>

- fork return twice
- pipe 
- execute(file, arg1, arg2, ..., arg_n) return -1 on error
- wait return error if no child processes
- exit(status)

----------------------------------

## Shell
<p id="partIII"></p>

I implemented shell in SJTU, so I am familiar with it.

you should know 

1. **redirection** 
2. **pipe** 
3. **background job**

You should have a basic idea how to implement it.
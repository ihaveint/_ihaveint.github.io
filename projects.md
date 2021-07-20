---
layout: page
title: Projects
---

Here are some projects I'm working on:
- fault-tolerant [MapReduce implementation](https://github.com/ihaveint/map_reduce)

The aim of this project is to build a MapReduce framework which needs the user to specify a source of data,
and a map function and reduce function for that source of data, which can be used in a MapReduce paradigm to solve the problem and then it takes care of 
solving the problem in a fault tolerance, parallel way. Currently there's a notable overhead with the implementation, but we have tested it on a large dataset (about 6.5GB) with the word-count problem in mind, and 
the performance is about 4x better when using 8 workers, relative to the normal sequential execution.

- Formal verification of distributed systems

Specifically I'm working towards a formal verification for [ABCD](https://mtefagh.github.io/papers/ABCD.html).

- Rust implementation of [Wait-Free Simulation for Lock-Free Data Structures](http://cs.technion.ac.il/~erez/Papers/wf-simulation-full.pdf), with help from [Jon's](https://www.youtube.com/c/JonGjengset/featured) streams

# Distributed System Algorithms

This repository contains implementations of fundamental algorithms used in distributed systems. These are the building blocks that help multiple computers work together and stay coordinated, even when they can't trust a single clock or communicate instantly.

Right now, it includes Lamport timestamps, which is one of the earliest and most elegant solutions to the problem of ordering events across different machines. When processes run on separate computers, figuring out what happened before what becomes tricky. Lamport's algorithm solves this with a simple logical clock that each process maintains.

The implementations are written in Go and meant to be practical references for understanding how these algorithms actually work in code.

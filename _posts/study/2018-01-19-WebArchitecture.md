---
layout: post
title: Scalable Web Architecture and Distributed Systems
tags: [Study, Distributed System]
---

## Scalable Web Architecture and Distributed Sysems
by Kate Matsudaira (aosabook.org)
(This article is focused on systems, but it is also applicable to other distributed systems)

### 1. Design of Large-scale web systems
* Make system **scalable**!: Distribute resource or accessing them across multiple servers
* Principle: Availability, Performance, Reliability, Scalability, Manageability, Cost
- Consider trade-offs each other

> Slice is like a reference to an array.
> A slice is a descriptor of an array segment.
> Piece of array (not array)

### Question? : Slice append 함수 사용 시 capacity 증가 규칙?
* https://blog.golang.org/slices


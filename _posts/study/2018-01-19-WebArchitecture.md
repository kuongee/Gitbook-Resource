---
layout: post
title: Study &#35;Scalable Web Architecture and Distributed Systems
tags: [Study, Distributed System]
---

## Scalable Web Architecture and Distributed Sysems
by Kate Matsudaira (aosabook.org)

### 1. Slices
Fixed size를 가지는 Array에 **dynamic size** 특성을 추가

> Slice is like a reference to an array.
> A slice is a descriptor of an array segment.
> Piece of array (not array)

### Question? : Slice append 함수 사용 시 capacity 증가 규칙?

Reference) 
* https://blog.golang.org/go-slices-usage-and-internals
* https://blog.golang.org/slices

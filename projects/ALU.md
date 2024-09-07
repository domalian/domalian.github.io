---
layout: project
type: project
image: img/ALU/ALU-logo.jpg
title: "ALU Design"
date: 2021-10-01
published: true
labels:
  - SystemVerilog
  - Digital Circuits Design
  - Hardware Engineering
summary: "A 4-bit arithmetic logic unit (ALU) that performs eight basic operations was designed using Falstad and EDA Playground as the final project for Basic Circuits I."
---

<div class="text-center p-4">
  <img width="200px" src="../img/ALU/ALU-overview.png" class="img-thumbnail" >
  <img width="200px" src="../img/ALU/edaplayground.png" class="img-thumbnail" >
</div>

## What is an ALU?

An ALU, which stands for Arithmetic Logic Unit, is an important component of a computer's CPU as it performs arithmetic and logic operations on binary data. Therefore, it can also be thought of as the "brain" as it carries out essential tasks required for processing instructions. An ALU can do many different calculations depending on its design, be it arithmetic, logic, bitwise, or comparison operations.

For this specific 4-bit ALU, it was designed to be able to perform these eight basic functions on two 4-bit binary data:

1. $A + B$ with carry in and carry out
2. $A - B$ with borrow in and borrow out
3. $B - A$ with borrow in and borrow out
4. $2 \times A$ with an overflow flag
5. $\frac{A}{2}$ with an overflow flag
6. $A \times B$ with an overflow flag
7. $A \oplus B$
8. $A \lt B$

## Logic Gate Design

To put our skills to the test, students were tasked to design an ALU in the logic gate-level, and program in SystemVerilog using EDA Playground. As a solo project, I divided the work by operations and worked up from simple calculations such as addition before getting to more complex ones such as multiplication. As I wired each operations together, I realized how some operations were closely related to each other and how I could recycle some subcircuits for other operations.

Looking back now, there were definitely ways in which some operations could have been better simplified such as through the use of flip-flops.

## SystemVerilog

To design this 4-bit ALU in SystemVerilog, behavioral methods were used to create a simple program. Below is the block of code that defined the ALU's operations.

![](../img/ALU/systemverilog-code.png)

Going through both gate-level and HDL designs really puts into perspective how desirable the latter can be for abstract-level design and how educational the former is for learning digital circuit design.

## GitHub

To further explore the details of this project, you can check out its [GitHub page](https://github.com/domalian/ALU).

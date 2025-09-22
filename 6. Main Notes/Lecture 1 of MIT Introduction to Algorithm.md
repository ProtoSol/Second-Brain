
2025-03-23 16:26

Status: #new

Tags: [[Computer Science]] [[Algorithm]]

# Lecture 1 of MIT Introduction to Algorithm

> The Link of the Book is present at the Reference

## What is an Algorithm?

An algorithm is any well-defined computational procedure that takes some value, or set of values, as input and produces some value, or set of values, as output.
It can be specified in English, as a computer program, or even as a hardware design. The only requirement is that the specification must provide a precise description of the computational procedure to be followed.
## What do you mean by Analysis of Algorithms?

The Theoretical study of computer program's performance and resource usage. 

The factor more important than performance is — 
1. Correctness
2. Features
3. Modularity
4. Robustness
5. User Friendliness

Then, why do we study algorithm and performance?
Performance measures the line between Feasible or Infeasible.

## What is a Data Structure?
A data structure is a way to store and organize data in order to facilitate access and modifications. No single data structure works well for all purposes, and so it is important to know the strengths and limitations of several of them.

> Example of an Algorithm [[6. Main Notes/Insertion Sort]]

## Running Time Depends on What Factors?

1. Input Size
2. Input Itself (Already Sorted)
3. We want the Upper Bounds of the Algorithm

## Kinds of Analysis

1. Worst Case (used mostly)
2. Average Case (sometimes)
3. Best Case (Bogus XD)

### What is the [[7. Drawings/Insertion Sort|Insertion Sort]]'s worst case time?

We don't see the machine for the worst case time, rather we see Asymptotic Analysis. It is independent of the machine constraints.

We look at the growth of the T(n) as n → $\inf$ 
# Reference

[MIT Course]([Lecture 1: Administrivia; Introduction; Analysis of Algorithms, Insertion Sort, Mergesort | Introduction to Algorithms (SMA 5503) | Electrical Engineering and Computer Science | MIT OpenCourseWare](https://ocw.mit.edu/courses/6-046j-introduction-to-algorithms-sma-5503-fall-2005/resources/lecture-1-administrivia-introduction-analysis-of-algorithms-insertion-sort-mergesort/))
[Introduction to Algorithms, Third Edition](https://ia601206.us.archive.org/11/items/introduction-to-algorithms-third-edition-2009/Introduction_to_Algorithms_Third_Edition_\(2009\).pdf)
[[Asymptotic Notations]]
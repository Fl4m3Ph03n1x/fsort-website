---
id: sort_types
title: Sort Types
sidebar_label: Sort Types
---

## Comparison sorts

A [comparison sort](https://en.wikipedia.org/wiki/Comparison_sort) is the type of sort that most of us think about when we hear the word *sorting*.
Basically, what it does is it compares two different objects on a property, and then returns the object who is bigger or smaller depending on what we want.

This notion is important: on comparisons sorts, you compare objects using some of their properties. Such objects need not have any special characteristics, all they need to share is the set of properties we want to compare.

Given this, there are two types of comparison algorithms this library implements: Simple algorithms and Advanced algorithms.

Simple algorithms don't use any additional data structures like maps and heaps. They usually work with the very list they are given.
Advanced algorithms, are the opposite. They require additional complex data structures and are harder to implement, but they usually outperform simple algorithms for very large data sets in most cases.

The list of algorithms implemented for each type is as follow:

| Simple algorithms |
| :---------------- |
| Bingo             |
| Bubble            |
| Cocktail          |
| Comb              |
| Gnome             |
| Insertion         |
| Selection         |
| Shell             |

| Advanced algorithms   |
| :-------------------- |
| Merge     ( TODO )    |
| Heap      ( TODO )    |
| Quick     ( TODO )    |
| Tim       ( TODO )    |
| Tree      ( TODO )    |

You can read more about the properties of each algorithm in the given documentation pages.

## Integer sorts

| Integer Sorts         |
| :-------------------- |
| Bucket    ( TODO )    |
| Radix     ( TODO )    |
| Counting  ( TODO )    |

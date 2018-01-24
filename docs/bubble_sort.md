---
id: bubble_sort
title: Bubble Sort
sidebar_label: Bubble Sort
---

Check the [documentation](https://docusaurus.io) for how to use Docusaurus.

## What?
Bubble sort ( aka sinking sort ) is an algorithm that steps through a list comparing adjacent items and swapping then when necessary.
This pass through is completed until no more swaps are needed.

| Best-case perf. | Worst-case perf.  | Average perf. | Worst-case space perf.  | Stable  |
| :-------------- | :---------------  | :------------ | :---------------------  | :-----  |
| O(n)            | O(nˆ2)            | O(nˆ2)        | O(1) aux                | Yes     |

## When?
When considering this algorithm, it is widely suggested to invest in other quadratic algorithms which generally produces faster results.

This algorithm main strength is not used to sort but to detect elements out of order.
This happens because it is able to detect if an array is not ordered very rapidly and it can be executed in various sections of the array in parallel.

## Additional Info:
- [Wikipedia](https://en.wikipedia.org/wiki/Bubble_sort)
- [Tutorials Point](https://www.tutorialspoint.com/data_structures_algorithms/bubble_sort_algorithm.htm)
- [GeeksforGeeks](http://www.geeksforgeeks.org/bubble-sort/)

## Variations:
- Odd-even sort and cocktail sort are both parallel versions of this algorithm.
- In some cases, the the algorithm starts from right to left. This is usual with partially sorted arrays, or arrays with unsorted items added to the end.

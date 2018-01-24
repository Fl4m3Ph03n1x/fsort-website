---
id: insertion_sort
title: Insertion Sort
sidebar_label: Insertion Sort
---

Check the [documentation](https://docusaurus.io) for how to use Docusaurus.

## What?

Insertion sort is a simple algorithm that builds the final sorted array one item at a time.

| Best-case perf. | Worst-case perf.  | Average perf. | Worst-case space perf.  | Stable  |
| :-------------- | :---------------  | :------------ | :---------------------  | :-----  |
| O(n)            | O(nˆ2)            | O(nˆ2)        | О(n) total, O(1) aux    | Yes     |

## When?
Although less efficient than quicksort, heapsort or merge sort for large data sets, it usually outperforms them for small data sets.
It also more efficient than other simple quadratic algorithms such as bubble sort and selection sort.

## Additional Info:

- [Wikipedia](https://en.wikipedia.org/wiki/Insertion_sort)
- [Tutorials Point](https://www.tutorialspoint.com/data_structures_algorithms/insertion_sort_algorithm.htm)
- [GeeksforGeeks](http://www.geeksforgeeks.org/insertion-sort/)

## Variations:

- Shell sort, as created by D.L. Shell has better perf. complexity on both its variants.
- Binary insertion sort, is a similar algorithm used when the cost of writing data is expensive VS the cost of read it ( using SSD for example ).
- Binary merge sort, is a composition of both insertion sort ( for small array ) and merge sort ( for the final, bigger array ).
- Both heap sort and Binary tree sort are adaptations of this algorithm for heaps and binary trees.
- Library sort, aka gapped insertion is a modification of this algorithm that runs with high probability in O(n log n) time.

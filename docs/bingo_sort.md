---
id: bingo_sort
title: Bingo Sort
sidebar_label: Bingo Sort
---

Check the [documentation](https://docusaurus.io) for how to use Docusaurus.

## What?

Bingo is a variation of selection sort that repeatedly looks through the remaining items to find the greatest value and then moving all items with that value to the end of the list.

| Best-case perf.         | Worst-case perf.        | Average perf.           | Worst-case space perf.  | Stable  |
| :---------------------- | :---------------------- | :---------------------  | :---------------------  | :-----  |
|  O(nˆ2) comp., O(n) sw. | O(nˆ2) comp., O(n) sw.  | O(nˆ2) comp., O(n) sw.  | О(n) total, O(1) aux.   | No      |

## When?

This algorithm is to be used in lists that have repeated items, as it will perform better than the original Selection Sort for this specific cases.

## Additional Info:

- [Wikipedia](https://en.wikipedia.org/wiki/Selection_sort)
- [NIST](https://xlinux.nist.gov/dads/HTML/bingosort.html)

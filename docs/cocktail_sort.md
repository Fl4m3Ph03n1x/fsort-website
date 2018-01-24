---
id: cocktail_sort
title: Cocktail Sort
sidebar_label: Cocktail Sort
---

Check the [documentation](https://docusaurus.io) for how to use Docusaurus.

## What?

Cocktail shaker sort ( aka bidirectional bubble sort, cocktail sort, shaker sort, ripple sort, shuffle sort, shuttle sort ) is a variation of bubble sort that sorts in both directions on each pass through the list.
Like comb sort, it attacks the problem of turtles and provides marginal performance improvements, making it usually around 2x faster than bubble sort.

| Best-case perf. | Worst-case perf.  | Average perf. | Worst-case space perf.  | Stable  |
| :-------------- | :---------------  | :------------ | :---------------------  | :-----  |
| O(n)            | O(nˆ2)            | O(nˆ2)        | O(1)                    | Yes     |

## When?

Like comb sort, this algorithm improves on bubble sort and can be used when one requires consistent sort times at the cost of efficiency.

## Additional Info:

- [Wikipedia](https://en.wikipedia.org/wiki/Cocktail_shaker_sort)
- [GrowingWithTheWeb](http://www.growingwiththeweb.com/2016/04/cocktail-sort.html)
- [GeeksforGeeks](https://www.geeksforgeeks.org/cocktail-sort/)

---
id: what_why_how
title: What, Why & How?
sidebar_label: What, Why & How?
---

## What is `fsort`?

`fsort` is a library with various sorting algorithms for the most various purposes.
It has both comparison and integer sorting algorithms alongside so that you don't have to worry with them.

## Why use `fsort`?

If you are a functional programmer, `fsort` is for you. It shares many features learned from other successful functional libraries, like [Ramda](http://ramdajs.com/) or [lodash/fp](https://github.com/lodash/lodash/wiki/FP-Guide) and it applies them to its public API.
Among this set of features, `fsort` provides:

- Pure public API
- All functions are naturally curried
- Data-last approach to functions

`fsort` also implements the optimised version of each algorithm so you can reap the greatest benefits of each implementation.

**But even if having a pure, functional based API** is not something that excites you, `fsort` still has a strong use case for your applications. You see, the default implementation of `Array.prototype.sort` has some issues:

- It varies from browser to browser and thus is very inconsistent across multiple environments
- The complexity of the algorithms used by each browser is implementation specific and varies from version to version, thus meaning [it is unknown](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/sort)
- The browsers implementation can be highly inefficient depending on your data set.

So if you want consistent results, with optimal performance, `fsort` really is one of the best ways to go about it.

## How do I use ?

To use this library simply install it from NPM:

```
npm i fsort
```

and you are done!

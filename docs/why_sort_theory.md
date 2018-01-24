---
id: why_sort_theory
title: Why is this important?
sidebar_label: Why is this important?
---

Imagine you have a data set, and an application with a list. In your list you want to show the best restaurants by score - but there is a problem: when you load the webpage everything lags horribly.

After a performance diagnosis you conclude that your app is trying to sort millions of restaurants to show in the list. Even if your list only shows the top 10, you still need to sort them all so you know which 10 restaurants are the best.

**This is a recurrent issue** for many applications. Most people use `Array.prototype.sort` thinking that's all you need, but in reality if you know your data set and which algorithm to pick you can easily improve the performance by at least 80%.

Sort theory is only important as long performance is important for your algorithms. Because most browsers tend to do wrong assumptions about the data sets you use, their algorithms usually lead to poor results - which can be an issue if you are sorting millions of restaurants.

Sort theory bases itself on three pillars:

1. Know your data set: it's size, it's format, it's distribution. Even if you don't know all this points, knowing some will already help you choose a better sorting algorithm.
2. Know the what you value the most: is the speed over consistency? is it an efficient usage of memory or the number of writes?
3. Know the properties of the algorithms: don't worry, we get this covered for you in our documentation as best as we can :D

With this 3 things in mind, you are ready to solve the restaurants problem of your app by simply replacing one method: the sort method!

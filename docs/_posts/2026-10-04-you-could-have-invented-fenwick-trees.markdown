---
layout: posts
title:  "You could have invented Fenwick trees"
category: "A paper a day"
date: 2026-10-04
tags: 
    - functional programming
    - binary trees
    - haskell
    - algorithms
---

## A paper a day: day 25
Today's [paper](https://doi.org/10.1017/S0956796824000169) I decided to read after refreshing in my mind the [Lucy_Hedgehog's algorithm](https://gbroxey.github.io/blog/2023/04/09/lucy-fenwick.html) for calculating the prime counting function. The blogpost uses a data structure called Fenwick (or binary indexed) trees to improve the asymptotics of Lucy_Hedgehog, but it very explicitly treats them as a black box that allows to quickly (log n) store and search for the prefix sums of a given array. I naturally first went to Wikipedia, but it treats the structure as three trees in a trenchcoat, and reading that article I didn't get any real intuition for _why_ this structure makes sense. Enter today's paper.

It gives a very natural and _intuitive_ construction for Fenwick trees: build a tree out of pairwise sums of adjacent elements, and then hide all _right children_. You can still reconstruct the whole tree by subtracting the nodes that are left (pun intended) from each other in appropriate combinations. You only store the same number of elements as the array you are trying to get range sums for has, i.e. it is linear in space. And as this is still a tree, despite most of its nodes being "inactive", you get a logarithmic time for both search and updates. 

But what I did _not_ expect, was that the rest of the paper is ultimately a very good tutorial on bit string operations in _Haskell_ of all things. I had not seen a single line of this language before this, and was pleasantly surprised at how familiar it is. I have played around with Lean before (read: finished the [Natural Number Game](https://adam.math.hhu.de/) and formalized a couple very simple proofs, which still nearly broke me), and the type system in Haskell is thus a very familiar beast. The syntax is a bit arghhh in places, but I think it is just the unfamiliarity screaming in me. I quite enjoyed the hyper functional nature of the language, now I kinda wanna play around with it myself. Like, come on, you can define everything purely recursively and not fear stack overflow? Sign me the hell up!
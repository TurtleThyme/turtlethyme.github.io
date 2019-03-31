---
layout: post
title: Binary Tree and Binary Search Tree
---

A binary tree is a tree data structure that has a left and a right side to it. According to wikipedia, they are refrenced as
the "right child and left child" The binary search tree is a certain variation of the binary tree where the binary tree's 
children from right to left children are sorted in order. The right child is greater than the parent and the left child
is less in vlaue than the parent. This pattern appears through out the whole tree. When this tree is sorted, it looks 
something like this:

<pre>
             30
           /    \
          20     50
         / \     /  \
        10  25   45  60
</pre>

![Tree](/images/asas.PNG)

This variation is used to find items and sort items really fast because the binary search tree is already in sorted order and
all you need to do is go down a path where your number is higher than or lower than and go through multipule paths until you
find your solution. This is an O(log(n)) solution to finding an item in a binary search tree. In the sorting items in a sorted
array for a binary search tree, all you need to do is write a simple 4 lines of logic in order to do that.

![Programm](/images/asasas.PNG)

---
layout: post
title: "Data Structures and Algorithms for adavancing to other domains"
tags:
  - technology
  - coding
  - algorithms
  - data structures
hero: https://media.geeksforgeeks.org/wp-content/uploads/20191010170332/Untitled-Diagram-183.png
overlay: green
published: true

---
__this is my article from Medium that is also about to be published on Analytics Vidhya and Hackernoon__ 

Well so, this blog post is what the title suggests. Exactly. I’ll be summarizing all the Data Structures and Algorithms you should be knowing before you move on to domains like competitive programming on a relatively large scale like Google Codejam, doing web development, building Python ( or any other language ) projects like games, utilities, projects implying your knowledge of that language or moving onto Machine Learning since I have the first-hand experience in doing all of the above-mentioned tasks and that started with learning the foundations of programming. I agree web development can be done without being great at data structures and algorithms and instead focusing on troubleshooting, writing tight code that implements the functionalities or just simply hacking your way to complete the project but it’s always a good idea to be good at the core foundations of programming before advancing to other domains of CS.

{: .lead}
<!–-break-–>

At the bare minimum, you need to be aware of the following Data Structures. I’ll be summarizing each of them with some Python code, and links to resources where you can learn more about them.

**Note: I won’t exactly be canvassing over to the details of these Data Structures since this blog post is mainly directed towards achieving the understanding of what to learn about initially before moving on to the other domains along with the resources I used to learn them. This in no way, is a tutorial or explanation of these Data Structures.**

The most essential Data Structures you need to know apart from the basic data structures like lists, dictionaries and numpy arrays ( numpy is a Python library ) are mainly :

* **Hashtables**

* **Heaps**

* **Stacks**

* **Queues**

* **Linked Lists**

* **Binary Trees**

* **Hashmaps**

We’ll start with the most basic one, Linked Lists.

### **1. Linked Lists :**

Linked Lists are of three types, Singly Linked Lists, Doubly Linked Lists, Circular Linked Lists.

We would be discussing the boiled down structure of a Linked List and it’s implementation in Python. I will, however, list down the resources for learning more about Doubly and Circular Linked Lists. They are good to know but not as essential to your knowledge of CS as the basic structure of a Linked List represented in form of a singly Linked List.

A singly linked list is a data structure consisting of a list of *node* objects. Each **node** contains a value and points to the next node in that list.

They are given preference over arrays due to their dynamic size, ease of insertion and deletion.

The **head pointer** points to the first node, and the last element of the list points to null. When the list is empty, the head pointer points to null.

![Singly Linked List ( source : geeksforgeeks.com )](https://cdn-images-1.medium.com/max/2000/0*VDJoebpT0cJL5OcO.png)*Singly Linked List ( source : geeksforgeeks.com )*

Implementation in Python :

<iframe src="https://medium.com/media/af4c7538ba259050868a4d25f09c9320" frameborder=0></iframe>

We follow three steps to achieve the implementation of Linked Lists :

1. We start with a single node.

1. Join the nodes to create a Linked List.

1. Add required methods to complete the Linked List class.

## **2. Heaps**

![](https://cdn-images-1.medium.com/max/2000/0*kIlppj8dRc4fxs-w.gif)

A heap is essentially a data structure that is an array object that we can view as an almost finished binary tree. The tree is filled on all levels except possibly the lowest, which is filled from the left up to a point.

There are two kinds of binary heaps: max-heaps and min-heaps. In both kinds, the values in the nodes satisfy a *heap property*. For max-heap, the property states as for every node i other than root.

Implementation :

<iframe src="https://medium.com/media/3e3deb685f0d463c980edde024e32d15" frameborder=0></iframe>

![](https://cdn-images-1.medium.com/max/2000/0*AO8GZomeTFtYvov1.png)

## 3. Stacks

A stack is a linear data structure that stores items in a Last-In/First-Out (LIFO) or First-In/Last-Out (FILO) manner. In stack, a new element is added at one end and an element is removed from that end only. The insert and delete operations are often called push and pop.

Implementation :

The implementation is done using the Queue module in Python3.

<iframe src="https://medium.com/media/db2a6b069c01fd5b9395015e46dca874" frameborder=0></iframe>

## 4. Queues

Like stack, *queue* is a linear data structure that stores items in First In First Out (FIFO) manner. With a *queue,* the least recently added item is removed first.

Dequeue: Removes an item from the *queue*. The items are popped in the same order in which they are pushed.

Implementation of Queues using Stacks in Python3 :

<iframe src="https://medium.com/media/767a2e593e2b6c3779dcb533f40ff1c7" frameborder=0></iframe>

## 5. Hashmaps/Hashtables

A Hash table or a Hashmap is a type of data structure that maps keys to its value pairs (implement abstract array data types). It basically makes use of a function that computes an index value that in turn holds the elements to be searched, inserted, removed, etc. This makes it easy and fast to access data. In general, hash tables store key-value pairs and the key is generated using a hash function.

![](https://cdn-images-1.medium.com/max/2000/1*fzLicCDg3GJ9q3htwzJSog.png)

Implementation :

<iframe src="https://medium.com/media/9784d259ea6a1cfb0a1abb5b892c66eb" frameborder=0></iframe>

## **6. Binary Search Trees**

**What are Binary Search Trees?**

In computer science, binary search trees, sometimes called ordered or sorted binary trees, are a particular type of container: a data structure that stores “items” in memory.

![](https://cdn-images-1.medium.com/max/2000/0*I_6ftEmr72Jn8uuJ.jpg)

Now, the BSTs can be traversed in three different ways :

* Pre-order Traversal

![](https://cdn-images-1.medium.com/max/2000/0*3yES3xTeoUNc5SY5.png)

* In-order Traversal

![](https://cdn-images-1.medium.com/max/2000/0*AU8WUzxPOmw1pdGy.png)

* Post-Order Traversal

![](https://cdn-images-1.medium.com/max/2000/0*-u2ppPcC8FvG7T5K.png)

The traversals are mostly implemented in the Node class.

Implementation :

<iframe src="https://medium.com/media/ffc733ff957e227215ac1b72da94724e" frameborder=0></iframe>

Albeit, I believe that having the the understanding of these Data Structures and their implementation will not only help you better your computing skills but it’ll go a long way in understanding concepts of various frameworks or a new language altogether.

**Some Resources that might help :**
[**Lecture Videos**
*This is one of over 2,200 courses on OCW.*ocw.mit.edu](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-006-introduction-to-algorithms-fall-2011/lecture-videos/)
[**geeksforgeeks.com**
*2020 Copyright. All Rights Reserved. The Sponsored Listings displayed above are served automatically by a third party…*geeksforgeeks.com](https://geeksforgeeks.com)
[**Solve Data Structures Code Challenges**
*Join over 7 million developers in solving code challenges on HackerRank, one of the best ways to prepare for…*www.hackerrank.com](https://www.hackerrank.com/domains/data-structures)

For me, Hackerrank and the MIT OCW course helped a lot, I also recommend checking out YouTube for videos.

Some channels and videos I highly recommend :
[**Nick White**
*Coding, Gaming, IRL, and some other stuff*www.youtube.com](https://www.youtube.com/channel/UC1fLEeYICmo3O9cUsqIi7HA)

<center><iframe width="560" height="315" src="https://www.youtube.com/embed/RBSGKlAvoiM" frameborder="0" allowfullscreen></iframe></center>
[**HackerRank**
*HackerRank is a technology hiring platform that helps over 1,000 companies hire skilled developers and innovate faster…*www.youtube.com](https://www.youtube.com/channel/UCOf7UPMHBjAavgD0Qw5q5ww)

With pure legitimacy, I hope this blog post helped you in some way, maybe to get started with Data Structures and Algorithms before you move on to learning other aspects of programming.

The next blog post would probably be on “My first-time experience with Arch Linux”.

Stay tuned.

**[My Medium Profile](https://medium.com/@arthtyagi)**{: style="color: blue; opacity: 0.80;" }
# 🗺️ Data Structures & Algorithms Roadmap

This roadmap is designed to take you from the basics of programming to advanced interview preparation, covering essential data structures, algorithms, and problem-solving techniques.

---

## 🏁 Phase 1: The Prerequisites
Before diving into DSA, ensure you are comfortable with the syntax and basics of one coding language.

- [ ] **Choose a Programming Language** (Python, Java, C++, JavaScript, etc.)
- [ ] Understand Variables, Loops, and Conditions
- [ ] Understand Functions and Classes

---

## 🏗️ Phase 2: Data Structures (The Building Blocks)
Learn how data is stored and organized.

### 2.1 🧱 Linear Data Structures
Sequential organization of data.

**1. Arrays (Static & Dynamic)**
- [ ] **Basics:** Understanding contiguous memory allocation & Indexing.
- [ ] **Operations:** Insert, Delete, Update, Traversal ($O(1)$ vs $O(N)$).
- [ ] **Dynamic Arrays:** Implementing automatic resizing (like `ArrayList` in Java or `vector` in C++).
- [ ] **2D Arrays / Matrices:** Row-major vs Column-major order.
- [ ] **Techniques:** Prefix Sum Arrays, Sliding Window on Arrays.

**2. Linked Lists**
- [ ] **Singly Linked List:** Node structure (Data + Next Pointer).
- [ ] **Doubly Linked List:** Handling `Prev` and `Next` pointers.
- [ ] **Circular Linked List:** Last node pointing back to Head.
- [ ] **Core Operations:**
    - [ ] Insertion (Head, Tail, Middle).
    - [ ] Deletion (Head, Tail, Middle).
    - [ ] Reversing a Linked List (Iterative & Recursive).
- [ ] **"Runner" Technique:** Fast & Slow pointers (Tortoise & Hare) for finding middle or detecting cycles.

**3. Stacks (LIFO - Last In, First Out)**
- [ ] **Implementation:** Using Arrays vs. Using Linked Lists.
- [ ] **Core Operations:** Push, Pop, Peek/Top, IsEmpty.
- [ ] **Monotonic Stack:** Finding "Next Greater Element" or "Previous Smaller Element".
- [ ] **Applications:**
    - [ ] Valid Parentheses checking `()[]{}`.
    - [ ] Expression Conversion (Infix to Postfix/Prefix).
    - [ ] Recursion Stack visualization.

**4. Queues (FIFO - First In, First Out)**
- [ ] **Implementation:** Using Arrays vs. Linked Lists.
- [ ] **Core Operations:** Enqueue (Add), Dequeue (Remove), Front, Rear.
- [ ] **Circular Queue:** Implementing a Ring Buffer (using modulo operator `%`).
- [ ] **Double-Ended Queue (Deque):** Insertion/Deletion at both ends.
- [ ] **Priority Queue:** (Introduction only) Elements processed by priority, not arrival.

### 2.2 🌳 Non-Linear Data Structures
Hierarchical or interconnected organization of data.

**1. Trees (Hierarchical Data)**
- [ ] **Binary Trees (General):**
    - [ ] **Structure:** Root, Left Child, Right Child, Leaf Nodes.
    - [ ] **Types:** Full, Complete, Perfect, Balanced Binary Trees.
    - [ ] **Traversals:**
        - [ ] Depth-First: Pre-order, In-order, Post-order (Iterative & Recursive).
        - [ ] Breadth-First: Level-order traversal (using Queue).
    - [ ] **Standard Problems:** Height of tree, Diameter of tree, Lowest Common Ancestor (LCA).

- [ ] **Binary Search Trees (BST):**
    - [ ] **Property:** Left < Root < Right.
    - [ ] **Operations:** Search, Insert, Delete ($O(\log N)$ average).
    - [ ] **Validation:** Checking if a Binary Tree is a valid BST.
    - [ ] **Balancing (Concept):** Understanding why unbalanced trees degrade to Linked Lists ($O(N)$).

- [ ] **Heaps (Priority Queues):**
    - [ ] **Types:** Min-Heap (smallest at top) vs. Max-Heap (largest at top).
    - [ ] **Implementation:** Binary Heap using Arrays (Index math: `2i+1`, `2i+2`).
    - [ ] **Operations:** Push, Pop (Extract Min/Max), Heapify, Decrease Key.
    - [ ] **Usage:** Finding "K-th" largest/smallest elements efficiently.

**2. Graphs (Network Data)**
- [ ] **Representation (How to store them):**
    - [ ] **Adjacency Matrix:** 2D Array (Good for dense graphs).
    - [ ] **Adjacency List:** Array of Lists/Vectors (Standard for interviews).

- [ ] **Graph Types:**
    - [ ] **Directed:** One-way streets (e.g., Web page links).
    - [ ] **Undirected:** Two-way streets (e.g., Facebook friends).
    - [ ] **Weighted:** Edges have cost/distance (e.g., Google Maps).
    - [ ] **Cyclic vs. Acyclic:** Detection of loops.

- [ ] **Core Algorithms:**
    - [ ] **Traversal:** BFS (Shortest path in unweighted) vs. DFS (Path finding/Backtracking).
    - [ ] **Cycle Detection:** Using DFS (Recursion stack) or Disjoint Set (Union-Find).
    - [ ] **Topological Sort:** Ordering tasks with dependencies (Directed Acyclic Graphs only).

- [ ] **Advanced Graph Algorithms (The "Hard" Questions):**
    - [ ] **Dijkstra’s Algorithm:** Shortest path in weighted graphs (No negative weights).
    - [ ] **Bellman-Ford:** Shortest path with negative weights.
    - [ ] **Prim’s / Kruskal’s:** Minimum Spanning Tree (MST).

### 2.3 CRUD Operations
Master the basic operations for all the structures above.
- [ ] **C**reate (Insert data)
- [ ] **R**ead (Retrieve data)
- [ ] **U**pdate (Modify data)
- [ ] **D**elete (Remove data)

---

## 🔍 Phase 3: Traversal & Searching
How to navigate through your data structures.

### 3.1 🔍 Searching Algorithms

**1. Linear Search**
- [ ] **Method:** Iterate through the collection element by element.
- [ ] **Use Case:** Unsorted data or very small datasets.
- [ ] **Complexity:** Time: $O(N)$ | Space: $O(1)$.
- [ ] **Optimization:** Sentinel Linear Search (removes one check inside the loop).

**2. Binary Search (Divide & Conquer)**
- [ ] **Pre-requisite:** Data **must** be sorted.
- [ ] **Core Logic:** Compare target with `mid`; discard half the search space.
- [ ] **Implementation:**
    - [ ] **Iterative:** Using `while(low <= high)` loop (Preferred to avoid stack overflow).
    - [ ] **Recursive:** Function calls itself with new bounds.
    - [ ] **Bug-Free Mid:** Using `mid = low + (high - low) / 2` to prevent integer overflow.
- [ ] **Advanced Patterns:**
    - [ ] **Lower Bound:** Finding the *first* occurrence of a value.
    - [ ] **Upper Bound:** Finding the first value *greater* than target.
    - [ ] **Search on Answer:** Using Binary Search to find the optimal solution (e.g., "Minimum capacity to ship packages").



**3. Depth First Search (DFS)**
- [ ] **Philosophy:** "Go deep before going wide." Explore a branch as far as possible, then backtrack.
- [ ] **Data Structure:** Uses a **Stack** (or the Call Stack via Recursion).
- [ ] **Graph/Tree Applications:**
    - [ ] **Path Finding:** Finding *any* path between two nodes (e.g., Solving a Maze).
    - [ ] **Cycle Detection:** Checking if a graph contains a loop.
    - [ ] **Topological Sort:** Scheduling tasks where order matters.
    - [ ] **Connected Components:** Counting islands in a grid.

**4. Breadth First Search (BFS)**
- [ ] **Philosophy:** "Go wide before going deep." Explore all immediate neighbors before moving to the next level.
- [ ] **Data Structure:** Uses a **Queue** (FIFO).
- [ ] **Graph/Tree Applications:**
    - [ ] **Level Order Traversal:** Printing a tree row by row.
    - [ ] **Shortest Path (Unweighted):** Finding the shortest distance in a graph where all edges have equal weight (Critical Interview Question).
    - [ ] **Social Networks:** Finding "Friends of Friends" (2nd degree connections).
### 3.2 Traversal Techniques
- [ ] **In-order Traversal** (Left, Root, Right)
- [ ] **Pre-order Traversal** (Root, Left, Right)
- [ ] **Post-order Traversal** (Left, Right, Root)
- [ ] **Level-order Traversal**

---

## 🔢 Phase 4: Sorting Algorithms
Techniques to rearrange data in a specific order.

**Basic & Educational**
- [ ] **Bubble Sort** (Simple, pairwise swapping)
- [ ] **Selection Sort** (Finds minimum, places at start)
- [ ] **Insertion Sort** (Builds sorted list one-by-one)
- [ ] **Cycle Sort** (Minimizes memory writes)

**Efficient ($O(N \log N)$)**
- [ ] **Merge Sort** (Divide and conquer, stable)
- [ ] **Quick Sort** (Pivot-based partitioning)
- [ ] **Heap Sort** (Uses binary heap data structure)
- [ ] **Shell Sort** (Generalized insertion sort)

**Non-Comparison / Linear ($O(N)$)**
- [ ] **Counting Sort** (Integer sorting based on keys)
- [ ] **Radix Sort** (Sorts digit by digit)
- [ ] **Bucket Sort** (Distributes elements into buckets)

**Hybrid (Real-World Defaults)**
- [ ] **TimSort** (Merge & Insertion hybrid - Python/Java default)
- [ ] **IntroSort** (Quick, Heap & Insertion hybrid - C++ default)
---

## 🧠 Phase 5: Core Algorithmic Concepts
Foundational concepts for solving complex problems.

- [ ] **Recursion** (Functions calling themselves)
- [ ] **Backtracking** (Solving incrementally, removing failed solutions)
- [ ] **Dynamic Programming (DP)** (Breaking problems into sub-problems)

---

## ⚡ Phase 6: Optimization Techniques (Problem Solving Patterns)
These are specific patterns frequently asked in coding interviews to optimize solutions.

- [ ] **Two Pointers** (Iterating with two references)
- [ ] **Sliding Window** (Sub-array/substring problems)
- [ ] **Prefix / Suffix Sums** (Pre-computation for range queries)

---

## 💼 Phase 7: Interview Preparation
Bringing it all together.

- [ ] Solve problems on LeetCode / HackerRank / CodeForces
- [ ] Practice Time Complexity Analysis (Big O Notation)
- [ ] Practice Space Complexity Analysis
- [ ] Mock Interviews

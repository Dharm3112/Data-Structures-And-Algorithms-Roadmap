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

### 2.2 Non-Linear Data Structures
Hierarchical or interconnected organization of data.


### 2.3 CRUD Operations
Master the basic operations for all the structures above.
- [ ] **C**reate (Insert data)
- [ ] **R**ead (Retrieve data)
- [ ] **U**pdate (Modify data)
- [ ] **D**elete (Remove data)

---

## 🔍 Phase 3: Traversal & Searching
How to navigate through your data structures.

### 3.1 Searching Algorithms
- [ ] **Linear Search** (Simple iteration)
- [ ] **Binary Search** (Divide and conquer - for sorted data)
- [ ] **Depth First Search (DFS)** (Stack-based graph/tree traversal)
- [ ] **Breadth First Search (BFS)** (Queue-based graph/tree traversal)

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

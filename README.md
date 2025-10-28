# Data-Structure-Algorithms-Patterns
A complete collection of essential Data Structures &amp; Algorithms patterns with clean, well-explained code examples to master problem-solving code examples to master problem-solving and crack MAANG interviews. Covers core patterns like Sliding Window,Two Pointers,DP, Graphs and Backtracking with templates,complexity notes and practical interview tips

# 🚀 Data Structures & Algorithms – Crack MAANG & Top Tech Interviews

![Stars](https://img.shields.io/github/stars/your-username/dsa-patterns?style=for-the-badge)
![Forks](https://img.shields.io/github/forks/your-username/dsa-patterns?style=for-the-badge)
![Issues](https://img.shields.io/github/issues/your-username/dsa-patterns?style=for-the-badge)
![License](https://img.shields.io/github/license/your-username/dsa-patterns?style=for-the-badge)
![MAANG](https://img.shields.io/badge/MAANG-Ready-blueviolet?style=for-the-badge)
![Companies](https://img.shields.io/badge/Amazon-Google-Meta-Netflix-Zomato-Swiggy-brightgreen?style=for-the-badge)

---

## 🧭 Table of Contents
1. [About the Repository](#about-the-repository)
2. [Core Concepts](#core-concepts)
3. [Popular DSA Patterns](#popular-dsa-patterns)
4. [MAANG-Level Problem Set](#maang-level-problem-set)
5. [Company-Wise Patterns](#company-wise-patterns)
6. [Contributing](#contributing)
7. [Resources & References](#resources--references)
8. [Author](#author)

---

## 📘 About the Repository
This repository is a **comprehensive collection of essential Data Structures & Algorithms (DSA)** patterns, designed to **help you master problem-solving and crack interviews at MAANG, Swiggy, Zomato, and top startups**.

Each pattern comes with:
- 🧩 Code templates in Python, C++, or Java  
- 🧠 Explanation of core logic  
- ⏱️ Time and Space Complexity  
- 🏹 Real-world interview problems  

---

## ⚙️ Core Concepts
Before diving into patterns, review these fundamental areas:
- Arrays & Strings  
- Recursion & Backtracking  
- Linked Lists, Stacks, Queues  
- Trees & Graphs  
- Dynamic Programming  
- Sorting & Searching  
- Greedy Algorithms  
- Bit Manipulation  

---

## 💡 Popular DSA Patterns

| Pattern | Description | Example Problems |
|----------|--------------|------------------|
| 🪟 **Sliding Window** | Optimize subarray problems for max/min/sum/k-length | Longest Substring Without Repeating Characters (LeetCode #3), Max Consecutive Ones, Minimum Window Substring |
| 🎯 **Two Pointers** | Works on sorted data to find pairs, partitions | 3Sum, Container With Most Water, Remove Duplicates from Sorted Array |
| 🧮 **Binary Search** | Efficient searching or optimization | Search Rotated Array, Find Peak Element, Median of Two Sorted Arrays |
| 🧵 **Fast & Slow Pointers** | Detect loops or middle nodes | Linked List Cycle, Palindrome Linked List |
| 🔁 **Dynamic Programming** | Break down complex problems into subproblems | Longest Increasing Subsequence, House Robber, Coin Change |
| 🌳 **Trees & Graphs (DFS/BFS)** | Hierarchical and connected data traversal | Binary Tree Level Order, Clone Graph, Word Ladder |
| 🎲 **Backtracking** | Generate all combinations or paths | N-Queens, Sudoku Solver, Permutations |
| 🧭 **Greedy** | Local optimal → global optimal | Jump Game, Interval Scheduling, Huffman Encoding |
| 🧮 **Prefix Sum / Kadane’s** | Efficient range calculations | Maximum Subarray, Subarray Sum Equals K |
| 🧱 **Stack & Monotonic Stack** | Useful in range problems | Largest Rectangle in Histogram, Daily Temperatures |

---

## 🔥 MAANG-Level Problem Set

### 🟠 Sliding Window
- **Longest Substring Without Repeating Characters** – *Google, Amazon*  
  👉 Use hash map to track characters; move window start as duplicates appear.  
  ⏱ O(N)  
- **Minimum Window Substring** – *Meta, Microsoft*  
  👉 Maintain counts of target chars and shrink window.  
  ⏱ O(N)

### 🔵 Two Pointers
- **Container With Most Water** – *Amazon, Netflix*  
  👉 Use pointers at both ends; move smaller height inward.  
  ⏱ O(N)
- **3Sum Problem** – *Google, Meta*  
  👉 Sort + Two Pointers from both ends to find zero-sum triplets.  
  ⏱ O(N²)

### 🟢 Dynamic Programming
- **Coin Change** – *Amazon, Meta*  
  👉 Classic DP to find min coins for target sum.  
  ⏱ O(N * amount)
- **Longest Increasing Subsequence** – *Google, Netflix*  
  👉 Use DP with binary search for O(N log N).

### 🟣 Graphs
- **Word Ladder** – *Google, Swiggy*  
  👉 BFS transformation sequence between words.  
  ⏱ O(N * L²)
- **Clone Graph** – *Meta*  
  👉 DFS clone with hash map to prevent duplication.

### 🔴 Backtracking
- **N-Queens** – *Amazon, Zomato*  
  👉 Recursive placement with column and diagonal checks.  
  ⏱ O(N!)
- **Permutations** – *Netflix, Google*  
  👉 Swap and explore recursively.  
  ⏱ O(N!)

### ⚫ Greedy
- **Jump Game** – *Amazon*  
  👉 Track maximum reachable index at each step.  
  ⏱ O(N)
- **Activity Selection** – *Zomato, Swiggy*  
  👉 Sort by end times; pick non-overlapping activities.  
  ⏱ O(N log N)

---

## 🏢 Company-Wise Patterns

| Company | Common Patterns | Example Problems |
|----------|------------------|------------------|
| **Amazon** | Sliding Window, Greedy, Trees | LRU Cache, Jump Game, Binary Tree Zigzag |
| **Google** | Graphs, DP, Backtracking | Word Ladder, N-Queens, LIS |
| **Meta** | Two Pointers, Hashing, DP | 3Sum, Clone Graph, Coin Change |
| **Netflix** | Binary Search, Greedy | Container With Most Water, Meeting Rooms II |
| **Swiggy** | Graphs, Greedy, BFS | Minimum Path Delivery, Word Ladder |
| **Zomato** | DP, Sorting, Greedy | Restaurant Allocation, Activity Scheduling |

---

## 📚 Resources & References
- [LeetCode](https://leetcode.com/)
- [GeeksForGeeks](https://www.geeksforgeeks.org/)
- [InterviewBit](https://www.interviewbit.com/)
- [Striver’s SDE Sheet](https://takeuforward.org/)
- [NeetCode.io](https://neetcode.io/)

---

## 🤝 Contributing
Contributions are welcome!  
1. Fork this repository  
2. Create a new branch (`feature/new-pattern`)  
3. Add explanations or code samples  
4. Submit a pull request 🚀  

---

## 👨‍💻 Author
**Pawan Kumar**  
📍 Product Manager | Data & DevOps Mentor | AI & Cloud Enthusiast  
🔗 [LinkedIn](https://www.linkedin.com/in/pawankhustlerdev/)  
✉️ [pawankm7654@gmail.com](mailto:pawankm7654@gmail.com)  

---

⭐ **Star this repository** if it helped you — it motivates to add more curated interview content every week!


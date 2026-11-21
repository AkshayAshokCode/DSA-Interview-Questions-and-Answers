# DSA Interview Questions & Answers

Data structures and algorithms for coding interviews, written for **Android, iOS and backend engineers**: **365 questions with fully explained answers** in 24 topics. It starts with how coding rounds work and a dedicated section on **recognising patterns, reusable templates and problem-solving tricks**, then covers every core data structure and algorithm family, design-style and mobile-flavoured coding problems, and **company-wise questions** for FAANG and product companies. Solutions are in **Kotlin**, with **Swift** for problems where it matters.

Every answer opens with a short **In short:** line you can say in the interview, then explains it in depth: the problem, edge cases, brute force, the key insight, a walkthrough, clean code, complexity, common mistakes and follow-ups. Answers are hidden in collapsible blocks, so you can **test yourself first** and then click to check.

> **📈 [Open the interactive study tracker](https://akshayashokcode.github.io/DSA-Interview-Questions-and-Answers/)**: mark questions ✓ Done or Revise, filter by difficulty, see your progress per topic, search every question, listen to answers read aloud, and continue where you left off.
>
> **No account needed.** Your progress saves automatically on your device. Want to keep it safe and in sync across your devices? Sign in (optional).

Also see: **[Android](https://github.com/AkshayAshokCode/Android-Interview-Questions-and-Answers)** · **[iOS](https://github.com/AkshayAshokCode/iOS-Interview-Questions-and-Answers)** · **[System Design](https://github.com/AkshayAshokCode/System-Design-Interview-Questions-and-Answers)** · **[AI](https://github.com/AkshayAshokCode/AI-Interview-Questions-and-Answers)**

---

## How to use this repo

1. **Start with the foundations (01–03)**: how coding rounds are graded, Big-O, and your language toolkit in Kotlin and Swift.
2. **Learn to spot patterns (04–06)** before grinding problems: what the constraints and keywords tell you, the templates worth memorising, and the tricks that unlock whole families of problems.
3. **Work through the pattern topics (07–21)**. For each question, read the problem, **solve it yourself or talk through the approach out loud**, then open the answer.
4. Finish with [design-style](topics/22-design-style-coding.md), [mobile-flavoured](topics/23-mobile-flavoured-coding.md) and [company-wise](topics/24-company-wise-coding.md) questions.

> Tip: interviewers grade how you think as much as the final code. Say the brute force first, explain why the better idea works, test your code on a small example, and state the complexity.

### Tags on every question

| Tag | Meaning |
|---|---|
| 🟢 Easy · 🟡 Medium · 🔴 Hard | Difficulty (LeetCode's rating for well-known problems) |
| 📘 Concept | An explanation question (how something works, how to choose) rather than a coding problem |
| ⭐ Product/FAANG favourite | Commonly reported in product-company and FAANG coding rounds (based on public candidate reports) |

In total: **41 easy, 170 medium, 28 hard** problems, **126 concept** questions, and **209** marked ⭐. The tracker lets you filter a topic by difficulty or ⭐.

---

## Topics

### 🧭 Foundations

| # | Topic | Questions | Key areas |
|---|---|---|---|
| 01 | [How Coding Interviews Work](topics/01-coding-interviews-overview.md) | 12 | Round formats, what's graded, the problem-solving framework, communicating, clarifying, testing, getting unstuck, OAs, AI-assisted rounds, mobile-role coding rounds |
| 02 | [Complexity Analysis (Big-O)](topics/02-complexity-analysis.md) | 14 | Big-O/Θ/Ω, common complexities, analysing loops and recursion, amortised analysis, space complexity, recursion stack, master theorem intuition, log n |
| 03 | [Kotlin & Swift for Coding Interviews](topics/03-kotlin-swift-for-interviews.md) | 16 | Collections and their costs, HashMap/Dictionary, sorting with comparators, PriorityQueue and heaps in Swift, deques, recursion depth, strings and characters, overflow, idioms |

### 🧩 Patterns & Problem-Solving Tricks

| # | Topic | Questions | Key areas |
|---|---|---|---|
| 04 | [Pattern Recognition: Reading the Problem](topics/04-pattern-recognition.md) | 18 | Constraints to target complexity, keyword-to-pattern signals, decision flow, sorted input, subarrays vs subsequences, counting vs optimising, choosing between candidate patterns |
| 05 | [Reusable Code Templates](topics/05-reusable-templates.md) | 18 | Sliding window, two pointers, binary search bounds, binary search on answer, BFS, DFS, backtracking, DP, topological sort, union-find, Dijkstra, monotonic stack, top-K, prefix sum, merge intervals, trie, fast & slow pointers |
| 06 | [Problem-Solving Tricks Worth Knowing](topics/06-problem-solving-tricks.md) | 22 | Prefix sum + hash map, dummy nodes, cyclic sort, XOR tricks, Kadane, two heaps, Boyer-Moore voting, multi-source BFS, in-place marking, reverse thinking, sentinels, coordinate compression, difference arrays, meet in the middle |

### 📚 Arrays, Strings & Searching

| # | Topic | Questions | Key areas |
|---|---|---|---|
| 07 | [Arrays, Strings & Hashing](topics/07-arrays-strings-hashing.md) | 19 | Frequency counting, anagrams, Two Sum, grouping, in-place array edits, product except self, rotation, matrix traversal, string building, encoding, sequences |
| 08 | [Two Pointers & Sliding Window](topics/08-two-pointers-sliding-window.md) | 16 | Opposite-end pointers, same-direction pointers, fixed and variable windows, character counts in a window, at-most-K trick, deque window |
| 09 | [Prefix Sums, Intervals & Sweep Line](topics/09-prefix-sums-intervals.md) | 12 | 1D and 2D prefix sums, range queries, merge/insert intervals, meeting rooms, sweep line events, non-overlapping intervals |
| 10 | [Binary Search](topics/10-binary-search.md) | 14 | Classic search, lower/upper bound, rotated arrays, search in 2D, peak finding, binary search on the answer, median of two arrays, off-by-one control |
| 11 | [Stacks, Queues & Monotonic Stack](topics/11-stacks-queues-monotonic.md) | 14 | Balanced brackets, min stack, expression evaluation, monotonic stack and queue, next greater element, histogram, decode string, queue via stacks |

### 🌳 Linked Lists, Heaps, Trees & Tries

| # | Topic | Questions | Key areas |
|---|---|---|---|
| 12 | [Linked Lists](topics/12-linked-lists.md) | 14 | Reversal, merging, fast & slow pointers, cycle detection, removing nodes, reordering, copying with random pointers, adding numbers, K-group reversal |
| 13 | [Heaps & Priority Queues](topics/13-heaps-priority-queues.md) | 12 | How a binary heap works, heapify, top-K, k-th largest, merge k sorted, k closest, scheduling, quickselect vs heap |
| 14 | [Trees & Binary Search Trees](topics/14-trees-bst.md) | 20 | Traversals (recursive and iterative), depth and diameter, balanced check, level order, views, LCA, path sums, construction from traversals, serialisation, BST validation and operations |
| 15 | [Tries & String Algorithms](topics/15-tries-string-algorithms.md) | 10 | Trie implementation, prefix search, wildcard search, word search with a trie, autocomplete, palindromes, KMP and rolling hash intuition |

### 🕸 Graphs

| # | Topic | Questions | Key areas |
|---|---|---|---|
| 16 | [Graphs: BFS, DFS & Topological Sort](topics/16-graphs-bfs-dfs-topo.md) | 18 | Graph representations, BFS/DFS on graphs and grids, connected components, islands, cloning, bipartite check, cycle detection, topological sort, word ladder, shortest path in unweighted graphs |
| 17 | [Advanced Graphs: Shortest Paths, Union-Find & MST](topics/17-advanced-graphs.md) | 12 | Dijkstra, Bellman-Ford, 0-1 BFS, Floyd-Warshall overview, union-find, Kruskal and Prim, network delay, cheapest flights with K stops, redundant connection, accounts merge |

### 🧠 Recursion, DP & Greedy

| # | Topic | Questions | Key areas |
|---|---|---|---|
| 18 | [Recursion & Backtracking](topics/18-recursion-backtracking.md) | 14 | Thinking recursively, subsets, permutations, combinations, combination sum, duplicates handling, pruning, N-Queens, word search, palindrome partitioning, generate parentheses |
| 19 | [Dynamic Programming](topics/19-dynamic-programming.md) | 24 | Recognising DP, memoisation vs tabulation, 1D DP, grid DP, knapsack (0/1, unbounded), LIS, LCS and edit distance, palindrome DP, interval DP, state machine DP, bitmask DP, space optimisation |
| 20 | [Greedy Algorithms](topics/20-greedy.md) | 12 | When greedy works, exchange arguments, jump game, gas station, intervals by end time, partition labels, hand of straights, candy, two-city scheduling |
| 21 | [Bit Manipulation & Math](topics/21-bit-manipulation-math.md) | 12 | Bit operations, counting bits, power of two, reverse bits, sum without +, subsets via bitmasks, GCD, primes (sieve), fast power, modular arithmetic, overflow-safe reverse integer |

### 🏗 Applied

| # | Topic | Questions | Key areas |
|---|---|---|---|
| 22 | [Design-Style Coding Problems](topics/22-design-style-coding.md) | 14 | LRU and LFU caches, iterators, rate limiter, hit counter, randomised set, snapshot array, time-based store, browser history, file system, leaderboard |
| 23 | [Mobile-Flavoured Coding Problems](topics/23-mobile-flavoured-coding.md) | 12 | List diffing (LCS/Myers idea), image cache with LRU and size limits, debounce and throttle, text truncation and wrapping, undo/redo, merging paginated feeds, retry with backoff, autocomplete, grid layout math, dependency ordering |
| 24 | [Company-Wise Coding Questions](topics/24-company-wise-coding.md) | 16 | What Google, Meta, Amazon, Microsoft, Apple, Uber, Netflix-style and Indian product companies (Flipkart, Swiggy, PhonePe, Razorpay, Zerodha, CRED) ask, frequently reported problems, OA patterns, machine coding |

## 🗓 Suggested revision plans

<details>
<summary>4-week plan (about 1–2 hours a day)</summary>

| Week | Topics |
|---|---|
| 1 | 01–06 (foundations, patterns, templates, tricks), 07 Arrays & Hashing, 08 Two Pointers & Sliding Window |
| 2 | 09 Prefix Sums & Intervals, 10 Binary Search, 11 Stacks & Monotonic Stack, 12 Linked Lists, 13 Heaps |
| 3 | 14 Trees & BST, 15 Tries & Strings, 16 Graphs, 17 Advanced Graphs, 18 Backtracking |
| 4 | 19 Dynamic Programming, 20 Greedy, 21 Bits & Math, 22–24 design-style, mobile and company-wise questions; redo everything marked Revise |

</details>

<details>
<summary>1-week crash plan</summary>

Day 1: 01, 04, 05 · Day 2: 07, 08 · Day 3: 10, 11, 13 · Day 4: 14, 16 · Day 5: 18, 19 (⭐ questions first) · Day 6: 22 and your target company in 24 · Day 7: redo every question marked Revise. In the tracker, filter each topic by ⭐ to focus on the most-asked problems.

</details>

## ⚡ Last-Minute Revision

<details>
<summary>Open the quick revision list</summary>

**Read the constraints first**
- About 10⁸ simple operations per second. n ≤ 20 → exponential (backtracking/bitmask) is fine; n ≤ 10⁴ → O(n²) may pass; n up to 10⁵–10⁶ → O(n log n) or O(n); huge n → O(log n) or maths.

**Signal → pattern**
- Sorted input or pairs → two pointers / binary search. Contiguous subarray or substring → sliding window / prefix sums.
- Top K / K-th → heap or quickselect. Next greater/smaller → monotonic stack. Intervals → sort by start (merge) or end (greedy).
- All combinations / permutations / subsets → backtracking. Count ways or best value over choices → DP.
- Shortest path: unweighted → BFS; non-negative weights → Dijkstra; negative weights → Bellman-Ford. Dependencies → topological sort. Groups/connectivity → union-find or DFS.
- Min/max value that still works → binary search on the answer. Prefix lookups → trie. Lookups, counts, duplicates → hash map.

**Tricks**
- Subarray sum = K → prefix sum + hash map. Range updates → difference array. Linked lists → dummy head; cycles/middle → fast & slow pointers.
- Numbers in 1..n → cyclic sort / index marking. Single or missing number → XOR. Running median → two heaps. Exactly K → atMost(K) − atMost(K−1).

**Language**
- Kotlin: `ArrayDeque` for stack/queue, `PriorityQueue` (min-heap; pass a comparator for max), `TreeMap` for floor/ceiling, `Long` against overflow.
- Swift: no built-in heap or deque, so hand-write them; `Array(s)` to index a string; `Int` overflow traps (use `&+` only on purpose).

**In the room**
- Clarify → examples → brute force → optimise → code → test on an example → complexity. Keep talking; ask for a hint before you go silent.

</details>

---

## Contributing

Found a mistake or have a question you were asked in an interview? Open an issue or PR. Keep the format: a numbered `###` question, a tag line (difficulty and optional ⭐), and a `<details><summary>Answer</summary>` block that starts with an **In short:** line and then explains the answer in full.

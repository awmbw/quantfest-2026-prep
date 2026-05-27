# 🏆 Quantfest 2026 — Preparation Repository

> **Target:** Quantfest 2026 Prelims (August 2026)  
> **Timeline:** 9 weeks (June 1 – August 2, 2026)  
> **Organized by:** [IICPC](https://iicpc.com)

---

## 📌 What is Quantfest?

Quantfest is a **national-level quantitative finance competition** organized by IICPC. It simulates real-world quantitative challenges across algorithmic trading, probability, market microstructure, and quantitative research.

### Competition Format (based on 2025)

| Stage | Format | Details |
|-------|--------|---------|
| **Prelims** | Online / On-campus | 12 problems: 5 math/probability + 7 coding (on Codeforces) |
| **Regionals** | In-person at IIT campuses | Heuristic simulations & quant problem sets |
| **Finals** | 3-day event at IIT Madras | Market simulations, trading games, advanced challenges |

---

## 📚 Three Core Resources

This entire preparation plan is built around **exactly three resources**:

### 1. 📖 Green Book — *A Practical Guide to Quantitative Finance Interviews* (Xinfeng Zhou)

**Target chapters & problems:**
- **Chapter 2: Brain Teasers** (36 problems) — Problem Simplification, Logic Reasoning, Thinking Out of the Box, Symmetry, Series Summation, Pigeon Hole, Modular Arithmetic, Induction, Proof by Contradiction
- **Chapter 4: Probability Theory** (42 problems) — Basic Probability, Combinatorial Analysis, Conditional Probability & Bayes', Distributions, Expected Value/Variance/Covariance, Order Statistics
- **Chapter 5: Stochastic Processes** (13 problems) — Markov Chain, Martingale & Random Walk, Dynamic Programming
- **Chapter 7: Algorithms & Numerical Methods** (13 problems) — Algorithms, Power of Two

**Total: ~104 problems**

### 2. 💻 USACO Guide — Competitive Programming Modules

| Level | Scope | Modules |
|-------|-------|---------|
| **General** | Full | Using This Guide, Intro to CP, Choosing a Language, Data Types, I/O, Expected Knowledge, How to Debug, How to Practice, Fast I/O, Basic Debugging, C++ Command Line |
| **Bronze** | Full | Time Complexity, Intro to Data Structures, Simulation, Complete Search, Recursion, Sorting, Sets & Maps, Casework, Greedy, Graphs, Rectangle Geometry, Ad Hoc |
| **Silver** | Full | Prefix Sums (intro + more), Two Pointers, Binary Search (sorted array + general), Custom Comparators, Greedy w/ Sorting, Priority Queues, Graph Traversal, Flood Fill, Trees, Functional Graphs, Bitwise Operators |
| **Gold** | Math + DP only | **Math:** Divisibility, Modular Arithmetic, Combinatorics · **DP:** Intro to DP, Knapsack, Paths on Grids, LIS, Bitmask DP, Range DP, Digit DP |

**Total: ~46 modules**

### 3. 🧩 CSES Problem Set

| Section | Problems |
|---------|----------|
| **Introductory Problems** | 24 problems |
| **Sorting and Searching** | 35 problems |
| **Dynamic Programming** | 23 problems |
| **Mathematics** | 37 problems |
| **Counting Problems** | 18 problems |
| **Additional (math-related)** | ~8 problems |

**Total: ~145 CSES problems**

→ Full problem lists in each week's README and in [PROGRESS.md](PROGRESS.md)

---

## 🗺️ Repository Structure

```
quantfest-2026-prep/
├── README.md                  # You are here
├── PROGRESS.md                # Weekly progress tracker & checklist
├── SCHEDULE.md                # Day-by-day study schedule overview
│
├── weeks/                     # Detailed week-by-week plans
│   ├── week-01/README.md      # Foundations: USACO General + Bronze start
│   ├── week-02/README.md      # Bronze completion + CSES Intro/Sorting
│   ├── ...
│   └── week-09/README.md      # Taper & competition prep
│
├── resources/                 # Extra resources (not part of core plan)
│   ├── books/README.md        # Book recommendations (extras)
│   ├── problem-sets/README.md # Extra problem sets (CF, puzzles, etc.)
│   └── links/README.md        # Useful websites, channels, tools
│
├── solutions/                 # Your solutions (organized by source)
│   ├── green-book/            # Green Book problem solutions
│   ├── usaco-guide/           # USACO Guide module solutions
│   ├── cses/                  # CSES problem solutions
│   └── extras/                # Solutions for optional extra problems
│
├── mock-tests/                # Timed practice tests
│   └── README.md
│
└── notes/                     # Personal study notes
    └── README.md
```

---

## 🎯 Preparation Strategy (9-Week Overview)

| Phase | Weeks | Focus | Goal |
|-------|-------|-------|------|
| **Phase 1: Foundations** | 1–3 | USACO General→Silver, CSES Intro/Sorting, Green Book Ch.2 & Ch.4 start | Build coding foundations & math intuition |
| **Phase 2: Deep Dive** | 4–6 | USACO Silver→Gold, CSES DP/Math, Green Book Ch.4 & Ch.5 | Tackle advanced topics & competition-level problems |
| **Phase 3: Peak & Taper** | 7–9 | CSES Counting + remaining, Green Book Ch.7, mock tests, review | Build speed, accuracy & peak performance |

---

## 📊 Daily Time Commitment

| Activity | Time | Notes |
|----------|------|-------|
| Green Book problems | 45 min | ~2–3 problems/day, review solutions |
| USACO Guide module | 45–60 min | Read module + solve starred problems |
| CSES problem solving | 60 min | Solve 2–3 CSES problems/day |
| Notes & review | 15 min | Document learnings, review weak areas |
| **Total** | **~2.5–3 hrs/day** | 6 days/week (1 rest day) |

---

## 🚀 Quick Start

1. **Clone this repo** and start with [Week 1](weeks/week-01/README.md). Obsidian would be a great app to view and interact with this repo. This is just a suggestion and you can use your favorite app!
2. **Track your progress** in [PROGRESS.md](PROGRESS.md) — check off items daily
3. **Store solutions** in the `solutions/` directory, organized by source
4. **Take notes** in `notes/` — especially for tricky concepts you want to revisit
5. **Do mock tests** starting Week 7 in `mock-tests/Search: "A Practical Guide to Quantitative Finance Interviews" by Xinfeng Zhou`

---

## 📦 Extra Resources (Optional)

These are **not** part of the core plan but may be useful for further practice:

- [YouKn0wWho Academy Topic List](https://youkn0wwho.academy/topic-list)
- [Codeforces Probabilities tag (≤ 1800)](https://codeforces.com/problemset?order=BY_RATING_ASC&tags=probabilities%2C-1800)
- [Codeforces Combinatorics tag (≤ 1800)](https://codeforces.com/problemset?order=BY_RATING_ASC&tags=combinatorics%2C-1800)
- [Jane Street Puzzles](https://www.janestreet.com/puzzles/archive/index.html)
- [Brainstellar](https://brainstellar.com/)
- [QuantQuestions.io](https://quantquestions.io/)
- [PuzzledQuant](https://www.puzzledquant.com/)
- [Cut the Knot](https://www.cut-the-knot.org/)
- [Quantfest 2025 Codeforces Blog](https://codeforces.com/blog/entry/145776)
- [Quantfest Preparation Video](https://www.youtube.com/watch?v=jE9y-lZeTYw)
- [IICPC YouTube Channel](https://www.youtube.com/@iicpc)
- [Full book collection (Google Drive)](https://drive.google.com/drive/folders/1-MRQ3_eMxUoG1RngMepdFBX24DTIy4SD?usp=sharing)
- [Quant Dev Resources (GitHub)](https://github.com/cybergeekgyan/Quant-Developers-Resources)

---

## 🤝 Contributing

If you find useful resources or have suggestions, open an issue.

---

## 📄 License

MIT License — Use freely for your own preparation.

---

*Good luck! See you at Quantfest 2026.* 🎯

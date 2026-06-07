# 50-Day FAANG Plan 

A self-contained, interactive study plan for FAANG-level software engineering interviews. Everything lives in a single HTML file — no build step, no dependencies, no server required.

**[Open the plan →](50-day-plan.html)**

---

## Overview

This is a structured **50-day curriculum** (~3 hours/day) covering:

| Area | Coverage |
|------|----------|
| **Language** | Java — LeetCode, concurrency, Spring Boot, JDBC/JPA |
| **DSA** | ~240 LeetCode problems · 55 patterns with Java snippets |
| **System Design** | 20 backend patterns · 6 FAANG-specific HLD cases |
| **SQL / DBMS** | 50+ SQL problems · JDBC, indexing, normalization |
| **Companies** | Meta · Amazon · Apple · Netflix · Google roadmaps |
| **Interview Q&A** | 62 oral questions (Java, DSA, Spring, JVM, SD) |

Target level: **L3 / E3 / SDE1** and equivalent mid-level backend roles.

---

## Quick Start

### Local

1. Clone or download this repository.
2. Open `50-day-plan.html` in any modern browser (Chrome, Firefox, Safari, Edge).

```bash
# macOS
open 50-day-plan.html

# Linux
xdg-open 50-day-plan.html

# Windows
start 50-day-plan.html
```
---

## Daily Schedule (3 hours)

| Block | Time | Focus |
|-------|------|-------|
| Learn | 60 min | Java / JVM / Spring concepts |
| Code | 90 min | LeetCode + small projects (Java only) |
| Log | 15 min | Pattern recognition + mistake log |
| Review | 15 min | Spaced repetition of weak areas |

---

## 8-Week Curriculum

| Week | Days | Phase |
|------|------|-------|
| **1** | 1–7 | Java foundation — OOP, Collections, Streams, early DSA |
| **2** | 8–14 | DSA in Java I — linked lists, stacks, queues, sliding window |
| **3** | 15–21 | Trees & graphs — BFS, DFS, topological sort |
| **4** | 22–28 | DP & backtracking — memoization, tabulation |
| **5** | 29–35 | Java expert — concurrency, Spring Boot, SQL sprint (Day 34) |
| **6** | 36–42 | FAANG system design — Search, Feed, Checkout, Streaming, iCloud |
| **7** | 43–49 | Company sprints — one FAANG company per day + OA marathon |
| **8** | 50 | FAANG graduation — full loop mock (code + SQL + SD + behavioral) |

### Timeline at a Glance

```
Days  1–7    100% Java boot — OOP · Collections · Streams
Days  8–28   All DSA in Java — ListNode · ArrayDeque · HashMap
Days 29–35  Java Expert + SQL (Day 34) → Backend + SD data layer
Days 36–42  FAANG SD + database design → Schema in every HLD
Days 43–49  FAANG Company Sprint → Meta · AMZ · Apple · NFLX · GOOG
Day   50    FAANG Graduation Loop → Full interview simulation
```

---

## What's Inside the Page

### Weekly day cards
Each day includes learn/drill blocks, linked LeetCode problems, SQL tasks where relevant, and a clear **exit criteria** checklist. Mark days complete to track progress.

### FAANG company roadmaps
Per-company breakdowns for all five companies:
- Interview process and online assessment format
- DSA / Java / SD / behavioral priority ratings
- Must-do problem lists (with LeetCode links)
- Leadership principle / behavioral prompts
- Mapping to specific plan days

### DSA patterns (55)
Searchable pattern library with:
- Trigger phrases (“when you see this in a problem…”)
- Time/space complexity
- Copy-ready **Java** code templates
- Linked practice problems

### System design patterns (20)
Spring Boot–oriented backend patterns (caching, Kafka, sharding, rate limiting, etc.) plus a 45-minute HLD interview framework.

### DBMS & SQL
Normalization, ACID, indexing, SQL vs NoSQL trade-offs, JDBC/JPA notes, and 25+ SQL pattern references.

### Interview Q&A (62)
Oral-prep questions grouped by topic: production “why” questions, core Java, DSA, Web/Spring, system design, and JVM/server internals.

### Quick reference
Java collections cheat sheet, pattern recognition flowchart, Day 50 graduation checklist, and SQL quick reference — all on one scrollable page.

---

## Features

- **Progress tracking** — Check off completed days; progress is saved in `localStorage` (`expert50day_progress`).
- **Sidebar navigation** — Jump to any week, company, or resource section.
- **Expand / collapse** — Toolbar buttons to expand all days, companies, patterns, or interview Q&A at once.
- **Search** — Filter DSA and system design patterns by keyword.
- **Mobile-friendly** — Responsive layout with a slide-out navigation menu on small screens.
- **Dark theme** — Easy on the eyes for long study sessions.
- **Zero dependencies** — Single HTML file with embedded CSS and JavaScript.

---

## How to Use Effectively

1. **Start at Day 1** and follow the sequence — later weeks assume earlier Java and DSA foundations.
2. **Solve every problem in Java** on LeetCode (set language to Java before you start).
3. **Use the pattern sections** when stuck — match trigger phrases to the right template.
4. **Check exit criteria** at the end of each day before moving on.
5. **Week 7** — pick your target company and lean into that day's sprint.
6. **Day 50** — run the full 3-hour mock loop solo; use the graduation checklist in Quick Reference.

---

## Browser Support

Works in all modern browsers. Progress persistence requires JavaScript and `localStorage` enabled.

To reset progress, use the **Reset Progress** button in the page header (clears saved day completions).

---

## File

| File | Description |
|------|-------------|
| `50-day-plan.html` | Complete interactive plan (~3,000 lines, self-contained) |

No other files are required to run the plan.

---

## License

Free to use for personal interview preparation. If you fork or share, attribution is appreciated.

---

**Good luck with your FAANG prep. See you on Day 50.**

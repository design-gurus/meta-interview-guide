# The Meta Coding Interview

A Meta coding round lasts 45 minutes and is commonly reported to contain two problems. After introductions and questions, about 35 minutes remain, so each problem gets 15 to 20 minutes. The questions are well known, and the difficulty is the pace.

Candidates meet this format three times: once in the technical screen and twice in the full loop. The screen is sometimes reported with one problem plus a follow-up that adds a constraint.

## Format

| Item | Commonly reported detail |
|---|---|
| Length | 45 minutes per round |
| Problems | Two per round; one or two in the technical screen |
| Tool | CoderPad, a shared online editor; a whiteboard in some on-site loops |
| Language | Any mainstream language; most candidates choose Python because it is short to write |
| Difficulty | Mostly medium, with some easy and some hard questions |
| Follow-ups | A new constraint or a larger input after the first working solution |

## What is graded

Interviewers are reported to grade four things. The language you choose is not one of them.

| Signal | What the interviewer looks for |
|---|---|
| Problem solving | You restate the problem, ask about edge cases, and compare two approaches before coding |
| Coding | Correct, readable code written at speed, with sensible names |
| Verification | You trace one example through the code and find your own bugs |
| Communication | You explain each step aloud and use hints when they are offered |

An edge case is an unusual input, such as an empty array or a single node. State the time and space complexity of the final solution without being asked. Complexity is the growth of running time or memory as the input grows, written in Big O notation.

## Topics and patterns commonly reported

A pattern is a reusable approach that solves a whole family of problems. Recognizing the pattern in the first two minutes is what makes two problems possible.

| Pattern or topic | Example problem | Where to learn it |
|---|---|---|
| Matrix traversal | [Diagonal Traverse](https://www.designgurus.io/course-play/grokking-meta-coding-interview/doc/diagonal-traverse-medium?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=coding-interview) | Grokking the Meta Coding Interview |
| Sliding window | [Minimum Window Substring](https://www.designgurus.io/course-play/grokking-meta-coding-interview/doc/minimum-window-substring-hard?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=coding-interview) | [Introduction to the sliding window pattern](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/introduction-to-sliding-window-pattern?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=coding-interview) |
| Tree breadth-first search | [Binary Tree Vertical Order Traversal](https://www.designgurus.io/course-play/grokking-meta-coding-interview/doc/binary-tree-vertical-order-traversal-medium?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=coding-interview) | [Introduction to tree breadth-first search](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/introduction-to-tree-breadth-first-search-pattern?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=coding-interview) |
| Merge intervals | [Merge Intervals](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/merge-intervals-medium?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=coding-interview) | [Introduction to the merge intervals pattern](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/introduction-to-merge-intervals-pattern?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=coding-interview) |
| Two heaps | [Sliding Window Median](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/sliding-window-median-hard?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=coding-interview) | [Introduction to the two heaps pattern](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/introduction-to-two-heaps-pattern?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=coding-interview) |
| K-way merge | [Merge K Sorted Lists](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/merge-k-sorted-lists-medium?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=coding-interview) | [Introduction to the K-way merge pattern](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/introduction-to-kway-merge-pattern?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=coding-interview) |
| Islands in a grid | [Shortest Path in Binary Matrix](https://www.designgurus.io/course-play/grokking-meta-coding-interview/doc/shortest-path-in-binary-matrix-medium?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=coding-interview) | [Introduction to the island pattern](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/introduction-to-island-pattern?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=coding-interview) |
| Monotonic stack | [Buildings With an Ocean View](https://www.designgurus.io/course-play/grokking-meta-coding-interview/doc/buildings-with-an-ocean-view-medium?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=coding-interview) | [Introduction to the monotonic stack](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/introduction-to-monotonic-stack?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=coding-interview) |
| Topological sort | [Alien Dictionary](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/alien-dictionary-hard?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=coding-interview) | Grokking the Coding Interview |

Arrays, strings, linked lists, trees, and graphs account for most reports. Recursion and dynamic programming also appear.

## A time budget for one problem

| Minutes | Activity |
|---|---|
| 0 to 2 | Restate the problem, ask two questions, and give one example |
| 2 to 4 | Name the approach and its complexity, and get agreement |
| 4 to 13 | Write the code while explaining it |
| 13 to 16 | Trace an example, fix bugs, and state the complexity |
| 16 to 18 | Answer the follow-up question |

## How to practice

1. Learn the nine patterns in the table before solving many problems. Twenty problems understood well are worth more than 200 problems seen once.
2. Time every session. Solve two medium problems in 35 minutes, in an editor without automatic completion.
3. Speak aloud during practice, because silent solving does not train the graded skill.
4. Test by hand. Trace one normal input and one edge case before you say that the code is finished.
5. Repeat a failed problem after three days, without looking at the solution.

The [question bank](question-bank.md) lists 31 coding problems with lesson links. The [four-week plan](four-week-plan.md) places them on a schedule.

## Go deeper

- [Grokking the Meta Coding Interview](https://www.designgurus.io/course/grokking-meta-coding-interview?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=coding-interview): the problems Meta is reported to ask, each with a worked solution.
- [Grokking the Coding Interview](https://www.designgurus.io/course/grokking-the-coding-interview?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=coding-interview): the patterns behind those problems.
- Lesson: [Custom Sort String](https://www.designgurus.io/course-play/grokking-meta-coding-interview/doc/custom-sort-string-medium?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=coding-interview), in Grokking the Meta Coding Interview
- Lesson: [Maximum Swap](https://www.designgurus.io/course-play/grokking-meta-coding-interview/doc/maximum-swap-medium?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=coding-interview), in Grokking the Meta Coding Interview
- Free article: [Top 20 coding questions to pass the Meta interview](https://www.designgurus.io/blog/top-20-coding-questions-to-pass-meta-interview?utm_source=github&utm_medium=repo&utm_campaign=meta-interview-guide&utm_content=coding-interview)
- Free guide: [Grokking Coding Interview on GitHub](https://github.com/design-gurus/grokking-coding-interview)

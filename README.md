# python-problem-solving

Python problem-solving practice, with documented approaches, tests, and lessons learned.

This repo follows a one-month plan that started on 30 October 2026: ten LeetCode problems, then a small Django + PostgreSQL lab. Each problem gets an honest attempt. A solved problem is not proof that I can solve it again without help, so help and tests are recorded separately.

## Progress

| ID  | Problem | Level | Focus | Status | Help | Log |
| --- | ------- | ----- | ----- | ------ | ---- | --- |
| P1  | [Group Anagrams](https://leetcode.com/problems/group-anagrams/) | Medium | Dictionaries and grouping | Solved | Python docs, AI guidance | [P1 log](logs/P1-group-anagrams.md) |
| P2  | [3Sum](https://leetcode.com/problems/3sum/) | Medium | Sorting, two pointers, duplicates | Not started | | |
| P3  | [Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/) | Medium | Prefix sums and counts | Not started | | |
| P4  | [Merge Intervals](https://leetcode.com/problems/merge-intervals/) | Medium | Sorting and boundaries | Not started | | |
| P5  | [Daily Temperatures](https://leetcode.com/problems/daily-temperatures/) | Medium | Monotonic stack | Not started | | |
| P6  | [Koko Eating Bananas](https://leetcode.com/problems/koko-eating-bananas/) | Medium | Binary search on feasible answers | Not started | | |
| P7  | [Number of Islands](https://leetcode.com/problems/number-of-islands/) | Medium | Graph traversal | Not started | | |
| P8  | [Coin Change](https://leetcode.com/problems/coin-change/) | Medium | Dynamic programming | Not started | | |
| P9  | [Merge k Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/) | Hard | Heaps and linked lists | Not started | | |
| P10 | [Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/) | Hard | Sliding window and frequency counts | Not started | | |

Difficulty labels are LeetCode's.

## Schedule

Four 90-minute sessions a week, plus an optional 45-minute review for unfinished work or re-solves.

| Week | Session 1 | Session 2 | Session 3 | Session 4 |
| ---- | --------- | --------- | --------- | --------- |
| 1 | P1 | P2 | P3 | P4 |
| 2 | P5 | P6 | P7 | P8 |
| 3 | P9 (hard) | P10 (hard) | Django + PostgreSQL setup, models, migrations | DRF job list/detail API |
| 4 | SQL joins and skill counts | Validated staff-only create endpoint + tests | System design discussion using the API | Delayed closed-book re-solve + backend demo + review |

## How I work on each problem

1. Tablet: restate the task, trace examples, sketch a simple approach.
2. Code in LeetCode's editor, using the Python documentation for language questions.
3. Test and debug. If I'm stuck for 15 to 20 minutes, I ask for one hint.
4. Explain the reasoning and the time and space cost in my own words.
5. Write a short log and pick the next review.

## Status and help

- **Attempted:** I wrote an actual attempt.
- **Solved:** working code with test evidence, possibly with help.
- **Retained:** solved again about a week later with no AI, notes or documentation, with tests and an explanation.

Help is recorded as: none, Python docs, AI hint, or worked solution.

## Log template

```markdown
Problem / link:
Date / minutes:
Status: Attempted | Solved | Retained
Help: None | Python docs | AI hint | Worked solution
First idea and why:
What failed / counterexample:
What changed and why:
Tests / result:
Time and space complexity / reasoning:
Code link / tablet sketch:
Next review or action:
```

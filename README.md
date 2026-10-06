# LeetCode

My solutions to LeetCode problems in SQL and Python, as part of a 12-week data engineering study plan. Every solution has a short note on the main idea and why it works.

## Structure

```
leetcode/
  sql/      0178-rank-scores.sql
  python/   0049-group-anagrams.py
```

Files are named `<problem number, 4 digits>-<slug>.<ext>`.

## Solution format

Each file starts with a header comment:

```
-- 178. Rank Scores · Medium · https://leetcode.com/problems/rank-scores/
-- Idea: DENSE_RANK() over score desc — ties share a rank, no gaps.
-- Revisit: no
```

`Revisit: yes` marks a problem I couldn't solve without help. I solve it again from scratch a few days later.

## Progress

| Track | Focus | Solved |
| --- | --- | --- |
| SQL | Window functions, CTEs, time series, cohorts | 0 |
| Python | Hashing, arrays, strings, intervals, stacks | 0 |

Daily log: [`../LOG.md`](../LOG.md)

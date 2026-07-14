# Danny's Diner — SQL Case Study

Case Study #1 of [Danny Ma's 8 Week SQL Challenge](https://8weeksqlchallenge.com/case-study-1/):
a small restaurant wants to use its sales data to understand customer visiting patterns,
spend, and menu favourites, and to evaluate its loyalty program.

## Files

| File | What it is |
|---|---|
| [`schema.sql`](schema.sql) | Creates the `diner` schema and the three tables (`sales`, `menu`, `members`) with seed data |
| [`questions.md`](questions.md) | The case-study questions (customer spend, visit frequency, first/most-popular items, membership effects, loyalty points) |
| [`solutions.xlsx`](solutions.xlsx) | Worked answers, one sheet per question |
| [`data/`](data/) | The three tables as CSVs for use outside SQL |

## Skills demonstrated

- Multi-table JOINs across facts (`sales`) and dimensions (`menu`, `members`)
- Aggregation and grouping: totals, counts, per-customer breakdowns
- Ranking and first/last-event questions (top items, first purchase after membership)
- Conditional logic for business rules (loyalty points with multipliers and bonus windows)

## Run it

```sql
-- MySQL
SOURCE schema.sql;
-- then work through questions.md
```

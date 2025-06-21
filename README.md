# LeetCode 601. Human Traffic of Stadium

## Problem

Given a Stadium table, return all the rows where there are 3 or more consecutive entries (by increasing id) where the number of people is >= 100.

## SQL Schema

```sql
CREATE TABLE Stadium (
  id INT,
  visit_date DATE,
  people INT
);

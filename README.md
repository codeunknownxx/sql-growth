# sql-growth

> A hands-on SQL lab for growth marketing, on a reproducible synthetic dataset.

## What it is

A small **SQLite database of paid-media campaigns** (Google Search, PMax, Meta,
LinkedIn, YouTube) and lessons that answer the questions a marketing manager
actually asks — "which days did this campaign overspend?", "what is the cost
per lead by channel?".

All data is **100% synthetic**: a generator with a fixed random seed creates the
same 7 campaigns and 644 daily rows (spend, impressions, clicks, leads, sales)
every time. No real client data.

## Why

I'm moving into data and AI roles. Practicing SQL on realistic marketing
metrics is closer to the job than toy datasets — and generating the data myself
keeps it legal and shareable.

## Stack

SQL (SQLite) · Python standard library only (`sqlite3`, `random`) — no
dependencies.

## What I learned

- Writing SQL to answer business questions instead of syntax drills.
- Generating realistic synthetic data with a fixed seed, so results are
  reproducible and safe to share.

## Status

Learning in public: lesson 01 (`SELECT`, `WHERE`, `ORDER BY`) so far; next
lessons cover aggregations, `JOIN`s and window functions.

## Source code

The source code is private. It is available on request for hiring processes —
reach me through my GitHub profile.

---

🇧🇷 Laboratório de SQL para growth marketing com dados 100% fictícios.

© 2026 Felipe Mendes. All rights reserved.

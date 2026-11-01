# HackerTube 可订阅版（非官方）

HackerTube (by Andrej Karpathy) has no accounts and no subscription feature.
This repo turns its **open data export** (2026-10-31, ODC-By 1.0 — credit
HackerTube and the open-index/hacker-news dataset) into subscribable RSS feeds.

Site: https://domijin.github.io/HackerTube/

## Feeds
- `feeds/weekly.xml` — five durably recommended talks per week, weeks 1–26 (130 items)
- `feeds/weekly-2.xml` — weeks 27–52 (130 items)
- `feeds/top.xml` — Top 200 overall
- `feeds/area-*.xml` — Top 80 in each of the 16 topic areas

The catalog is a static 2007–2026 snapshot; the official site has announced
no update schedule, so these feeds are a fixed curated collection. Every item
links to the original YouTube video with HN's reasons and stats.

Unofficial wrapper; not affiliated with HackerTube, YouTube, or Y Combinator.

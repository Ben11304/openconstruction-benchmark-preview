# OpenConstruction — Benchmark Preview

Static preview of the OpenConstruction **benchmark** pages with results populated, for review before merging into the official site.

Only the benchmark flow is included (landing, task, application, results) plus the shared styles/scripts they need. Other site pages are intentionally left out, so top-nav links to them will not resolve here.

## Live pages

- `benchmarks.html` — Benchmarks landing / Task index
- `benchmark_task.html?key=<task>` — datasets and models for a task label
- `benchmark_results.html?id=<board-id>` — full results table and comparison chart for one board

## Data

- `data/benchmark-results.json` — 61 boards, 279 reported results, compiled from published papers and public leaderboards.
- `data/datasets.json` — minimal dataset index derived from the boards (so the landing shows task tiles).
- `data/models.json`, `data/task-vocabulary.json` — placeholder stubs.

The benchmark JSON is intended to be merged into the official data repo (`ruoxinx/open-construction-data`); the deploy pipeline copies it into `site/data/`.

---
pretty_name: "Meridian Exec-Trace (Raw)"
license: other
language:
  - en
tags:
  - execution-traces
  - tool-use
configs:
  - config_name: default
    data_files: data/*.parquet
---

# Meridian Exec-Trace (Raw)

Raw execution traces captured from customer sandbox runs: one record per
full program execution, including every tool call, intermediate output and
exit code.

## Provenance

Upstream corpus is assigned per renewal cycle.  See the operations
repository for the current licence review.

## Files

- `data/train-00001-of-00002.parquet`
- `data/train-00002-of-00002.parquet`

## Maintenance

Rebuilt monthly from the upstream snapshot; the schema is stable across
releases.

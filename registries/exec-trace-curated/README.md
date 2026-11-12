---
pretty_name: "Meridian Exec-Trace (Curated)"
license: other
language:
  - en
tags:
  - execution-traces
  - curated
configs:
  - config_name: default
    data_files: data/*.parquet
---

# Meridian Exec-Trace (Curated)

Curated execution traces: noisy records removed, tool arguments
normalised, and exit codes mapped to a stable taxonomy.

## Curation rules

1. Drop runs shorter than three tool calls.
2. Remove customer-identifying paths and hostnames.
3. Keep the final assistant message verbatim.

## Files

- `data/train-00001-of-00001.parquet`

**License**

The license for this dataset is cc-by-sa-4.0.

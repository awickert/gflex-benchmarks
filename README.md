# gFlex Benchmarks

Benchmark timing results for [gFlex](https://github.com/awickert/gFlex) solver
runs, organized by machine.

## Layout

```
results/
  {hostname}/
    {short_commit}_{UTC_timestamp}.txt
```

Each file records the git commit hash, branch, and hardware/software
details at the top, followed by timing tables for all solvers and grid sizes.

## Running benchmarks

From the gFlex repo root:

```bash
python benchmarks/bench_solvers.py
```

Results are saved locally to `benchmarks/results/` and pushed here automatically.

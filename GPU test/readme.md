# Enable GPU acceleration for XGBoost

## Changes in code
- New parameter added: `tree_method` = `'gpu_hist'`.
- Parameter deleted: n_jobs.

## PC performance
CPU runs at full speed. GPU 1 runs at full speed on `compute 0` unit.

## Results
- With acceleration off, the script ran for too long (avg. 10 min per iteration); but with it on, the script ran for 1 iteration in 2 min and then exit (no exception raised).

## Problem
- It's still to be determined whether the GPU-accelerated script have completed the modeling process.

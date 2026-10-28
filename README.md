# Quant ML Challenge

My entry for the [Wunder Fund Alpha Connectome](https://wundernn.io/connectome) machine-learning competition.

## The task

Predict two targets, the future price moves of one instrument, from a stream of 112 order-book and trade features, one row at a time. Entries are scored by weighted Pearson correlation on a hidden test set.

The scoring environment is tight: one CPU core, no GPU, 16 GB of RAM, an hour for roughly 39 million rows, a 20 MB upload and no internet, and the model has to be deterministic.

## Status

The competition runs until 15 November 2026, and its rules do not allow sharing code, models or strategy before it ends. The code and a write-up of the approach will be published here after that.

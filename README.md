# Kaggle Blueprints: Time Series

A workspace for time-series forecasting references and future notebook blueprints.

## Current contents

The current branch contains this README and [Useful Links.txt](Useful%20Links.txt), a collection of references on tabular-data performance, memory optimization, Keras, and PyCaret.

Forecasting notebooks, datasets, dependency manifests, and trained models are not included yet. There is no runnable forecasting pipeline in this repository.

## Related implementation

For an existing notebook covering tabular classification experiments, explore [Kaggle-Blueprints](https://github.com/ataturhan21/Kaggle-Blueprints). It is a separate project and does not establish a time-series evaluation workflow.

## Adding a forecasting blueprint

Each future notebook should document its dataset, target, forecast horizon, chronological training/validation/test boundaries, baseline, metric, and environment. Fit preprocessing on the training period and evaluate on later observations so the reported result represents a forward forecast.

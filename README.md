# Kaggle Blueprints: Time Series

A workspace for time-series forecasting references and future notebook blueprints.

## Current contents

The current branch contains this README and its reference list on tabular-data performance, memory optimization, Keras, and PyCaret.

Forecasting notebooks, datasets, dependency manifests, and trained models are not included yet. There is no runnable forecasting pipeline in this repository.

## References

- [Never worry about optimization: process GBs of tabular data 25x faster with no-code pandas](https://towardsdatascience.com/never-worry-about-optimization-process-gbs-of-tabular-data-25x-faster-with-no-code-pandas-e85ede4c37d5)
- [Seven killer memory optimization techniques every pandas user should know](https://towardsdatascience.com/seven-killer-memory-optimization-techniques-every-pandas-user-should-know-64707348ab20)
- [Building complex deep learning models using the Keras functional API](https://pub.towardsai.net/building-complex-deep-learning-models-using-keras-functional-api-38090f4769a4)
- [Scaling PyCaret with Spark or Dask through Fugue](https://towardsdatascience.com/scaling-pycaret-with-spark-or-dask-through-fugue-60bdc3ce133f)
- [PyCaret review](https://towardsdatascience.com/pycaret-review-65cbe2f663bb)

## Earlier Migros notebooks

This repository previously held Migros datathon notebooks (`Migros.ipynb`, `Migros-Catboost.ipynb`, `Migros-Final.ipynb`) with their logs and submission files. They were removed in commit 4b01801 and remain available in the history at commit [ffc79f3](https://github.com/ataturhan21/Kaggle-Blueprints-Time-Series/tree/ffc79f3565af76e9e4c551370be4126e4f222ca9).

## Related implementation

For an existing notebook covering tabular classification experiments, explore [Kaggle-Blueprints](https://github.com/ataturhan21/Kaggle-Blueprints). It is a separate project and does not establish a time-series evaluation workflow.

## Adding a forecasting blueprint

Each future notebook should document its dataset, target, forecast horizon, chronological training/validation/test boundaries, baseline, metric, and environment. Fit preprocessing on the training period and evaluate on later observations so the reported result represents a forward forecast.

## License

[MIT](LICENSE).

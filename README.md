<a href="https://github.com/haghish/fair"><img src='man/figures/logo.PNG' align="right" height="200" /></a>

`fair` : Machine Learning Fairness and Classification Parity Assessment
===============================================================================

**`fair`** provides a set of functions for evaluating classification parity, not only for general classification models, but also for classification models of severely imbalanced outcome. 

The package allows comparing different classification groups based on a variety of metrics, used for balanced or imbalanced data. The supported metrics are:

| **Metric** | **Description**                                                                   |
|------------|-----------------------------------------------------------------------------------|
| `AUC`      | Area Under Curve, used for balanced data                                          |
| `F1`       | F-Measure, used for balanced data                                                 |
| `Fpoint5`  | F-Measure, Used for putting more weight on specificity                            |
| `AUCPR`    | Area Under Precision-Recall Curve, used for evaluating imbalanced data            |
| `F2`       | F-Measure, used for evaluating imbalanced data                                    |
| `MCC`      | matthews correlation coefficient, used for evaluating imbalanced data             |
| `MPCE`     | Mean Per Class Error, used for evaluating classification problems in a fairer way |




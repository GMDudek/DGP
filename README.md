# Data for the following paper
Orzeszko W., Pełka P., Dudek G.: Matching Forecasting Models to Data-Generating Processes: Evidence from Monte Carlo Simulations

Abstract:
This study compares the forecasting performance of statistical, machine-learning, and neural models across 17 data-generating processes in a comprehensive Monte Carlo study to investigate how the characteristics of the underlying data-generating process and sample size influence their relative forecasting performance. The considered processes include chaotic, linear, long-memory, nonlinear-in-mean, conditionally heteroskedastic, and GARCH-in-mean dynamics. Twelve forecasting methods are evaluated for short and long time series using MSE, MAE, out-of-sample \(R^2\), the Model Confidence Set procedure, and Diebold--Mariano tests. The results show that no single method dominates across all DGPs. Linear models perform strongly for linear processes, whereas SVR-RBF, RF, and LGBM are generally most effective for nonlinear stochastic dynamics. N-BEATS performs exceptionally well for the deterministic logistic map, but its advantage weakens in the presence of noise. Complex neural architectures often underperform simpler alternatives, particularly in small-sample, univariate, one-step-ahead settings. The findings demonstrate that forecasting performance depends critically on aligning model inductive bias and complexity with the structural characteristics of the underlying data-generating process and the available sample size.

Research highlights

- Forecast accuracy depends on DGP structure, model bias, and sample size.

- Conditional-mean nonlinearity is easier to exploit than variance nonlinearity.

- SVR-RBF and tree ensembles perform best for nonlinear stochastic processes.

- Linear models remain highly competitive for linear data-generating processes.

- Complex neural models often underperform in local, small-sample settings.

Keywords

Machine learning, Time-series forecasting, Data-generating processes, Monte Carlo simulation

**Abstract**

Spatial analysis is a powerful approach used to understand patterns,
relationships, and variations across geographic space. While Gaussian
Process Regression (GPR) offers flexibility in modeling complex spatial
structures, it remains underutilized in spatial analysis. This study introduces
an integrated framework that combines GPR with Bayesian Model Averaging
(BMA) to improve predictive accuracy and model stability in spatial data
analysis. Using the Boston Housing dataset, multiple GPR models with
varying predictor combinations were generated to address model uncertainty,
guided by Bayesian Information Criterion (BIC), Scaled Prior BIC (SPBIC),
and Maximum A Posteriori (MAP) probability.
The proposed GPR-BMA framework applies Bayesian techniques to
compute posterior model probabilities and generate weighted predictions,
mitigating the risk of suboptimal model selection. Results showed that
GPR-BMA outperformed standalone GPR in terms of predictive accuracy, as
evaluated by Root Mean Squared Error (RMSE). However, Geographically
Weighted Regression (GWR) still yielded the best performance among the
methods compared. This study demonstrates the practical benefits of
integrating BMA with GPR in spatial modeling and contributes to the
expanding literature on Bayesian methods in spatial data analysis.

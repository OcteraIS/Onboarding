Replication and reproducibility are very important but most important is to get accurate, true results.

# ML Projects
Taken from https://doi.org/10.1186/s13040-017-0155-3 

ML is useful when we have a lot of data and a fairly easy to understand, well determined labeling approach. It works well when our task is less about "why" and more about "what".

1. Check and arrange your input dataset properly
2. Split data into test/train/validate. Test is only used at the very end.
3. Start with simple algs before deep learning.
4. Balance data using weighting, under-sampling, collecting more data.
5. Use hyperparameter optimization 
6. Minimize over-fitting with regularization
7. Carefully select performance measures. Likely MCC or AUC is the one to go for. But in some software applications, we might prefer high recall or high precision.
8. Commit all code and analysis to git / Github 

Chakkrit has a [useful series of pitfalls](http://chakkrit.com/assets/papers/tantithamthavorn2018pitfalls.pdf) to be aware of:
1. Testing hypotheses without including control metrics.
2. Failure to deal with correlated metrics when interpreting models
3. Class rebalancing techniques improve model performance
4. Not experimenting with different learners and using default parameter values for learners
5. Using threshold-dependent performance measures (e.g, F-measure) to measure the performance of a model
6. Using 10-folds cross-validation for model validation
7. Using ANOVA Type-I when interpreting a model 
8. Interpreting a model using the coeffcients of the variables
 
# Bayesian Analysis
Bayesian analysis does well when we have small datasets, and some prior knowledge about what the data should be modeled as (e.g. we suspect a normal distribution). It works well when we need the "why" because it produces an explicit model for decision analysis.


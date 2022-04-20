# dcnl_ml_predicting_detox_outcomes



### Code used for the analysis in Paper: XXX

### DOI: XXX



### Summary of contents:

`divide_test_and_training.ipynb` - Code used for cleaning up the data, create outcomes based on percentiles, and separata training vs test dataset (80/20 Split).

`analysis_feature_selection_30_70.ipynb` - Code used to select features for downstream analysis.

`hyperparameter_tuning.ipynb` - Code used for hyperparameter tunning of the 6 classifiers we picked.

`cross_validation_comparison.ipynb` - Code used for comparing the top model for each classifier using 20X 5-Fold Cross Validation on the Training Dataset.

`cross_validation_comparison_NO_CSSA1.ipynb` - Same code as above, but excluding the CSSA1 variable from the analysis. We wanted to see how the models would perform without the strongest predictive variable.

`model_testing.ipynb` - Comparison of models using the test dataset.

 `model_testing_NO_CSSA1.ipynb` - Same as above but removing CSSA1 variable. Models were refit on training data without CSSA1 variable before being used to predict test dataset outcomes.
 
 `SHAP_analysis_KNN_Model.ipynb` - Generation of SHAP graphs for model explainability using the test dataset. Only the best classifier was included in this analysis: KNN.
 
 `SHAP_analysis_KNN_Model_NO_CSSA1.ipynb` - Same as above but without CSSA1 variable.
 
 `SHAP_analysis_Logistic_Regression_Model_NO_CSSA1.ipynb` - Same as above but without CSSA1 variable and for logistic regression model.




#  Plot Outputs for Parkinson's Disease Detection

This folder contains visualizations generated during training and evaluation of machine learning models applied to the PC-GITA dataset for Parkinson's disease detection.

##  Contents

Each file corresponds to a specific fold or model configuration and provides insights into model performance:

###  Confusion Matrices
- `conf_matrix_fold{N}_{model_id}.png`: 
  Shows the confusion matrix for a specific fold `N` and model configuration. It visualizes how well the classifier distinguishes between Healthy Control (HC) and Parkinson's Disease (PD) samples.

###  ROC Curves
- `roc_curves_{model_id}.png`:  
  Receiver Operating Characteristic (ROC) curves for all validation folds under a specific model configuration. AUC scores are included in the legend for each fold.

###  Bar Plots
- `barplot_{model_id}.png`:  
  Displays per-fold metrics such as Accuracy, Sensitivity, Specificity, and AUC, offering a compact view of model performance across folds.

###  Training Metrics (for deep models like LSTM)
- `metrics_fold{N}.png`:  
  Loss and validation accuracy over epochs for fold `N`. Useful for checking convergence and overfitting.

###  SHAP or Feature Importance (if applicable)
- `shap_summary_fold{N}.png`:  
  SHAP-based feature interpretability (for classical models like Logistic Regression).
- `xgb_feature_importance.png`:  
  Top 15 most influential features from XGBoost based on average importance across folds.

##  Notes
- Fold indices and model identifiers (`model_id`) are included in file names for clarity.
- All plots are saved at `dpi=300` for publication-quality visuals.
- These figures are referenced in the Results and Discussion chapters of the thesis.


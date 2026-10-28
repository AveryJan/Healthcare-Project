Notebook	Verified task and methods	Verified evaluation or outputs
Assignment One	Decision tree classifying hospitalization billing ≥$25,000 using eight demographic, clinical, insurance, and stay variables; one-hot encoding; stratified 70/30 split.	50.64% accuracy, below the 51.18% majority-class baseline. Includes confusion matrix, classification report, tree rules, and feature importance.
Assignment Two	Random forests comparing 10–200 trees on the same classification task.	Final 100-tree model: 56.20% accuracy, 5.02 percentage points above baseline. Age and length of stay had the highest feature importance.
Assignment Three	Billing-amount regression using standardized predictors and LASSO with 10-fold cross-validation.	RMSE $14,213.74; R² approximately 0. All 34 encoded predictor coefficients were shrunk to zero.
Assignment Four	K-means on standardized age, billing amount, and length of stay; inertia and sampled silhouette comparisons.	Four-cluster model with cluster profiles and visualizations. Saved silhouette: 0.2620 for K=4, versus 0.2689 for K=5.

Healthcare Billing Analytics | Python, pandas, NumPy, scikit-learn, Matplotlib, Jupyter

Analyzed 55,392 hospitalization records after cleaning to explore high-billing classification, billing-amount prediction, and patient segmentation. Engineered length of stay, encoded categorical features, and applied decision trees, random forests, 10-fold cross-validated LASSO, and K-means. The final random forest achieved 56.20% accuracy against a 51.18% baseline; LASSO achieved RMSE $14,213.74 and R² near zero. Demonstrates data preparation, feature engineering, model comparison, visualization, and critical interpretation. Results are exploratory, with limited predictive performance and no demonstrated clinical validation.

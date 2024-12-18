# prediction_task


## Code Organization
All codes are written in `python`. 

### Code 
The script to reproduce all the figures, and tables in the paper is as follows:
- `Feature.ipynb`: data processing and feature engineering
- `PCA.ipynb`: PCA analysis
- `roc_analysis_weak_ml_classifier.py`: training setting search and ROC analysis for 
     - Decision Tree (DT)  
     - Random Forest (RF)  
     - Logistic Regression (LR)  
     - Naive Bayes (NB)  
     - K-Nearest Neighbors (KNN)  
     - Gradient Boosting (GB)  
     - Voting Classifiers (DT+LR+RF and KNN+LR+RF)
- `roc_analysis_lasso.py`: training setting search and ROC analysis for the LASSO model.
- `roc_analysis_mlp.py`: training setting search and ROC analysis for the MLP model.
- `roc_analysis_lstm.py`: training setting search and ROC analysis for the LSTM model.
- `roc_analysis_kan.py`: training setting search and ROC analysis for the Kolmogorov-Arnold Network (KAN).

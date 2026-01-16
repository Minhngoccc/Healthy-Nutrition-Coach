PHASE 1: Data Preparation
├── data_preparation.ipynb
└── → processed_data_v2.csv (6,761 món ăn)
         ↓
PHASE 2: NRF9.3 Scoring  
├── nrf9.3_scoring.ipynb
└── → labeled_data_final.csv (với labels Good/Medium/Bad)
         ↓
PHASE 3: Feature Analysis
├── feature_analysis.ipynb
├── → Pearson/Spearman Correlation Heatmaps
└── → PCA Visualization
         ↓
PHASE 4: Model Training (2 models song song)
├── logistic_regression.ipynb → Coefficients, Odds Ratio
└── random_forest.ipynb → Feature Importance
         ↓
PHASE 5: SHAP Analysis
├── shap_analysis.ipynb
└── → So sánh SHAP giữa 2 models
         ↓
PHASE 6: Results
└── Final Report

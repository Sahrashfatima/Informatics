# Informatics
This research project explores the relationships between hemodialysis frequency and various patient factors including demographics, comorbidities, CKD severity, lab parameters, and other clinical attributes. We employed both statistical and machine learning methods to test hypotheses and predict dialysis needs, ultimately supporting clinical decision-making in the management of ESRD (End-Stage Renal Disease).
🎯 Objectives
	•	Develop a predictive model using SQL-stored patient data from a real-time hospital dataset (Kaggle).
	•	Analyze correlations and test hypotheses around dialysis frequency using statistical and ML techniques.
	•	Design a reproducible, modular pipeline in Python for:
	•	  Data preprocessing
	•   Visualization
	•	  Statistical testing
	• 	Machine learning classification
 📈 Data Science & Machine Learning
	•	SQL-based data extraction and cleansing using MySQL and Python (MySQLdb).
	•	Applied:
	•	Statistical testing (Shapiro-Wilk, Chi-Square, Mann-Whitney U, Spearman correlation)
	•	Visualization tools (heatmaps, scatter plots, bar charts using matplotlib & seaborn)
	•	ML algorithms:
	•	 Logistic Regression
	•	 Random Forest Classifier
	•	 Gradient Boosting Classifier
	•	 Model tuning via Grid Search
	•	 ROC curve analysis and evaluation metrics (accuracy, CV)
📊 Computational Complexity
	•	Compared model performance and computational trade-offs across algorithms.
	•	Evaluated overfitting risks and handled potential class imbalance in the target variable.
🧠 Applied Learning
	•	Integrated supervised learning to classify dialysis frequency.
	•	Demonstrated ability to handle non-parametric data and build models that generalize across real-world clinical variability.
 📁 Technologies Used
	•	Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
	•	MySQL / phpMyAdmin
	•	Jupyter Notebooks
	•	Kaggle Dataset: Hemodialysis Real-time Hospital Dataset
 ✅ Outcome
Despite extensive analysis, most patient variables did not significantly associate with hemodialysis frequency, except for Kt/V and hypertension. The model with the highest predictive performance was Gradient Boosting (Accuracy: ~36.5%), suggesting further research is needed with larger, more balanced datasets for improved generalizability.

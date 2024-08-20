# Diabeters-prediction-using-PIMA-dataset
Diabetes Mellitus, a chronic condition characterized by elevated blood sugar levels, poses significant public health challenges worldwide. To address this need, we developed a robust and accurate predictive model for diabetes using random forest classifier and advanced machine learning techniques. Our findings indicate that the use of  smote combined with advanced preprocessing and handling techniques, significantly enhances the robustness and accuracy of diabetes prediction models. The developed model demonstrates high predictive performance with a mean  accuracy of 97.9 % validated through rigorous evaluation metrics. This approach contributes to better disease management and improved patient outcomes, showcasing the potential of machine learning algorithms in addressing complex healthcare challenges.
# Methodology
The study focuses on feature engineering, exploratory data analysis, data preparation, and using a Random Forest classifier to increase prediction accuracy. To correct the class imbalance in the dataset, Synthetic Minority Over-sampling Technique (SMOTE) is also applied. This part will provide a thorough description of the techniques utilized to accomplish the research objectives by going into depth about the procedures involved in data preparation, visualization, model training, and evaluation. 
Type of Research
This study employs a quantitative research approach, focusing on the statistical analysis and machine learning techniques to predict diabetes outcomes based on a set of health metrics.
Research Strategy
The research strategy involves an experimental design where various data preprocessing steps       are applied, and the performance of different models is evaluated. The primary steps include:
Data Preprocessing: Handling missing values, visualizing data distributions, and applying transformations to clean and prepare the data for analysis.
Exploratory Data Analysis (EDA): Utilizing histograms, heatmaps, and pair plots to understand the relationships between features and identify potential correlations.
Feature Engineering: Selecting relevant features based on statistical analysis and domain knowledge, and filtering the data to improve model performance.
Model Training: Applying the Random Forest classifier to the prepared dataset and tuning the model parameters using cross-validation.
Addressing Class Imbalance: Implementing SMOTE to balance the dataset by generating synthetic samples for the minority class.
Model Evaluation: Evaluating the model’s performance using cross-validation scores and analyzing the results to determine the effectiveness of the approach.
This experimental strategy ensures a systematic and comprehensive examination of the factors influencing diabetes prediction and the efficacy of the chosen methodologies.

Data Sources
The dataset used in this study was sourced from Kaggle, specifically the Pima Indians Diabetes Database. This dataset is a secondary data source that has been made publicly available for research purposes. It contains several medical predictor variables and one target variable, Outcome, which indicates whether or not a patient has diabetes. The dataset can be accessed at [Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database).

Sampling Method
Since the dataset was pre-collected and made available as a complete dataset, no additional sampling was conducted for this research. The dataset comprises 768 observations, each representing an individual patient, with 8 feature variables and 1 target variable. 

# Results 
After implementing everything the model was evaluated. The performance metric used to analyze this model is accuracy. The model was executed several times and the mean of those accuracies was obtained. The mean accuracy is 97.7969348659003.
# Conclusion
In this paper, we have performed random forest classification over PIMA Indian Diabetes Dataset and used SMOTE (Synthetic Minority Over-sampling Technique) to rectify the imbalance in the dataset. Our model has achieved an accuracy of 97.79% which is one of the highest accuracies achieved for diabetes classification over PIMA dataset. 

# Future enhancement
This model can be further developed through building a mobile application by incorporating this algorithm into it, so that the user can give the input himself and predict his health status right away. This model should also be tested on a variety of datasets to see how it performs. It has to be tested on larger datasets. Model can be tested on different types of datasets like breast cancer dataset or brain tumor dataset etc. by making necessary changes in the code to check its flexibility.

#Youtube link 
https://www.youtube.com/watch?v=DqH4ijE6-gA

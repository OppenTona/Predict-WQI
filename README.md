**Abstract**
Machine learning has been extensively explored to decrease the number of parameters 
required for Water Quality Index management, with the aim of lowering monitoring cost 
and time. This study addresses several key gaps, including the absence of a standardized 
evaluation framework, limited use of WQI sub-indices as engineered features, and the 
lack of direct comparisons between machine learning models and reduced-parameter 
WQI formulations. The dataset comprised 1,110 records collected from 125 monitoring 
locations between 2021 and 2024 and included 16 water quality features. A total of five 
single models (Random Forest, Gradient Boosting, Linear Regression, K-Nearest 
Neighbors, and Support Vector Regression) were evaluated individually. These models 
were also used as base learners to construct 26 stacking models, representing all 
possible combinations. All models were evaluated using GridSearchCV with five-fold 
cross-validation. Four experimental scenarios were designed to compare raw inputs and 
WQI sub-indices as engineered features, before and after feature selection, reducing the 
input space from 16 to six parameters. Correlation analysis and permutation importance 
were applied to eliminate redundant and low-impact variables. For raw inputs, Gradient 
Boosting achieved the best performance (MSE = 8.53, R
2 = 0.95), while stacking models 
showed no meaningful improvement. In contrast, using WQI sub-indices substantially 
improved model performance, after feature selection, Support Vector Regression 
achieved the best result (MSE = 5.59, R
2 = 0.97). The best AI model outperformed the 
reduced-parameter WQI formula. Overall, the proposed framework enhances predictive 
efficiency, reduces monitoring burden, and provides a scalable reference for WQI 
prediction.

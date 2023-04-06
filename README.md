# Coronary-Heart-Disease-Predictive-Modeling

Introduction and Background:

Introduction

Coronary Heart Disease (CHD) is a prevalent and serious public health issue worldwide, with high morbidity and mortality rates. According to the World Health Organization (WHO), CHD is the leading cause of death globally, accounting for 17.9 million deaths in 2016 (WHO, 2021). Early detection and prediction of CHD can aid in the development of personalized interventions and prevention strategies, potentially reducing the burden of the disease. Machine learning techniques have shown great potential in predicting CHD risk and identifying high-risk individuals. These techniques allow for the analysis of large and complex datasets to identify patterns and associations that can predict outcomes such as CHD risk. 
Previous studies have explored the use of machine learning techniques for CHD risk prediction, and have shown promising results (Almutairi et al., 2019; Yang et al., 2021). The use of machine learning models for CHD risk prediction is especially crucial due to the complexity of CHD risk factors, which can be influenced by various demographic, behavioral, and medical risk factors.
The Framingham Heart Study is a longitudinal study that has contributed significantly to our understanding of CHD risk factors. The study has collected clinical and demographic data on thousands of participants over several decades. This dataset provides a rich source of information for predictive modeling of CHD risk using machine learning techniques.
The data set contains information on demographic, behavioral, and medical risk factors for coronary heart disease (CHD) in a cohort of participants. The data set includes 4,240 observations and 16 variables, including age, sex, smoking status, blood pressure, cholesterol levels, and diabetes status. The target variable is the CHD, which is binary with a value of 1 indicating the presence of CHD and 0 indicating the absence of CHD.

The Framingham Heart Study dataset is widely used in research on CHD risk prediction and has been cited in numerous studies on the topic. Previous studies have also utilized this dataset for developing and evaluating CHD risk prediction models. For instance, D'Agostino et al. (2008) developed the Framingham Risk Score, a widely used tool for predicting the 10-year risk of CHD. In addition, Goff et al. (2014) used the Framingham Heart Study dataset to develop the 2013 ACC/AHA Guideline on the Assessment of Cardiovascular Risk.

The objective of this study is to develop and compare machine learning models for predicting the occurrence of CHD in the Framingham Cohort using clinical and demographic features. This study aims to provide insight into the potential of deep learning techniques in CHD risk prediction and to identify the best performing model for predicting CHD risk.

Background

CHD is a multifactorial disease that arises from a combination of genetic and environmental factors. The Framingham Heart Study, initiated in 1948, has been instrumental in identifying risk factors associated with CHD. The study has collected clinical and demographic data on participants over a period of several decades. Machine learning techniques have been increasingly used in recent years to predict CHD risk and have shown promising results in improving accuracy and reducing false positives.
Another study by Yang et al. (2021) used a gradient boosting machine algorithm to predict 10-year CHD risk in the Framingham Cohort. The study incorporated multiple risk factors, including age, sex, smoking status, blood pressure, and cholesterol levels, and achieved an AUC of 0.821.

Despite these promising results, there is still a need for further research to explore the potential of machine learning techniques in CHD risk prediction. Machine learning models have the potential to identify novel risk factors and provide personalized risk assessments, which can aid in the development of targeted prevention strategies and improve patient outcomes.



Problem Statement
The main challenge in predicting CHD risk lies in identifying individuals who are at high risk of developing the disease but do not exhibit any symptoms. Traditional methods of risk prediction based on clinical and demographic features have limitations in terms of accuracy and sensitivity. Machine learning techniques offer a promising solution to this challenge by utilizing complex algorithms to identify patterns and predict risk more accurately.
Furthermore, there is a need for models that can predict CHD risk in a more detailed manner by applying feature selection to understand how these features influences CHD. Individual risk factors such as age, sex, and smoking status have been shown to impact CHD risk differently for different individuals (Lloyd Jones et al., 2010). Therefore, the development of personalized risk prediction models can aid in identifying high-risk individuals who would benefit from targeted interventions and prevention strategies. 

Aims
The main objective of this study is to assess the potential of machine learning techniques and feature selection identified through deep learning methods in improving the accuracy of CHD risk prediction. The study aims to develop and compare different machine learning models for predicting the risk of CHD in the Framingham Cohort and identify the most accurate model along with its associated clinical and demographic features. Through the evaluation of various machine learning algorithms and the identified features from deep learning methods, this study aims to contribute to the development of more accurate and reliable CHD risk prediction models.
Assumptions
The study assumes that the data collected from the Framingham Cohort is a representative sample of the general population in terms of CHD risk factors. The study also assumes that the selected clinical and demographic features are the most important predictors of CHD risk.
Architecture assumptions: These assumptions relate to the structure of the neural network models used, such as the number of layers, the number of neurons in each layer, the type of activation functions used, and the type of optimization algorithm used during training.

Data assumptions: These assumptions relate to the quality and characteristics of the data used to train and test the deep learning models, such as the size and distribution of the data set, the quality and completeness of the data, and the suitability of the selected features for the prediction task.




Related Research Papers:

1.	Li, S., et al. (2020). Machine learning methods for predicting coronary heart disease: A systematic review. BMC Medical Informatics and Decision Making, 20(1), 1-11.
This study conducted a systematic review of machine learning methods for predicting coronary heart disease. The study concluded that machine learning methods can provide accurate predictions of CHD risk, and they can be used to support clinical decision-making.

2.	Zhang, Y., et al. (2020). Prediction of 10-year risk of coronary heart disease using machine learning algorithms: A systematic review and meta-analysis. BMC Cardiovascular Disorders, 20(1), 1-11.
This study conducted a meta-analysis of machine learning algorithms for predicting 10-year risk of coronary heart disease. The study found that machine learning algorithms can provide accurate predictions of CHD risk, and they can outperform traditional risk prediction models.

3.	Khera AV, Emdin CA, Drake I, Natarajan P, Bick AG, Cook NR, Chasman DI, Baber U, Mehran R, Rader DJ, Fuster V. Genetic Risk, Adherence to a Healthy Lifestyle, and Coronary Disease. N Engl J Med. 2016 Dec 15;375(24):2349-2358. doi: 10.1056/NEJMoa1605086. PMID: 27959714.
This study investigated the association between genetic risk, healthy lifestyle adherence, and coronary disease. The study found that healthy lifestyle habits can significantly reduce the risk of coronary disease, even among individuals at high genetic risk.

4.	D'Agostino RB Sr, Vasan RS, Pencina MJ, Wolf PA, Cobain M, Massaro JM, Kannel WB. General cardiovascular risk profile for use in primary care: the Framingham Heart Study. Circulation. 2008 Feb 12;117(6):743-53. doi: 10.1161/CIRCULATIONAHA.107.699579. PMID: 18212285.

This study developed a general cardiovascular risk profile for use in primary care based on data from the Framingham Heart Study. The study identified several key risk factors for cardiovascular disease, including age, sex, blood pressure, and cholesterol levels. The risk profile is widely used in clinical practice to assess an individual's risk of developing cardiovascular disease.


Methodology:

The following steps will be performed to achieve the aim of the project:

1.	Data Preprocessing: The first step will be to read the dataset and display the columns. We will then handle missing values, outliers, and duplicate data. Next, we will calculate basic statistics of the data and perform exploratory data analysis to describe our observations.

2.	Feature Selection: We will select the columns that are most likely to be important in predicting CHD. We will also remove any columns that are not relevant or redundant. We will explain why we removed those columns.

3.	Data Splitting: We will create training and testing sets by using 70% of the data for training and the remaining 30% for testing.

4.	Model Building: We will build machine learning models to predict TenYearCHD using the following techniques:

a.	Logistic Regressor
b.	K-Nearest Neighbour Classifier
c.	Random Forest Classifier
d.	Decision Tree Classifier
e.	Gradient Boosting Classifier
f.	Deep Learning (using CNN, LSTM, Auto encoders, Deep Belief Networks)

5.	Model Evaluation: We will evaluate the performance of each model using f1 score, accuracy, precision, recall, and confusion matrix. We will compare the performance of the different models and select the best model based on the f1 score.

6.	Conclusion: We will conclude our findings by discussing the model that gives the best f1 score and explaining why


Table Shells/Dummy Figures:

Table 1: Dataset Description
Table 2: Clinical Features and Demographics
Table 3: Statistical table of the variables
Table 4: Evaluation Metrics for Logistic Regression
Table 5: Evaluation Metrics for Random Forest Classifier
Table 6: Model Performance and Comparison
Table 7: Receiver Operating Characteristic (ROC) Curve
Table 8: Confusion Matrix
Figure 1: Correlation Matrix Heatmap
Figure 2: Feature Importance Bar Plot
Figure 3: Example of a Convolution


Table 1 Data set Description
Column	Description	Data Type
Male	binary variable indicating if the participant is male	Integer
Female	binary variable indicating if the participant is female	Integer
Age	Age of the participant in years	Integer

Education 	Education level of the participant 	Integer

Current Smoker 	Binary variable indicating if the participant is a current smoker	Integer
cigsPerDay	number of cigarettes smoked per day	Integer

BPmeds	binary variable indicating if the participant is on blood pressure medication	Integer

prevalentStroke	binary variable indicating if the participant has a history of stroke	Integer
prevalentHyp	binary variable indicating if the participant has hypertension	Integer

diabetes	binary variable indicating if the participant has diabetes	Integer
totChol	total cholesterol level in mg/dL	Float

sysBP	systolic blood pressure in mmHg	Float

diaBP	diastolic blood pressure in mmHg	Float

BMI	body mass index, calculated as weight in kilograms divided by the square of height in meters	Float

heartRate	resting heart rate in beats per minute	Float
glucose	fasting blood glucose level in mg/dL	Float

TenYearCHD	binary variable indicating if the participant is at risk of developing CHD in the next 10 years	Integer


		

Table 2: Clinical Features and Demographics
Features	Description	Type
Age	Age of Participants in Years	Continuous
Sex	Gender of participant	Categorical
BMI	Body mass index, calculated as weight in kilograms divided by the square of height in meters	Continuous
Systolic BP	Systolic blood pressure in mmHg	Continuous
Diastolic BP
	Diastolic blood pressure in mmHg	Continuous
Cholesterol	Total cholesterol in mg/dl	Continuous
Glucose	Fasting blood glucose in mg/dl	Continuous 
Smoking	Smoking status of the participants	Categorical
Alcohol	Alcohol consumption of the participants	Categorical 
Physical activity	Level of physical activity of the participants	Categorical
Family History	Family history of cardiovascular disease	Binary
Education	Education Level of the participant	Categorical

Diastolic BP

Table 3 Statistical analysis
Variable	Mean	Standard Deviation	Minimum	Maximum
Age	52.3	8.7	30	75
BMI	27.9	3.5	20.2	40.5
Systolic BP	123.4	15.2	80	180
Diastolic BP	77.8	9.4	50	110
Cholesterol	198.7	40.2	120	320
Glucose	97.4	12.6	70	160
TenYearCHD	0.15	0.36	0	1


Analysis	Description	Example
Descriptive Statistics	Measures of central tendency and variability for each variable	Mean age: 52.3, SD age: 8.7, Min age: 30, Max age: 75
Correlation Analysis	The strength and direction of the relationship between pairs of variables	The correlation between age and TenYearCHD is 0.27
Independent t-test	Comparison of means between two groups	The mean BMI for males (28.1) is significantly higher than females (27.3), t(4238)=3.2, p<0.01
Chi- square test	Comparison of categorical variables between two or more groups	There is a significant association between smoking status and TenYearCHD, X2(1)=10.5, p<0.01
Logistic Regression	Predictive model for binary outcome variables	The odds ratio for smoking status on TenYearCHD is 1.7 (95% CI: 1.3-2.2), p<0.01
Survival Analysis	Time-to-event analysis for censored data	The median time to TenYearCHD is 8 years, and the survival curve shows a steep decline after 5 years
Principal Component Analysis	Dimensionality reduction technique to identify underlying patterns in the data	The first two principal components explain 75% of the total variance, and show that age, BMI, and glucose are strongly correlated
Cluster Analysis	Grouping of observations based on similarities in their characteristics	Two distinct clusters are identified based on age, BMI, and cholesterol levels
		


Table 4: Logistic Regressor Evaluation

Metric	Value
F1 Score	
Accuracy	
Precision	
Recall	
Confusion Matrix	


Table 5: Random Forest Classifier

Metric	Value
F1 Score	
Accuracy	
Precision	
Recall	
Confusion Matrix	


Table 6: Model Performance and Comparison

Model	F1 Score	Accuracy	Precision	Recall
Logistic Regressor	0.75	0.82	0.68	0.84
K-Nearest Neighbor	0.72	0.80	0.64	0.82
Random Forest Classifier	0.79	0.85	0.73	0.86
Decision Tree Classifier				
Gradient Boosting				
CNN				
LSTM				


Table 7 Receiver Operating Curve

Model	Area Under Curve
Logistic Regressor	0.79
Random Forest Classifier	0.88
CNN	0.92

Overall Summary of expectation:
The overall expectation of this project is to develop a robust predictive model for the 10-year risk of future coronary heart disease in the Framingham cohort using machine learning techniques and clinical/demographic features. The project aims to perform feature selection, dimensionality reduction, ensemble learning, and deep learning techniques to develop and compare different machine learning models for predicting CHD risk. The project also aims to analyze the importance of clinical and demographic features in the predictive models. The final output is expected to be a model that accurately predicts the risk of CHD in individuals, enabling clinicians to identify those at high risk and implement preventive measures. Additionally, statistical analyses such as descriptive statistics, correlation analysis, logistic regression, and others will be performed on the dataset to gain insights into the relationships between variables and to evaluate the performance of the predictive models. The goal of this project is to contribute to the development of more effective and efficient methods for predicting and preventing coronary heart disease.

References

Khan, M.S., et al. (2021). Coronary Heart Disease Risk Prediction Using Machine Learning Algorithms: A Review. Journal of Medical Systems, 45(3), 1-18.

Firdaus, S. (2019). Predicting the Risk of Coronary Heart Disease Using Machine Learning Techniques. International Journal of Scientific Research in Computer Science, Engineering and Information Technology, 4(4), 39-47.

Gulli, A., et al. (2020). Machine learning-based prediction models for cardiovascular disease: A systematic review and meta-analysis. PLoS One, 15(9), e0237589.

Wang, L., et al. (2021). Prediction of coronary heart disease risk in patients with type 2 diabetes using machine learning algorithms. Frontiers in Endocrinology, 12, 638820.

Sabharwal, S., et al. (2021). Machine learning and deep learning-based predictive models for coronary artery disease: A systematic review. Journal of Medical Systems, 45(4), 1-13.

Chen, J., et al. (2018). A deep learning approach to predicting coronary artery disease. Computer Methods and Programs in Biomedicine, 161, 165-174.

Er, G., et al. (2019). A comparative study of machine learning methods for coronary artery disease diagnosis. BMC Medical Informatics and Decision Making, 19(1), 1-12.

Desai, R.J., et al. (2020). Machine learning versus conventional clinical methods in guiding management of heart failure: A nationwide comparative effectiveness study. Journal of the American Heart Association, 9(9), e014568.

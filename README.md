Detection-of-Heart-Disease-Using-Classification-Algorithms-Logistic-Regression_KNN_MLP_RF_Dec.Tree
This is a Machine Learning project for the detection of the heart diseases using the Classification Algorithms approach based on the standard dataset taken from the Kaggle


**(i.) Data collection** 
Overall process of predicting heart disease carries following procedure: 
	We have collected data from dataset provider –Kaggle.com. The dataset which is published  as in the title of Heart Disease dataset .The dataset collected consists of 1024 records of patients, data carries 14 features.
	Dataset is the information or a tool essential to do any kind of research or a project.


**(ii.) Data Analysis**
	This , process involves studying the attributes and features of the dataset and analyzing their correlation with each other.
	Further, in this process we find out the different measures of statistics and also describe the dataset and analyze it on the basis of the different first few and last few tuples of the whole dataset.


	Now the attributes which are used in this project are described as follows and for what they are used or resemble:
(i)Age—age of patient in years. 
(ii)sex—(1 = male; 0 = female).
(iii)Cp—chest pain type.
(iv)Trestbps—resting blood pressure (in mm Hg on admission to the hospital). The normal range is 120/80 (if you have a normal blood pressure reading, it is fine, but if it is a little higher than it should be, you should try to lower it. Make healthy changes to your lifestyle).
(v)Chol—serum cholesterol shows the amount of triglycerides present. Triglycerides are another lipid that can be measured in the blood. It should be less than 170 mg/dL (may differ in different Labs).
(vi)Fbs—fasting blood sugar larger than 120 mg/dl (1 true). Less than 100 mg/dL (5.6 mmol/L) is normal, and 100 to 125 mg/dL (5.6 to 6.9 mmol/L) is considered prediabetes.
(vii)Restecg—resting electrocardiographic results.
(viii)Thalach—maximum heart rate achieved. The maximum heart rate is 220 minus your age.
(ix)Exang—exercise-induced angina (1 yes). Angina is a type of chest pain caused by reduced blood flow to the heart. Angina is a symptom of coronary artery disease.
(x)Oldpeak—ST depression induced by exercise relative to rest.
(xi)Slope—the slope of the peak exercise ST segment.
(xii)Ca—number of major vessels (0–3) colored by fluoroscopy.
(xiii)Thal—no explanation provided, but probably thalassemia (3 normal; 6 fixed defects; 7 reversible defects).
(xiv)Target (T)—no disease = 0 and disease = 1, (angiographic disease status).


**(iii.)  Data Preprocessing** 
	Segregation of target data and feature data as training and test data. 
	Scaling the values in the data to be values between 0 and 1 in which and scale all the values before training the Machine Learning models.


**(iv.) Applying Algorithms**
	Comparing 5-machine learning algorithms such as Logistic Regression, Decision tree, Random forest classifier and K- nearest neighbor  & MLP as well ,to get the better accuracy to which highest parameter may cause disease. 
	For each algorithm, there is a pseudo code helpful to develop any kind of programming language. In python, there is a simple way to establish any kind of algorithm in which simple and short code easier to predict accuracy.


**Machine Learning Algorithms:** 
	The algorithms used in this project is highly helpful to predict the accurate result to detect heart disease in which factors that cause a disease can be detected. The following algorithms have built in this project. 


•	**K-Nearest Neighbor algorithm:** KNN is a supervised classifier that carry-outs a observations from within a test set to predict classification labels. KNN is one of the classification technique used whenever there is a classification. It has a few assumptions includes dataset has little noise, labeled and it should contains relevant features. By applying KNN in large datasets takes long time to process. The accuracy gained with this algorithm is 79 %. 


•	**Random Forest Classifier:** Random forest classifier is a powerful tool in the machine learning library. With this classifier, we will be able to get higher accuracy and training time should be less. Initially, we have to build a model and by splitting variables into training and test set. After splitting the data, train the dependent variables and predict the response. By using the random forest classifier, the accuracy predicted result is of 100 %.



•	**Decision tree classifier:** In this algorithm, preprocessing made initially by splitting data into training and test data .Feature scaling can be done because of normalizing the values before prediction. Import a decision tree classifier to fit the training sets of dependent and independent variables in which Gini-index criterion is used to predict the accuracy or response for the test set. The accuracy gained with this algorithm is 90 %.



•	**Logistic Regression:** This algorithm is one of the most popular Machine Learning algorithms, which comes under the Supervised Learning technique. It is used for predicting the categorical dependent variable using a given set of independent variables. Logistic regression predicts the output of a categorical dependent variable. The accuracy gained with this algorithm is 92 %.



•	**MLP:** Multi-layer Perceptron (MLP) is a supervised learning algorithm that learns a function f ( ⋅ ) : R m → R o by training on a dataset, where is the number of dimensions for input and is the number of dimensions for output. The accuracy gained with this algorithm is 75 %.


![This is an image](https://user-images.githubusercontent.com/100425990/160139323-400b12e2-bb80-4922-b323-389339c5b7e7.png)

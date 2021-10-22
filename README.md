# classificaton_all_model

Introduction:
Daibetes Classification: Design a model which can prognosticate the likelihood of diabetes in patients with maximum accuracy using the data from  the National Institute of Diabetes and Digestive and Kidney Diseases.
Tools Used: Google Colab
Algorithm: k-nearest neighbour algorithm
                    Distance tree classification algorithm
                      Rain Forest Classifier
                       XG boost RF classifier
                       Random SearchCV on XGBRF Classifier
Method:
After reading data into a pandas data frame, Data corelation between all the features is plotted. It suggested, no two data feature are too co-realated. 
Then some NULL values rows of some specific columns(which have less Null values) are dropped. Remaining Null values are imputed iteratively and are filled.
Then, 75% of given data is used training different ML model and 25% of data for the testing of the model. Further all the data had been given standard scaling too.
10 different ML models are build using different algorithms and dataset(normal & standardised). The accuracy of the models are:
Model	Normal Data	Standardised Data
kNN	71.27%	71.82%
DTC	69.61%	64.08%
RFC	72.92%	66.85%
XGBRF	75.13%	75.13%
Best XGBRF	77.34%	77.34%



Conclusion:
ML model is successfully developed for the diabetes dataset.
Best accuracy of the model build is 77.34%

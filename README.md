# CE888---Re-assesment-
## The following code is based on the dataset which was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he is the driver. For more information about the dataset, please refer to the paper: 

Wang, Tong, Cynthia Rudin, Finale Doshi-Velez, Yimin Liu, Erica Klampfl, and Perry MacNeille. 'A bayesian framework for learning rule sets for interpretable classification.' The Journal of Machine Learning Research 18, no. 1 (2017): 2357-2393.

### **Link to download the dataset: https://archive.ics.uci.edu/ml/datasets/in-vehicle+coupon+recommendation**

### We have performed data pre-processing by using the data_preprocessing.ipynb for different attributes and then generated the final preprocessed cssv file. (data-preprocessed.csv). Further we have implemented two cross validation techniques including Stratified K-fold cv and 10-fold GridSearch cv for hyperparameter tuning of the models. 

### Stratified K-fold cv is initially used on a Random Forest Classifier, 
### 10-fold GridSearchCV is used for Random Forest Classifier, AdaBoost classifier and K-NN respectively.

### Instructions to run the above files:

####  1) **Using the 'in-vehicle-coupon recommendation.csv' file, run 'data_preprocessing.ipynb' which will generate the final processed csv file named data-preprocessing.csv**
####  2) **Upload the 'data-preprocessing.csv' file onto your jupyter notebook and run the 'Machine_learning_models.ipynb'**
####  3) **After running the above mentioned files you can now see the produced results**
####  4) **You can also use the combined file (CE888 Preprocesing_&_Predcition.ipynb) which includes data-preprocessing and model implementation**
####  5) **To understand the importance & distribution of all the features in the dataset, refer figure 'Feature importance.png'.** 
#### **NOTE: The accuracy results may differ a bit as compared to the combined file (CE888 Preprocesing_&_Predcition.ipynb) and the individual files(data_preprocessing.ipynb & Machine_learning_models.ipynb).**

# RSL PROJECT

## Project Description: 
The following project aims to Classify a Google Earth image  

## Database Description:

Google Earth Image .ecw Format

## Attribute Information:
Creating Training set using QGIS
Making Labels Banana field, Harvested Field,Fresh_Field
1050 sample in each label

## Libraries Involved:
1. pandas
2. Numpy
3. Scikit learn
4. GDAL
5. Matplotlib
6. Seaborn

## Steps Involved:
1. Importing the libraries
2. Loading the dataset
3. train and test data split
4. Building the model
5. Compare model performance
6. selection model based on performance
7. Evaluation 
8. Plot confusion_matrix

## Machine Learning Steps Involved
1. Multiple Algorithm used 
   * DecisionTreeClassifier
   * KNeighborsClassifier
   * RandomForestClassifier
   * AdaBoostClassifier
2. Find best Algorithm is Random Forest

Conclusion:- The given dataset have target varibale and it is a type of binary class (0,1) its a Supervised machine learning task,after performing varius supervised machine learning models, i found Random Forest Classifier is most suitable model. hence Random Forest Classifier is implimented the model accuracy is 89%.


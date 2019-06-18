# Breast Cancer Prediction


### In this project we have data of Breasr Cancer.

### we apply machine learning to this data to predict the stage of the cancer.

### We apply some processes below to this project:->

### 1-> Load the Breasr Cancer Data By 
**from sklearn.datasets import load_breast_cancer**

### 2-> Then we crate a data frame of this data by :-> **df = pd.DataFrame(load_breast_cancer().data,columns=load_breast_cancer().feature_names)**

### 3-> Visualize this data by:-> 
**f,ax = plt.subplots(figsize=(20,20))
sns.heatmap(df.corr(),annot=True,linewidths = 0.5,linecolor='red',fmt='0.01f',ax=ax)**

### 4-> Then take data into x as input & in y as output values.

### 5-> Crate a classifier of any machine learning model like SVC, DecisionTree,RandomForest,etc 

### 6-> Fit the data to the model.

### 7-> Now predict from by the model as:
**random_forest.predict(df.values[1][:-1].reshape(1,-1))**

### 8-> Finally we get the stage name of Breast Cancer as 0,1,2,3 which are present in the dataset 
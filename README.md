# DecisionTreeClassifier-Basic

1. Importing Libs

Pandas	Numpy	Seaborn
Matplotlib	Sklearn	Scipy
Warning	Graphviz

2. Exploratory Data Analysis:

-	Checking variables
   `df.info()`
-	Profile Report

-	Visualization

3. Dataset Preparation

Label Encoder

4. Training Model

-	Decision Tree Model with Gini Index
`model = tree.DecisionTreeClassifier()`

-	Decision Tree Model with Entropy
`model2  = tree.DecisionTreeClassifier(criterion ='entropy')`

6. Visualizing Tree

7. Accuracy

`results = cross_val_score(model, X_train, y_train, scoring='accuracy')`

8. Confusion Matrix and CLassification Report 

9. Post Pruning

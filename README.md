# Heart Disease Prediction using Decision Trees and Random Forest

This project demonstrates the application of Decision Tree and Random Forest classifiers on the Heart Disease Cleveland dataset. The objective is to classify whether a patient has heart disease based on clinical features.
### Train and Visualize a Decision Tree
- Trained a `DecisionTreeClassifier` on the dataset
- Visualized the full decision tree using `plot_tree`

### Analyze Overfitting and Control Tree Depth
- Trained decision trees with depths from 1 to 10
- Compared training and testing accuracy
- Observed overfitting behavior as tree depth increased

###  Train a Random Forest and Compare Accuracy
- Trained a `RandomForestClassifier`
- Compared accuracy with the single decision tree
- Found that the random forest performs consistently well

### Interpret Feature Importances
- Extracted feature importance scores from the random forest
- Plotted a bar chart to show which features contributed most to predictions

### Evaluate Using Cross-Validation
- Used 5-fold cross-validation to evaluate model performance
- Reported average accuracy and standard deviation
## Results
- Both Decision Tree and Random Forest achieved very high accuracy (100%) on this dataset
- Feature importance analysis showed that some features like chest pain type and thalassemia were most influential
- Cross-validation confirmed stable and high performance
## Requirements
- Python 3.x
- scikit-learn
- pandas
- matplotlib



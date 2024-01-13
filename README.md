# Classification-Tree-for-Flight-Status
This project revolves around the development of a classification tree to predict flight status, distinguishing between 'delayed' and 'ontime', using a dataset that includes various predictor variables. The initial phase involves data preprocessing, including data upload, exploration, and cleaning. Categorical variables are transformed, and unnecessary columns are removed. The subsequent steps encompass the creation of training and validation partitions, training a DecisionTreeClassifier with specified parameters, and explaining flight outcomes based on specific conditions. Confusion matrices are generated to evaluate the model's performance.

Furthermore, the project employs grid search optimization to enhance the classification tree's control parameters, considering factors like maximum depth, minimum impurity decrease, and minimum number of node records. The improved parameters are presented, and the associated classification tree is displayed. The final stage involves a comparative analysis of confusion matrices between different models, providing insights into their accuracy rates. A recommendation is then made based on the evaluation, suggesting the preferred classification tree model for making predictions regarding flight status.

### Addition to the project
in continuationing of the previous project, this addtion revolves around the development and comparison of logistic regression for predicting flight arrival status. Beginning with the preparation and partitioning of the dataset, the logistic regression model is trained using Python's LogisticRegression() and its parameters, including intercept and coefficients, are examined. The mathematical equation of the trained model is derived, offering insights into the relationships among predictor variables. Subsequent steps involve prediction analysis, where the model's accuracy and performance on the validation dataset are assessed through confusion matrices and a lift chart, providing a visual representation of its predictive capabilities, particularly for 'delayed' flight status. 

The logistic regression model is then compared to a classification tree model employed before, and based on accuracy metrics, the former is recommended for its superior performance in classifying flight arrival status.

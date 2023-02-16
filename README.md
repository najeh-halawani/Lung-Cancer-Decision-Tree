# Lung Cancer Decision Tree

The lung cancer dataset is crucial for identifying patterns and developing models that can predict the risk of lung cancer in individuals.
The dataset is based on various features such as smoking habits, age, and symptoms such as yellow fingers, anxiety, and fatigue. By analyzing the dataset, researchers can gain insight into the risk factors that lead to lung cancer and develop models that can identify individuals at high risk for the disease.
This can help in the development of preventive measures and personalized treatment options.


## Detailed Steps:
* Importing Required Libraries
  *	Import the required libraries, including scikit-learn, Graphviz, and pydotplus.
  These libraries are used to load and process data, build decision tree models, evaluate model accuracy, and visualize the decision tree.
* Loading Data
  *	Load the lung cancer dataset into a pandas DataFrame. The dataset should contain relevant features, and most importantly whether the patient has lung cancer or not. 
* Feature Selection
  * Select the relevant features for the decision tree model. Remove any irrelevant or redundant features that may not contribute to the Model’s accuracy. Divide them into two types of variables, dependent and independent.
* Splitting Data
  *	Split the dataset into training and testing sets. The training sets is used to build the decision tree model, while the testing set is used to evaluate the model’s     accuracy.
* Building Decision Tree Model
  *	Build the decision tree model using scikit-learn’s DecisionTreeClassifier class. Set the appropriate hyperparameters, such as the maximum depth of the tree and the     criterion used for splitting nodes.
* Evaluating Model and Finding its Accuracy
  *	Evaluating the decision tree model’s accuracy on the testing set. Calculate the accuracy using scikit-learn’s classification metrics.
* Visualizing
  *	Visualize the decision tree model using Graphviz and Pydotplus. Create a dot file using the export_graphviz method and convert the file to a png.


## Final Decision Tree:
![](https://github.com/najeh-halawani/Lung-Cancer-Decision-Tree/blob/main/Lung-Cancer-Tree.png?raw=true)

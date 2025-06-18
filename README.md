# DECISION-TREE-IMPLEMENTATION

*COMPANY*:CODTECH IT SOLUTIONS

*NAME*:Marem Hemalatha

*INTERN ID*:CT04DG1515

*DOMAIN*:Machine Learning

*DURATION*:4 WEEKS

*MENTOER*:NEELA SANTOSH

*DESCRIPTION*:

*TASK 1: DECISION TREE IMPLEMENTATION*
Task 1 involved implementing a Decision Tree  to perform classification on a chosen dataset. The purpose of this task was to understand how decision trees work, how to preprocess and train a model, and how to evaluate its performance. The task required building and visualizing a decision tree model using the scikit-learn library in Python. I selected the Zoo Classification Dataset from Kaggle for this implementation, as it provides a clear, structured classification problem that is suitable for beginners and educational purposes.

*DATASET DESCRIPTION* :

The Zoo Classification Dataset contains 101 animal records and 17 attributes. Out of these, 16 are feature columns representing various characteristics of animals such as: 
- Presence of hair, feathers, or eggs 
- Whether the animal gives milk or not 
- Number of legs 
- Whether it is venomous, a predator, or domestic 
- Ability to fly or swim 
The final column, class_type, is the target variable which classifies animals into 7 distinct categories (labeled 1 to 7). These categories represent different animal types such as mammals, birds, reptiles, amphibians, insects,fish,bugs and more.

*TOOLS AND LIBRARIES USED*:
To perform this task, I used the following tools and Python libraries: 
-- Jupyter Notebook: An open-source web application used for writing and executing code interactively. I launched Jupyter Notebook via Command Prompt (cmd) to execute the code. 
It offers an interactive environment and is excellent for data visualization and documentation.
--command Prompt(CMD):Jupyter Notebook was launched from the Windows Command Prompt,enabling flexibility in environment management.
--python:The core programming language used.It is highly popular in machine learning for its extensive libraries.
--Pandas: Used for data loading and manipulation the dataset in tabular form.
 NumPy: For handling numerical operations. 
-- Matplotlib & Seaborn: For visualizing data and model evaluation. Including the confusion matrix and decision tree plotting.
-- Scikit-learn (sklearn): The main library used to build the decision tree model, split data, and evaluate the model. It is a machine learning library in python that provides simple and efficient tools for data mining and analysis.It was used to create and visualize the Dcision Tree model.

*IMPLEMENTATION AND WORKFLOW*:

The workflow included the following steps: 
1. Loading the dataset: Using pandas, the dataset was read into a DataFrame. 
2. Data preprocessing: Features and target were separated. No null values were present, so minimal preprocessing was needed. 
3. Train-test split: The data was split into training and testing sets using train_test_split() from 
sklearn.model_selection. 
4. Model training: A DecisionTreeClassifier from sklearn.tree was trained on the training set. 
5. Prediction and Evaluation: Predictions were made on the test set, and accuracy was calculated using accuracy_score. A confusion matrix was plotted to visualize the model's performance. 

*RESULTS AND VISUALIZATION* :

The decision tree model performed exceptionally well. Based on the confusion matrix, the model correctly predicted all classes in the test set. There were no misclassifications, and the accuracy score was 100%. This high performance indicates that the dataset is well-suited for decision tree classification, likely due to its structured, non-noisy nature and clearly defined features. 

*APPLICATIONS OF THE TASK*:

This classification task has real-world applications such as: 
-	Educational tools in machine learning and data science 
-	Zoological classification systems for species identification 
-	Expert systems for automated animal recognition 
-	Biological research support tools
 
*CONCLUSION* :
This task demonstrated how decision trees can be effectively used for classification problems, especially with structured datasets. By using the Zoo dataset, I was able to implement a clean, interpretable model and visualize its performance. Jupyter Notebook provided an ideal environment for this hands-on experience, and scikit-learn made model building intuitive and efficient

*OUTPUT*:

![Image](https://github.com/user-attachments/assets/04fba0ec-e8ff-477d-a019-e2803688a699)

![Image](https://github.com/user-attachments/assets/f3535c7f-4ba9-47e8-a1cf-62566f522053)

![Image](https://github.com/user-attachments/assets/b0f3f706-b7b9-4dd8-98fe-a67f3b8052f3)

![Image](https://github.com/user-attachments/assets/a6dd0aa3-7278-43fd-ad23-cc52b5cd7195)

![Image](https://github.com/user-attachments/assets/8d36d462-ba4a-44c4-acc4-e15dc6ed7c5d)

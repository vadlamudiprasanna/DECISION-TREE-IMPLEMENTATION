# DECISION-TREE-IMPLEMENTATION

COMPANY: CODETECH IT SOLUTIONS

NAME: VADLAMUDI PRASANNA

INTERN ID: CT08DF213

DOMAIN: MACHINE LEARNING

DURATION: 8 WEEKS

MENTOR: NEELA SANTOSH

##This project focuses on predicting student performance using a Decision Tree Classifier, implemented in Python on the Google Colab platform. The dataset used is in a non-standard format, containing a single column of data where each record is separated by the pipe (|) character. The project begins by uploading the file using Colab’s built-in file upload feature, followed by parsing and cleaning the data using the Pandas library. The single-column text data is split into separate columns representing features such as HoursStudied, Attendance, AssignmentsSubmitted, and the target label Result. Unnecessary columns and redundant header rows are removed, and all data is stripped of extra whitespace and converted into appropriate numeric types to prepare it for machine learning.

Once the data is cleaned, the features (HoursStudied, Attendance, AssignmentsSubmitted) and the target (Result) are separated. The dataset is then split into training and testing subsets using scikit-learn’s train_test_split method to evaluate model performance. A DecisionTreeClassifier from the scikit-learn library is trained on the training data using the entropy criterion, which is based on information gain. After training, the model is used to predict outcomes on the test data. Model performance is evaluated using accuracy and a classification report, which includes precision, recall, and F1-score for each class.

Finally, the decision tree is visualized using Matplotlib and scikit-learn’s plot_tree function to provide insight into how the model makes predictions. The resulting tree clearly shows decision paths based on the input features. Overall, this project demonstrates a complete pipeline—from handling messy real-world data to training and visualizing a machine learning model—using widely adopted Python libraries such as Pandas, Matplotlib, and scikit-learn, all within a Google Colab environment.

OUTPUT: 
<img width="1135" height="800" alt="Image" src="https://github.com/user-attachments/assets/8c3d13ce-eb8a-4e85-ac42-19364c9c0078" />

Part 1
CONTEXT: Medical research university X is undergoing a deep research on patients with certain conditions.  University has an internal AI team. Due to confidentiality the patient’s details and the conditions are masked by  the client by providing different datasets to the AI team for developing a AIML model which can predict the  condition of the patient depending on the received test results.

DATA DESCRIPTION: The data consists of biomechanics features of the patients according to their current conditions. Each patient is represented in the data set by six biomechanics attributes derived from the shape and  orientation of the condition to their body part.

PROJECT OBJECTIVE: To Demonstrate the ability to fetch, process and leverage data to generate useful predictions  by training Supervised Learning algorithms.

STEPS AND TASK [30 Marks]:

Data Understanding: [5 Marks]
Read all the 3 CSV files as DataFrame and store them into 3 separate variables. [1 Mark]
Print Shape and columns of all the 3 DataFrames. [1 Mark]
Compare Column names of all the 3 DataFrames and clearly write observations. [1 Mark]
Print DataTypes of all the 3 DataFrames. [1 Mark]
Observe and share variation in ‘Class’ feature of all the 3 DaraFrames. [1 Mark]
Data Preparation and Exploration: [5 Marks]
Unify all the variations in ‘Class’ feature for all the 3 DataFrames. [1 Marks]
For Example: ‘tp_s’, ‘Type_S’, ‘type_s’ should be converted to ‘type_s’
Combine all the 3 DataFrames to form a single DataFrame [1 Marks]
Checkpoint: Expected Output shape = (310,7)
Print 5 random samples of this DataFrame [1 Marks]
Print Feature-wise percentage of Null values. [1 Mark]
Check 5-point summary of the new DataFrame. [1 Mark]
Data Analysis: [10 Marks]
Visualize a heatmap to understand correlation between all features [2 Marks]
Share insights on correlation. [2 Marks]
Features having stronger correlation with correlation value.
Features having weaker correlation with correlation value.
Visualize a pairplot with 3 classes distinguished by colors and share insights. [2 Marks]
Visualize a jointplot for ‘P_incidence’ and ‘S_slope’ and share insights. [2 Marks]
Visualize a boxplot to check distribution of the features and share insights. [2 Marks]
Model Building: [6 Marks]
Split data into X and Y. [1 Marks]
Split data into train and test with 80:20 proportion. [1 Marks]
Train a Supervised Learning Classification base model using KNN classifier. [2 Marks]
Print all the possible performance metrics for both train and test data. [2 Marks]
Performance Improvement: [4 Marks]
Experiment with various parameters to improve performance of the base model. [2 Marks]
(Optional: Experiment with various Hyperparameters - Research required)
Clearly showcase improvement in performance achieved. [1 Marks]
For Example:
Accuracy: +15% improvement
Precision: +10% improvement.
Clearly state which parameters contributed most to improve model performance. [1 Marks]

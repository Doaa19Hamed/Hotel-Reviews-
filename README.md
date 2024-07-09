"Hotel Reviews Analysis and Predictive Modeling"

Objective: Analyzed and processed hotel review data to predict average scores using machine learning techniques.

Tools and Technologies: PySpark, Python (pandas, numpy, seaborn, matplotlib), Jupyter Notebook.

Data Processing:
Loaded and explored a dataset of hotel reviews using PySpark.
Dropped unnecessary columns to streamline the dataset.
Checked and handled missing values and duplicate entries.
Performed label encoding on categorical variables such as 'Hotel_Name', 'Hotel_Address', 'Room_Type', and more.
Feature Engineering:
Assembled selected features into a single vector using VectorAssembler.
Split data into training and testing sets.

Modeling:

Implemented a Linear Regression model to predict the average score of hotels.
Created a pipeline to streamline the machine-learning process.
Evaluated the model's performance using Mean Squared Error (MSE).

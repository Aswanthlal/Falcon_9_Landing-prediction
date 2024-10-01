# Falcon_9_Landing-prediction

The goal of this project was to predict whether the first stage of SpaceX's Falcon 9 rocket would successfully land after launch, based on a variety of mission parameters. Accurate prediction is essential for cost reduction and mission planning.

Solution:
To solve this problem, the following steps were taken:

Data Preprocessing:

Collected and cleaned data from public SpaceX records, which included parameters such as launch site, payload mass, and flight number.
Applied feature scaling techniques to standardize the data.
Handled missing values and encoded categorical variables to prepare the dataset for model training.
Modeling:

Implemented various machine learning models, including Logistic Regression and Support Vector Machine (SVM), to predict the success of a Falcon 9 landing.
Applied Principal Component Analysis (PCA) to reduce the dimensionality of the dataset and enhance model performance.
Evaluation:

Evaluated model performance using metrics such as accuracy, precision, and recall.
Visualized the results of the prediction with confusion matrices and ROC curves to assess the model's ability to correctly classify successful and failed landings.
Results:
The model achieved satisfactory accuracy, providing valuable insights for SpaceX's mission planning by correctly predicting the majority of successful landings. The project demonstrated the viability of machine learning in aerospace engineering.

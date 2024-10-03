## Malaria Infection Classification using Logistic Regression
Overview
This project demonstrates the step-by-step process of applying machine learning techniques to classify malaria-infected and uninfected cells using a dataset obtained from Kaggle. 
It covers the essential phases of the machine learning pipeline, including data cleaning, preparation, visualization, model development, and performance evaluation.

### Dataset
The dataset used in this project was sourced from Kaggle's Malaria Dataset. 
It consists of images of parasitized and uninfected red blood cells, which are labeled as "Infected" or "Uninfected" respectively.

### Project Outline
Data Cleaning:

1. The raw dataset was cleaned to handle missing or inconsistent values.
Outliers were identified and appropriately handled.
Data Preparation:

2. The images were resized, converted to grayscale, and normalized for better model performance.
Labels were encoded for binary classification (Infected vs Uninfected).
Data Visualization:

3. Various visualizations were created to explore the dataset, including sample image displays of infected and uninfected cells.
Statistical insights were extracted and plotted using libraries like matplotlib and seaborn.
Model Development:

A custom function was developed to classify cells into infected and uninfected groups.
Logistic regression was used as the primary classification algorithm.
The model was further designed to label the infection by its grade based on severity.
Model Evaluation:

A confusion matrix was used to assess the model's performance by comparing predicted and actual values.
The model was evaluated on metrics like precision, recall, and F1-score to validate its effectiveness.
Result:

The model's predictions were compared with actual values, achieving an accuracy score of 1 (100%).
The confusion matrix confirmed that the model successfully classified all instances correctly.
Libraries and Tools Used
Python
Pandas, NumPy (for data manipulation)
Matplotlib, Seaborn (for data visualization)
Scikit-learn (for model training and evaluation)
How to Run the Project
Clone the repository:

bash
Copy code
git clone <repository-url>
cd <project-directory>
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Download and prepare the dataset from Kaggle. Follow the steps in the data_preparation.py script to clean and preprocess the data.

Run the model:

bash
Copy code
python model.py
View the results and confusion matrix to verify the model's accuracy.

### Conclusion
This project showcases a comprehensive approach to building a machine learning model that accurately classifies malaria-infected and uninfected cells. 
By leveraging logistic regression and a confusion matrix for evaluation, the model achieved a perfect accuracy score of 1, demonstrating its effectiveness in real-world applications.

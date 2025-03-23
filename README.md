# HR-Department-Case-Study

Data Source: https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset<img width="746" alt="image" src="https://github.com/user-attachments/assets/761e9dfd-11cd-4dd5-a96c-c6c5e66aaf95" />

# Employee Attrition Prediction

This project aims to predict employee attrition using machine learning techniques, including **Logistic Regression, Random Forest Classifier, and Artificial Neural Network (ANN)**. The dataset consists of various HR-related features such as employee demographics, job roles, and satisfaction levels.

## Project Structure
- `Human_Resources_Department_Skeleton.ipynb` - Jupyter notebook containing the full analysis, data preprocessing, model training, and evaluation.
- `data/` - Folder containing the dataset.
- `models/` - Trained machine learning models (if saved).
- `README.md` - Project documentation.

## Installation & Dependencies

To run this project, you need Python and the following libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow keras
```
Alternatively, you can use `requirements.txt`:
```bash
pip install -r requirements.txt
```

## Dataset Description
The dataset contains employee information and their attrition status. Key features include:
- `Age` - Employee's age
- `MonthlyIncome` - Employee's salary
- `TotalWorkingYears` - Total experience
- `JobSatisfaction` - Level of job satisfaction
- `Attrition` - Target variable (Yes/No)

## Machine Learning Models Used
1. **Logistic Regression** - A baseline model for binary classification.
2. **Random Forest Classifier** - An ensemble learning method for better accuracy.
3. **Artificial Neural Network (ANN)** - A deep learning model to capture complex patterns.

Evaluation metrics used: **Accuracy, Precision, Recall, F1-score, and Confusion Matrix.**

## How to Run
1. Clone the repository:
```bash
git clone https://github.com/snarisya/employee-attrition.git
```
2. Navigate to the project directory:
```bash
cd employee-attrition
```
3. Open the Jupyter Notebook:
```bash
jupyter notebook Human_Resources_Department_Skeleton.ipynb
```

## Results & Visualizations
- **Feature Importance Analysis** - Identified key factors influencing attrition.
- **Model Performance Comparison** - ANN performed best with the highest accuracy.
- **Visualizations** - Correlation heatmaps, box plots, and classification reports.

![image](https://github.com/user-attachments/assets/79e203a2-20a0-448e-b3ff-c36f7c26a03e)


## Contributors
- **Siti Nurul Arisya** - Data Scientist | [LinkedIn](https://www.linkedin.com/in/sitinurularisyamohdhanifah23)

For questions or feedback, feel free to contact me at **sitinurularisya@gmail.com**.


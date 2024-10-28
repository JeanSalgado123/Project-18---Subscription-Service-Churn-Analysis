# Project 18: Churn Analysis in a Subscription-Based Company

## Project Overview
This project aims to analyze customer churn in a subscription-based service company. The main objective is to identify key factors that contribute to churn and develop predictive models to forecast potential churn, allowing the company to take proactive retention measures.

## Objectives
- Understand customer behavior by analyzing historical data.
- Identify patterns and trends related to customer churn.
- Build predictive models to forecast the likelihood of churn.
- Provide actionable insights for improving customer retention strategies.

## Dataset
The dataset is simulated to represent customer data in a subscription-based service company. It includes features such as customer tenure, monthly charges, total charges, support interactions, and payment history issues, among others.

## Methods
- **Data Preprocessing:** Handling missing values, outliers, and feature scaling.
- **Exploratory Data Analysis (EDA):** Analysis of customer behavior and identification of churn patterns.
- **Modeling:** Random Forest classifier is used to predict customer churn.
- **Evaluation:** Model performance is evaluated using metrics like accuracy, precision, recall, and ROC-AUC.

## Results
The model achieved satisfactory performance in predicting customer churn, with an ROC-AUC score that indicates good discriminative ability. The analysis identified several key factors contributing to churn, including:
- Low customer tenure.
- High number of support interactions.
- Issues with payment history.

## Key Insights
- Customers with shorter tenure are more likely to churn.
- Frequent support interactions may indicate dissatisfaction, increasing churn risk.
- Payment issues correlate strongly with churn, suggesting that improving billing processes could reduce churn rates.

## Visualizations
The project includes several visualizations to illustrate churn trends and model performance, such as:
- Confusion Matrix: To evaluate model accuracy.
- ROC Curve: To measure the trade-off between true positive rate and false positive rate.
- Feature Importance Plot: To highlight the most significant factors in predicting churn.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/project_18_churn_analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd project_18_churn_analysis
   ```
3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook or Python script:
   ```bash
   jupyter notebook churn_analysis.ipynb
   # or
   python churn_analysis.py
   ```

## Project Structure
- **data/**: Contains the dataset used for the analysis.
- **models/**: Contains the trained model files.
- **reports/**: Includes the PDF report and visualizations.
- **scripts/**: Python scripts for data analysis and modeling.
- **README.md**: Detailed project description and execution guide.

## Requirements
The project requires the following Python libraries:
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- fpdf
- joblib
Install them using:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn fpdf joblib
```

## Conclusion
This project successfully demonstrates how to analyze and predict customer churn in a subscription-based service company. By implementing data-driven insights and predictive modeling, the company can take proactive measures to retain customers, reduce churn, and improve overall business performance.

## Future Improvements
- Include more features in the dataset, such as demographic information, to improve model accuracy.
- Experiment with other machine learning algorithms to boost predictive performance.
- Develop a dashboard to visualize real-time churn predictions for business users.


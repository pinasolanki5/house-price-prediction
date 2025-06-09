# House Price Prediction Project

This project was completed as part of my internship at **Hex Softwares** as a Data Science Intern. It focuses on predicting house prices using various regression models including Linear Regression, Ridge Regression, and Lasso Regression. The goal is to accurately estimate housing prices based on available features in the dataset.

---

## Project Overview

- **Internship:** Data Science Intern at Hex Softwares  
- **Dataset:** Contains house features and their sale prices.  
- **Models Used:**  
  - Linear Regression  
  - Ridge Regression  
  - Lasso Regression  
- **Evaluation Metrics:**  
  - R² Score (Coefficient of Determination)  
  - Root Mean Squared Error (RMSE)  
  - Mean Absolute Error (MAE) 

---

## Results

| Model             | R² Score |
|-------------------|----------|
| Linear Regression | 0.8628   |
| Ridge Regression  | 0.8240   |
| Lasso Regression  | 0.9306   |

*Lasso Regression shows the best performance with an R² score of 0.9306, indicating that it explains about 93% of the variance in house prices.*

---

## Visualizations

- Actual vs Predicted Price scatter plots  
- Residual plots to analyze prediction errors  
- Feature importance charts
- Correlation heatmaps  

---

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/house-price-prediction.git
   cd house-price-prediction

   
2.Install required packages:

pip install -r requirements.txt


3.Run the Jupyter notebook or Python script:

jupyter notebook house_price_prediction.ipynb



Requirements:

Python 3.x

pandas

numpy

matplotlib

seaborn

scikit-learn

folium 

Author

Pina Solanki
Data Science Intern at Hex Softwares




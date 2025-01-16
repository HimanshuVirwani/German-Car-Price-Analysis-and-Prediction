# German-Car-Price-Analysis-and-Prediction# Car Price Prediction and Analysis

## Project Overview
This project focuses on analyzing a dataset of used cars to uncover actionable insights and build a predictive model for car prices. The goal is to address the challenges faced by "Check25," a used car sales company, which has experienced a 15% decline in sales and a €250,000 revenue loss. By understanding customer preferences and improving pricing strategies, this project aims to help the company regain its market share.

## Key Features
1. **Data Cleaning & Preprocessing**
   - Handled missing values and removed irrelevant data.
   - Created new features, such as "Age of Car," for enhanced analysis.

2. **Exploratory Data Analysis (EDA)**
   - Identified trends between mileage, age, fuel type, and car prices.
   - Found insights like price depreciation with age and preferences for specific fuel types.

3. **Predictive Modeling**
   - Developed a Linear Regression model for car price prediction.
   - Evaluated the model using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R²).

4. **Visualization**
   - Used bar charts, line plots, scatter plots, and heatmaps to present findings clearly.

5. **Future Scope**
   - Explore advanced regression models (e.g., Random Forest, Gradient Boosting).
   - Perform clustering for market segmentation.
   - Deploy the model for real-time price prediction.

## Tools and Technologies
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Machine Learning Model:** Linear Regression  

## Dataset
The dataset used in this project is sourced from Kaggle: [Cars Germany Dataset](https://www.kaggle.com/datasets/ander289386/cars-germany). It contains information on car features, mileage, age, and prices.

## Key Insights
1. Price decreases as car age increases.
2. Most cars have a mileage between 0–50k.
3. Electric and diesel cars are priced higher, while ethanol cars are the cheapest.
4. Volkswagen dominates the inventory in terms of car count.

## Results
The predictive model achieved:
- **Mean Squared Error (MSE):** High (room for improvement).
- **Root Mean Squared Error (RMSE):** Moderate.
- **R-squared (R²):** Indicates reasonable performance.

## Visualizations
The project includes visualizations such as:
- Bar charts showing top car models and average prices by mileage.
- Line plots illustrating car price trends over age.
- Heatmaps displaying correlations between numeric features.

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/car-price-prediction.git
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook or Python script to explore the analysis and model.

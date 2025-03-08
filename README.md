# Car Price Prediction

## Introduction

Car price prediction aims to estimate vehicle prices based on factors like brand, features, selling price, and mileage. This project develops a machine learning model to predict car prices accurately.

## Dataset

The dataset used in this project, **car data.csv**, contains various features such as:
- **Year:** Manufacturing year of the car
- **Present Price:** Current market price of the car
- **Selling Price:** Price at which the car is sold
- **Driven KMs:** Total distance driven by the car
- **Fuel Type:** Type of fuel used (Petrol/Diesel/CNG)
- **Seller Type:** Individual or Dealer
- **Transmission:** Manual or Automatic
- **Owner:** Number of previous owners

## Project Goals

- Build a high-accuracy machine learning model.
- Identify key factors influencing car prices.
- Evaluate models using performance metrics.

## Methodology

1. **Data Preprocessing:** Clean data, handle missing values, and create new features.
2. **EDA:** Analyze relationships between features and car prices.
3. **Model Development:** Train models including:
   - Linear Regression
   - Decision Trees
   - Random Forests
   - Gradient Boosting
4. **Evaluation:** Use MAE, MSE, and R² score to assess models.

## Observations

- **Price Correlation:** Selling Price and Present Price show a strong positive correlation.
- **Year Effect:** Newer cars tend to have higher selling prices and lower mileage.
- **Mileage Influence:** Lower mileage cars typically sell for more.
- **Market Impact:** Present market value strongly affects the final selling price.

## Conclusion

This project showcases machine learning’s effectiveness in car price prediction. By leveraging advanced algorithms and data analysis, we provide insights into pricing factors and develop a reliable predictive model.

## Technologies Used

- Python, Pandas, NumPy
- Scikit-learn, XGBoost
- Matplotlib, Seaborn

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/car-price-prediction.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the script:
   ```bash
   python train_model.py
   ```

## Future Enhancements

- Add economic and demand-related factors.
- Implement deep learning for better accuracy.
- Create a web app for easy price estimation.

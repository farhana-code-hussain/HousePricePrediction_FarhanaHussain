# House Price Prediction using Machine Learning

## Overview

This project predicts house prices using machine learning techniques based on property features such as area, bedrooms, bathrooms, parking, furnishing status, and other amenities.

The project demonstrates the complete machine learning workflow, including:

- Data loading and exploration
- Data preprocessing
- Feature encoding
- Data visualization
- Model training
- Model evaluation
- Price prediction

---

## Dataset

Dataset Used: `Housing.csv`

The dataset contains information about:

- Price
- Area
- Bedrooms
- Bathrooms
- Stories
- Main Road Access
- Guest Room
- Basement
- Hot Water Heating
- Air Conditioning
- Parking
- Preferred Area
- Furnishing Status

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## Project Structure

```
HousePricePrediction_FarhanaHussain/
│
├── analysis.ipynb
├── Housing.csv
├── summary.docx
├── charts/
│   ├── price_distribution.png
│   ├── area_vs_price.png
│   ├── bedrooms_vs_price.png
│   ├── correlation_heatmap.png
│   └── actual_vs_predicted.png
```

---

## Data Preprocessing

The following preprocessing steps were performed:

- Checked for missing values
- Explored dataset statistics
- Converted categorical values into numerical form
- Prepared features and target variables
- Split data into training and testing datasets

---

## Machine Learning Models

### 1. Linear Regression

Used as a baseline model to predict house prices.

### 2. Random Forest Regressor

Used to improve prediction performance and capture more complex relationships between features.

---

## Visualizations

The project includes multiple visualizations:

- Price Distribution
- Area vs Price
- Bedrooms vs Price
- Correlation Heatmap
- Actual vs Predicted Prices

---

## Results

The Random Forest model achieved better prediction performance compared to Linear Regression.

Key observations:

- Larger houses generally have higher prices.
- More bedrooms and bathrooms tend to increase property value.
- Preferred location and modern amenities positively affect pricing.
- Area is one of the strongest predictors of house price.

---

## Conclusion

This project demonstrates how machine learning can be used to estimate house prices using housing characteristics. The workflow includes data preprocessing, visualization, model training, and performance evaluation.

---

## Author

**Farhana Hussain**

Machine Learning Internship Project

Car Price Prediction

This project predicts used car prices using machine learning, comparing Linear Regression with Random Forest. All code and data are in the notebook.

 How to Run

1. Install the requirements:
2. 2. Open `car_price_prediction.ipynb` in Jupyter Notebook or VS Code.
3. Run all cells in order to get results and plots.
 Dataset

- The dataset is embedded in the notebook itself as a CSV string.
- It contains columns like: Car Name, Year, Present Price, Driven Kms, Fuel Type, Transmission, etc.
- Motorcycles and unrelated vehicles are filtered out in preprocessing.

 Models Used

- Linear Regression
- Random Forest Regressor

 Results

Typical output shows Random Forest gives a better R² score than Linear Regression.
Sample output (your results may vary):
Linear Regression - MSE: 13.21, R²: 0.83
Random Forest - MSE: 4.97, R²: 0.96

Visualizations

- Actual vs Predicted prices plot
- Residuals distribution
- Present Price vs Selling Price scatter plot



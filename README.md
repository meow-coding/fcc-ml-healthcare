# Healthcare Cost Prediction 💗

<!-- temp -->

This project predicts **healthcare expenses** using a Linear Regression model.

## Dataset
- Public dataset: `insurance.csv`
- Features: `age`, `sex`, `bmi`, `children`, `smoker`, `region`
- Target: `charges`

## How to run
1. Clone this repository
2. Create a virtual environment (optional)
3. Install requirements:
pip install -r requirements.txt

markdown
Copy code
4. Run the Jupyter Notebook `healthcare_regression.ipynb`

## Model
- Linear Regression
- Train/test split: 80/20
- Mean Absolute Error: ~4181

## Notes
- Plots included to visualize predictions and residuals
- Dataset preprocessing done with OneHotEncoding for categorical features
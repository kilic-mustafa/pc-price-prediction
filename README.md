# PC Price Prediction

## Overview  
This project uses machine learning to predict the price of PCs based on hardware specifications. It includes data scraping, cleaning, exploratory analysis, and regression modeling to estimate a computer’s value from its features.

## Project Structure  
- `extract_data.ipynb` — scripts for collecting and structuring raw data  
- `data.csv`, `data_cleaned.csv` — raw and cleaned datasets  
- `statistical_review.ipynb` — descriptive statistics and data exploration  
- `regression.ipynb` — building and evaluating predictive models  
- `classification.ipynb` — (optional) exploring classification approaches  

## Methodology  
1. **Data Extraction**: Collected a dataset of PC hardware specs and prices.  
2. **Preprocessing**: Cleaned missing values, encoded categorical features, and scaled numerical ones.  
3. **Exploratory Data Analysis**: Investigated relationships between components (e.g. CPU, GPU, RAM) and price.  
4. **Modeling**: Trained and compared regression models (e.g., linear regression, tree-based) to predict price.  
5. **Evaluation**: Assessed models using metrics such as R², MAE, and RMSE.

## Usage  
1. Clone the repository  
2. Install required Python packages (e.g., `pandas`, `numpy`, `scikit-learn`)  
3. Run the notebooks in order: data extraction → cleaning → EDA → modeling  
4. Use the final trained model to predict the price of new PC configurations

## Results & Insights  
- Identified which hardware features most strongly influence PC price  
- Reported model performance and error margins  
- Suggest improvements and future directions (feature engineering, hyperparameter tuning, more data)

## Requirements  
- Python 3.x  
- `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`  

## Contributing  
Contributions are welcome! Feel free to:  
- Add new data sources  
- Try different regression or ensemble algorithms  
- Improve feature engineering or performance  

## License  
This project is licensed under the MIT License - see the LICENSE file for details.

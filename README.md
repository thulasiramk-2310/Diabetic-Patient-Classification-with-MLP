# Diabetic Patient Classification with MLP

This project demonstrates an end-to-end machine learning workflow for classifying diabetic status using patient health data. The workflow is implemented in a Jupyter notebook and leverages Python, pandas, scikit-learn, and MLPClassifier.

## Features
- Data loading and cleaning from Excel
- Feature engineering and labeling
- Train/test split and normalization
- Model training with Multi-Layer Perceptron (MLP)
- Hyperparameter tuning using GridSearchCV
- Model evaluation with accuracy and confusion matrix

## Project Structure
- `mlp.ipynb`: Main Jupyter notebook containing all code and analysis
- `data_file.xlsx`: Input dataset 

## How to Run
1. Install dependencies:
   - Python 3.x
   - pandas
   - numpy
   - scikit-learn
   - openpyxl (for Excel support)
2. Place `data_file.xlsx` in the project directory.
3. Open `mlp.ipynb` in Jupyter or VS Code.
4. Run all cells to execute the workflow.

## Key Libraries/Frameworks
- Python
- pandas
- numpy
- scikit-learn
- Jupyter Notebook

## Model Details
- Uses `MLPClassifier` for classification
- Hyperparameters tuned: hidden layer sizes, activation functions, solvers, learning rates, max iterations
- Evaluation metrics: accuracy, confusion matrix

## Example Output
- Best hyperparameters found via GridSearchCV
- Test set accuracy and confusion matrix


---
Feel free to modify or extend the notebook for further analysis or model comparison.

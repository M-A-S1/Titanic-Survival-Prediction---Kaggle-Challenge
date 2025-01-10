# Titanic Survival Prediction - Kaggle Challenge

This repository contains my solution for the Titanic Survival Prediction challenge on Kaggle, where I achieved a top 4.29% ranking globally.

## Project Overview
The Titanic Survival Prediction challenge involves predicting whether a passenger survived the Titanic disaster based on features like age, gender, ticket class, and more. The goal is to build a machine learning model that maximizes accuracy on the test dataset provided by Kaggle.

## Achievements
- **Top 4.29%** ranking globally on the Kaggle leaderboard.
- Implemented feature engineering, data preprocessing, and multiple machine learning models.

## Dataset
The dataset is available on the [Kaggle Titanic page](https://www.kaggle.com/competitions/titanic/data). It includes:
- `train.csv`: Training data with labels (Survived = 0 or 1).
- `test.csv`: Test data without labels.
- `gender_submission.csv`: A sample submission file.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-Learn
- Jupyter Notebook

## Steps Followed
1. **Data Exploration and Cleaning:**
   - Handled missing values
   - Explored data distributions and correlations
2. **Feature Engineering:**
   - Created new features from existing data (e.g., Title extraction, Family size)
3. **Model Training and Evaluation:**
   - Tried multiple classifiers (e.g., Logistic Regression, Random Forest, Gradient Boosting)
   - Used cross-validation and hyperparameter tuning
4. **Submission:**
   - Generated predictions on the test dataset and submitted to Kaggle

## Results
- Achieved a **top 4.29%** ranking with a highly optimized model.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/titanic-survival.git
   cd titanic-survival
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open the `mas-titanic.ipynb` notebook and run all cells.

## Folder Structure
```
|-- mas-titanic.ipynb          # Main notebook
|-- requirements.txt           # List of dependencies
|-- data/                      # Dataset (train/test csv files)
|-- models/                    # Saved models (if applicable)
|-- README.md                  # Project documentation
```

## Contact
For any questions or collaborations, feel free to reach out:
- GitHub: [yourusername](https://github.com/yourusername)
- Kaggle: [yourkaggleprofile](https://www.kaggle.com/yourkaggleprofile)

## License
This project is licensed under the MIT License.


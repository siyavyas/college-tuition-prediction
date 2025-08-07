# college-tuition-prediction

# College Tuition Prediction

This project predicts the tuition costs of over 600 U.S. colleges based on a combination of institutional and geographic features. We applied feature engineering techniques and trained multiple regression models to uncover trends and drivers of college pricing.

## Project Highlights

- **Dataset**: 600+ U.S. college records with engineered features
- **Models Used**:
  - Ridge Regression
  - Gradient Boosting Regressor
  - Neural Network (PyTorch)
- **Evaluation Method**: 7-Fold Cross Validation (CV)
- **Performance**:
  - Best Model RMSE: **5,860.88**
  - R² Score: **0.799**
  - Baseline RMSE: **13,086.66** → Achieved a **55% improvement**
- **Team Rank**: 2nd out of 13 teams

## 📁 Files

- `final_proj.ipynb`: Main notebook with data exploration, feature engineering, model training, evaluation, and results.

## Key Learnings

- Importance of engineered features (e.g., region, institution type) in capturing tuition variability
- Ridge regression helped regularize high-dimensional features
- Gradient Boosting outperformed linear baselines due to its flexibility and ability to capture non-linear relationships

## Tech Stack

- Python, Pandas, NumPy
- scikit-learn (regression, CV, preprocessing)
- PyTorch (custom neural network)
- Matplotlib & Seaborn (visualizations)

## Results & Reflections

Our pipeline demonstrated strong performance across all major regression techniques, with Gradient Boosting and Ridge performing particularly well. Neural networks also showed promise but required careful hyperparameter tuning. We ranked 2nd in our class competition and significantly outperformed the baseline model.

## Contact

For questions or collaboration, feel free to reach out!


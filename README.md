# Gold Price Prediction using Random Forest

This project predicts gold prices using historical data and a **Random Forest Regressor**. The dataset is sourced from Kaggle's [Gold Price Data](https://www.kaggle.com/datasets/altruistdelhite04/gold-price-data). The key steps include data preprocessing, correlation analysis, model training, and evaluation.

---

## Project Steps:
1. **Dataset Download**: Using the `kagglehub` library to access the gold price dataset.
2. **Data Analysis**:
   - Generated a correlation heatmap to explore feature relationships.
   - Visualized the distribution of gold prices.
3. **Feature Preparation**:
   - Selected relevant features, excluding `Date` and `GLD` columns.
   - Split data into training and testing sets.
4. **Model Training**:
   - Trained a **Random Forest Regressor** with `n_estimators=100`.
5. **Evaluation**:
   - Achieved **R² Score: 0.9886**, indicating high model accuracy.
6. **Visualization**:
   - Compared actual vs predicted values using scatter and line plots.

---

## Results:
- **R² Score**: 0.9886
- The model performs well in predicting gold prices based on the dataset.

---

## Visuals:
- **Correlation Heatmap**
- **Distribution Plot of Gold Prices**
- **Actual vs Predicted Gold Prices** (Scatter and Line Plots)

---

## References:
- Dataset: [Gold Price Data on Kaggle](https://www.kaggle.com/datasets/altruistdelhite04/gold-price-data)

Feel free to provide feedback or suggestions for improvement. You can reach me at Email: mfauzanfauzan123@gmail.com and: [Linkedin](https://www.linkedin.com/in/muhammadfauzandsml/)

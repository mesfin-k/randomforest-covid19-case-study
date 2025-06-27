# Random Forest COVID-19 Case Study 🦠🌲

This project is a machine learning case study using the Random Forest algorithm to analyze COVID-19 patient data from South Korea. It demonstrates how ensemble methods outperform simpler models in the presence of multicollinearity and missing data.

## 📊 Objective

- Predict the **patient state** (isolated, released, deceased) using patient data
- Explore the performance of **Random Forest** vs. other models
- Handle **missing values**, **categorical encoding**, and **feature correlations**

## 🧠 Key Features Used

- Age & Birth Year
- Sex
- Infection Case
- Contact Number
- Province / City
- Disease (boolean)
- Date Fields (e.g. confirmed_date)

## 🔍 Highlights

- **EDA**: Distribution, heatmaps, and boxplots for feature exploration
- **Data Cleaning**: Missing value handling, type conversions, correlation filtering
- **Modeling**: RandomForestClassifier with hyperparameter tuning and feature importance
- **Visualization**: Correlation heatmap and tree plots

## 📈 Tools & Libraries

- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Scikit-learn (RandomForest, train_test_split, metrics)
- Jupyter Notebook

## ✅ Results

- Random Forest handled multicollinearity well
- Accuracy and feature importance evaluated on test data
- Linear Regression performed poorly due to multicollinearity and categorical variables

## 💡 Conclusion

Random Forest is a robust model when dealing with real-world messy datasets that include missing values, categorical variables, and high correlation. This case study highlights its effectiveness for multiclass classification tasks such as predicting patient outcomes during a pandemic.

---

### 📎 Author

**Mesfin Kebede**  
GitHub: [mesfin-k](https://github.com/mesfin-k)


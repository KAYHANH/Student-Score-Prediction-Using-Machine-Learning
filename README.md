# 🎓 Student Score Prediction Using Machine Learning

This project aims to predict student subject scores using machine learning techniques. It analyzes key features like study hours, attendance, and extracurricular involvement to estimate performance in subjects such as Math, History, Physics, Chemistry, Biology, and Geography.

## 📌 Problem Statement

Accurately predicting student performance is critical for educators and institutions. Manual analysis is limited in scale and accuracy. This project solves that problem using data-driven prediction models.

## 💡 Proposed Solution

We developed a regression-based prediction system using Random Forest and Linear Regression models. It includes:
- **Data Collection**: Kaggle dataset on student performance
- **Preprocessing**: Feature encoding, handling missing values, scaling
- **Modeling**: Random Forest Regressor wrapped in MultiOutputRegressor
- **Evaluation**: R², MAE, and RMSE metrics
- **Visualization**: Scatter plots of actual vs predicted scores

## ⚙️ System Requirements

- Python 3.x
- Jupyter Notebook
- RAM: 4GB minimum

### 📚 Libraries Used
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`
- `xgboost` (optional)

## 🤖 Algorithms Used

- **Random Forest Regressor** (with MultiOutputRegressor for multi-target prediction)
- **Linear Regression** (baseline comparison)

## 📊 Results

| Subject          | R² Score | MAE   | RMSE  |
|------------------|----------|-------|-------|
| Math             | 0.1277   | 9.41  | 12.03 |
| History          | -0.0933  | 11.66 | 14.12 |
| Physics          | -0.0736  | 10.72 | 13.17 |
| Chemistry        | -0.0087  | 10.59 | 12.99 |
| Biology          | 0.1015   | 11.28 | --    |
| Geography        | -0.1077  | 10.52 | 12.64 |

> Note: Negative R² scores indicate the model is underperforming for those subjects and can be improved.

## ✅ Conclusion

- Built a working ML pipeline for multi-subject score prediction
- Gained insights into influential features and model performance
- Identified challenges like low model generalization for some subjects

## 🚀 Future Scope

- Use deep learning (MLPs or LSTMs) for better performance
- Add features like attendance, sleep hours, socio-economic status
- Deploy using Flask or Streamlit for real-time prediction
- Expand to real-world school datasets across cities or states

## 📚 References

- [Student Performance Dataset (Kaggle)](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- [Scikit-learn Documentation](https://scikit-learn.org/)
- Educational Data Mining Research Papers

## 🙏 Acknowledgments

This project was developed as part of the coursework in the Department of Computer Science and Engineering.


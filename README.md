\# Heart Disease Prediction Using Machine Learning



\## Overview



This project applies machine learning classification techniques to predict the presence of heart disease using clinical attributes from a heart disease dataset.



The objective is to compare multiple classification algorithms, evaluate their predictive performance, and examine the usefulness of Logistic Regression as a final model.



This project demonstrates practical skills in data analysis, statistical modelling, machine learning, and model evaluation relevant to actuarial analytics and healthcare risk analysis.



\## Objectives



\- Explore and prepare the heart disease dataset.

\- Train and compare multiple classification algorithms.

\- Evaluate models using accuracy, precision, recall, F1-score, and ROC-AUC.

\- Examine the final Logistic Regression model's performance.

\- Communicate predictive results and their limitations.



\## Tools and Technologies



\- Python

\- Jupyter Notebook

\- pandas and NumPy

\- scikit-learn

\- Matplotlib

\- Machine learning classification and evaluation metrics



\## Models Compared



The baseline comparison includes:



\- Logistic Regression

\- Support Vector Machine (SVM)

\- Random Forest

\- AdaBoost

\- K-Nearest Neighbours (KNN)

\- Gradient Boosting

\- Naive Bayes

\- Decision Tree



\## Final Model Results



The recorded evaluation results for the final Logistic Regression model are:



| Metric | Result |

|---|---:|

| Accuracy | 85.25% |

| Precision | 83.33% |

| Recall | 90.91% |

| F1-score | 86.96% |

| ROC-AUC | 89.39% |



The baseline Logistic Regression model recorded a ROC-AUC of approximately 91.41% in the separate baseline results file. These baseline and final-model results are reported separately.



\## Project Files



\- `project heart disease.ipynb` — notebook containing the analysis and modelling workflow.

\- `baseline\_results.csv` — comparison of baseline classification models.

\- `final\_model\_results.csv` — recorded final-model evaluation metrics.

\- `final\_logistic\_regression\_roc\_curve.png` — ROC curve visualisation.



\## Key Takeaways



This project demonstrates a complete machine learning workflow involving model comparison, evaluation, and communication of predictive performance.



Recall is particularly relevant when considering the consequences of missed positive cases. However, the appropriate balance between recall, precision, and other measures depends on the intended use and the costs of different prediction errors.



\## Limitations



\- Predictive performance depends on the dataset, its quality, and how the evaluation was conducted.

\- Results may not generalise to other populations or healthcare settings.

\- The evaluation metrics do not establish clinical validity.

\- The model is an educational machine learning project, not a medical diagnostic tool.



\## Reproducibility



Open the Jupyter Notebook and follow the cells in order. The Python environment and dataset requirements should be checked against the notebook before reproducing the results.



\## Author



Actuarial Science student interested in statistical modelling, machine learning, healthcare analytics, and quantitative risk analysis.


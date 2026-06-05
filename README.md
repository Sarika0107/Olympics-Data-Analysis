# Olympics Data Analysis & Medal Prediction

## Project Overview

The Olympic Games generate a vast amount of data related to athletes, countries, sports, and medal achievements. This project performs an end-to-end data analysis and machine learning workflow to analyze Olympic medal data and predict medal outcomes.

The project combines data preprocessing, exploratory data analysis (EDA), visualization, and machine learning techniques to uncover trends, identify top-performing countries and athletes, and build predictive models for medal classification.

---

## Objectives

- Analyze Olympic medal distribution across countries and years
- Identify top-performing countries and athletes
- Study gender participation trends in Olympic events
- Perform exploratory data analysis (EDA)
- Build machine learning models for medal prediction
- Evaluate model performance
- Derive insights from historical Olympic data

---

## Dataset

The dataset contains Summer Olympic medal records from 1976 to 2008.

### Features Include

- City
- Year
- Sport
- Discipline
- Event
- Athlete
- Gender
- Country Code
- Country
- Event Gender
- Medal

### Target Variable

- Medal Category (Gold, Silver, Bronze)

---

## Exploratory Data Analysis (EDA)

### Key Insights

- Medal distribution varies significantly across countries.
- Certain nations consistently dominate Olympic competitions.
- A small number of athletes account for a large number of medal wins.
- Gender participation has increased across multiple sports over time.
- Medal trends show changes in country performance across Olympic years.

EDA was performed using visualizations such as bar charts, line plots, pie charts, and statistical summaries.

---

## Machine Learning Approach

### Models Implemented

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

### Key Techniques

- Data cleaning and preprocessing
- Handling missing values
- Label Encoding
- Train-Test Split
- Feature Selection
- Model Evaluation

---

## Model Performance

- Logistic Regression provided baseline classification results.
- Decision Tree improved the ability to capture non-linear relationships.
- Random Forest achieved better performance by combining multiple decision trees and reducing overfitting.
- Model evaluation was performed using Accuracy Score, Confusion Matrix, and Classification Report.

---

## Feature Importance

Important factors influencing medal prediction include:

- Country
- Sport
- Discipline
- Gender
- Event Category

These attributes significantly impact the likelihood of winning a particular medal category.

---

## Applications

This project can help:

- Sports analysts understand Olympic performance trends
- Researchers study athlete and country performance
- Organizations identify strengths across sports disciplines
- Analysts forecast medal outcomes using historical data
- Support strategic planning for future Olympic events

---

## Limitations

- Dataset is limited to Summer Olympics from 1976–2008.
- Athlete-specific performance metrics are not included.
- External factors such as training quality and economic conditions are not considered.
- Prediction accuracy depends on available historical features.
- Results should be interpreted as analytical insights rather than definitive forecasts.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Repository Contents

- Olympics(s).ipynb → Complete analysis and machine learning workflow
- Summer-Olympic-medals-1976-to-2008.csv → Dataset
- README.md → Project documentation

---

## Author

**Sarika T A**  
Aspiring Data Analyst / Data Scientist

---

## Conclusion

This project successfully analyzed the Summer Olympics medal dataset from 1976 to 2008 using Exploratory Data Analysis (EDA) and Machine Learning techniques. The analysis helped identify top-performing countries, successful athletes, medal distribution patterns, and gender participation trends across different Olympic events. Various visualizations provided valuable insights into how Olympic performance evolved over the years.

Machine learning models such as Logistic Regression, Decision Tree, and Random Forest were implemented to predict medal outcomes based on factors including country, sport, discipline, and gender. The results demonstrated that these features significantly influence medal achievements and can be effectively utilized for predictive analysis.

Overall, the project highlights how data analytics and machine learning can transform historical Olympic data into actionable insights, supporting sports analysis and future performance forecasting.

---

## Future Improvements

- Implement advanced machine learning models such as XGBoost and Gradient Boosting.
- Include recent Olympic datasets for more comprehensive analysis.
- Incorporate additional athlete-related features such as age, rankings, and previous performance.
- Perform feature engineering and hyperparameter tuning to improve model accuracy.
- Develop interactive dashboards using Power BI or Tableau.
- Build a real-time Olympic analytics and medal prediction system.
- Integrate external factors such as GDP, population, and sports funding to enhance predictive capabilities.

---

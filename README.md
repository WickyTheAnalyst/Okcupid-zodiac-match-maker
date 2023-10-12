# OkCupid Zodiac MatchMaker

### 1. Introduction
The Astrological Sign Prediction Project aims to predict users' astrological signs based on their OkCupid profiles. Astrology is often considered significant in compatibility matching, making this a relevant predictive modeling task. This report presents a detailed analysis of the project, encompassing data collection, exploration, cleaning, preprocessing, analysis, results, visualization, discussion, conclusion, recommendations, references, and appendices.

### 2. Objective
To explore and predict OkCupid users' astrological signs based on the information contained in their profiles

### 3.Goal
The goal of this project is to scope, prep, analyze, and create a machine learning model to solve a question.
*Whether a OkCupid's user astrological sign can be predicted using other attributes from their profiles.*

### 4. Data Collection
The dataset used for this project was obtained from OkCupid, a popular dating platform. It consists of 924,628 user profiles, including self-reported astrological signs. The dataset comprises various features such as age, location, essay responses, and astrological sign.

### 5. Data Exploration
In this stage, we explored the dataset's structure, dimensions, and basic statistics. It includes 675 unique astrological sign categories. We identified missing values and gained insights into the distribution of astrological signs and other features.

### 6. Data Cleaning and Preprocessing
Data cleaning involved handling missing values, converting data types, and addressing outliers. Preprocessing included feature engineering, where we derived insights from text data (essay responses) and encoded categorical variables.

### 7. Data Analysis
Three models—Logistic Regression, K Nearest Neighbors (KNN), and Decision Tree—were built to predict astrological signs. We evaluated model performance using classification metrics like precision, recall, F1-score, and accuracy.

### 8. Results and Findings
The Logistic Regression model showed poor predictive performance, with an accuracy of 12%. The KNN model achieved 33% accuracy, while the Decision Tree model, though initially overfit, achieved an impressive 78% accuracy. Cross-validation highlighted the need for model improvement.

### 9. Data Visualization
Confusion matrices and visualizations were used to present the results, showcasing model predictions and performance.

### 10. Discussion
The discussion addressed limitations, challenges, and insights. Overfitting was identified in the Decision Tree model, suggesting a need for regularization. Feature engineering and model selection were discussed to improve predictive performance.

### 11. Conclusion
While the KNN model showed promise, predictive performance was limited, emphasizing the need for further enhancements. Recommendations include feature enrichment, hyperparameter tuning, and exploring additional models.

### 12. Recommendations
1. **Feature Enrichment**: Include more features that could contribute to astrological sign prediction.
2. **Hyperparameter Tuning**: Experiment with different hyperparameters to optimize model performance.
3. **Explore Additional Models**: Consider exploring more complex models to improve prediction accuracy.

### 13. References
- Scikit-Learn Documentation: https://scikit-learn.org/
- OkCupid: https://www.okcupid.com/

### 14. Appendices
- Detailed code implementations for data cleaning, preprocessing, model building, and evaluation.

---

This structured report provides a comprehensive overview of the Astrological Sign Prediction Project, outlining the methodology, results, and recommendations for future enhancements. The project highlights the challenges and opportunities in predicting astrological signs based on user profiles, aiming for improved predictive accuracy in subsequent iterations.


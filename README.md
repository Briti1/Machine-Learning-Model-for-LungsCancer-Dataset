# Machine Learning Model for LungsCancer Dataset

🧾 Conclusion
In this project, we built and evaluated multiple machine learning models to predict lung cancer based on patient lifestyle and symptom data. The dataset included features such as age, smoking, anxiety, wheezing, and other medical conditions that may correlate with lung cancer.

✅ Models Used:

Logistic Regression

K-Nearest Neighbors (KNN)

Random Forest Classifier

Support Vector Machine (SVM)

Naive Bayes


🔍 Key Findings:
Support Vector Machine (SVM) achieved the highest accuracy of ~98%, outperforming all other models on the test data.

SVM also delivered excellent precision, recall, and F1-score, making it the most reliable model in this scenario.

Visual exploration through heatmaps, scatter plots, distribution plots, and pairplots revealed that features such as:

Smoking, Anxiety, Wheezing, Age are highly correlated with lung cancer presence.

📊 Visual Summary:
A correlation heatmap illustrated strong relationships between features and the target variable.

Scatter plots of age vs. smoking and wheezing vs. coughing showed distinct separations between cancer-positive and cancer-negative individuals.

A scatter matrix (pairplot) provided deeper multivariate insights across all numeric features.

🏁 Final Verdict:
Based on overall performance and interpretability, SVM is the most effective model for this dataset and should be considered the go-to algorithm for early-stage lung cancer prediction using survey data.


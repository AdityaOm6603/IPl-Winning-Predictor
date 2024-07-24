## IPl-Winning-Predictor
### Project Description
In a cricket-crazy nation like ours, the Indian Premier League (IPL) since 2008, holds a special place. It's not just a tournament; it's a celebration of cricketing prowess, strategies, and unpredictable outcomes. Predicting IPL match outcomes accurately has always been a challenge due to various dynamic factors like player form, team performance, and match conditions.

The primary goal of this project is to leverage historical match data, player statistics, team performance metrics, and other relevant features to predict which team is likely to win a particular match. This project aims to assist fantasy cricket players in selecting the most effective team for IPL fantasy leagues and to contribute to more informed and balanced betting markets.

### Methods and Algorithms Used
#### Data Collection and Preprocessing
#### ->Datasets:
->Match.csv (756, 18)

->Final_df (71,342, 10)

->Delivery.csv (149,578, 24)

#### ->Workflow:
->Data Cleaning: Enhancing the quality and reliability of the dataset.

->Data Extraction: Retrieving specific information or patterns from the dataset.

->Exploratory Data Analysis (EDA): Visually and statistically summarizing, interpreting, and understanding the main characteristics of the dataset.

->Visualization: Representing data through visual elements like charts, graphs, and maps to facilitate better understanding, analysis, and communication of patterns and insights.

### Machine Learning Models
#### Seven machine learning classification algorithms were employed for predicting IPL match outcomes:
->Linear Regression: A statistical method used for modeling the relationship between a dependent variable and one or more independent variables.

->Logistic Regression: A binary classification algorithm used to predict the probability of an instance belonging to a particular class.

->K-Nearest Neighbors (KNN): A classification algorithm that classifies an object by the majority class of its k nearest neighbors in the feature space.

->Gaussian Naïve Bayes: A probabilistic classification algorithm based on Bayes' theorem, effective for text and real-valued data.

->Decision Tree: An algorithm that recursively partitions the data into subsets based on feature values to make decisions.

->Random Forest Classifier: An ensemble algorithm that constructs multiple decision trees and outputs the mode or mean prediction of the individual trees.

->XGBoost Classifier: A powerful gradient boosting framework that builds a series of decision trees sequentially, optimizing for errors in predictions.

### Best Model
The best-performing model among the above was selected based on its accuracy and reliability in predicting match outcomes.

### Model Efficiency
Graphical representations of the training and testing accuracy for all models were created to visualize their performance. These graphs included runs scored after each over, wickets fallen, and both win and loss percentages of the batting team.

### Conclusion
The IPL Winning Predictor, powered by machine learning, offers rich statistical insights and trends that deepen our understanding of player and team performances. This enhances cricket fans' engagement and excitement as they eagerly anticipate match outcomes, enriching the field of cricket analytics and sports science research. IPL teams can leverage these strategic insights to better understand their opponents, leading to more refined team strategies..

### Sample Output


![Screenshot 2024-07-24 234906](https://github.com/user-attachments/assets/54fd07e5-50cf-4905-a7bf-e3cdaab129ec)

<img src="hairloss1.jpg" alt="Balding Men">

# Hair-Loss
Machine Learning Project Designed to Predict Hair Loss in an Individual

Overview 

As someone who’s father is bald and is concerned about their own chances, this dataset drew my attention. The goal of this project was to create two different models to predict if an individual would experience hair loss or not. The data used was sourced from the Kaggle dataset linked below. It covers a range of factors that may play a role in the loss of hair. The final model for this project was a Linear Regression model with an accuracy of 54.5% on unseen test data. Based on the results and various other attempts at feature engineering, it was concluded that the data was not predictive given our chosen target. Given this, recommendations for model/data were given in the conclusion of this page. 

Understanding / Context 

For many people, the possibility or the presence of hair loss is a big concern, as it can really affect one's external and internal image, creating complications. The Majority of men will experience some hair loss in their lifetime, but not as talked about, many women will as well. Even with it being a completely normal thing, happening to millions of people, it’s an ever prevalent insecurity. In today’s world, there are ways to prevent it, slow it down, and in some cases, reverse it. However, the best time to address it is before it occurs, which is often missed. With a proper model, one could fill out some personal information and be presented with their possibility of hair loss. Such a tool could stave off this condition and alleviate stress for millions of people. 

Data Understanding 

The Hair Health Dataset contains 999 entries. Each entry/row is an individual with information covering various factors that may or may not contribute to baldness. These factors are genetics, hormone changes, medical conditions, medications/treatments, nutritional deficiencies, stress, age, hair care, environment, smoking, and weight loss. Though the dataset had no missing or null values, there was some preparation necessary for model use. The column names were simplified for use throughout the project, removing unnecessary spaces. The Id column was removed as. All columns except the age column were encoded as numerical values (using ordinal, replace, and dummy). Finally, though not entirely needed given the models, the data was scaled after being split, due to the age column. 

Model Evaluation 

The two models used for this project were a Linear Regression model of 500 max iterations and a Random Forest Classifier model using GridSearchCV. In reviewing the results, the former received higher accuracy scores on both the training data and the validation data, being 58.6% and 50%. The latter received 51.4% and 48.5%. Thus, with faster compute times and higher scores, the Linear Regression model was used for evaluating the test data. (To preface, due to the low scores, there were attempts at featuring engineering before using the test data, but they only made marginal changes in score.) It received an accuracy score of 54.5%. While this is better than the validation set and shows that the model is not too overfitted to the training data, the result is still not stellar. 

Conclusion

This model, despite attempts at feature engineering, does not show any promising use and no one should be using it to see if they will go bald or not. As mentioned in the overview, the data just did not seem predictive given our target variable. Despite this, I do believe that it can be built upon. I would recommend that more samples be collected with an increase in features. These could include, but are not limited to weight, their father’s hair status, hat usage, sleep satisfaction level, sleep time,  workout time, and use of braids or hair ties. With enough data, this can be something that can be predicted and prevented, benefitting countless people; myself included. - I would love to see this dataset updated for future use, but as it stands right now, there simply are not enough data points to make a sound prediction. 

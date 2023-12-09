The file Final_Sub_1 takes 'iith_foml_2023_train.csv' as input training data
It standardises the dataset and works using Gradient Boosting algo similar to the previous one, but
I used the correlation matrix and found some features that are very much related to each other and removed them to make sure that the model does not gets overfit to the data.
In this attempt, we can see that the accuracy is decreased which implies that those features might be important/necessary ones.

For testing, it takes input from 'test_input.csv' and outputs the predictions into 'test_output.csv' in the same way as asked in kaggle
Run all the cells to get the 'test_output.csv'

Public_Score: 0.62562
Private_Score: 0.49473

Note: It takes around 10 to 12 mins for th model to get trained, incase that it takes more time, please restart the program

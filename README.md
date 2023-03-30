# Deep-Learning-Challenge

##Overview:
The purpose of this analysis is to assist the nonprofit foundation Alphabet Soup in selecting the applicants for funding with the best chance of success in their ventures.

##Data Processing
1. The target variable for my model was the column "Is Successful" which evaluated if the money given was used effectively.
2. The features for my model were the remaining columns: Application Type, Affiliation, Classification, Use Case, Organization Status, Income Amount, Special Considerations and Ask Amount.
3. The variables that were removed from the initial dataframe were EIN and Name. When the model was optimized only the EIN was removed.

##Compiling, Training and Evaluating the Model
1. In my model I used 2 hidden layers with many neurons to assist in obtaining the target accuracy of greater than 75%.
2. I was able to achieve the target performance by adding the Name column in during optimization and combining all values less than 10 into a single category "other".

##Summary
By optimizing the model I was able to predict the accuracy of applicant success to 78%. The Alphabet Soup foundation will find the most success when:
  Applicant types are from T3, T4, T5, T6, T7, T8, T10 OR T19 and Classification C1000, C2000, C1200, C3000, C2100.

# Credit-Eligibility-

Objective: Objective of the project to predict the target variable y whose value is yes or no. Y attributes provide information
whether the person is eligible for the credit card or. The features like age, job ,education, marital status present in 
the data which impacts the target variable. In the give data  target variable is categorical, so various classification algorithms 
has been implemented to check and find the best fit.

Statistical approach were also implemented , where the effort were put on to find the significant attributes 
from the data 


Conclusion from the project
1. The data contains null values that were dropped as these were very few in number

2. Chi square test informs that the all categorical features are relevant and impact target variable

3. From walt test it was known that only numerical features were significant except job  , pdays, and previous

4. From visualisation it was clears that all categorical variables affected the target variables as the mean of both classes was different 

5. There was correlation between age and balance , it is significant correlation as proved from the spearmant test. However the strength of correlation was very less. 

6. Many models were built but these were not successful when checked with classification report as the data was imbalance it contain no class with around 90% while the representation of yes class was only 10%

7. The oversampling and undersampling technique both were implemented to improve model but the performance was still poor

8. Later, outlier treatment was done and  implemented a smote technique to balance the class. Checking several models we obtained Random forest performed very well which was tuned further. Recursive elminiation approach is preferred for feature selection.

9. The accuracy of the final is 90%, the model was able to classify with almost same precision and recall. The feature required for the test and training of the model includes 'age', 'balance', 'day', 'duration' and 'campaign.

10. Now the model is ready to find the credit eligibiltiy of person based on 'age', 'balance', 'day', 'duration' and 'campaign.

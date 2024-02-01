This is the project for Machine learning certification course by berkley 

Practical Application Assignment 3: The data is related with direct marketing campaigns (phone calls) of a Portuguese banking institution. The classification goal is to predict if the client will subscribe a term deposit (variable y).Full dataset has 41188 entries. Goal is to detremine whta client/contact factors gives most importance so that they will sign up for term deposit. As a result we should provide a clear analysis and understaning of the contacts they are targeting. This can also help them in developing a better strategy in future on what client to contacts.  

Problem statement - For campaigns we need to determine if a client will sign up for term deposing or not. If we do some analysis on all clients available and give some guidance to the marketing team on which clients are more likely to sign up then they we can help company save on lot of unnecessray calls. 

Approach - I first cleaned up all the data that is not needed. Scaled and extrapolate on all columns that will be used for model building. Built few models and then determined the best model 

Detailed Analysis - 
I did all the data analysis and tried to answer few questions based on data. I then converted 'default', 'housing', 'loan' from yes/no to 1/0.Below non numerical features were convetered to numeric 'job', 'marital', 'education', 'contact', 'month', 'poutcome'. All duplicate data was removed and nulls were replaced. 

I then split tha into 80% training and 20% test data. I then trained and fit models - "Logistic Regression", "Nearest Neighbors","Linear SVM" and "Decision Tree"

Next steps - 
We should run this against actual validation dataset and see if our model fits.
Also expand the selection to include state, make, model etc 

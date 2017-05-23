# HR-Analytics
Using Keras we analyze HR data from https://www.kaggle.com/ludobenistant/hr-analytics

### HR Analytics Neural Network in Keras
The goal of the notebook is for us to create a neural network model in Keras that can help us predictively identify whether an employee is likely to leave the company, by using employee records as input features and as targets a binary classification (0/1); left=1; stay=0. We also compare the model performance using LeakyReLU and normal relu activations.

We will create employment categories, which allows us to view the overall distribution of employees according to category and which will also allow us to compare employee performance according to their categorical averages and standard deviations to create numerical representations of "overperformance" and "underperformance".

Using these performance metrics, we will be able to identify likely to leave employees that offer "overperformance" that should be incentivized to remain at the company as well as employees that offer "underperformance" that could be considered for retrenchment if it becomes a necessary for the survival of the company.

# Predicting Churn
For my second capstone project, I chose to model customer churn within a telecom company. The primary dataset was downloaded from [here](https://www.kaggle.com/raumonsa11/churn-telco-europa). I have uploaded it [here](https://github.com/ashtonreed/Springboard/blob/master/Capstone2/data/train_churn_kg.csv).

First, I cleaned and analyzed the data in [this Jupyter notebook](https://github.com/ashtonreed/Springboard/blob/master/Capstone2/Capstone2_Cleaning_and_Analysis.ipynb).

Then, I built 2 Cox Proportional Hazard models to determine which model was best [here](https://github.com/ashtonreed/Springboard/blob/master/Capstone2/Capstone2_Machine_Learning.ipynb). Ultimately, it was the model created from the dataset that included many one-hot-encoded features that had the best score of 0.63.

For the final results, please check out the [final report](https://github.com/ashtonreed/Springboard/blob/master/Capstone2/Capstone_Project_2_Final_Report.pdf) or the [presentation deck](https://github.com/ashtonreed/Springboard/blob/master/Capstone2/Predicting_Churn_Presentation.pdf).

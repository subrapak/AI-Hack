# AI-Hack

The attached notebook contains a project completed during and after Imperial College London's inaugral 'AI Hack' in November 2018. The challenge was to, given a dataset with a number of samples and features, predict current house prices for the Brooklyn area. A number of data cleaning techniques were used as much of the data was unrecorded, or unusable (e.g. having a year of sale as 0), which had to be accounted for. Once data cleaning was done, the non-numerical data (e.g. categorical variables) were removed, and of the remaining variables, even more were discarded based on the author's discretion.

Finally, with a usable dataset, a number of machine learning techniques were used to estimate house prices on a validation set, and the performance of each technique was measured by the R^2 value between the predicted and actual sale price for each sample in the validation dataset. The best performing method was the RandomForestRegressor model provided in the sklearn library, with an R 2  value just under 0.8, and outperformed all other models comfortably.

Refer to `CleanedUpSolution.ipynb` for all the code with step by step explanations and justifications.

# Brief
This dataset contains the house sales record in Brooklyn, New York City, from 2003 to 2017. It is a combination of NYC Rolling Sales from the NYC Department of Finance and the PLUTO for roughly 30,000 properties, which we have then merged into a single .csv file. Candidates are required to predict the property sale prices using only the data provided

**NB: The train and test datasets are too large to upload. They can be downloaded at the link below:**
https://www.kaggle.com/tianhwu/brooklynhomes2003to2017

# used-car-price-prediction
This project focuses on cleaning the data and perform feature engineering.
However, it could be extended to ultimatimately build a predictive model which guides the auction participants to understand the true value of used cars.


### Dataset
There are 2 data files. These files are too large to put on github.
  - data/Data_Scientist_case_study_Auctions.csv
  - data/Data_Scientist_case_study_Inspections.csv

### Data Cleaning and Feature engineering
The first step of this project is to clean the data and engineer the features before building the model. 
This dataset is nuique in that most of the useful information is initially stored in one column as json-formatted text. 
The challenge is to extract infomation from the column and build features from it. 
Also there are a lot of N/A values and inconsistencies in the dataset.

##### Skills learned from this part:
  - Using json.loads()
  - Dealing with N/A in your data (automated)

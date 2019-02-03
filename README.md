# railways-data-analysis

## Data Analysis using the FRA data
(DS 6001 , Dec 2018)

#### Description
The goal is to  build a small data pipeline to process the FRA data on rail equipment accidents. The pipeline will perform the functions of ingesting, cleaning, and visualizing the data. The pipeline
should be able handle new data as it becomes available on the FRA site. Cleaning the data should incorporate the following-

1. Remove duplicates.
2. Join narratives.
3. Transform variable encodings (e.g., TYPE, TYPEQ, CAUSE).
4. Correct for time value of money with CPI (ACCDMG).
5. Impute the missing values for TYPEQ.

Additionally, I've fit an ARIMA model to the yearly cost of the most expensive accidents

There are 4 notebooks which contain the following -

* Notebook 1: Cleaning and Saving Data
* Notebok 2: Cleaning and Saving Updated Data
* Notebook 3: Producing visualizations
* Notebook 4: Fitting an ARIMA model to the data

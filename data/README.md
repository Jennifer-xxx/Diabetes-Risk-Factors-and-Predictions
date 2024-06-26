The 2022 BRFSS Survey Data and Documentation used for this project can be found at this [website](https://www.cdc.gov/brfss/annual_data/annual_2022.html). 

Since the data is large, it is not directly included in the folder. The zip data file can be downloaded through the [link](https://www.cdc.gov/brfss/annual_data/2022/files/LLCP2022XPT.zip).

The load-data chunk in the file Risk-Factors-of-Diabetes-And-Predictions.rmd can be directly run to acquire the data.

The preprocessed data after selecting the columns of interests, cleaning the values, removing missing observations and outliers, and downsampling the dataset is stored in this folder as **clean_data.csv**. This is the final dataset used for applying the machine learning techniques.

The preprocessed data with all categorical numbers replaced with their corresponding category name is saved in the folder as **vis_data**.csv.
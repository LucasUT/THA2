# THA2: DATA MANAGEMENT

### Gun Violence Incidents

For my research project, I plan to explore various factors and conditions leading to spikes in gun violence in major American cities. To explore this issue, I begin with a gun violence .csv dataset pulled from Kaggle (https://www.kaggle.com/jameslko/gun-violence-data) and originally compiled by James Ko using data from www.gunviolencearchive.org. The data includes over 260,000 gun violence incidents in the U.S. from 2013-2018, which provide an adequate sample through which I hope to draw important inferences and identify factors relevant to gun violence frequency. 

The codebook and variable descriptions can be found at the aforementioned Kaggle URL, but for convenience, I have also included the codebook as an .xlsx file, which can be found in this repository.

### Economic Influence

Obviously, conditions influencing gun violence vary across different policy areas, but one factor often attributed to gun violence and crime more generally is economic viability. Based on this theory, I have also included an .xlsx data file of the monthly unemployment rates from the Bureau of Labor Statistics (https://data.bls.gov/timeseries/LNS14000000). The date range covered, 2013-2018, is the same as the set of gun violence incidents, which should allow for easier merging of the two tables. However, it was nontheless necesary to clean the dataset in excel in order to reach a usable format. Since unemployment is but one variable contributing to a person or area's economic viability, I plan to gather further economic data, such as average household income, type of work, poverty rate, and localized information, to shed more light on possible economic connections to gun violence.

### Education

### THA1

In order to view THA1, which utilizes data no longer needed, please download the THA1_ls.ipynb file, as well as the k12.csv and gun-violence-data.csv.zip, which are both located in the RAWDATA folder of the repository. The K12 dataset includes data on school shootings dating back to 1970, produced by the Center for Defense and Homeland Security (<i> Citation for use: Riedman, David, and Desmond O’Neill. “CHDS – K-12 School Shooting Database.” Center for Homeland Defense and Security, [date accessed], www.chds.us/ssdb </i>). Both K12.csv and the unzipped gun-violence-data.csv must share the same directory as THA1_ls.ipynb in order to run. In addition, a third data file is included inside the notebook, which is to be pulled directly from the given URL. This file contains all U.S. Mass Shootings from 1982-2019, produced by Mother Jones magazine during reporting investigations.

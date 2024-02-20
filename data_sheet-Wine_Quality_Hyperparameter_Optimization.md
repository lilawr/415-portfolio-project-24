# Datasheet Wine Quality of Vinho Verde

## Motivation

- The dataset was created in order to find a link between wine quality and wine's physicochemical properties.
- The data set was created by Paulo Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis in 2009
 
## Composition

- Each instance in the dataset represents a single wine with features of 11 physicochemical properties and 1 output value of wine quality score between 0 and 10
- There are 1143 instances of data
- This is only the red wine instances of the original data set collected by creators
- There are no missing values in the data set
- There is no confidential data included as all confidential/private variables have been omitted such as grape type, brand and price

## Collection process

- The original data was collected from samples tested at the official certification entity (CVRVV) which an organisation working towards the quality and marketing of vinho verde [1](http://www3.dsi.uminho.pt/pcortez/wine5.pdf)
- iLab was used to record the testing data and then it was exported to a single datasheet of all the tests both analytical or sensory for each candidate wine sample
- The data was collected between 2004 May and 2007 Feb

## Preprocessing/cleaning/labelling

- The testing data was transformed into a single row per wine
- Feature selection was used to select only the more common physicochemical tests
- The outputs were calculated from the median of three sensory evaluations by blind tasters (rated from 0-10)
- The original data set differentiates the red and white wines and is also available in the same format to test the models [online](http://www3.dsi.uminho.pt/pcortez/wine/) and could be useful for further analysis

## Uses

- This dataset was specifically designed for linking quality with physicochemical properties and doesnt include other labels so might not have many other applications
- Some of the less common physicochemical tests were omitted in preprocessing in order to not have any missing data points so there may be links that are unclear or features missing

## Distribution

- The data set has already been distributed with a public licence (for research only) on the internet on Kaggle and originally from the [UCI ML repository](https://archive.ics.uci.edu/dataset/186/wine+quality)
- It is available for public use as long as the correct credit is given to its creators [Original Posting](http://www3.dsi.uminho.pt/pcortez/wine/)
- Reference: P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553, 2009.

## Maintenance

- Update frequency of the dataset is Annually according to its [listing on Kaggle](https://www.kaggle.com/datasets/yasserh/wine-quality-dataset/data)


(1) http://www3.dsi.uminho.pt/pcortez/wine5.pdf
# Starbucks-Offers
This is the Capstone project I submitted in order to complete my Data Science Nanodegree at Udacity platform (https://www.udacity.com/).
## Installation
The code uses Jupyter Notebook and the libraries which are already installed in it. However, I had to update my pandas version by running 'conda update pandas' in the terminal so that pandas can read the json input files.
## Motivation
As part of Udacity Data Science Nanodegree Capstone Project, Starbucks has offered simulated data that mimics customer behavior on the Starbucks rewards mobile app. I use demographic, transaction and offer data in order split people in different demographic groups and predict the following for each group:

1. Conversion rate for each of the 10 different offer types
2. View rate of overall offer types
3. Non-offer related spending

The files I used for this project were provided by Udacity platform as json inputs.

## File description
There is one Jupyter Notebook here named Starbucks_Capstone_notebook.ipynb. This file includes the full Python code I used for this project along with informative comments.

## Results

The findings of this investigation have been posted in Medium. Please see link here:
(https://medium.com/@georgios.kokkinopoulos/starbucks-offers-conversion-rate-demographics-4df4bf1cbae1)
You can find a summary of the results here as well:
* Demographic data about customers (profile dataset) was cleaned
* Transcript data was enhanced in order to include converted offers, view rate and non-offer related spending by person
* Some inference about overall CR, VR and non-offer spending revealed significant differences between potential categories so the decision was made to split age and income in 3 equal categories. That created 18 categories in total.
* Transcript dataset was further enhanced to include categories.
* Random Forest Regressor, Gradient Boosting Regressor and Support Vector Regressor were trained and fitted to the data and RFR was proved to be the best estimator.
* A heatmap at the end (predicted target variables by category) provided very useful insight as to what offers should be sent to what categories.

## Licensing, Authors, Acknowledgements
As mentioned above this is simulated data provided by Starbucks (no personal data of customers is present here).
You can find references of the resources I used at the end of the Medium article above.

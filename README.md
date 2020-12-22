# Capstone_Udacity-Starbucks


### Table of Contents
1. Installation
2. Project Motivation
3. File Descriptions
4. Results
5. Licensing, Authors, and Acknowledgements


### Installation

To install the code the following libraries are needed:
- pandas
- numpy
- matplotlib
- seaborn
- sklearn
- pickle
- joblib



### Project Motivation
The goal of this project was to develop a machine learning algorithm that is able to classify starbucks customers regarding their tendency to react to an offer they receive. The business objective is to improve the targeting in order to increase customer spending.



### File Descriptions
The project contains the following files/folders:

- Starbucks_Capstone_notebook.ipynb: contains the entire python code including visualizations and the classifier
- data: contains the input data consisting of transcript(transaction data), profile(customer data), portfolio(data on offers) data
- classifier.pkl: contains the tuned RandomforestTree classifier
- promotions_completed.csv: contains a dataframe with labels (true,false) for completed informational offers
- offer_completed.csv:  contains a dataframe with labels (true,false) for completed bogo and discount offers



### Results
The classifier performs relatively poorly (f1score~.6) indicating the difficulty to effectively segment the customers based on their demographic charateristics. The algorithm might be improved by using another classifier such as a kn-neighbour or by using additional features (customer data). A more comprehensive summary can be found here: https://medium.com/@nassimo/using-machine-learning-to-help-starbucks-increase-its-conversion-ee5f458573fb


### Licensing, Authors, Acknowledgements
n.a.






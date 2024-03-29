# Machine Learning Course (Udacity) Final Project

<h3>Enron dataset - Using Machine Learning to identify persons of interest in Enron scandal</h3>

Link to Udacity repo for this project: https://github.com/udacity/ud120-projects

Link to Project (Jupyter Nbviewer): http://nbviewer.jupyter.org/github/karthik-25/Udacity-MachineLearning-FinalProject/blob/master/poi_id.ipynb?flush_cache=true

<h3>Project Overview</h3>
In 2000, Enron was one of the largest companies in the United States. By 2002, it had collapsed into bankruptcy due to widespread corporate fraud. In the resulting Federal investigation, there was a significant amount of typically confidential information entered into public record, including tens of thousands of emails and detailed financial data for top executives. In this project, you will play detective, and put your new skills to use by building a person of interest identifier based on financial and email data made public as a result of the Enron scandal. To assist you in your detective work, we've combined this data with a hand-generated list of persons of interest in the fraud case, which means individuals who were indicted, reached a settlement, or plea deal with the government, or testified in exchange for prosecution immunity.

<h3>Project Requirements</h3>

We will provide you with starter code, that reads in the data, takes your features of choice, then puts them into a numpy array, which is the input form that most sklearn functions assume. Your job is to engineer the features, pick and tune an algorithm, test, and evaluate your identifier.

The features in the data fall into three major types, namely financial features, email features and POI labels.

<b>1) financial features:</b> ['salary', 'deferral_payments', 'total_payments', 'loan_advances', 'bonus', 'restricted_stock_deferred', 'deferred_income', 'total_stock_value', 'expenses', 'exercised_stock_options', 'other', 'long_term_incentive', 'restricted_stock', 'director_fees'] (all units are in US dollars)

<b>2) email features:</b> ['to_messages', 'email_address', 'from_poi_to_this_person', 'from_messages', 'from_this_person_to_poi', 'shared_receipt_with_poi'] (units are generally number of emails messages; notable exception is ‘email_address’, which is a text string)

<b>3) POI label:</b> [‘poi’] (boolean, represented as integer)
You are encouraged to make, transform or rescale new features from the starter features.

The starter code can be found in the final_project directory of the codebase that you would have already downloaded: 

<b>- poi_id.py:</b> starter code for the POI identifier, your code will be written here

<b>- final_project_dataset.pkl:</b> dataset for the project

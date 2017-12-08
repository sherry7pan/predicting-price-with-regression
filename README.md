Pricing Regression 
======================

The goal of the model is to predict the sale price of a particular piece of
heavy equipment at auction based on it's usage, equipment type, and configuration.
The data is sourced from auction result postings and includes information on usage
and equipment configurations.

Evaluation
======================
The evaluation of the model will be based on Root Mean Squared Log Error. Which
is computed as follows:

![](images/rmsle.png)

where *p<sub>i</sub>* are the predicted values and *a<sub>i</sub>* are the target
values.

See the code in score_model.py for details.


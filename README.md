This Github is part of the final project for Laura Brooks 501146410 in CIND 820 at Toronto Metropolitan University.
Supervisor is Ceni Babaoglu

Notebook will be used to evaluate Airbnb data from: https://public.opendatasoft.com/explore/dataset/airbnb-listings/table/?disjunctive.host_verifications&disjunctive.amenities&disjunctive.features

There is an HTML file that contains the initial results.

The dataset is broken down into a subset containing only Airbnb listings from Toronto. The research is aimed to help new hosts list their property with an accurate price so only includes data fields a new host would have access for. This removes any review information, information about how the host interacts with a customer, etc.

The dataset consisets of a mix of structured and unstructured, numerical, text and categorical data. A data description is provided for all data.

There are many null values in this dataset that needed to be transformed and/or removed.

The models evaluated include:
Linear Regression
Random Forest Regressor
Decision Tree Regressor

The RFE package from sklearn is used for feature selection.

K Fold Cross Validation is used, it was evaluated and best results came from 3 folds.
## belugadb case study

This is a solution for the data scientist case study from BelugaDB.
The exercise details can be found on https://belugadb.github.io/challenges/data-science-challenge

The analysis, feature engineering and model creation and evaluation were done through the use of jupyter notebooks.

The proper order to check the solution should be:

1. EDA.ipynb
2. FE.ipynb
3. Model.ipynb

Main conclusions were that data features seem relevant and should be further explored.
Given the nature of the business problem presented, it would be relevant to know if any of the features are the equipment/team ids.
That would allow for new feature engineering, such as time from last maintenance, avg true labels by equipment/team so far, and so on.

Model used was a lightgbm. Parameter tunning was done manually, but alternatives were proposed.
No attempt of enseemble/stacking was done.

# Decision-Tree-to-predict-heart-diseases

In this project, I applied supervised learning to classify and predict heart diseases using decision tree. This project was done as my homework for the Data Mining course under supervision of Dr. Ehsan Nazerfard.

1) Preparing the data: The implementation of decision tree in sklearn package expects digit
encoded categorical data, for example for age data one could have digit 0 for ages from
0 to 10, digit 1 for ages from 11 to 20 and so on. So, I had to convert numerical
features to categories each representing possible value ranges. Then I needed to encode
non-numerical values with digits. The dataset has a number of categorical and binary
features that require encoding.
2) Splitting the data: To see how well my classifier performs I needed to test it with new
entries. First I split dataset into a training set with 80% of data and a test
set with 20% of data. The training set is used to actually train the classifier and test set is
used to measure it
3) Training and classification: Finally, my decision tree will classify the test dataset. The
Decision Tree in sklearn has various parameters. I tried different values for criterion,
max_depth and min_sample_split parameters and trained different classifiers. Then I Visualized
each decision tree, test them with the test set and report accuracy for each one.

This code is implemented by python programming language and its related libraries.

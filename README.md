# IPWK9-CORE
This week's project requires us to implement a K-nearest neighbor (kNN) classifier  and a Naive Bayes classifier. Once we conduct the experiments, we will calculate the resulting metrics:
# Download the two datasets from the given links:

## Dataset 1 Source: 
[Train Dataset Source: Link (https://archive.org/download/train5_202002/train%20%285%29.csv), 

Test Dataset Source: Link (https://archive.org/download/test1_202002/test%20%281%29.csv)]
## Dataset 2 Source: 

[Link (https://archive.ics.uci.edu/ml/datasets/Spambase)]
## Experimental Procedure:

1. Randomly partition each dataset into two parts i.e 80 - 20  sets.
2. For dataset 1, because we don't have the label for the test set, we will use the train set to create train and test data (i.e. splitting further), then perform K-nearest neighbor classification.
3. For dataset 2, perform classification of the testing set samples using the Naive Bayes Classifier.
4. Compute the accuracy (percentage of correct classification).
5. Report the confusion matrix of each classifier.
6. Repeat step 1 to step 3 twice, each time splitting the datasets differently i.e. 70-30, 60-40, then note the outcomes of your modeling.
7. Suggest and apply at least one of the optimization techniques that you learned earlier this week.
8. Provide further recommendations to improve both classifiers.

## Create a notebook for each project.  

## License
[MIT](https://choosealicense.com/licenses/mit/)

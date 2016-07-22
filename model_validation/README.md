# Model-validation
Once the model is built, how do we determine its performance in "out-of-sample" data.

1. We can train and test on the entire dataset. We know the "true" response from the dataset and we compare it to the predicted response. (Find the classification error("loss function") or the classification accuracy("reward function")
Disadvantages: Do well in in-sample data but poorly in out-of-sample data

2. We can split the dataset into two components: training (for model building) and testing(for model validation). We use the "true" response from the testing set and we compare to the predicted response from our model.

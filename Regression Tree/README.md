# Regression Tree

This [regression tree](https://en.wikipedia.org/wiki/Decision_tree_learning) was created with the [Holdout Method](https://towardsdatascience.com/validating-your-machine-learning-model-25b4c8643fb7), which is the simplest training method available.

The following tree was generated using one of the built-in R datasets, Iris.

![reg-tree](https://user-images.githubusercontent.com/74436565/132058238-f1bd7d71-9495-4c2d-aac4-c202cc13f50d.png)

To [evaluate the method](https://towardsdatascience.com/metrics-to-evaluate-your-machine-learning-algorithm-f10ba6e38234), the *accuracy* function was used, which is part of the *forecast* library.

             ME         RMSE      MAE       MPE        MAPE
    Test set 0.02751479 0.4446286 0.3492157 0.09384631 6.037737
    
![graph-plot](https://user-images.githubusercontent.com/74436565/132058267-70813785-869b-416f-b798-d322026f8af2.png)

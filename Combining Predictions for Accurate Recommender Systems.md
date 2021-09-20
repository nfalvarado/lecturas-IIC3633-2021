# Combining Predictions for Accurate Recommender Systems

As the title of the paper says, the principal subject is the combination of algorithms of recommender systems to improve accuracy. 
The paper start explaining Collaborative filtering and specifically, their most useful CF in the Netflix Prize challenge. The authors explain
a strategy to combine 2 or severals recommendations techniques and this implies an advantage. As they demonstrate, different kinds of collaborative 
filtering algorithms leads to significant performance improvements over individual algorithms.

Something that I think is interesting, is the K-Nearest Neighbors Blending - KNN. The authors adjust the size of the neighborhood using cross validation 
(also to optimize the model parameters). The goal of this, is to improve the speed of the KNN algorithm because when the training set is large, 
the algorithm is slow in predicting new samples.

It's kind of intuitive that the use of neuronal networks can improve the accuracy because the big amount of data. 
But the idea of using this technique is appropriate, clean and intelligent.

The paper shows a big amount of test that the authors did. This helps to understand how they solved the problem of improving 
accuracy by combining prediction combination algorithms. This may be a good reference to understand how it works the specific combinations
and leaves open the following questions: 
How can improve more the combinations given in the paper? 
What kind of hyperparameters optimize the blending? 
What happen if we mix two blendings?

# Collaborative Filtering Recommender Systems
The paper explains all the basic ideas and constructions of Collaborative Filtering Recommender Systems.  
In fact, the first definition says that Collaborative Filtering is the process of filtering or evaluating items using the opinion of other people.
Also, the authors explain the Core Concepts, as *rating* (association of user and item). The interesting fact about the rating is that they can be explicit or implicit. 
These kinds of rating give us information about the users, as well their preferences and what types of items they will like.

Other interesting discussed idea of the paper are the tasks for which people use collaborative filtering. 
Despite that most of them are intuitive, it has to be done to create a good collaborative filtering. For example, 
*Advise me on a particular item* is kind off direct but is the skeleton of the recommendations.
Something I would like to highlight about collaborative filtering system functionality is the proposed *meta-recommendation* system that generates recommendations 
from a blending of multiple recommendation sources. It's like learn to learn in the world of the Recommendation Systems.

About the collaborative filtering algorithms, in my opinion, one of the most important characteristic is the User-Based Nearest Neighbor Algorithms because we can 
get information directly from the behavior of the nearest users. That's from the non-probabilistic algorithms. Now, about the probabilistic algorithms, 
essentially represent probability distributions when computing predicted ratings or ranked recommendation lists. 
This allow us to study in a specific way how the formalisms of probability affects collaborative filtering. So, the next concern is to study the recommendation and the prediction.
Authors says that to recommend items, a system must be prepared to know about a subset of items, but perhaps not all. And to provide predictions for a particular item, 
a system must store information about every item, even rarely rated ones. That's one of the reason why investigators use collaborative filtering metrics.
Collaborative filtering metrics can supply a confidence metric that indicates the support for a particular prediction. Also, these measures
can also be used when selecting items for recommendation. Having saying that, I'd like to close these comments with the open question about the *Evaluation metrics*.
The authors says that there have been many metrics of recommendation quality proposed. So the explicit question is: Which ones capture what people perceive as good quality? 
Which ones are important? This two questions are interesting to be answered in a mathematical way. Mathematicians has many tools to study metrics in different spaces, abstractaly  
and in a way a bit more applied. I think that if we study the different kinds of metrics, in the same collaborative filtering, maybe we can get an approach to get 
the best metric to this particular problem and then, maybe, we can generalize metrics to be used in differents collaborative filterings.

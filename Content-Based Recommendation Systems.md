# Content-Based Recommendation Systems

It is interesting that a simple idea can be used in a smartly way.  In a Content-Based Recommendation System, items that can be recommended
to the user are often stored in a database table.  As an example, we can describe synopsis of different animes and we can rate these animes in order to recommendate.
Now, another important feature of these kind of recommendations is the user's profile.  This profile may consist of a number of different
types of information like a description of the types of items that interest the user and a history of the user's interaction.  
The last one is the key to learn how to recommend the best item to the user. As an example, if the user have seen Dragon ball, Dragon ball Z, GT and super, 
it will be recommender a similar anime to consume, because of the user's interaction.
About limitations, specifically in the context of user customization systems, it require a big effort from the user and this give rise to a problem, 
principally because the user's interest changes in time. Also, customization systems don't provide a way to determine the order in which to present 
items and can find either too few or too many matching items to display. Content based recommenders have their own limitations too. 
They are not good at capturing inter-dependencies or complex behaviors.

Other important thing described in the paper that will discuss are the Decision trees. These trees can be represented given feedback on the items. 
So, the trees may provide us information about who prefers one kind of item from another. But decision tree has bias and this bias obstructs the 
unstructured text classification tasks. This might be avoid with the small trees with few tests. In the context of text classifications, 
a decision tree can lead to a bad performance but if we have a small number of structured attributes, the performance grows. To finalize this part
it would be interesting asking about how big can be this decision trees? This depends on the specific problem or maybe in the amount of task? 
There exists a number that optimize similar tasks?


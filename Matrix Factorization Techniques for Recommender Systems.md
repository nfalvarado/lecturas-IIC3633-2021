# Matrix Factorization Techniques for Recommender Systems

It is interesting the fact that matrix factorization characterizes items and users using vectors of factors. 
This factors are inferred from item rating patterns and from this, we can give a useful recommendation thanks to the predictive accuracy.  
Is kind of intuitive the idea of the relation between an item i (as well user u) and a vector q_i (and a vector p_u)  in order to measure the degree
to which the item (and the user) possesses those factors. 

Also, wondering how recommendation may change in time is direct because if you rate (for example) a movie, or a song, in some cases the rating that you gave 
to the item can be different in time due to effects associated with either users or items, independent of any interactions (item’s popularity  and  
users preferences might change over time). In the paper this is explained as the bias. I wish to discuss the dynamics behind this or how biases and preferences turns dynamical.

As new selections are available, the perception of the products are changing. This give rise to dynamical bias because we have to redefine the taste of the user 
to give a consecuent rating. To understand this idea, we have to consider the temporal effects given by the dynamic of the bias. 
The matrix factorization approach lends itself well to modeling temporal effects, which can significantly improve accuracy. 
Maybe an interesting question about this are the dynamics itself. Mathematically speaking, the dynamic world is rich (refer to information)
for the study of the behavior of the functions. Thus, the bias dynamical functions (<img src="https://render.githubusercontent.com/render/math?math=b_i(t), b_u(t)">) can be
manipulated to give an accurate rating. Item biases, user biases and user preferences describes in a good way how the rating behave in time. 

Following the idea of the previous paragraph, we can study specific recommender systems in order to give an exact (bias) function for the modeling and
understanding of the system. And maybe, generalize that function for a clutch of recommender systems, considering the causes of the changes in the bias. 
For example:
- Popularity of a movie given by an external event like an actor.
- Popularity of a band or a song given by a change of a member.
- Popularity of a restorant given by a new menu or chef.

These examples gives us an idea of the dynamic of the bias over time and it fits to the Netflix Prize Competition discussed in the paper. Basically because
Netflix works smartly by recommender systems. Users here can qualify a movie or a tv show and then Netflix can recommend similar items to the user. Also, taste of the user
may change or they can see a movie/tv show by the recommendation of a friend, but this still works to Netflix as it enlarges the dataset. 

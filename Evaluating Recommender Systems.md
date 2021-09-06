# Evaluating Recommendation Systems

The study of Recommender Systems is important for the user experience. In many modern applications, that has a wide collections of items, 
this tool is useful for the user so they don't handle this collection. The systems provide the user with a list of items that they might prefer. 
Thus, the systems help the users to decide which item consume or use. Recommenders usually have been evaluated on their prediction accuracy i.e. 
their ability to accurately predict the user’s choices. 
The paper discuss three different types of experiments in order to study the process of evaluate recommendation systems. This experiments are offline, 
user studies and online experiments.
It's important to discuss a few features to understand, first, offline experiments. Offline experiments are easy to carry on because they no require interaction with real users. 
To do an offline experiment we need to have a hypothesis before run any experiment. 
Then, we can control the variables comparing candidate algorithms on the hypothesis that we form. The non tested variables must be fixed. 
Finally, the generalization is given when the conclusions of the experiments are written. 
After choosing an algorithm and write the conclusions about its applications we have to generalize beyond the experimental data set. 
Another fundamental part of the offline experiment is to prove that a property is relevant to the users and then, affect their experience. From this point, 
we can design algorithms that improve these properties.
So, the goal of offline experiments is to avoid inappropriate approaches in order to test a few candidate algorithms (comparing cost with other types of experiments).
In contrast, the use of large data sets is expensive because, usually, it might be changed the set of the information prior to each recommendation.
Now, about user studies we can say that are conducted by recruiting a set of test subject, and asking them to perform several tasks requiring 
an interaction with the recommendation system. Sadly, user studies have disadvantages. One of the more interesting is their cost. Use a large set of subjects and asking them to perform a 
huge sets of tasks is expensive in time context, even monetarily speaking. One example of this cost, is that users may be employed, so they have to be payed.
For the conclusions of the experiments, there is a possibility that the algorithm that performed best on a test set did so because the experiment was fortuitously suitable for that algorithm. So, we introduce significance testing on the results. The more important testings are the following:

- Confidence intervals and $p$-values.
- Paired Results.
- Unpaired Results.
- Multiple test.

Some details here are interesting. In Paired Results, we can do a Wilcoxon signed rank test. This test is a non-parametric statistical hypothesis test used to
compare the locations of two populations using a set of matched samples. On a set of matched samples, it's a paired difference test similar to $t$-Student. 
But the Wilcoxon signed-rank test doesn't assume that the data is normally distributed and it's less likely to detect a truly significant result.
To stand out in Unpaired Results we have the Mann-Whitney U-test. This test is a non-parametric test of the null hypothesis that, 
for randomly selected values X and Y from two populations $P(X>Y)=P(Y>X).$ All this testings are smartly used for improve purposes 
and maybe we can study another types of testing in order to get better results (statistically speaking). So here arise some questions: 
Why not use a Binormal distribution on paired results? 
Why it must be the Wilcoxon signed rank test? 
What happens if we use parametric statistical tests instead of non-parametric? 
Maybe these questions are already answered but is interesting have a discuss of them.

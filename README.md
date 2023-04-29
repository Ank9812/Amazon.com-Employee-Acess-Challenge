# Amazon.com-Employee-Acess-Challenge


We start by loading the various libraries using the py-forest.
We also do some visualization to get to know our dataset better.
Then we also check the correlation that is existent among the various features that we have in our dataset.

Then we start by building our model using the **CAT boost classifier**.
If you want to visualize the tree that we have over here, we can also do that.
We also do some cross validation and then check the features that are very important to algorithm,
which are contributing the most by using the get feature importance function.

After that, we also check the score of our model.
I also show you an alternative way where we can use the logistic regression together with the one host
encoder to achieve the same thing.


Together with the Amazon dataset, we can learn a lot of incredible new things.

So let's get started.
`CatBoost features importance:`
![Screen Shot 2023-04-29 at 3 50 10 pm](https://user-images.githubusercontent.com/48951896/235286220-8003da7f-4034-494c-98c1-e780edb2fa99.png)

`HEatmap of trained.corr`
![Screen Shot 2023-04-29 at 3 50 40 pm](https://user-images.githubusercontent.com/48951896/235286238-bd34ea97-be71-47b9-80d7-23c2706a21ac.png)

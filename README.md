# Business understanding :

Cross selling : Marketers sell additional products to existing customers ( Selling complementary product with primary product). For example, seller always suggest sound system with TV.

So it take into account two questions:
1, Which product will the customer buy next?
2, In which sequence they will buy?

Thus, it's a multi-class classifications as the multiple potential solutions should be predicted.



# Algorithm:
we used Multinomial logis & KNN neareast to predict the first product that customer will buy next

# Bref intro of Multinomial logis
For a logistic regression, we have 1 equation that models the likelihood of something happening (1) relative to not (0). 

For a multinomial logistic regression, we have K-1 equations. Each equation models the likelihood of a certain scenario happening relative to a baseline. 

An example will make this clearer: Suppose we want to predict if someone's favourite colour is red, green or blue. As we have three categories, the multinomial logistic regression will consist of 2 equations. Suppose blue is our baseline, then we will have the following equations: 

        (1) Equation 1: Likelihood that someone's favourite colour will be red relative to blue.
        (2) Equation 2: Likelihood that someone's favourite colour will be green relative to blue. 

Finally, the outcome of a multinomial logistic regression consists of the likelihoods of the different possible outcomes. The outcome with the highest likelihood, will be the predicted outcome.  



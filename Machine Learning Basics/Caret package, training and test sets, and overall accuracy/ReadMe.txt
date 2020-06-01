This model aims to predict the gender of an individual given their height. Males tend to be taller than females so we know there might be some truth to this. 

When we first compute overall accuracy, we get an accuracy of 51.04% which is just as good as a coin flip. This model doesn't help us in any way. 

Now let's say that we have a cutoff of 62 inches. Our model accuracy increases to 79.33%. The model works better because it is consistent with the idea that males are not shorter than 62 inches. 

However, we selected 62 inches almost arbitrarily, we can do even better. Let's test different cutoffs from 61 to 70. From this test we find that the model with the highest accuracy is 84.95% accurate in our training set which has a cutoff of 64. 

Let's really check if our model is accurate by using it against a testing test. Our model has an accuracy of 74% which is not as good as our training set but still much better than guessing! 
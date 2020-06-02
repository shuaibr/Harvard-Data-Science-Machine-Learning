The F1-measure can help us by summarizing specificity and sensitivity. The F1-score is the harmonic average of sensitivity (recall) and specificity (precision). 

In this R code segment, we are computing the max F1-score by testing different height cutoffs from 61 to 70. We can see that the max F1-score is 0.6140351 which gives us the best cutoff of 65. 

With this new cutoff we can test our new precision and recall. After computing the results we get a sensitivity of 60.50% and a specificity of 88.42%. Their difference is significantly smaller and the model performs 1% better on the test set!
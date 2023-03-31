# i310D-assignment-10

I am testing to see bias in the Perspective API model. My initial hypothesis for this assignment was that Perspecrtive API is more likely to consider a comment toxic if the comment contains threats. However, once I performed the test, I realized that comments that contain profanity is more likely to be considered tosic than comments that contain threats. Thus, I performed a second test that tested to see if my findings were correct. Both my initial hypothesis and second hypothesis were correct. 

This is a more detailed explanation of my results which can also be found in the jupyter notebook named "10(1)":
Based on the reults of the test, I found that the model tends to give higher toxicity scores for comments that contain provanity than comments that are threatening. One explanation for this is that the Perspective API model values profanity scores more than threat scores. The datasets that Perspective API was trained with is likely to be biased in that there probably were more comments with profanity than threats. In one aspect, it makes sense that profanity is more focused in the model, as profanity is more commonly seen online than threats. However, to humans, threats are considered more toxic that provanity. Perspective API may want to take threatening comment more seriously. 

The jupyter notebook named "10" includes the code for my test, the results, and hypothesis. The two csv files contain the results.

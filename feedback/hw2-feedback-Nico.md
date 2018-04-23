### ***Project 2 Feedback***

***Nico Van de Bovenkamp***

***

**Overall:**  
Great work on this assignment! You made great use of various pandas, and matplotlib functionality. The only direct advice that I have is to keep on practicing and take note of some of the 'tricks' and best practices that you see in class.

**Some Notes**  
* In *Question 9*, though it is true that it is not *exactly* normal, we usually would not quite say that it doesn't fit that assumption. What I would normally do is just flag that as a cause for concern or suspicion when it comes to making our model. If, for example, we were to build some form of linear regression to predict GRE score and we saw that there was some error, we could flag the non-normal distribution of the data as a cause for error.
* In *Question 10*, you are right that we could square that values to lift the skew, but beware that we don't usually 'expand' values when we input them into our model. In fact, we usually prefer to condense and standard scale them. You could standard scale a square or exponent value! That would be interesting to experiment with.
* In *Question 13*, though I am sure you are a bit familiar given our most recent classes on classification, note that you would not use an OLS for this problem. You would want to use some form of classification model to solve this supervised learning task.

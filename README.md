# Random-Forest

Working of Random Forest Algorithm
Create Many Decision Trees: The algorithm makes many decision trees each using a random part of the data. So every tree is a bit different.
Pick Random Features: When building each tree it doesn’t look at all the features (columns) at once. It picks a few at random to decide how to split the data. This helps the trees stay different from each other.
Each Tree Makes a Prediction: Every tree gives its own answer or prediction based on what it learned from its part of the data.
Combine the Predictions:
For classification we choose a category as the final answer is the one that most trees agree on i.e majority voting.
For regression we predict a number as the final answer is the average of all the trees predictions.
